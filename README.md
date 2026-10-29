# Katalog Tech & Gear - Flutter Mobile App

Aplikasi katalog produk berbasis mobile Android yang dibuat menggunakan framework Flutter. Aplikasi ini mengambil data produk secara dinamis melalui REST API dari `dummyjson.com` dan mendukung tampilan katalog responsif, fitur pencarian, serta halaman detail produk.

Aplikasi ini dikembangkan untuk memenuhi Tugas Praktikum Pemrograman Mobile.

---

## Fitur Utama

- **Integrasi REST API**: Fetching data produk secara asynchronous menggunakan package `http`.
- **Tampilan Grid Katalog**: Penyajian item katalog dalam bentuk GridView dua kolom dengan tema warna pastel.
- **Pencarian Real-time**: Filter produk berdasarkan kata kunci pencarian.
- **Halaman Detail Produk**: Menampilkan informasi lengkap produk (gambar resolusi penuh, harga, rating, dan deskripsi).
- **Native Android Build**: Dijalankan secara native pada perangkat Android fisik (Samsung Galaxy A15).

---

## Tech Stack

- **Framework**: Flutter
- **Bahasa Pemrograman**: Dart
- **State Management**: StatefulWidget (Native)
- **Networking**: `http` package
- **Data Source**: [DummyJSON API](https://dummyjson.com/products)
- **Target Platform**: Android (Native)

---

## Persyaratan Sistem & Dependensi

Sebelum menjalankan proyek ini, pastikan sistem kamu sudah terpasang:
- Flutter SDK (v3.x atau terbaru)
- Dart SDK
- Android Studio & Android SDK Command-line Tools
- Device Android (Fisik / Emulator) dengan opsi USB Debugging aktif

---

## Cara Menjalankan Proyek

1. **Clone Repositori**
   ```bash
   git clone [https://github.com/USERNAME/REPO-NAME.git](https://github.com/USERNAME/REPO-NAME.git)
   cd katalog_pastel
