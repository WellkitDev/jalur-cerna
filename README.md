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

Situs live: https://wellkitdev.github.io/jalur-cerna/

Setiap push ke branch `main` menjalankan GitHub Actions (`.github/workflows/pages.yml`): file situs dicek, lalu diterbitkan ke branch `gh-pages`. GitHub Pages menayangkan branch `gh-pages` (Settings → Pages → Source: Deploy from a branch → `gh-pages` / root). Jangan mengedit branch `gh-pages` langsung, karena isinya ditimpa setiap kali `main` berubah.

## Catatan

Isian LKPD, centang refleksi, dan skor kuis tersimpan di browser masing-masing siswa (localStorage), tidak dikirim ke server.
