
# 🚍 Data-Driven Insights for Improving TransJakarta Service Efficiency and User Satisfaction

## 📌 Deskripsi Proyek
Proyek ini bertujuan memberikan **insight berbasis data** dari transaksi TransJakarta untuk mendukung pengambilan keputusan yang strategis. Dengan menggunakan data selama **April 2023**, aku mengeksplorasi **pola perjalanan, demografi pengguna, serta transaksi dengan nominal Rp0** untuk mengidentifikasi potensi perbaikan layanan.

## 🎯 Tujuan Analisis
- Mengidentifikasi **tren penggunaan** berdasarkan waktu dan lokasi.
- Menganalisis **profil demografi pengguna** (usia dan gender).
- Mendeteksi **pola transaksi tidak biasa** seperti tarif Rp0.
- Merumuskan **rekomendasi strategis** berdasarkan hasil analisis.

## 📂 Dataset
- File: `df_cleaned.csv`
- Periode: April 2023
- Jumlah kolom: 26, termasuk informasi waktu, lokasi halte, usia pengguna, jarak tempuh, dan nominal pembayaran.

## 🛠 Tools yang Digunakan
- Python (Pandas, Seaborn, Matplotlib, numpy)
- Google Looker Studio
- Git & GitHub

## 🔍 Analisis & Insight Utama

### 1. Pola Penggunaan Berdasarkan Waktu
- **Jam sibuk** pengguna TransJakarta terjadi pada **pukul 05:00 - 06:00** dan **17:00 - 18:00**.
- Volume transaksi menurun drastis di luar jam operasional umum.

### 2. Segmentasi Hari
- Aktivitas pengguna **lebih tinggi di hari kerja** dibanding akhir pekan.
- Terdapat perbedaan pola pemakaian yang signifikan.

### 3. Koridor Paling Padat
- Top 3 koridor: `1T`, `S21`, dan `JIS3` → memerlukan **alokasi armada lebih banyak**.

### 4. Perilaku Transaksi Rp0
- Terjadi puncak transaksi Rp0 pada jam **06:00** dan **17:00**.
- **Segmen Dewasa** mendominasi transaksi Rp0 → perlu investigasi lebih lanjut: apakah bagian dari **program tertentu** atau potensi error teknis.

### 5. Segmentasi Pengguna: Loyal vs Dinamis
- **86.2%** pengguna tergolong **dinamis** (jam & rute fleksibel).
- **13.8%** tergolong **loyal**, sangat bergantung pada bus di jam pagi.

### 6. Demografi Pengguna
- Mayoritas pengguna berada pada kelompok **usia 18-50 tahun (Dewasa)**.
- **Pengguna pria** sedikit lebih dominan dibanding wanita.

## 📊 Dashboard Interaktif

Dashboard dibangun di **Looker Studio** mencakup:
- Jam Sibuk Penumpang
- Top Koridor Terpadat
- Proporsi Transaksi Rp0
- Segmentasi Gender & Usia
- Perbandingan Hari Kerja vs Akhir Pekan

🔗 Link Dashboard: https://lookerstudio.google.com/reporting/6dc3986e-ab6d-4729-8ed7-5170f5b38973

## ✅ Rekomendasi Strategis
1. **Optimalkan Armada** di koridor 1T, S21, dan JIS3.
2. **Perjelas program promosi/subsidi Rp0**, terutama untuk kelompok usia dewasa & lansia.
3. **Rancang strategi retensi** untuk pengguna loyal & pendekatan akuisisi untuk segmen dinamis.
4. **Perluas layanan** di waktu non-puncak untuk menjangkau pengguna dengan pola lebih fleksibel.

## 📎 Struktur File
```
📁 Project Folder/
├── Capstone3.ipynb          # Notebook Python (EDA + cleansing)
├── df_cleaned.csv           # Dataset hasil pembersihan
└── README.md                # File ini
```

## 🙋‍♂️ Kontak
Dikembangkan oleh **Muhammad Aldi Priaga** – jika ingin berdiskusi lebih lanjut, silakan hubungi via www.linkedin.com/in/muhammad-aldi-priaga-269aa9179
