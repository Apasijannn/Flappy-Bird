# 🐦 Flappy Bird - Construct 3 Edition

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)
![Construct 3](https://img.shields.io/badge/Engine-Construct%203-green)
![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20Mobile-orange)
![Published on Itch.io](https://img.shields.io/badge/Published%20on-Itch.io-FA5C5C?style=flat&logo=itchdotio)

Replikasi game arkade klasik **Flappy Bird** yang dibuat menggunakan engine **Construct 3**. Proyek ini difokuskan pada implementasi mekanik *gravity-based movement* dan *procedural obstacle spawning*.

## 🎮 Play Now
Kamu bisa langsung memainkan game ini secara gratis melalui halaman itch.io saya:
👉 **[Mainkan di itch.io](https://username-kamu.itch.io/nama-game-kamu)**

## ✨ Fitur Utama
- **Mekanik Flap:** Kontrol satu tombol (klik/tap) yang responsif.
- **Infinite Pipes:** Pipa di-generate dengan ketinggian acak secara terus-menerus.
- **Parallax Background:** Menambahkan kedalaman visual pada environment game.
- **High Score System:** Menyimpan skor tertinggi menggunakan sistem *Local Storage*.
- **Responsive Canvas:** Ukuran game menyesuaikan layar browser (Desktop/Mobile).

## 🛠️ Detail Teknis (Construct 3)
- **Engine:** Construct 3 (Event Sheet Visual Scripting).
- **Core Logic:**
  - `Sine Behavior`: Untuk efek melayang pada menu utama.
  - `Bullet Behavior`: Untuk pergerakan pipa dari kanan ke kiri.
  - `Every X Seconds`: Untuk *spawning* pipa secara berkala.
  - `Collision Detection`: Logika kalah saat menabrak pipa atau jatuh ke tanah.

## 📂 Struktur Folder
- `/src`: Berisi file proyek mentah `.c3p`.
- `/assets`: Aset visual dan audio yang digunakan.

## 🚀 Cara Import ke Construct 3
Jika kamu ingin mempelajari bagaimana logika game ini dibuat:
1. Download file `.c3p` dari folder `/src`.
2. Buka [Construct 3 Editor](https://editor.construct.net).
3. Import file tersebut dan klik **Preview**.

---
Dibuat dengan ❤️ sebagai bagian dari eksplorasi pengembangan game.
