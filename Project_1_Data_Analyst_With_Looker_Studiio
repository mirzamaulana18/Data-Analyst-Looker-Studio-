# Analisis Data Penjualan E-Commerce Global

## 📌 Latar Belakang Proyek

Proyek ini bertujuan untuk menganalisis dataset transaksi dari sebuah perusahaan ritel online yang berbasis di Inggris selama periode satu tahun (Desember 2010 - Desember 2011). Tujuan utamanya adalah untuk menggali wawasan bisnis yang dapat ditindaklanjuti dari data penjualan, perilaku pelanggan, dan performa produk untuk membantu pengambilan keputusan strategis.

**Dashboard Interaktif:**
**[➡️ Lihat Dashboard di Looker Studio](https://lookerstudio.google.com/s/nj9zR6QyBvE)**

---

## ## 🎯 Tujuan Bisnis

Analisis ini difokuskan untuk menjawab pertanyaan-pertanyaan bisnis berikut:

1.  **Tren Penjualan:** Bagaimana tren penjualan bulanan? Apakah ada pola musiman yang signifikan?
2.  **Performa Produk:** Produk apa saja yang menjadi best-seller dan penyumbang pendapatan terbesar?
3.  **Analisis Pelanggan & Geografis:** Siapa pelanggan paling berharga (top customers)? Dan dari negara mana pendapatan terbesar berasal?
4.  **Analisis Operasional:** Berapa tingkat pembatalan transaksi dan produk apa yang paling sering dibatalkan?

---

## ## 📊 Dataset

Dataset yang digunakan adalah **"Online Retail Dataset"** dari UCI Machine Learning Repository. Dataset ini berisi 541.909 baris data transaksi yang mencakup informasi faktur, detail produk, kuantitas, harga, ID pelanggan, dan negara.

* **Sumber:** [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/online+retail)
* **Atribut:** `InvoiceNo`, `StockCode`, `Description`, `Quantity`, `InvoiceDate`, `UnitPrice`, `CustomerID`, `Country`.

---

## ## ⚙️ Teknologi & Tools

* **Pembersihan & Analisis Data:**
    * **Python:** Bahasa utama untuk pemrosesan data.
    * **Pandas:** Untuk manipulasi dan pembersihan data.
    * **Jupyter Notebook / Google Colab:** Lingkungan kerja untuk analisis.
* **Visualisasi & Dashboard:**
    * **Looker Studio:** Untuk membuat dashboard interaktif dan memvisualisasikan temuan utama.

---

## ## 📈 Metodologi Analisis

Proses analisis dibagi menjadi beberapa tahap utama:

1.  **Pemuatan Data:** Memuat data dari file sumber.
2.  **Pembersihan Data (Data Cleaning):**
    * Menangani nilai yang hilang (missing values), terutama pada kolom `CustomerID` dan `Description`.
    * Menghapus data duplikat.
    * Memfilter anomali data seperti transaksi dengan kuantitas negatif (yang merupakan pembatalan) dan harga unit nol.
3.  **Rekayasa Fitur (Feature Engineering):**
    * Membuat kolom baru `TotalPrice` (`Quantity * UnitPrice`) untuk menghitung total pendapatan per item.
    * Membuat kolom `IsCancelled` untuk menandai transaksi yang dibatalkan.
4.  **Analisis Data Eksploratif (EDA):**
    * Melakukan agregasi data untuk menjawab setiap tujuan bisnis.
5.  **Visualisasi:**
    * Hasil dari analisis kemudian divisualisasikan dalam sebuah dashboard interaktif menggunakan Looker Studio untuk memudahkan pemahaman bagi para pemangku kepentingan.

---

## ## 💡 Temuan Utama (Key Findings)

* **Pola Penjualan Musiman:** Terjadi puncak penjualan yang signifikan pada bulan **November**, kemungkinan besar didorong oleh persiapan belanja liburan akhir tahun.
* **Dominasi Pasar Domestik:** **Inggris (United Kingdom)** menyumbang lebih dari 80% dari total pendapatan, menunjukkan ketergantungan yang kuat pada pasar lokal.
* **Produk Paling Populer:** Produk seperti "WHITE HANGING HEART T-LIGHT HOLDER" secara konsisten menjadi salah satu produk terlaris.
* **Tingkat Pembatalan:** Ditemukan bahwa sekitar **1.7%** dari total item transaksi adalah item yang dibatalkan, memberikan wawasan untuk perbaikan operasional.



