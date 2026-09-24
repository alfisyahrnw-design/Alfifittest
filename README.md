# ALFI Test — Account Officer Fit Indicator

Tes interaktif berbasis situasi kerja untuk mengukur seberapa cocok seseorang dengan peran **Account Officer (AO)** di lembaga pembiayaan mikro.

🔗 Demo: buka `index.html` langsung di browser, atau aktifkan GitHub Pages (lihat di bawah).

## Tentang

ALFI Test terdiri dari **15 pertanyaan pilihan ganda** berbasis skenario kerja nyata, mencakup 6 aspek utama tugas AO:

| Aspek | Deskripsi |
|---|---|
| **PLAN** | Perencanaan pemasaran & kunjungan harian |
| **SURVEY** | Survei & analisa kelayakan calon nasabah |
| **PROCESS** | Administrasi pengajuan pembiayaan |
| **RELATION** | Kunjungan rutin & menjaga hubungan nasabah |
| **COLLECT** | Menagih & memonitor angsuran nasabah |
| **TEAM** | Koordinasi dengan KUM, FAO, dan SAO |

Setiap jawaban diberi skor 0–3 sesuai kedekatannya dengan perilaku ideal seorang AO. Di akhir tes, pengguna mendapat:
- Skor kecocokan keseluruhan (dalam %)
- Kategori hasil (Sangat Cocok / Cocok / Cukup Perlu Pendampingan / Kurang Cocok Saat Ini)
- Rincian skor per aspek kompetensi dalam bentuk bar chart

## Cara Pakai

Tidak perlu instalasi apa pun — ini murni file HTML statis (CSS & JavaScript sudah menyatu di dalamnya, tanpa dependency eksternal).

1. Unduh atau clone repo ini
2. Buka `index.html` di browser mana saja, atau
3. Hosting gratis lewat **GitHub Pages**:
   - Masuk ke **Settings → Pages** di repo ini
   - Pilih branch `main` dan folder root (`/`)
   - Simpan — GitHub akan memberi URL seperti `https://<username>.github.io/<nama-repo>/`

## Struktur File

```
.
├── index.html   # Seluruh aplikasi tes (HTML + CSS + JS dalam satu file)
└── README.md    # Dokumen ini
```

## Kustomisasi

Untuk mengubah pertanyaan, bobot skor, atau kategori hasil, edit langsung array `questions` dan blok `if/else` di bagian `showResult()` pada `index.html` — tidak perlu tool build tambahan.

## Lisensi

Bebas digunakan dan dimodifikasi untuk keperluan internal rekrutmen/pelatihan.
