# Latihan Praktikum 4 - Pemrograman Mobile

Latihan Praktikum 4 mata kuliah Pemrograman Mobile di Universitas Esa Unggul. Aplikasi ini dibuat menggunakan Flutter untuk mendemonstrasikan penerapan *Design System* sederhana, pembuatan *reusable widget*, dan integrasi link eksternal ke Google Maps.

## Fitur Utama

- **Custom Theme**: Pengaturan tema aplikasi berbasis Material 3 (`lib/theme/app_theme.dart`).
- **Reusable AppButton**: Widget tombol yang bisa digunakan kembali dengan dukungan label, ikon, dan penanganan URL (`lib/widgets/app_button.dart`).
- **Integrasi Google Maps**: Tombol pada halaman utama untuk membuka lokasi kampus Universitas Esa Unggul di Google Maps menggunakan `url_launcher`.

## Struktur Project

```text
lib/
├── main.dart             # Entry point & tampilan halaman utama
├── theme/
│   └── app_theme.dart    # Konfigurasi ThemeData & skema warna
└── widgets/
    └── app_button.dart   # Widget tombol kustom
```

## Cara Menjalankan

1. Clone repositori:
   ```bash
   git clone https://github.com/nadhifshoeemagoldist-wq/LatihanPraktikum4.git
   cd LatihanPraktikum4
   ```

2. Install dependensi:
   ```bash
   flutter pub get
   ```

3. Jalankan aplikasi:
   ```bash
   flutter run
   ```
