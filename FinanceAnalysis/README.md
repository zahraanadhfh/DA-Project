# 💰 Finance Analysis Dashboard

![Finance Analysis Dashboard]
<img width="1342" height="707" alt="Dashboard FinanceAnalysis" src="https://github.com/user-attachments/assets/fd366b09-eb8c-4be1-be25-cf0d444c0840" />

## 👋 Tentang Dashboard Ini

Dashboard **"finalysis"** ini saya buat untuk memberikan *real-time insight* terhadap transaksi keuangan, perilaku pelanggan, dan risiko bisnis. Dibuat menggunakan **Power BI**, dashboard ini terdiri dari dua halaman utama — **Overview Analysis** dan **Transactions** — dengan panel filter interaktif di sisi kiri sehingga data bisa dieksplorasi sesuai kebutuhan.

---

## 🎛️ Panel Filter (Slicer)

Tersedia beberapa filter dinamis untuk menyaring data sesuai kebutuhan analisis:

| Filter | Keterangan |
|---|---|
| **Dynamic Measure** | Mengubah ukuran/metrik yang ditampilkan pada visual |
| **Year** | Filter berdasarkan tahun transaksi |
| **Occupation** | Filter berdasarkan pekerjaan pelanggan |
| **Merchant Category** | Filter berdasarkan kategori merchant |

Tombol **Clear All Slicers** memudahkan reset seluruh filter ke kondisi awal.

---

## 🔢 Key Metrics (Ringkasan Utama)

| Metrik | Nilai | Perbandingan vs Tahun Sebelumnya |
|---|---|---|
| **Total Amount** | $455.53M | +43.00% |
| **Total Transactions** | 50.00K | +0.43 |
| **Avg Transactions Value** | 9.11K | 0.00 |
| **Total Fees** | 726.24K | +0.44 |
| **Total Tax** | 130.74K | +0.44 |

*"Dari lima kartu KPI ini, saya bisa langsung melihat kesehatan transaksi secara umum — total nilai transaksi naik signifikan 43% dibanding tahun sebelumnya, jadi tren pertumbuhannya positif."*

---

## 📈 Penjelasan Tiap Visualisasi

### 1. Total Amount by Month *(Line Chart)*
Menunjukkan tren nilai transaksi bulanan sepanjang tahun. Terlihat titik tertinggi terjadi di awal tahun (Januari, ±$50M) kemudian mengalami penurunan signifikan hingga Mei, dan cenderung stabil di kisaran $33–35M pada bulan-bulan berikutnya.

### 2. Total Amount by Transaction Status *(Donut Chart)*
Membagi transaksi berdasarkan statusnya:
- **Success**: $389.02M (85.4%)
- **Failed**: $47.46M (10.42%)
- **Pending**: $19.06M (4.18%)

*"Mayoritas transaksi berhasil, tapi porsi failed masih cukup terlihat — ini bisa jadi area yang perlu ditelusuri lebih lanjut."*

### 3. Total Amount by Customer Segment *(Bar Chart)*
Membandingkan kontribusi nilai transaksi per segmen pelanggan:
- **Retail**: $0.25bn (segmen dominan)
- **Premium**: $0.08bn
- **SME**: $0.07bn
- **Corporate**: $0.03bn
- **Wealth**: $0.02bn

### 4. Total Amount by State *(Horizontal Bar Chart)*
Menampilkan sebaran nilai transaksi per provinsi/state. **Maharashtra** memimpin dengan $68M, diikuti Karnataka ($53M) dan Gujarat ($50M), hingga Telangana sebagai yang terendah ($19M).

### 5. Transaction Type Analysis *(Tabel Detail)*
Rincian nilai Amount, Fees, Tax, dan jumlah Transactions untuk tiap jenis transaksi (Bill Payment, Card Payment, Deposit, Fee Charge, Interest Credit, Investment, Loan EMI, Refund, Transfer, dll) — memudahkan analisis mendalam per kategori transaksi.

### 6. Total Amount by Gender *(Donut Chart)*
Distribusi nilai transaksi berdasarkan gender:
- **Female**: $219.9M (48.2%)
- **Male**: $235.6M (51.7%)

Distribusi antara pelanggan pria dan wanita relatif seimbang.

---

## ✅ Insight & Kesimpulan

1. **Pertumbuhan positif** — total nilai transaksi naik 43% dibanding tahun sebelumnya, menandakan tren bisnis yang sehat.
2. **Tingkat keberhasilan transaksi tinggi** (85.4%), namun proporsi transaksi *failed* (10.42%) tetap perlu dipantau dan dianalisis penyebabnya.
3. **Segmen Retail mendominasi** kontribusi transaksi, sehingga strategi bisnis bisa terus difokuskan pada segmen ini sambil menjajaki potensi pertumbuhan di segmen lain (Premium, SME).
4. **Maharashtra menjadi wilayah dengan nilai transaksi tertinggi**, indikasi pasar utama yang perlu dipertahankan dan dijadikan tolok ukur ekspansi ke wilayah lain.
5. **Distribusi gender cukup seimbang**, tidak menunjukkan bias signifikan terhadap salah satu segmen gender pelanggan.

---

## 🛠️ Tools yang Digunakan

- **Power BI** — pembuatan dashboard & visualisasi interaktif
- **Data source**: dataset transaksi keuangan (finance/transaction dataset)

---

## 👤 Author

**Zahra Anadhifah**
GitHub: [@zahraanadhfh](https://github.com/zahraanadhfh)
