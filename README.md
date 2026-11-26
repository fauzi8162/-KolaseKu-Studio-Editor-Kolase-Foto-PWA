# 🎨 KolaseKu Studio — Editor Kolase Foto PWA
Demo : https://fauzi8162.github.io/KolaseKu-Studio-Editor-Kolase-Foto-PWA/

![HTML5](https://img.shields.io/badge/HTML5-Canvas-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PWA](https://img.shields.io/badge/PWA-Ready-7C5CFF?style=for-the-badge)

**KolaseKu Studio** adalah aplikasi web progresif (*Progressive Web App* / PWA) berbasis **HTML5 Canvas** untuk menggabungkan dan mengedit kolase foto secara bebas maupun menggunakan template *auto-arrange*. Dirancang dengan pendekatan **Mobile-First** yang responsif untuk perangkat seluler (*touch gesture*) maupun desktop (*mouse & keyboard*).

Seluruh pemrosesan gambar berjalan **100% di sisi klien (lokal di browser)** tanpa mengunggah foto ke server mana pun, sehingga privasi pengguna terjaga sepenuhnya dan proses ekspor resolusi tinggi berjalan instan.

---

## ✨ Fitur Utama

### 🖼️ Manajemen Foto & Layer
* **Multi-Upload & Drag-and-Drop:** Tambahkan banyak foto sekaligus dari galeri HP atau komputer tanpa menimpa foto yang sudah ada.
* **Kontrol Layer Lengkap:** Atur urutan tumpukan (*naik, turun, paling depan, paling belakang*), duplikat, sembunyikan/tampilkan, kunci (*lock*) posisi, hingga tukar foto (*replace*) pada layer tertentu.
* **Undo & Redo:** Riwayat perubahan hingga 35 langkah terakhir (`Ctrl+Z` / `Ctrl+Y`).

### 📐 Template Layout & Bebas Atur (*Freeform*)
* **11 Preset Layout Instan:** Mulai dari mode *Bebas (Freeform)*, *Grid 2×2*, *3 Bento*, *1 Besar + 3*, *Grid 2×3 / 3×2*, hingga gaya *Scrapbook*.
* **Kustomisasi Jarak & Padding:** Atur jarak antar foto (*gap*) dan jarak tepi kanvas (*padding*) secara *real-time*.

### ✂️ Kontrol Gestur Sentuh & *In-Frame Crop*
* **Multi-Touch Mobile:**
  * **1 Jari:** Pilih dan geser posisi layer dengan panduan *smart snap* ke tengah kanvas.
  * **2 Jari:** *Pinch-to-zoom* dan putar (*rotate*) foto langsung di kanvas.
  * **Double-Tap / Mode Geser Isi:** Masuk ke mode *crop* di dalam bingkai untuk menggeser dan memperbesar bagian foto yang ditampilkan (*Rule of Thirds grid*).
* **Kontrol Desktop:** Mendukung klik-seret, *scroll wheel* untuk zoom, serta pintasan keyboard (`Delete`, `Esc`, `Enter`, `Ctrl+Z`, `Ctrl+Y`).

### 🎨 Dekorasi, Frame & Filter
* **6 Gaya Bingkai Dekoratif:** *Tanpa Frame*, *Minimalis Putih*, *Polaroid Klasik*, *Film Strip*, *Neon Glow*, dan *Vintage Paper*.
* **Latar Belakang Variatif:** Warna *Solid* (dengan *color picker*), 8 preset *Gradien*, serta pola (*Transparan*, *Polkadot*, *Grid Halus*, *Garis Miring*).
* **Edit Per Foto:** Atur skala, rotasi, opasitas, kelengkungan sudut (*border radius*), bayangan (*drop shadow*), *flip* horizontal/vertikal, serta 6 filter warna (*Normal, B&W, Sepia, Warm, Cool, Vivid*).

### 📱 Ukuran Kanvas, PWA & Ekspor Resolusi Penuh
* **Preset Rasio Populer:** `1:1` (Feed), `4:5` (Portrait), `9:16` (Story), `16:9` (Wide), `3:4`, `4:3`, `2:3`, serta input ukuran kustom hingga `4000 × 4000 px`.
* **Installable PWA:** Dilengkapi *Web App Manifest* dan ikon SVG dinamis sehingga dapat diinstal langsung ke layar utama Android maupun iOS (Safari) layaknya aplikasi native.
* **Ekspor & Bagikan:** Unduh hasil kolase dalam format **PNG** (mendukung latar transparan) atau **JPG** (dengan pengaturan kualitas), serta dukungan *Web Share API* untuk langsung membagikan ke media sosial.

 ### 📱 📁 Project Manager & Autosave
* **Auto-Save Lokal & Kelola Proyek:** Pulihkan otomatis editan terakhir saat dibuka ulang, simpan proyek baru/perbarui, ganti nama, duplikat, hapus proyek, dan tombol Proyek Baru untuk reset kanvas.
 

---

## 🛠️ Teknologi yang Digunakan

* **HTML5 Canvas API** — *Rendering* kanvas interaktif dengan dukungan *Device Pixel Ratio* (DPR) tinggi serta *offscreen rendering* untuk ekspor resolusi penuh.
* **Vanilla JavaScript (ES6+)** — Manajemen *state*, *history stack* (Undo/Redo), *hit-testing* koordinat lokal terotasi, dan engine gestur *multi-touch*.
* **Tailwind CSS (CDN)** — Antarmuka pengguna (*UI*) mode gelap (*dark mode*) yang responsif (*bottom sheet* di mobile dan *sidebar* di desktop).

---
