# Jalur Cerna

Situs belajar interaktif **Sistem Pencernaan Manusia** untuk siswa SMP–SMA, disusun dari Modul Ajar IPA Kelas VIII (Kurikulum Merdeka, model Problem Based Learning).

## Isi

- **Materi**: diagram organ yang bisa diketuk, animasi perjalanan makanan, skala pH, enzim, perubahan zat makanan, dan gangguan di setiap organ. Dilengkapi latihan memilah pencernaan mekanis/kimiawi dan tabel ringkasan enzim.
- **Model PBL**: pengertian, ciri, identitas modul, capaian dan tujuan pembelajaran.
- **Sintaks PBL**: lima fase menurut Arends (2012) beserta aktivitas LKPD berbasis kasus Dimas.
- **Kuis**: 12 soal dengan pembahasan langsung.

## Struktur

```
index.html        seluruh halaman (HTML, CSS, JS dalam satu file)
favicon.svg       ikon tab
.github/workflows/pages.yml   deploy otomatis ke GitHub Pages
```

Tidak ada proses build atau dependensi. Untuk mencoba di komputer, buka `index.html` langsung di browser.

## Deploy

Setiap push ke branch `main` otomatis dideploy ke GitHub Pages lewat GitHub Actions.
Syarat sekali saja: **Settings → Pages → Build and deployment → Source: GitHub Actions**.

## Catatan

Isian LKPD, centang refleksi, dan skor kuis tersimpan di browser masing-masing siswa (localStorage), tidak dikirim ke server.
