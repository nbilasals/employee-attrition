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
---

## Business Dashboard

Dashboard interaktif dibuat menggunakan Looker Studio. 
![image](https://github.com/user-attachments/assets/6a12cde4-5ba9-43d6-87b7-446e2c104fc4)


- Jumlah total karyawan
- Jumlah Attrition
- Attrition rate
- Rata-rata pendapatan bulanan karyawan
- Rata-rata umur karyawan
- Rata-rata tahun bekerja karyawan
- Attrtion by Job Satisfaction
- Attrition by Education Field
- Attrition by Department
- Attrition by Gender
- Attrition by Work Life Balance
- Attrition by Monthly Income
- Attrition by Years At Company


---

## Machine Learning Model
- Model: XGBoost Classifier
- Accuracy: 90%
- Recall (attrition class): 90%
- F1-Score: 90%
- Teknik penyeimbangan data: SMOTE

---  

## Conclusion

Dari proyek ini, ditemukan beberapa faktor utama yang berkontribusi terhadap employee attrition, seperti tingkat keterlibatan dala pekerjaan, tingkat kepuasan kerja, dan jumlah tahun bekerja di perusahaan.

Dengan melakukan analisis menyeluruh terhadap data karyawan dan membangun model prediktif berbasis machine learning, proyek ini memberikan solusi konkret kepada manajemen HR untuk:
- Memahami mengapa karyawan keluar
- Mengidentifikasi siapa yang berisiko keluar
- Membangun strategi retensi yang berbasis data dan prediksi

### Temuan Utama:
- **Gender:** Mayoritas karyawan adalah laki-laki (60%), dan mereka juga mendominasi angka attrition (108 vs 71).
- **Job Satisfaction:** Karyawan dengan kepuasan kerja **rendah** memiliki attrition tertinggi.
- **Department:** Departemen **Research and Development** menyumbang attrition terbanyak.
- **Job Role:** Posisi **Laboratory Technician** memiliki attrition tertinggi, sedangkan **Research Director** terendah.
- **Job Involvement:** Tingkat keterlibatan kerja rendah berkorelasi dengan attrition yang tinggi.
- **Work-Life Balance:** Attrition tinggi ditemukan pada karyawan dengan work-life balance **rendah** dan **sangat tinggi**.
- **Monthly Income:** Attrition paling tinggi terjadi pada karyawan dengan gaji **5–10 juta**. Semakin tinggi gaji (>10 juta), semakin kecil kemungkinan resign.
- **Years at Company:** Attrition paling tinggi terjadi di **tahun pertama dan kedua**. Setelah bekerja lebih dari 10 tahun, karyawan cenderung memilih untuk bertahan.


### Rekomendasi Strategis:

- **Program retensi**: Fokus pada karyawan baru (<3 tahun) dengan pelatihan, mentorship, dan career path yang jelas.
- **Review kompensasi**: Tinjau ulang sistem kenaikan gaji dan insentif untuk departemen dengan attrition tinggi.
- Employee engagement: Buat program engagement rutin (misalnya one-on-one HR check-in).
- Pemanfaatan prediksi: Gunakan model ini sebagai sistem peringatan dini untuk intervensi sebelum resign terjadi.
- **Improve Job Satisfaction:** Lakukan survey dan program apresiasi.
- **Review R&D & Lab Technician Roles:** Tinjau beban kerja dan jalur karir.
- **Boost Job Involvement:** Berikan tanggung jawab dan proyek yang melibatkan karyawan.
- **Balanced Work-Life Policy:** Berikan fleksibilitas tanpa mengorbankan produktivitas.
- **Gender-Neutral Strategy:** Fokus pada perbaikan umum tanpa bias gender.
- **Attrition Monitoring Dashboard:** Gunakan Looker dashboard untuk tracking rutin.

