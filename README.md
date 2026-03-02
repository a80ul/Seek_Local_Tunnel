# 🚀 Seek Local Tunnel (SLT) - Network Dashboard

**Seek Local Tunnel** adalah aplikasi desktop modern yang dirancang untuk memudahkan manajemen *tunneling* mesin lokal ke internet publik menggunakan `localtunnel`, sekaligus berfungsi sebagai Control Panel terintegrasi untuk layanan XAMPP.

---

## ⚠️ Prasyarat Sistem (Penting)

Meskipun aplikasi ini berbentuk `.exe`, sistem Anda tetap memerlukan "mesin" pendukung agar fitur-fiturnya berjalan sempurna:

1.  **Node.js & NPM**: Wajib terinstal agar perintah `npx` dapat menjalankan `localtunnel`. [Unduh Node.js di sini](https://nodejs.org/).
2.  **XAMPP**: Harus terinstal di direktori default (`C:\xampp\`) agar fitur Start/Stop Service dapat mendeteksi file sistem.
3.  **Koneksi Internet**: Diperlukan untuk proses jabat tangan (*handshake*) antara mesin lokal dan server tunnel publik.

---

## ✨ Fitur Utama
* **One-Click Tunneling**: Ekspos localhost ke URL publik secara instan dengan custom subdomain.
* **XAMPP Service Manager**: Kontrol layanan Apache, MySQL, FileZilla, Mercury, dan Tomcat langsung dari dashboard tanpa buka panel asli.
* **System Monitor**: Pantau penggunaan CPU dan RAM secara real-time untuk menjaga stabilitas server lokal.
* **Authentication System**: Sistem Login & Register lokal untuk memastikan hanya Anda yang memiliki akses ke dashboard.
* **Clean UI**: Antarmuka modern yang responsif, minimalis, dan bebas gangguan.
* **Live Log System**: Pantau aktivitas koneksi, URL yang digenerate, dan pesan error secara transparan.

---

## 🛠️ Teknologi di Balik Layar
Aplikasi ini dibangun menggunakan arsitektur **Eel**, menggabungkan kekuatan **Python** untuk kontrol sistem dan **Web Technologies** (HTML/CSS/JS) untuk antarmuka pengguna yang modern.

---

## 📖 Cara Menggunakan

1.  **Persiapan**: Pastikan Node.js dan XAMPP (di folder C:\xampp) sudah terinstal di komputer Anda.
2.  **Jalankan**: Buka file `Seek Local Tunnel.exe`.
3.  **Autentikasi**: Silakan lakukan Register (jika pertama kali) lalu Login untuk masuk ke dashboard.
4.  **Kontrol XAMPP**: Aktifkan layanan yang diperlukan (misal: Apache & MySQL) melalui tab XAMPP di dalam aplikasi.
5.  **Aktifkan Tunnel**: Masukkan Port (misal: 80) dan Subdomain pilihan Anda, lalu klik **Establish Connection**.
6.  **Selesai**: Tunggu hingga log memunculkan URL `https://...`. Proyek lokal Anda kini sudah online dan bisa diakses siapa saja!

---

## 🤝 Dukungan & Donasi

Jika proyek ini mempermudah pekerjaan Anda, pertimbangkan untuk memberikan dukungan agar pengembangan fitur baru tetap berjalan:

| Platform | Link / Widget |
| :--- | :--- |
| **Ko-fi** | [![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/a80ul) |
| **Saweria** | [![Saweria](https://img.shields.io/badge/Saweria-Donasi-orange?style=for-the-badge&logo=heart)](https://saweria.co/A80ul421) |
| **GitHub** | Berikan ⭐️ pada repositori ini sebagai bentuk apresiasi. |

---
Developed with ❤️ by **A80ul**
