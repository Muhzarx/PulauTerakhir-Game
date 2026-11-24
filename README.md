# 🏝️ Pulau Terakhir — Survival Adventure Game

<p align="center">
  <img src="https://img.shields.io/badge/Genre-Adventure%20%2F%20Survival-2ea44f?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Platform-Web%20%7C%20Android-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Development-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-Copyright-red?style=for-the-badge" />
</p>

<p align="center">
  <b>Survive the island. Explore the unknown. Find your way home.</b>
</p>

<p align="center">
  Sebuah game petualangan dan survival 2D yang mengajak pemain bertahan hidup di sebuah pulau misterius setelah mengalami kecelakaan kapal.
</p>

---

## 🎮 Live Demo

Mainkan Pulau Terakhir langsung melalui browser tanpa perlu mengunduh atau memasang aplikasi.

<p align="center">
  <a href="https://muhzarx.github.io/PulauTerakhir-Game/">
    <img src="https://img.shields.io/badge/▶_PLAY_NOW-MAINKAN_SEKARANG-2ea44f?style=for-the-badge&logo=github" alt="Play Now" />
  </a>
</p>

**Live Demo:** https://muhzarx.github.io/PulauTerakhir-Game/

> Catatan: Live Demo dapat diakses setelah GitHub Pages diaktifkan dan file game berhasil dipublikasikan.

---

## 📖 Tentang Game

Pulau Terakhir merupakan game bergenre **Adventure / Survival** dengan perspektif 2D Top-Down.

Pemain berperan sebagai seseorang yang terdampar di sebuah pulau misterius setelah kapal yang ditumpanginya mengalami kecelakaan.

Tanpa persediaan makanan, air, maupun perlengkapan bertahan hidup, pemain harus memanfaatkan sumber daya alam untuk mempertahankan hidup.

Jelajahi lingkungan pulau, kumpulkan material, buat perlengkapan, bangun tempat perlindungan, dan temukan cara untuk kembali ke rumah.

**Setiap keputusan menentukan seberapa lama kamu mampu bertahan hidup.**

## ✨ Fitur Utama

- 🌴 **Island Exploration** — Jelajahi pulau dan temukan berbagai area.
- ❤️ **Health System** — Jaga kesehatan karakter agar tetap hidup.
- 🍖 **Hunger System** — Kelola kebutuhan makanan.
- 💧 **Thirst System** — Pastikan persediaan air selalu tersedia.
- 🪵 **Resource Gathering** — Kumpulkan kayu, batu, dan sumber daya lainnya.
- 🛠️ **Crafting System** — Buat perlengkapan untuk bertahan hidup.
- 🏕️ **Survival Mechanics** — Bangun tempat perlindungan dan kelola kebutuhan karakter.
- 🌙 **Day & Night Cycle** — Hadapi perubahan kondisi siang dan malam.
- 💾 **Save System** — Simpan perkembangan permainan.
- 📱 **Mobile Support** — Dirancang agar dapat dimainkan melalui perangkat Android.

*Fitur dan mekanisme permainan akan terus dikembangkan mengikuti roadmap proyek.*

## 🕹️ Gameplay

Tujuan utama permainan adalah bertahan hidup selama mungkin dan menemukan jalan keluar dari pulau.

Aktivitas pemain meliputi:

1. Mengeksplorasi lingkungan pulau.
2. Mengumpulkan sumber daya alam.
3. Mengelola makanan, air, dan kesehatan.
4. Membuat peralatan melalui crafting.
5. Membangun tempat perlindungan.
6. Menghadapi berbagai tantangan lingkungan.
7. Menyelesaikan misi untuk menemukan jalan pulang.

## 🎯 Kontrol Permainan

| Tombol | Fungsi |
|---|---|
| W / ↑ | Bergerak ke atas |
| S / ↓ | Bergerak ke bawah |
| A / ← | Bergerak ke kiri |
| D / → | Bergerak ke kanan |
| Touch Control | Kontrol melalui layar sentuh |

