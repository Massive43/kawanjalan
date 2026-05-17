[![Flutter Version](https://img.shields.io/badge/Flutter-3.x-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev)
[![Dart Version](https://img.shields.io/badge/Dart-3.x-0175C2?style=for-the-badge&logo=dart&logoColor=white)](https://dart.dev)
[![Platform](https://img.shields.io/badge/Platform-Android%20Only-green?style=for-the-badge&logo=android&logoColor=white)](#)

Aplikasi mobile berbasis **Flutter** yang dirancang khusus untuk platform **Android**. Berfungsi untuk mempermudah eksplorasi, perencanaan jadwal, dan pemesanan tiket destinasi wisata populer secara praktis. Memiliki desain antarmuka modern dengan konsep *Dark Mode* yang nyaman di mata, transisi yang intuitif, serta manajemen data lokal yang efisien.

---

## ✨ Fitur Utama

Aplikasi ini dilengkapi dengan berbagai modul interaktif yang mendukung pengalaman pengguna dari awal hingga proses pasca-wisata:

* **🔒 Autentikasi & Manajemen Akun:** Alur masuk terintegrasi dengan penanganan validasi input, fitur pemulihan kata sandi (*Forgot Password*), dan pembaruan data profil secara sinkron melalui penyimpanan data lokal (`UserDatabase`).
* **🔍 Eksplorasi Wisata & Pencarian Cerdas:** Beranda dinamis yang membagi destinasi ke dalam kategori *Destinasi Terlaris* dan *Rekomendasi*. Dilengkapi dengan pencarian berbasis teks dan pelacakan riwayat pencarian terakhir (*Search History*).
* **💬 Sistem Ulasan Interaktif (Review & Rating):** Pengguna dapat melihat daftar ulasan, memberikan penilaian berbasis bintang (1-5), serta menuliskan feedback langsung untuk tiap destinasi wisata secara *real-time*.
* **❤️ Manajemen Favorit:** Fitur bookmarking terpusat yang disinkronisasikan langsung antar halaman beranda dan tab khusus favorit untuk menyimpan lokasi impian.
* **📅 Manajer Jadwal Wisata:** Halaman monitoring status perjalanan untuk mengetahui destinasi mana yang sudah dikunjungi (`Selesai`) atau yang akan datang (`Mendatang`).
* **💳 Simulasi Pembayaran QRIS & E-Ticket:** Alur transaksi tiket yang aman dengan tampilan kode QRIS, validasi pembayaran, hingga penerbitan *E-Ticket* otomatis dengan generator QR Code unik per transaksi.
* **🚨 Pusat Bantuan Terpadu:** Menu pelaporan masalah langsung di halaman profil untuk mengirimkan kendala teknis atau laporan terkait pemandu wisata.

---

## 🛠️ Tech Stack & Arsitektur

* **Framework:** Flutter (Channel Stable)
* **Bahasa Pemrograman:** Dart 3.x
* **Target OS:** Android (API Level 21+)
* **Manajemen State:** Stateful Widget Lifecycle, Static Memory Database (RAM Cache)
* **Desain Antarmuka:** Custom Dark Theme (`Material 3` design tokens)
* **Tipografi:** Google Fonts (Poppins)

---

## 📂 Struktur Direktori Proyek

Arsitektur kode diatur secara modular agar mudah dikembangkan dan dipelihara (*maintainable*):
