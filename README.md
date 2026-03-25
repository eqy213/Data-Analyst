# Analisis Data FMCG — Produk Susu Formula
**Portfolio Data Analyst | 50.000 Transaksi | Python**

---

## Deskripsi Proyek

Proyek ini merupakan analisis end-to-end terhadap dataset transaksi produk susu formula (FMCG) yang mencakup 50.000 baris data dengan 22 variabel. Tujuannya adalah mengidentifikasi pola perilaku konsumen, efektivitas promosi, dan peluang pertumbuhan penjualan menggunakan Python.

---

## Dataset

| Atribut | Detail |
|---|---|
| Jumlah baris | 50.000 transaksi |
| Jumlah kolom | 22 variabel |
| Sumber | FMCG Milk Powder Dataset |
| Format | CSV |

### Daftar Kolom

| Kolom | Tipe | Deskripsi |
|---|---|---|
| `customer_id` | string | ID unik pelanggan |
| `age_group` | kategorikal | Kelompok usia (18-24, 25-34, 35-44, 45-54) |
| `gender` | kategorikal | Jenis kelamin (M/F) |
| `loyalty_member` | kategorikal | Status member loyalitas (Yes/No) |
| `income_bracket` | kategorikal | Kelompok pendapatan (Low/Medium/High) |
| `transaction_date` | tanggal | Tanggal transaksi |
| `day_of_week` | kategorikal | Hari transaksi |
| `month` | numerik | Bulan transaksi (1–12) |
| `total_basket_value` | numerik | Total nilai belanja per transaksi |
| `total_items_bought` | numerik | Jumlah item yang dibeli |
| `product_category` | kategorikal | Kategori produk |
| `product_subcategory` | kategorikal | Sub-kategori (Stage 1–4, Lactose-Free) |
| `brand` | kategorikal | Nama brand (KidPlus, MaxiMilk, NutriKids, SuperGrow) |
| `unit_price` | numerik | Harga per unit |
| `quantity` | numerik | Jumlah unit dibeli |
| `promo_applied` | kategorikal | Apakah promo diterapkan (Yes/No) |
| `discount_rate` | numerik | Persentase diskon |
| `last_purchase_days` | numerik | Hari sejak pembelian terakhir |
| `category_frequency_milk` | numerik | Frekuensi beli susu per kategori |
| `avg_monthly_spend` | numerik | Rata-rata pengeluaran bulanan |
| `loyalty_points_used` | numerik | Poin loyalitas yang digunakan |
| `will_purchase_milk` | kategorikal | **Target**: apakah akan beli susu (Yes/No) |

---

## Library yang Digunakan

| Library | Versi | Kegunaan |
|---|---|---|
| `pandas` | ≥ 1.5 | Manipulasi dan analisis data |
| `numpy` | ≥ 1.23 | Kalkulasi numerik |
| `matplotlib` | ≥ 3.6 | Visualisasi dasar |
| `seaborn` | ≥ 0.12 | Visualisasi statistik |
| `scikit-learn` | ≥ 1.2 | Machine learning |

---

## Hasil & Temuan Utama

### Insight 1 — Promo sangat efektif
Promosi meningkatkan conversion rate dari **20.1%** menjadi **41.4%** — peningkatan sebesar **+106%**. Namun hanya 39.8% transaksi yang menggunakan promo, menandakan adanya potensi besar yang belum dimanfaatkan.

### Insight 2 — Persaingan brand sangat ketat
Empat brand (KidPlus, MaxiMilk, NutriKids, SuperGrow) bersaing dengan selisih revenue yang sangat tipis — tidak ada satu brand yang mendominasi secara jelas.

### Insight 3 — Usia dan income tidak menentukan keputusan beli
Conversion rate hampir identik di semua kelompok usia dan income bracket. Susu formula bersifat kebutuhan esensial yang tidak dipengaruhi oleh daya beli.

### Insight 4 — Revenue sangat stabil sepanjang tahun
Variasi revenue bulanan sangat kecil dengan puncak di bulan Agustus. Stabilitas ini memudahkan perencanaan stok dan anggaran promosi.

### Insight 5 — Stage 4 dan Lactose-Free paling diminati
Kedua subkategori ini memiliki volume transaksi tertinggi, mengindikasikan segmen konsumen toddler dan pelanggan dengan kebutuhan khusus yang dominan.

---

## Rekomendasi Bisnis

| # | Rekomendasi | Dampak |
|---|---|---|
| 1 | Perluas cakupan promosi ke segmen non-member | Tinggi |
| 2 | Gunakan behavioral segmentation bukan demografis | Sedang |
| 3 | Buat bundle lintas Stage 1–4 untuk tingkatkan LTV | Sedang |
| 4 | Optimalkan stok di bulan Agustus (peak demand) | Sedang |
| 5 | Kembangkan model ML prediksi pembelian untuk CRM | Tinggi |

---

## Tentang Proyek Ini

Dataset yang digunakan adalah dataset publik FMCG susu formula dengan 50.000 transaksi sintetis yang merepresentasikan pola pembelian konsumen produk susu formula.

**Tech stack:** Python · Pandas · NumPy · Matplotlib · Seaborn · Scikit-learn