*Kontrol dapat disesuaikan mengikuti implementasi versi permainan.*

## 📱 Platform

| Platform | Dukungan |
|---|---|
| Windows | Browser |
| Linux | Browser |
| macOS | Browser |
| Android | Web / APK |
| Tablet | Browser |

## 🚀 Cara Menjalankan Game

### 1. Melalui Browser

1. Buka halaman Live Demo.
2. Tunggu permainan dimuat.
3. Mulai petualangan dan bertahan hidup.

### 2. Menjalankan Secara Lokal

Clone repository:

```bash
git clone https://github.com/Muhzarx/PulauTerakhir-Game.git
```

Masuk ke direktori:

```bash
cd PulauTerakhir-Game
```

Jalankan menggunakan local development server atau buka melalui browser sesuai kebutuhan proyek.

### 3. Instalasi Android

Untuk membangun aplikasi Android menggunakan Capacitor:

```bash
npm install
npx cap add android
npx cap sync android
npx cap open android
```

Kemudian buka proyek melalui Android Studio dan lakukan proses Build APK.

## 🛠️ Teknologi

Teknologi yang digunakan dalam pengembangan proyek ini meliputi:

- HTML5
- CSS3
- JavaScript
- Progressive Web App (PWA)
- Capacitor
- GitHub Pages

## 📂 Struktur Proyek

```text
PulauTerakhir-Game/
│
├── index.html
├── manifest.webmanifest
├── sw.js
├── package.json
├── capacitor.config.json
│
├── assets/
│   ├── images/
│   ├── audio/
│   └── sprites/
│
└── README.md
```

*Struktur direktori dapat berkembang seiring penambahan fitur.*

## 🗺️ Roadmap Pengembangan

- [x] Konsep utama permainan
- [x] Prototype awal
- [x] Pengembangan versi web
- [x] Persiapan dukungan Android
- [ ] Pengembangan peta pulau yang lebih luas
- [ ] Penambahan hewan dan musuh
- [ ] Sistem combat
- [ ] Sistem crafting lanjutan
- [ ] Sistem pembangunan rumah
- [ ] Sistem quest dan storyline
- [ ] Pengembangan animasi karakter
- [ ] Penambahan efek suara dan musik
- [ ] Penyempurnaan UI/UX
- [ ] Optimasi performa Android
- [ ] Rilis versi stabil

## 🤝 Kontribusi

Pengembangan Pulau Terakhir terbuka terhadap ide, saran, dan laporan bug.

Jika menemukan masalah atau memiliki ide pengembangan:

1. Fork repository.
2. Buat branch baru.
3. Lakukan perubahan.
4. Kirim Pull Request.

Untuk laporan bug dan saran, silakan gunakan fitur Issues pada GitHub.

## 📌 Informasi Proyek

| Informasi | Detail |
|---|---|
| Nama Game | Pulau Terakhir |
| Genre | Adventure / Survival |
| Perspektif | 2D Top-Down |
| Mode | Single Player |
| Platform | Web & Android |
| Developer | Muhammad Hafizd Anshari |
| Repository | Muhzarx/PulauTerakhir-Game |

## 📜 Hak Cipta

**© 2026 Muhammad Hafizd Anshari. All Rights Reserved.**

Pulau Terakhir merupakan proyek game yang dikembangkan oleh Muhammad Hafizd Anshari.

Seluruh hak atas kode sumber asli, desain, identitas proyek, dan elemen kreatif yang dibuat secara orisinal dilindungi oleh hak cipta.

Dilarang menyalin, mendistribusikan ulang, menjual, atau menggunakan kembali bagian dari proyek ini untuk kepentingan komersial tanpa izin tertulis dari pemilik hak cipta.

---

<p align="center">
  <b>🏝️ PULAU TERAKHIR</b>
  <br />
  <i>One Island. One Survivor. One Last Chance.</i>
  <br /><br />
  Developed with ❤️ by <b>Muhammad Hafizd Anshari</b>
</p>
