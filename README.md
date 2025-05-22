# 🏦 Clustering Pola Transaksi Bank

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk mengelompokkan nasabah berdasarkan **pola transaksi bank** menggunakan algoritma **Clustering**. Dengan mengelompokkan nasabah ke dalam segmen-segmen tertentu, bank dapat memahami perilaku transaksi pengguna dan merancang strategi pemasaran atau layanan yang lebih personal dan efektif.

## 🧠 Tujuan Analisis
- Mengidentifikasi pola transaksi berdasarkan frekuensi dan nominal transaksi.
- Membentuk segmen nasabah menggunakan algoritma clustering (K-Means).
- Visualisasi hasil segmentasi untuk interpretasi lebih lanjut.

## 📂 Dataset
Dataset mencakup informasi transaksi nasabah, seperti:
- `Customer ID`
- `Transaction Count`
- `Total Transaction Amount`
- `Average Transaction`
- `Time Period (Monthly/Yearly)`

*Catatan: Dataset ini adalah data fiktif/sintetis yang digunakan untuk keperluan analisis pembelajaran.*
---
## 🧪 Metodologi
1. **Data Preprocessing**
   - Menghapus nilai null
   - Normalisasi data numerik
2. **Elbow Method**
   - Menentukan jumlah cluster optimal
3. **K-Means Clustering**
   - Segmentasi nasabah ke dalam beberapa cluster
4. **Visualisasi**
   - Scatter plot cluster
   - Interpretasi pola tiap kelompok
---
## 📊 Tools & Teknologi
- Python
- Pandas
- scikit-learn
- Matplotlib
- Seaborn
---
## 📈 Hasil & Insight
- Nasabah terbagi menjadi beberapa segmen berdasarkan intensitas dan besaran transaksi.
- Setiap cluster memiliki karakteristik unik:
  - **Cluster A**: Nasabah premium dengan nominal transaksi tinggi
  - **Cluster B**: Nasabah reguler dengan frekuensi transaksi sedang
  - **Cluster C**: Nasabah pasif dengan aktivitas rendah

Bank dapat memanfaatkan hasil ini untuk:
- Menyusun promosi berdasarkan segmen
- Mendeteksi potensi churn
- Menyediakan layanan yang lebih relevan per kelompok
---
## 📁 Struktur Proyek
clustering-pola-transaksi-bank/
│
├── dataset/
│ └── data_transaksi_nasabah.csv
│
├── notebook/
│ └── clustering_transaksi.ipynb
│
├── images/
│ └── hasil_cluster.png
│
└── README.md

---

## 🧑‍💻 Kontributor
- **Nama**: Daffa Haidar Farras  
- 📧 Email: daffahaidarfarras@gmail.com  
- 📇 Dicoding ID: daffa_haidar

## 📎 Lisensi
Proyek ini dibuat untuk keperluan pembelajaran dan pengembangan kemampuan analisis data. Silakan gunakan atau modifikasi sesuai kebutuhan dengan mencantumkan atribusi.

---
