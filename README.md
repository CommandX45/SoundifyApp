<div align="center">

# 🎵 Soundify Desktop

**Aplikasi pemutar musik desktop modern, cepat, dan bebas iklan dengan integrasi YouTube Music & sinkronisasi lirik.**

[![Platform](https://img.shields.io/badge/Platform-Windows-0078D6?style=flat-square&logo=windows)](https://github.com/CommandX45/SoundifyApp)
[![Release](https://img.shields.io/badge/Release-v1.0.0-1ed760?style=flat-square&logo=github)](https://github.com/CommandX45/SoundifyApp/releases)
[![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![Developer](https://img.shields.io/badge/Developed%20by-mata__bintang.id-black?style=flat-square&logo=visualstudiocode)](https://github.com/CommandX45)

</div>

---

## ✨ Fitur Baru di v1.1.0

- 👤 **Local Profile System**: Kustomisasi nama panggilan dan avatar emoji favorit langsung dari top bar tanpa perlu login akun cloud.
- ⏱️ **Smart Listening Tracker**: Pelacakan statistik mendengarkan di latar belakang secara otomatis (hanya mencatat waktu nyata pemutaran, kebal terhadap seek dan skip cepat).
- 📊 **Animated Soundify Recap**: Tampilan rekap musik bergaya *Story* interaktif (ala Spotify Wrapped) dengan animasi transisi:
  - Total jam dan menit mendengarkan dilengkapi persona musik (misal: *Burung Hantu*, *Audiophile Sejati*).
  - Sorotan Artis Top 1 dengan cincin cahaya (*glow ring*) dan daftar Top 5 Artis.
  - Lagu yang paling sering diputar beserta Top 5 Lagu.
  - Poster ringkasan rasio 9:16 yang estetik dan siap tangkap layar (*screenshot*).
  - Filter periode fleksibel (Bulan Ini, Tahun Ini, atau Sepanjang Waktu).
- 💾 **Mode Portabel (`portable.flag`)**: Cukup letakkan file kosong `portable.flag` di sebelah `.exe`, seluruh data riwayat dan profil (`user_data.json`) akan tersimpan rapi di dalam folder aplikasi tanpa menyentuh folder `%APPDATA%` sistem.

---

## 🌟 Fitur Utama

* **Pencarian & Pemutaran Cepat:** Streaming audio berkualitas tinggi langsung dari katalog YouTube Music tanpa jeda iklan[cite: 11, 23].
* **Lirik Sinkron Real-Time:** Menampilkan lirik lagu dinamis (*synced lyrics*) yang bergulir otomatis mengikuti detik alunan musik[cite: 11, 20].
* **Impor Playlist Spotify:** Cukup tempel tautan playlist Spotify publik, lagu-lagu akan langsung diindeks dan siap diputar[cite: 11, 23].
* **Discord Rich Presence:** Mempercantik profil Discord kamu dengan status *Listening to Soundify* lengkap dengan cover album, judul lagu, artis, dan bar durasi waktu[cite: 10, 22].
* **Audio Lab:** Equalizer grafis 10-band interaktif, efek transisi antar lagu (*Crossfade*), mode Audio Mono, dan pengaturan batas penyimpanan *cache*[cite: 20].
* **System Tray Control:** Dapat disembunyikan ke pojok *taskbar* Windows dengan menu klik-kanan untuk putar, jeda, ganti lagu, dan buka aplikasi[cite: 12].
* **Sistem Pembaruan Otomatis:** Periksa dan perbarui software ke versi terbaru langsung dari dalam aplikasi via GitHub Releases[cite: 22, 23].

---

## 💻 Prasyarat Sistem

* **Sistem Operasi:** Windows 10 atau Windows 11 (64-bit)
* **Portabel:** Siap pakai langsung tanpa perlu instal software tambahan (mesin pemutar audio sudah tertanam di dalam aplikasi).

---

## 🚀 Panduan Instalasi (Untuk Pengguna)

1. Buka halaman **[Releases](../../releases)** pada repositori ini[cite: 22].
2. Unduh file **`Soundify-v1.0.0.zip`** versi terbaru[cite: 22].
3. Ekstrak file ZIP tersebut ke folder komputer kamu (misalnya di `Documents` atau `Program Files`).
4. Buka folder hasil ekstrak, lalu klik dua kali **`SoundifyApp.exe`** untuk mulai mendengarkan musik[cite: 24].

---

## 🛠️ Menjalankan dari Kode Sumber (Untuk Pengembang)

Jika kamu ingin mengembangkan atau memodifikasi kode sumber aplikasi ini:

1. **Clone Repositori:**
   ```bash
   git clone [https://github.com/CommandX45/SoundifyApp.git](https://github.com/CommandX45/SoundifyApp.git)
   cd SoundifyApp
