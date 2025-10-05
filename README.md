# Apotek Gia Farma

Situs static (frontend-only) untuk manajemen apotek sederhana.
Data disimpan di browser (localStorage). Struktur:
- index.html (halaman login)
- dashboard.html (sistem utama)

## Cara menjalankan secara lokal
1. Tempatkan `index.html` dan `dashboard.html` di folder yang sama.
2. Buka `index.html` di browser.
3. Login menggunakan `admin` untuk akses penuh atau nama lain untuk role kasir.

## Deploy ke GitHub Pages
1. Buat repository baru di GitHub.
2. Upload file `index.html`, `dashboard.html`, dan README.md.
3. Di repo settings -> Pages, pilih branch `main` dan folder `/ (root)`.
4. Tunggu beberapa menit, akses di `https://<username>.github.io/<repo>/`.

## Catatan
- Untuk penyimpanan server-side dan multi-user, integrasikan backend (Node/Express + DB atau Firebase).
- File ini dibuat sebagai starting point untuk pengembangan lebih lanjut.
