# E-Commerce Sales Performance & RFM Customer Segmentation Analysis (2024–2026)

## Project Overview
Proyek ini bertujuan untuk menganalisis kinerja penjualan dan perilaku pelanggan pada dataset *e-commerce* (1.000 transaksi) menggunakan Python. Analisis difokuskan pada pembersihan data, eksplorasi tren pendapatan bulanan, analisis kinerja kategori produk, serta segmentasi pelanggan menggunakan metode **RFM (Recency, Frequency, Monetary)** untuk mendukung pengambilan keputusan bisnis berbasis data.

---

## Tech Stack & Tools
* **Programming Language:** Python 3.14
* **Data Processing & Analysis:** Pandas, Datetime
* **Data Visualization:** Matplotlib
* **Development Environment:** Visual Studio Code / Jupyter Notebooks

---

## Key Findings & Business Insights

### 1. Data Cleaning & Integrity
* Berhasil menangani dan menambal **missing values** pada kolom `status_pembayaran` menggunakan metode imputation `.fillna()`, memastikan akurasi perhitungan agregasi.

### 2. Category Performance & Revenue Drivers
* **Kategori Produk Terlaris (Volume):** **Makanan & Minuman** mendominasi jumlah volume transaksi (771 unit dibeli).
* **Kategori Produk Penyumbang Revenue Terbesar:** **Elektronik** menyumbangkan pendapatan tertinggi sebesar **Rp 2.296.650.000**, menunjukkan bahwa produk *high-value items* merupakan pendorong utama margin bisnis.

### 3. Monthly Revenue Trend (2024–2026)
* **Puncak Penjualan (Peak Period):** Terjadi pada **September 2024**.
* **Titik Penurunan (Dip Period):** Terjadi pada **Maret 2026**.

### 4. RFM Customer Segmentation
* **Champions / VIP Customer:** Ditemukan **2 pelanggan** dengan kontribusi nilai transaksi terbesar (*Top Spender* dipimpin oleh **Rizki** dengan total belanja **Rp 427.290.000**).
* **Loyal Customers:** Terdapat **10 pelanggan** yang memiliki frekuensi transaksi terbanyak (dipimpin oleh **Ahmed**).

---

## Actionable Business Recommendations

1. **Strategi Retention Pelanggan VIP:** 
   * Buat program *VIP / Tiered Loyalty Membership* eksklusif untuk pelanggan kategori *Champions* (seperti Rizki) agar terus melakukan *repurchase* produk bernilai tinggi.
2. **Promosi Terfokus untuk Frequent Buyers:**
   * Berikan penawaran khusus berbentuk *bundle deals* atau diskon ongkir bagi kelompok *Loyal Customers* (seperti Ahmed) untuk mendorong kenaikan nilai transaksi rata-rata (*Average Order Value*).
3. **Evaluasi Periodik & Strategi Musiman:**
   * Melakukan replikasi strategi kampanye/promosi yang sukses di **September 2024** untuk diterapkan kembali pada bulan-bulan dengan performa rendah seperti **Maret 2026**.

---

## How to Run the Project

1. Clone repositori :
   ```bash
   git clone https://github.com/MFSugara98/ecommerce-sales-analysis.git
