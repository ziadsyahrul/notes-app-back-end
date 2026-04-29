# Notes App Backend

Backend sederhana untuk aplikasi Notes yang dibuat sebagai bagian dari submission Dicoding.

## Deskripsi
Project ini merupakan REST API backend yang digunakan untuk mengelola data catatan (notes). Backend ini menangani proses CRUD (Create, Read, Update, Delete) dan menjadi penghubung antara client dan data.

## Fitur
- Menambahkan catatan
- Melihat daftar catatan
- Melihat detail catatan
- Mengubah catatan
- Menghapus catatan

## Teknologi
- Node.js
- JavaScript (ES Module)
- ESLint

## Struktur Project
- `server.js` → entry point aplikasi
- `routes.js` → definisi endpoint API
- `handler.js` → logic handler untuk setiap request
- `notes.js` → penyimpanan data sementara

## Cara Menjalankan

1. Install dependencies
   ```bash
   npm install
   ```

2. Jalankan server
   ```bash
   npm run start
   ```

## Catatan
Project ini dibuat untuk keperluan pembelajaran dan submission Dicoding, sehingga implementasi masih sederhana dan belum menggunakan database permanen.
