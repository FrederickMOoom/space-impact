# 🚀 Space Impact: Cute Alien Adventure! 👾✨

Game petualangan aksi luar angkasa bergaya kartun yang seru, penuh warna ceria, ramah anak (*family-friendly*), dan beranimasi mulus (*smooth* 60 FPS). Terinspirasi dari game klasik retro *Space Impact*, kini dengan visual modern, desain responsif untuk PC & Android, sistem leaderboard, bos kelipatan 200 poin, serta koleksi 9 pesawat dengan animasi tembakan unik!

![HTML5](https://img.shields.io/badge/Game-HTML5%20Canvas-orange?style=for-the-badge)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-yellow?style=for-the-badge)
![CSS3](https://img.shields.io/badge/CSS-Responsive-blue?style=for-the-badge)
![Web Audio](https://img.shields.io/badge/Audio-Web%20Audio%20API-purple?style=for-the-badge)

---

## 🌟 Fitur Utama

- **📱 & 💻 Desain Responsif Penuh (PC & Android)**:
  - **PC / Desktop**: Rasio 4:3 dinamis tanpa scrollbar, panduan tombol keyboard di bawah layar, mode layar penuh (`F`), dan tombol on-screen toggle (`🎮`).
  - **Android Portrait (Handheld Console Mode)**: Tata letak konsol portabel genggam (GameBoy / Switch style) lengkap dengan **D-Pad multi-touch slide** dan **tombol Fire hold-to-shoot**.
  - **Android Landscape**: Tampilan layar penuh horizontal dengan kontrol di pojok kiri dan kanan bawah, aman dari *safe-area insets*.
  - **Touch-to-Move**: Dukungan kontrol langsung geser jari di atas layar canvas dengan auto-fire continuous tanpa jeda.

- **👾 Boss Tiap Kelipatan 200 Poin (Multi-Tier Boss Engine)**:
  - Bos muncul otomatis setiap kelipatan **200 poin** (200, 400, 600, 800, 1000+).
  - 👑 **Tier 1 (200)**: *Raja Jeli Blobby* (Slime mahkota emas, HP 120, peluru spiral).
  - 🐙 **Tier 2 (400)**: *Ratu Octo-Puff* (Gurita ungu kosmik, HP 180, tembakan kipas 3 arah).
  - 🦖 **Tier 3 (600)**: *Jenderal Chompy* (Monster lapis baja hijau, HP 260, semburan peluru cepat).
  - 🦑 **Tier 4 (800)**: *Kaisar Tentaking* (Kraken abisal raksasa, HP 350, serangan tentakel ganda).
  - 🌌 **Tier 5+ (1000+)**: *Dewa Bintang Void-Lord* (Dewa nebula kosmik berputar, HP 450+, salvo peluru menyeluruh).

- **🏆 Papan Peringkat Persisten (Leaderboard)**:
  - Menyimpan Top 10 skor tertinggi di penyimpanan lokal browser (`localStorage`).
  - Mencatat Peringkat, Nama Pilot, Skor Akhir, Level, Ikon Pesawat, dan Tanggal.
  - Medali penghargaan untuk Juara 1 (Emas 🥇), Juara 2 (Perak 🥈), dan Juara 3 (Perunggu 🥉).
  - Form input nama pilot saat Game Over dan tombol akses di HUD (`🏆`), Menu Utama, Menu Jeda, dan shortcut tombol `L`.

- **🛒 Toko Pesawat (Hangar) & 4 Tingkat Kelangkaan (Rarity)**:
  - ⚪ **Common**:
    - 🐱 **Astro-Cat** (Default): Tembakan *Bintang Kejora* ⭐ (Dart bintang berputar).
    - 🐤 **Robo-Chirp** (10 🪙): Tembakan *Cincin Sonik* 🔘 (Cincin suara frekuensi tinggi).
  - 🔵 **Rare**:
    - 🐰 **Candy-Bunny** (25 🪙): Tembakan *Hati Gula-Gula* 💖 (Peluru hati pink manis).
    - 🐸 **Mecha-Frog** (40 🪙): Tembakan *Plasma Gelembung* 🟢 (Gelembung plasma hijau zamrud).
  - 🟣 **Epic**:
    - 🐶 **Puppy-Hero** (60 🪙): Tembakan *Tulang Surya* 🦴 (Tulang energi emas berputar).
    - 🦖 **Dino-Jet** (80 🪙): Tembakan *Cakar Api Naga* 🐾🔥 (Cakar api menyala tajam).
    - 🦊 **Cyber-Fox** (100 🪙): Tembakan *Tombak Petir Plasma* ⚡ (Panah petir ultraviolet cepat).
  - 🟡🌈 **Legendary**:
    - 🛸 **Cosmic-UFO** (150 🪙): Tembakan *Kristal Nebula Kosmik* 💎 (Berlian prisma berpelangi).
    - 🦅🔥 **Phoenix-Prime** (200 🪙): Tembakan *Nova Burung Api* 🔥 (Burung api raksasa berkilau).
  - Kartu Legendary dilengkapi efek visual animasi border pelangi bersinar (*rainbow glow*).

- **✨ Efek Suara & Visual Tembakan Unik**: Setiap pesawat memiliki proyektil kustom dan profil sintesis Web Audio API tersendiri tanpa membutuhkan file suara eksternal.

---

## 🎮 Kontrol Permainan

### PC / Komputer:
- **WASD / Tombol Panah**: Menggerakkan pesawat
- **Spasi**: Menembak
- **Escape / P**: Jeda / Buka Menu
- **F**: Toggle Layar Penuh (Fullscreen)
- **M**: Mute / Unmute Suara
- **L**: Buka / Tutup Papan Juara (Leaderboard)

### Android / Perangkat Sentuh:
- **D-Pad Virtual**: Sentuh & geser jempol untuk navigasi 8 arah yang mulus
- **Tombol FIRE**: Tahan jempol untuk menembak bertubi-tubi secara kontinu (*hold-to-fire*)
- **Touch-to-Move**: Geser jari langsung pada layar pertempuran untuk meluncur dan menembak otomatis
- **Tombol Konsol**: Akses cepat jeda, toko pesawat, dan papan juara

---

## 🚀 Cara Menjalankan

Cukup klik ganda file `index.html` pada browser apa pun (Google Chrome, Microsoft Edge, Mozilla Firefox, Opera, Safari). Tidak memerlukan instalasi server atau dependensi tambahan!
