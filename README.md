# Proyek Akhir: Menyelesaikan Permasalahan HR

## 📊 Dashboard
**Tool:** Looker Studio  
**Link:** [Employee Attrition Dashboard](https://lookerstudio.google.com/reporting/b8e88212-ef2a-4d1f-ad7b-407e7a2ae68b)

---

## 💼 Business Understanding

### Latar Belakang

Jaya Jaya Maju adalah perusahaan multinasional yang telah berdiri sejak tahun 2000, dengan lebih dari 1000 karyawan yang tersebar di berbagai wilayah Indonesia. Meskipun perusahaan ini telah berkembang secara signifikan, tim Human Resources (HR) masih menghadapi tantangan besar dalam hal retensi karyawan.

Tingkat **employee attrition** (karyawan keluar) di perusahaan tercatat lebih dari **10%**, yang berdampak pada peningkatan biaya rekrutmen, pelatihan, serta menurunnya produktivitas tim.

---

## ❗ Permasalahan Bisnis

- Departemen HR kesulitan dalam **mengidentifikasi pola dan karakteristik karyawan** yang berisiko tinggi keluar dari perusahaan.
- Tidak tersedianya **sistem pemantauan berbasis data** yang dapat digunakan oleh manajemen HR untuk mengambil langkah pencegahan secara tepat waktu.
- Tidak ada sistem prediktif yang membantu manajemen dalam menurunkan attrition rate secara terukur.

---

## 🎯 Tujuan Proyek

- Mengidentifikasi faktor-faktor utama yang memengaruhi employee attrition.
- Membangun **model prediktif** menggunakan machine learning untuk memperkirakan risiko karyawan keluar.
- Menyusun dashboard interaktif sebagai alat bantu pengambilan keputusan tim HR.

---

## 🔍 Cakupan Proyek

- Eksplorasi dan analisis data attrition.
- Feature engineering dan pemodelan machine learning.
- Evaluasi model menggunakan metrik akurasi, recall, dan f1-score.
- Pembuatan dashboard untuk monitoring risiko attrition.

---

### Persiapan

**Sumber Data:** [Dataset Employee Attrition](https://github.com/dicodingacademy/dicoding_dataset/tree/main/employee)

**Setup Environment:**

```bash
git clone https://github.com/nbilasals/employee-attrition.git
cd employee-attrition
pip install -r requirements.txt
```

## Business Dashboard

Dashboard interaktif dibuat menggunakan Looker Studio. 

- Jumlah total karyawab
- Jumlah Attrition
- Attrition rate
- Rata-rata pendapatan bulanan karyawan
- Rata-rata umur karyawan
- Rata-rata tahun bekerja karyawan
- Attrtion by Job Satisfaction
- Attrition by Education Field
- Attrition by Department
- Attrition by Gender


---

## Machine Learning Model
### Model yang dicoba
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- K-Nearest Neighbors
- Support Vector Machine

### Model Terbaik
- Model: Random Forest Classifier
- Accuracy: 88%
- Recall (attrition class): 79%
- F1-Score: 81%
- Teknik penyeimbangan data: SMOTE

---  

## Conclusion

Dari proyek ini, ditemukan beberapa faktor utama yang berkontribusi terhadap employee attrition, seperti jarak rumah ke kantor, tingkat kepuasan kerja, dan jumlah tahun bekerja di perusahaan.

Dengan melakukan analisis menyeluruh terhadap data karyawan dan membangun model prediktif berbasis machine learning, proyek ini memberikan solusi konkret kepada manajemen HR untuk:
- Memahami mengapa karyawan keluar
- Mengidentifikasi siapa yang berisiko keluar
- Membangun strategi retensi yang berbasis data dan prediksi

### Temuan Utama:
#### Karakteristik Umum Karyawan yang Resign
- Usia 20–30 tahun, masa kerja < 3 tahun
- Kepuasan kerja rendah
- Bekerja di departemen Sales dan Human Resources
- Menerima gaji rendah-menengah
- Tinggal >10 km dari kantor pusat

#### Faktor-faktor yang Mempengaruhi Attrition
- Job Satisfaction (kepuasan kerja)
- Distance From Home (jarak rumah ke kantor)
- Job Involvement (tingkat keterlibatan kerja)
- Monthly Income (penghasilan per bulan)

### Rekomendasi Strategis:

- Fleksibilitas kerja: Terapkan sistem hybrid atau WFH untuk karyawan yang tinggal jauh dari kantor.
- Program retensi: Fokus pada karyawan baru (<3 tahun) dengan pelatihan, mentorship, dan career path yang jelas.
- Review kompensasi: Tinjau ulang sistem kenaikan gaji dan insentif untuk departemen dengan attrition tinggi.
- Employee engagement: Buat program engagement rutin (misalnya one-on-one HR check-in).
- Pemanfaatan prediksi: Gunakan model ini sebagai sistem peringatan dini untuk intervensi sebelum resign terjadi.
