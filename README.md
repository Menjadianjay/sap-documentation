<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:16213e,100:0f3460&height=200&section=header&text=SAP%20Documentation&fontSize=52&fontColor=e94560&fontAlignY=38&desc=Analisis%20Proses%20Bisnis%20%7C%20Universitas%20Sanata%20Dharma&descAlignY=58&descSize=16&descFontColor=a8b2d8" width="100%"/>

<br/>

![Modul](https://img.shields.io/badge/Modul%20Selesai-6%20Laporan-e94560?style=for-the-badge&logo=bookstack&logoColor=white)
![Exercise](https://img.shields.io/badge/Exercise-15%20Selesai-0f3460?style=for-the-badge&logo=checkmarx&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-1a6b3c?style=for-the-badge&logo=statuspage&logoColor=white)
![Tahun](https://img.shields.io/badge/Tahun-2026-orange?style=for-the-badge&logo=calendar&logoColor=white)

<br/>

> **Repositori dokumentasi laporan praktikum mata kuliah Analisis Proses Bisnis**  
> *Implementasi praktikum menggunakan sistem SAP ERP — Universitas Sanata Dharma Yogyakarta*

</div>

---

<div align="center">

| Info | Detail |
|------|--------|
| **Mata Kuliah** | Analisis Proses Bisnis |
| **Prodi** | Informatika — Fakultas Sains dan Teknologi |
| **Universitas** | Universitas Sanata Dharma, Yogyakarta |
| **Dosen** | Agnes Maria Polina, S.Kom., M.Sc. |
| **Tahun** | 2026 |

</div>

---

##  Daftar Laporan Praktikum

### Modul 1 — Login, Navigation & Master Data

> **Folder:** `1/`

| # | Topik | Keterangan |
|---|-------|------------|
| I | Login & Navigation | Koneksi ke sistem SAP, login, pengecekan status dengan `/nsm04` |
| II.1 | Display Customer Master | Navigasi menu Logistics → Customer → Display Complete |
| II.2 | Change Customer Master | Mengubah Shipping Condition menjadi *Immediately* & Delivery Priority |
| III.1 | Display Material Master | Menampilkan material id `578` (Sunny Sunny), Basic Data, Plant Stock |
| III.2 | Create Material Master | Membuat material `T-MMC-04` (Printer), konfigurasi MRP, Accounting, Sales |

---

### Modul 2 — Procurement / Purchasing (MM)

> **Folder:** `2/`

| # | Exercise | Topik |
|---|----------|-------|
| 1 | Exercise 4-1 | Membuat Purchase Order untuk stok material |
| 2 | Exercise 4-2 | Goods Receipt — membuat nota belanja dengan referensi PO |
| 3 | Exercise 4-3 | Publikasi Invoice (Logistics Invoice Verification) |

---

### Modul 3 — Sales & Distribution (SD)

> **Folder:** `3/`

| # | Exercise | Topik |
|---|----------|-------|
| 1 | Exercise 4-4 | Membuat Standard Sales Order (kode OR) |
| 2 | Exercise 4-5 | Membuat Outbound Delivery & Post Goods Issue |
| 3 | Exercise 4-6 | Membuat Billing Document & melihat Document Flow |

---

### Modul 4 — Production Planning (PP)

> **Folder:** `4/LAPRAK/`

| # | Exercise | Topik |
|---|----------|-------|
| 1 | Exercise 4-7 | Menampilkan Material BOM (Bill of Materials) |
| 2 | Exercise 4-8 | Menampilkan Stock/Requirements List |
| 3 | Exercise 4-9 | Membuat & memverifikasi Production Order (Final Confirmation) |

---

### Modul 5 — Financial Accounting (FI)

> **Folder:** `5/`

| # | Exercise | Topik |
|---|----------|-------|
| 1 | Exercise 5-1 | Menampilkan Chart of Accounts (kode INT) — G/L Account `160000` |
| 2 | Exercise 5-2 | Display Vendor Line Items & Post Outgoing Payment |
| 3 | Exercise 5-3 | Display Customer Line Items & Post Incoming Payment |

---

### Modul 6 — Controlling (CO)

> **Folder:** `6/`

| # | Exercise | Topik |
|---|----------|-------|
| 1 | Exercise 5-4 | Membuat Cost Center (`SAP01-C04`, Hierarchy H9500) |
| 2 | Exercise 5-5 | Memproses Vendor Invoice & melihat laporan Cost Center Actual/Plan/Variance |

---

### Modul Lanjutan

> Folder `7/` — `16/` & `PROJECT-GENAP/`

---

## Struktur Repositori

```
📦 sap-documentation/
│
├── 📂 1/                        # Modul 1 — Login & Master Data
├── 📂 2/                        # Modul 2 — Purchasing (MM)
├── 📂 3/                        # Modul 3 — Sales & Distribution (SD)
├── 📂 4/
│   └── 📂 LAPRAK/               # Modul 4 — Production Planning (PP)
├── 📂 5/                        # Modul 5 — Financial Accounting (FI)
├── 📂 6/                        # Modul 6 — Controlling (CO)
├── 📂 7/ – 📂 16/
│   └── 📂 LAPRAK/               # Modul lanjutan (akan diperbarui)
│
├── 📂 PROJECT-GENAP/            # Proyek Akhir Semester Genap
├── 📄 TEMPLATE.docx             # Template laporan resmi
└── 🔧 SCHEDULE_COPY.bat.txt     # Script backup otomatis (Windows)
```

---

## Script Backup Otomatis

File `SCHEDULE_COPY.bat.txt` adalah Windows Batch script untuk backup laporan ke tiga destinasi sekaligus menggunakan `robocopy`.

```bash
# 1. Rename file
rename SCHEDULE_COPY.bat.txt SCHEDULE_COPY.bat

# 2. Sesuaikan path di dalam file:
#    BASE  → Direktori laprak utama
#    DEST1 → Backup lokal
#    DEST2 → External drive
#    DEST3 → Flashdisk

# 3. Jalankan
./SCHEDULE_COPY.bat
```


<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-Menjadianjay-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Menjadianjay)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f3460,50:16213e,100:1a1a2e&height=120&section=footer" width="100%"/>

</div>
