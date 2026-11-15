# Tugas 3 Komputasi Awan - Deployment Website (GitHub Pages)

Website statis tiga halaman (HTML + CSS) yang dipublikasikan melalui GitHub Pages.

## Struktur berkas
```
index.html         -> Beranda (landing page)
materi.html        -> Materi Komputasi Awan
portofolio.html    -> Portofolio Tugas
assets/css/style.css
assets/images/     -> foto-profil, favicon
```

## Yang WAJIB diganti sebelum upload
| Berkas | Ganti |
|---|---|
| index.html, materi.html, portofolio.html | `NAMA LENGKAP` dan `000000000` (NIM), Program Studi |
| assets/images/foto-profil.svg | Ganti dengan foto Anda (misal `foto-profil.jpg`), lalu ubah `src` di index.html |
| portofolio.html | Judul, ringkasan, dan tautan Tugas 1 dan Tugas 2 |

## Cara membuat versi 2 (cukup ubah satu hal)
Buka `assets/css/style.css`, ubah warna pada baris:
```css
--primary: #4f46e5;
--accent:  #06b6d4;
```
Ubah juga teks `Versi 1.0` pada footer menjadi `Versi 2.0`, lalu commit dengan pesan **Pembaruan versi 2**.
