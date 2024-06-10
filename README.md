# DiCo Fashion Analysis

## Latar Belakang
Perusahaan yang bergerak di bidang online fashion, Dicoding Collection (DiCo), perlu mengevaluasi performa penjualan dan memahami item fashion yang paling banyak dibeli. Selain itu, perusahaan juga perlu lebih memahami pelanggannya sehingga dapat membuat strategi kampanye yang lebih efisien.

## Pertanyaan Bisnis
Berdasarkan latar belakang, berikut adalah pertanyaan bisnis yang akan dijawab melalui proses analisis data:
1. Bagaimana performa penjualan dan revenue perusahaan dalam beberapa bulan terakhir?
2. Produk apa yang paling banyak dan paling sedikit terjual?
3. Bagaimana demografi pelanggan yang kita miliki?
4. Kapan terakhir pelanggan melakukan transaksi?
5. Seberapa sering seorang pelanggan melakukan pembelian dalam beberapa bulan terakhir?
6. Berapa banyak uang yang dihabiskan pelanggan dalam beberapa bulan terakhir?

## Dataset
Dataset yang digunakan adalah dataset [DicodingCollection](https://github.com/dicodingacademy/dicoding_dataset/tree/main/DicodingCollection) yang merupakan hasil modifikasi dari dataset [Shopping Cart Database](https://www.kaggle.com/datasets/ruchi798/shopping-cart-database) yang dipublikasi dalam platform Kaggle. Dataset ini terdiri atas empat buah tabel:
- **customers**: Menyimpan berbagai informasi terkait pelanggan.
  - `customer_id`
  - `customer_name`
  - `gender`
  - `age`
  - `home_address`
  - `zip_code`
  - `city`
  - `state`
  - `country`
- **orders**: Menyimpan berbagai informasi terkait pesanan.
  - `order_id`
  - `customer_id`
  - `order_date`
  - `delivery_date`
- **products**: Berisi berbagai informasi terkait produk.
  - `product_id`
  - `product_type`
  - `product_name`
  - `size`
  - `colour`
  - `price`
  - `quantity`
  - `description`
- **sales**: Mengandung informasi detail terkait penjualan.
  - `sales_id`
  - `order_id`
  - `product_id`
  - `price_per_unit`
  - `quantity`
  - `total_price`

## Tahapan Proyek
Proyek ini dibagi menjadi tiga tahapan utama:
### 1. Data Wrangling
   - **Persiapan Data**: Mengimpor data dari berbagai sumber.
   - **Gathering Data**: Mengumpulkan data yang diperlukan dari tabel-tabel yang tersedia.
   - **Assessing Data**: Mengevaluasi kualitas dan kelengkapan data.
   - **Cleaning Data**: Membersihkan data dari kesalahan atau inkonsistensi.
### 2. Exploratory Data Analysis
   - **Penentuan Pertanyaan Bisnis**: Menentukan pertanyaan-pertanyaan bisnis yang akan dieksplorasi.
   - **Eksplorasi Data**: Menggunakan teknik visualisasi dan statistik untuk menjawab pertanyaan-pertanyaan bisnis.
### 3. Data Visualization
   - Membuat visualisasi yang informatif untuk menyajikan temuan dari eksplorasi data.
