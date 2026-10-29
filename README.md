# Katalog Tech & Gear - Flutter Mobile App

Aplikasi katalog produk berbasis mobile Android yang dikembangkan menggunakan framework Flutter. Aplikasi ini mengambil data produk secara dinamis melalui REST API dari `dummyjson.com` serta mendukung tampilan katalog responsif, fitur pencarian real-time, dan halaman detail produk.

---

## Fitur Utama

- **Integrasi REST API**: Fetching data produk secara asynchronous menggunakan package `http`.
- **Tampilan Grid Katalog**: Penyajian item katalog dalam bentuk grid dua kolom dengan nuansa warna pastel.
- **Pencarian Real-time**: Filter produk berdasarkan kata kunci pencarian secara otomatis.
- **Halaman Detail Produk**: Menampilkan informasi lengkap produk meliputi gambar resolusi penuh, harga, rating, dan deskripsi.
- **Native Android Build**: Dikompilasi dan dijalankan secara native pada perangkat Android fisik (Samsung Galaxy A15).

---

## Video Demonstrasi

Tonton video demonstrasi pengujian aplikasi pada perangkat Android fisik melalui link berikut:
- **YouTube**: [https://www.youtube.com/watch?v=LINK_VIDEO_KAMU](https://www.youtube.com/watch?v=LINK_VIDEO_KAMU)

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

Sebelum menjalankan proyek ini, pastikan sistem telah terpasang:
- Flutter SDK (v3.x atau terbaru)
- Dart SDK
- Android Studio & Android SDK Command-line Tools
- Device Android (Fisik / Emulator) dengan USB Debugging aktif

---

## Cara Menjalankan Proyek

1. **Clone Repositori**
   ```bash
   git clone [https://github.com/USERNAME/REPO-NAME.git](https://github.com/USERNAME/REPO-NAME.git)
   cd katalog_pastel
   ```

2. **Install Dependensi**
   ```bash
   flutter pub get
   ```

3. **Pastikan Perangkat Terhubung**
   ```bash
   flutter devices
   ```

4. **Jalankan Aplikasi**
   ```bash
   flutter run
   ```

---

## Struktur Folder

```text
lib/
├── main.dart             # Entry point aplikasi & konfigurasi tema
├── models/
│   └── product.dart      # Model data produk dari DummyJSON
├── services/
│   └── api_service.dart  # Logika fetching HTTP request
└── screens/
    ├── home_screen.dart  # Halaman katalog utama & search bar
    └── detail_screen.dart# Halaman detail informasi produk
```

---

## Identitas Pengembang

- **Nama**: Muhammad Viary Hanifasha Maulana
- **NIM**: 254025001
- **Program Studi**: Teknik Informatika
- **Perguruan Tinggi**: Universitas Muhammadiyah Bandung
