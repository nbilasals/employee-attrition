# Proyek Akhir: Menyelesaikan Permasalahan HR

## Dashboard 
**Dashboard:** [Looker HR Dashboard](https://lookerstudio.google.com/reporting/b8e88212-ef2a-4d1f-ad7b-407e7a2ae68b)

## Business Understanding

Jaya Jaya Maju merupakan salah satu perusahaan multinasional yang telah berdiri sejak tahun 2000. Ia memiliki lebih dari 1000 karyawan yang tersebar di seluruh penjuru negeri.

Walaupun telah menjadi perusahaan yang cukup besar, Jaya Jaya Maju masih kesulitan dalam mengelola karyawan. Hal ini berimbas pada tingginya attrition rate (rasio jumlah karyawan yang keluar dengan total karyawan keseluruhan) hingga lebih dari 10%.

### Permasalahan Bisnis

- Bagaimana mengidentifikasi faktor utama yang mempengaruhi employee attrition?
- Bagaimana membangun model prediktif untuk memprediksi karyawan yang berpotensi keluar?
- Apa insight yang bisa diberikan ke manajemen untuk mengurangi attrition rate?

### Cakupan Proyek

- Melakukan eksplorasi dan analisis data employee attrition.
- Membangun model machine learning untuk memprediksi employee attrition.
- Menyusun dashboard dan laporan untuk membantu pengambilan keputusan HR.

### Persiapan

**Sumber Data:** [Dataset Employee Attrition](https://github.com/dicodingacademy/dicoding_dataset/tree/main/employee)

**Setup Environment:**

```bash
git clone https://github.com/nbilasals/employee-attrition.git
cd employee-attrition
pip install -r requirements.txt
```

## Business Dashboard

Dashboard interaktif dibuat menggunakan Tableau/Streamlit (sesuai implementasi). Dashboard ini menampilkan:

- Tren employee attrition dari tahun ke tahun.
- Faktor-faktor yang berpengaruh terhadap attrition.


## Conclusion

Dari proyek ini, ditemukan beberapa faktor utama yang berkontribusi terhadap employee attrition, seperti jarak rumah ke kantor, tingkat kepuasan kerja, dan jumlah tahun bekerja di perusahaan.

### Temuan Utama:

- **Karyawan laki-laki memiliki tingkat attrition lebih tinggi dibandingkan perempuan.**
- **Attrition paling tinggi terjadi di departemen Sales, diikuti oleh Human Resources.**
- **Karyawan dengan gaji lebih rendah memiliki tingkat attrition lebih tinggi.**
- **Karyawan dengan kepuasan kerja rendah dan kepuasan lingkungan kerja rendah memiliki tingkat attrition tertinggi.**

### Rekomendasi Action Items

- **Meningkatkan work-life balance** dengan kebijakan WFH atau fleksibilitas jam kerja.
- **Menyediakan program retensi** seperti pelatihan dan insentif bagi karyawan dengan risiko tinggi keluar.
- **Menganalisis ulang kebijakan promosi dan kenaikan gaji** untuk meningkatkan kepuasan karyawan.
