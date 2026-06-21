# CatatanUtang

CatatanUtang adalah aplikasi Android untuk membantu pemilik warung atau usaha kecil mencatat hutang pelanggan dengan lebih rapi, cepat, dan mudah dipantau. Aplikasi ini dibuat agar pemilik usaha bisa melihat total piutang, mencatat pelanggan baru, menambah hutang, serta menerima pembayaran pelanggan dari satu dashboard sederhana.

## Tampilan Aplikasi

| Dashboard | Catat Transaksi |
| --- | --- |
| ![Dashboard CatatanUtang](docs/screenshots/dashboard-menu.png) | ![Form Catat Transaksi](docs/screenshots/catat-transaksi.png) |

## Fitur Utama

- Dashboard ringkas untuk melihat total piutang dan hutang jatuh tempo.
- Tambah pelanggan baru lengkap dengan nama, nomor WhatsApp, alamat, dan nominal hutang awal.
- Catat transaksi pelanggan dengan dua tipe transaksi:
  - Tambah Hutang untuk menambah saldo hutang pelanggan.
  - Terima Pembayaran untuk mengurangi saldo hutang pelanggan.
- Pilih pelanggan melalui dropdown atau ketik nama pelanggan secara manual.
- Data dashboard otomatis ikut berubah setelah transaksi dikonfirmasi.
- Daftar pelanggan menampilkan informasi pelanggan dan sisa hutang terbaru.
- Profil pengguna dengan nama, inisial, dan foto profil.
- Deteksi lokasi untuk mendukung pencatatan transaksi berbasis lokasi.
- Tampilan mobile yang bersih, modern, dan mudah digunakan.

## Alur Penggunaan

1. Pengguna membuka aplikasi dan masuk ke dashboard.
2. Pengguna dapat menambahkan pelanggan baru dari tombol tambah.
3. Jika pelanggan ingin berhutang lagi, pengguna memilih menu Catat Transaksi lalu memilih Tambah Hutang.
4. Jika pelanggan membayar hutang, pengguna memilih Terima Pembayaran.
5. Setelah transaksi dikonfirmasi, total piutang dan sisa hutang pelanggan langsung diperbarui di dashboard.

## Teknologi

- Kotlin
- Android Native Views
- SharedPreferences untuk penyimpanan data lokal
- Material Components
- Gradle Kotlin DSL

## Struktur Project

```text
CatatanUtang/
+-- app/
|   +-- src/main/
|       +-- java/com/example/catatanutang/
|       +-- res/
+-- docs/screenshots/
+-- build.gradle.kts
+-- settings.gradle.kts
```

## Cara Menjalankan

1. Buka project ini di Android Studio.
2. Pastikan JDK yang digunakan minimal Java 11.
3. Sinkronkan Gradle.
4. Jalankan aplikasi ke emulator atau perangkat Android.

Atau build melalui terminal:

```bash
./gradlew assembleDebug
```

Untuk Windows:

```powershell
.\gradlew.bat assembleDebug
```

## Status

Project ini masih dalam tahap pengembangan. Fitur yang sudah tersedia berfokus pada pencatatan pelanggan, transaksi hutang, pembayaran, dan ringkasan dashboard.
