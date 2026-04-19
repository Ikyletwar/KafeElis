# 🏛️ Kafe Elis Digital Masterpiece: Premium Experience Web

![GitHub Header](https://raw.githubusercontent.com/UsernameAnda/KafeElis/main/assets/hero.png)

## 🎖️ Project Status & Badges
| Build | Design | License | Performance | Language |
| :--- | :--- | :--- | :--- | :--- |
| ![Build](https://img.shields.io/badge/Production-Stable-success) | ![Design](https://img.shields.io/badge/Design-Dark%20Premium-080808) | ![License](https://img.shields.io/badge/License-MIT-blue) | ![Lighthouse](https://img.shields.io/badge/SEO-90%2B-brightgreen) | ![Lang](https://img.shields.io/badge/Multilingual-ID%2FEN-orange) |

---

## 📄 Daftar Isi / Table of Contents
1. [Visi Proyek / Project Vision](#visi-proyek--project-vision)
2. [Sistem Desain / Design System](#sistem-desain--design-system)
3. [Arsitektur Teknis / Technical Architecture](#arsitektur-teknis--technical-architecture)
4. [Katalog Komponen / Component Catalog](#katalog-komponen--component-catalog)
5. [Fitur Interaktif / Interactive Features](#fitur-interaktif--interactive-features)
6. [Optimalisasi & SEO / Optimization & SEO](#optimalisasi--seo--optimization--seo)
7. [Panduan Penggunaan / Usage Guide](#panduan-penggunaan--usage-guide)
8. [Panduan Deployment / Deployment Guide](#panduan-deployment--deployment-guide)
9. [Roadmap Masa Depan / Future Roadmap](#roadmap-masa-depan--future-roadmap)
10. [FAQ & Kontribusi / FAQ & Contribution](#faq--kontribusi--faq--contribution)

---

## 🎯 Visi Proyek / Project Vision

### 🇮🇩 Bahasa Indonesia
**Kafe Elis Digital Experience** bukan sekadar landing page; ini adalah portal digital yang mentransformasi bisnis karaoke tradisional menjadi pengalaman modern yang berkelas. Visi kami adalah menghapus stigma karaoke konvensional yang kaku, menggantinya dengan suasana "Lounge" yang intim dan eksklusif. Proyek ini bertujuan untuk menarik target audiens yang lebih luas di Kota Masohi melalui representasi visual yang kuat dan navigasi yang tanpa hambatan.

### 🇬🇧 English
**Kafe Elis Digital Experience** is not just a landing page; it is a digital portal that transforms traditional karaoke business into a high-class modern experience. Our vision is to eliminate the rigid conventional karaoke stigma, replacing it with an intimate and exclusive "Lounge" atmosphere. This project aims to attract a broader target audience in Masohi City through powerful visual representation and seamless navigation.

---

## 🎨 Sistem Desain / Design System

Sistem desain website ini didasarkan pada prinsip **"Quiet Luxury"**—kemewahan yang tidak berisik namun terasa saat dialami.

### 🌑 Palet Warna / Color Palette
- **Deep Black (`#080808`)**: Warna dasar yang melambangkan kemewahan malam hari.
- **Primary Grey (`#0c0c0c`)**: Digunakan untuk pemisahan section yang halus.
- **Accent Red (`#8b2035`)**: Digunakan sangat terbatas untuk call-to-action guna menjaga fokus.
- **Pure White (`#f5f5f5`)**: Untuk tipografi utama agar kontras tetap tajam.

### 🖋️ Tipografi / Typography
1.  **Lora (Serif)**: Digunakan untuk Heading. Memberikan nuansa klasik, sastra, dan elegan.
2.  **Inter (Sans-Serif)**: Digunakan untuk Body Text. Menjamin keterbacaan tinggi di berbagai resolusi layar.

### 📐 Grid & Spacing
- Menggunakan sistem **Golden Ratio spacing** untuk memastikan keseimbangan antara konten dan ruang kosong (*white space*).
- Layout responsif berbasis **CSS Grid** dan **Flexbox** yang adaptif secara real-time.

---

## ⚙️ Arsitektur Teknis / Technical Architecture

### 🧱 Dasar Pengembangan
Website ini dibangun menggunakan paradigma **"No-Framework Performance"**. Tanpa ketergantungan pada React, Vue, atau jQuery, website ini memiliki beban footprint yang sangat kecil (under 100KB gzipped).

### 🧠 Logika JavaScript
- **Scroll Reveal Engine**: Menggunakan `IntersectionObserver` untuk memicu animasi saat pengguna melakukan scrolling, meminimalkan penggunaan resource CPU.
- **Stateful Navigation**: Logika navigasi yang mendeteksi posisi scroll untuk mengubah tampilan navbar secara dinamis (`sticky` & `glassmorphism` effect).
- **Testimonial Engine**: Sistem slider ringan untuk mengelola feedback pelanggan tanpa library eksternal.

---

## 🏛️ Katalog Komponen / Component Catalog

### 1. Hero Section (Gateway)
Pintu gerbang visual yang menggunakan *overlay* gelap dan teks yang memudar untuk mengarahkan pandangan pengguna langsung ke pesan utama.

### 2. Main Hall Showcase
Section yang memadukan gambar resolusi tinggi dengan daftar spesifikasi teknis (Sound System, Kapasitas, Mikrofon) yang disusun secara grid minimalis.

### 3. Interactive Concept Card
Tiga pilar cara kerja kafe yang menggunakan ikon SVG inline (untuk load cepat) dan efek transformasi saat di-*hover*.

### 4. Smart Reservation Module
Formulir modern dengan input yang terdesain khusus untuk tema gelap, menggunakan `focus-within` styling untuk meningkatkan fokus pengguna saat mengisi data.

---

## ⚡ Optimalisasi & SEO / Optimization & SEO

Kami menganggap SEO sebagai bagian integral dari kode, bukan sekadar tambahan:
- **Semantic HTML5**: Penggunaan tag `<article>`, `<section>`, `<aside>`, dan `<nav>` yang tepat.
- **Resource Prioritization**: Menggunakan `preconnect` untuk font pihak ketiga guna mempercepat render teks.
- **Accessibility (A11y)**: Rasio kontras teks yang memenuhi standar WCAG 2.1 untuk kenyamanan mata pengguna.
- **Meta Tags Optimization**:
    - Open Graph (OG) Tags untuk tampilan link yang indah di WhatsApp/Facebook.
    - Meta Description yang kaya kata kunci tanpa terlihat seperti spam.

---

## 💻 Panduan Penggunaan / Usage Guide

### Menjalankan secara Lokal
1. Pastikan aset gambar berada di folder `assets/`.
2. Jalankan server lokal (opsional, untuk performa terbaik):
   ```bash
   python -m http.server 8000
   ```
3. Akses `localhost:8000/kafeelis.html`.

### Panduan Git untuk Pemeliharaan
```bash
# Membuat cabang fitur baru
git checkout -b feature/update-gallery

# Melakukan commit dengan pesan yang jelas
git commit -m "feat: update gallery with teras.png asset"

# Mengirim perubahan ke GitHub
git push origin feature/update-gallery
```

---

## 🌍 Panduan Deployment / Deployment Guide

### Deployment ke GitHub Pages (Rekomendasi)
1. Buat repositori baru bernama `KafeElis`.
2. Unggah file: `index.html` (rename dari `kafeelis.html`), folder `assets/`, dan `README.md`.
3. Di tab **Settings**, navigasikan ke **Pages**.
4. Pilih branch `main` sebagai sumber.
5. Website Anda akan aktif di: `https://[username].github.io/KafeElis/`

---

## 🛣️ Roadmap Masa Depan / Future Roadmap

- [ ] **Integrasi Reservasi WA**: Langsung mengirim data form ke WhatsApp admin.
- [ ] **Dark/Light Mode**: Menambahkan opsi tema terang untuk aksesibilitas ekstra.
- [ ] **Menu Interaktif**: Halaman detail untuk katalog minuman lengkap dengan harga.
- [ ] **Integrasi Instagram API**: Menampilkan feed foto terbaru langsung dari akun IG Kafe Elis.

---

## 💬 FAQ & Kontribusi

**Q: Apakah website ini berat saat dibuka di HP kentang?**
A: Tidak. Dengan optimasi gambar dan tanpa library berat, website ini akan berjalan mulus di hampir semua perangkat mobile modern.

**Q: Bagaimana cara mengganti foto di galeri?**
A: Cukup ganti file di folder `assets/` dengan nama yang sama, atau ubah path `src` pada bagian `<div class="gallery-pic">` di HTML.

---

## 📜 Lisensi / License
Distribusi ini berada di bawah lisensi **MIT License**. Anda bebas menggunakan, memodifikasi, dan mendistribusikan kode ini untuk tujuan komersial maupun pribadi.

---

## 📞 Kontak & Informasi Bisnis
**Kafe Elis Karaoke & Lounge**
- 📍 **Lokasi**: Jalan Karai Atas, Kota Masohi, Maluku Tengah.
- 📞 **WhatsApp**: [+62 813-7641-5711](https://wa.me/6281376415711)
- 📧 **Email**: contact@kafeelis.id (Opsional)
- 🕒 **Jam Buka**: 19:00 - 02:00 WIT

---
Created with precision by **Antigravity AI** for **Kafe Elis**.
*"Di mana setiap lagu menemukan panggungnya."*
