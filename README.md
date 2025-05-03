# Project Background

Walmart adalah perusahaan ritel multinasional Amerika yang mengoperasikan jaringan hypermarket, department store, dan toko kelontong di Amerika Serikat dan 23 negara lainnya.

Dalam industri ritel, fluktuasi penjualan berdasarkan waktu, lokasi, dan produk dapat memberikan wawasan penting untuk mengoptimalkan strategi bisnis. Oleh karena itu, analisis data penjualan Walmart dilakukan untuk mengidentifikasi pola penjualan dan dapat meningkatkan kesuksesan dalam penjualan.

**Tujuan Project :**
1. **Product Performance Analysis**: Mengidentifikasi kategori produk mana yang memberikan kontribusi pendapatan terbesar serta produk mana yang
memiliki performa terendah.
2. **Impact of Discounts**: Mengevaluasi apakah penerapan diskon benar-benar meningkatkan pendapatan.
3. **Regional Sales Analysis**: Mengetahui kota mana yang memberikan pendapatan tertinggi bagi perusahaan, sebagai dasar untuk pengambilan
keputusan distribusi dan ekspansi.
4. **Customer Analysis**: Menelusuri faktor-faktor yang memengaruhi pelanggan untuk kembali melakukan pembelian

# Data Structure
Dataset yang digunakan dalam analisis ini diperoleh dari Kaggle dan dapat diakses melakui tautan berikut: [Walmart Customer Purchase Behavior Dataset](https://www.kaggle.com/datasets/logiccraftbyhimanshi/walmart-customer-purchase-behavior-dataset)

### Penjelasan mengenai kolom pada dataset:
| Nama Kolom         | Deskripsi                                                                 |
|--------------------|---------------------------------------------------------------------------|
| `Customer_ID`      | Unique identifier untuk setiap pelanggan.                                 |
| `Age`              | Usia pelanggan.                                                           |
| `Gender`           | Jenis kelamin pelanggan (Male/Female/Other).                             |
| `City`             | Kota tempat pembelian dilakukan.                                          |
| `Category`         | Kategori produk (misalnya: Electronics, Clothing, Groceries).             |
| `Product_Name`     | Nama produk yang dibeli.                                                  |
| `Purchase_Date`    | Tanggal pembelian.                                                        |
| `Purchase_Amount`  | Total jumlah uang yang dibelanjakan.                                     |
| `Payment_Method`   | Metode pembayaran (Credit Card, Cash, Digital Wallet, dll.).              |
| `Discount_Applied` | Apakah diskon diterapkan pada pembelian (Yes/No).                        |
| `Rating`           | Rating dari pelanggan terhadap pembelian (skala 1–5).                     |
| `Repeat_Customer`  | Menunjukkan apakah pelanggan pernah membeli sebelumnya (Yes/No).          |

# Summary
![dashboard](dashboard2.png)

# **Product Performance Analysis**
![Visualisasi1](output1.png)

- Product "Headphones" memberikan kontribusi pendapatan terbesar dengan total revenue sebesar $846878.56 dalam periode Februari 2024 – Februari 2025.
- Produk dengan performa terendah adalah "Lipstick", dengan pendapatan sebesar $768327.28 dalam periode Februari 2024 - Februari 2025

**Recomendasi :**
- Selalu memastikan ketersediaan stok headphone tetap terjaga dan lakukan bundling untuk produk lipstik untuk melakukan upscaling


# **Impact of Discounts**
- Diskon tidak meningkatkan pendapatan, tetapi menurunkan pendapatan dan berkurang sebesar $7036.779

**Recomendasi :**
- Lakukan strategi lain selain memberikan diskon, seperti loyalty program untuk pembeli yang sering berbelanja atau voucher cashback sebagai alternatif program

# **Regional Sales Analysis**

- Kota yang menghasilkan keuntungan terbesar berada di North Michael

**Recomendasi :**
- Lakukan analisis terhadap karakteristik pelanggan di North Michael dan kembangkan strategi pemasaran yang tepat untuk mempertahankan pangsa pasar di wilayah tersebut.
- Identifikasi faktor-faktor kunci yang mendorong performa tinggi di North Michael dan evaluasi potensi penerapannya di kota-kota lain untuk mendorong pertumbuhan penjualan secara merata.

# **Customer Analysis**
- Tidak ada fitur yang memiliki pengaruh yang signifikan terhadap pelanggan yang kembali atau tidak

**Recomendasi :**
- Evaluasi ulang variabel/fitur yang digunakan: Perluasan fitur yang lebih relevan
- Lakukan analisis kualitatif tambahan: Misalnya survei atau wawancara pelanggan untuk memahami faktor non-kuantitatif yang memengaruhi loyalitas pelanggan.
