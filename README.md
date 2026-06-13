# Template LaTeX Buku Tugas Akhir ITS

Template LaTeX resmi untuk buku tugas akhir ITS berdasarkan SK Rektor ITS No. 280 Tahun 2022, dengan struktur dan format yang telah disesuaikan untuk kebutuhan penulisan tugas akhir.


## Fitur

- Format halaman, margin, dan font sesuai aturan ITS
- Dilengkapi bagian-bagian standar buku tugas akhir (sampul, lembar pengesahan, abstrak, kata pengantar, daftar isi, bab, daftar pustaka, lampiran, biografi penulis)
- Daftar pustaka otomatis menggunakan biblatex dengan gaya APA
- Penomoran gambar, tabel, dan referensi otomatis
- Dukungan berbagai format gambar (JPEG, PNG)
- Daftar, persamaan ilmiah, dan tabel
- Kompilasi otomatis melalui GitHub Actions
- Dilengkapi contoh penulisan: persamaan, tabel, kode program, figure, subfigure, timeline, dan lainnya

## Struktur direktori

```
├── main.tex                  # Dokumen utama
├── abstrak/                  # Abstrak Bahasa Indonesia dan Inggris
├── bab/                      # File .tex per bab dan sub-bab
├── gambar/                   # Berkas gambar
├── lainnya/                  # Lembar pengesahan, kata pengantar, pernyataan, biografi
├── program/                  # Contoh kode program
├── lampiran/                 # Kode program lampiran
├── pustaka/                  # Daftar pustaka (.bib) dan variabel identitas
└── sampul/                   # Sampul luar dan dalam
```

## Cara menggunakan

1. Isi identitas Anda di `pustaka/variables.tex`
2. Ubah judul dan konten abstrak di `abstrak/`
3. Ubah lembar pengesahan dan pernyataan keaslian di `lainnya/` (atau gunakan file PDF)
4. Tulis bab-bab di `bab/` dan subdirektorinya
5. Tambahkan gambar ke `gambar/`
6. Tambahkan daftar pustaka ke `pustaka/pustaka.bib`
7. Kompilasi dengan `pdflatex`, `biber`, `pdflatex` (atau gunakan GitHub Actions)

## Prasyarat

Sebelum mengompilasi, pastikan telah menginstal:

- **TeX Live** (disarankan) — https://tug.org/texlive/
  - Atau distribusi LaTeX lain (MiKTeX, etc.)
- Paket-paket berikut (otomatis tersedia pada instalasi TeX Live penuh):
  - `biblatex` + `biber` (daftar pustaka gaya APA)
  - `listings` (kode program)
  - `txfonts` (font Times)
  - `amsmath`, `amssymb` (matematika)
  - `graphicx`, `subcaption`, `float` (gambar)
  - `tabularx`, `longtable`, `makecell`, `multirow`, `booktabs`, `colortbl` (tabel)
  - `titlesec`, `fancyhdr` (tata letak halaman)
  - `hyperref` (PDF metadata)

## Kompilasi

Jalankan perintah berikut secara berurutan:

```bash
pdflatex main
biber main
pdflatex main
pdflatex main
```

Atau gunakan `latexmk` untuk kompilasi otomatis:

```bash
latexmk -pdf main
```

Repositori ini juga dilengkapi **GitHub Actions** (`.github/workflows/ci.yaml`) yang akan mengompilasi dan mendeploy PDF ke GitHub Pages setiap kali ada push ke branch `main`.

## Referensi

Template ini merupakan modifikasi dari:

1. [**template-buku-ta-its**](https://github.com/b201lab/template-buku-ta-its) — template resmi LaTeX buku tugas akhir ITS berdasarkan SK Rektor ITS No. 280 Tahun 2022.
2. [**TUGAS-AKHIR**](https://github.com/AgathaSamuel/TUGAS-AKHIR) — buku tugas akhir Agatha Samuel Sitompul yang dikembangkan dari template di atas dengan penambahan fitur penulisan (persamaan, tabel, kode, timeline, subfigures, dll.).

## Lisensi

MIT


