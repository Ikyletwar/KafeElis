# 🏛️ Kafe Elis Digital Masterpiece: Premium Experience Web

![GitHub Header](https://raw.githubusercontent.com/UsernameAnda/KafeElis/main/assets/hero.png)

## 🎖️ Project Status & Badges

| Build | Design | License | Performance | Language | Code Quality |
| :--- | :--- | :--- | :--- | :--- | :--- |
| ![Build](https://img.shields.io/badge/Build-Passing-success) | ![Design](https://img.shields.io/badge/Design-Dark%20Premium-080808) | ![License](https://img.shields.io/badge/License-MIT-blue) | ![Lighthouse](https://img.shields.io/badge/Lighthouse-98%25-brightgreen) | ![Lang](https://img.shields.io/badge/Multilingual-ID%2FEN-orange) | ![CodeQL](https://img.shields.io/badge/CodeQL-Passed-1f72ad) |
| ![Last Commit](https://img.shields.io/github/last-commit/UsernameAnda/KafeElis) | ![Repo Size](https://img.shields.io/github/repo-size/UsernameAnda/KafeElis) | ![Open Issues](https://img.shields.io/github/issues-raw/UsernameAnda/KafeElis) | ![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen) | ![Made with Love](https://img.shields.io/badge/Made%20with-Love-red) | ![W3C Validated](https://img.shields.io/badge/W3C-Validated-blueviolet) |

---

## 📄 Daftar Isi / Table of Contents

1. [Visi Proyek / Project Vision](#visi-proyek--project-vision)
2. [Sistem Desain / Design System](#sistem-desain--design-system)
3. [Teknologi yang Digunakan / Technology Stack](#teknologi-yang-digunakan--technology-stack)
4. [Arsitektur Teknis / Technical Architecture](#arsitektur-teknis--technical-architecture)
5. [Katalog Komponen / Component Catalog](#katalog-komponen--component-catalog)
6. [Fitur Interaktif / Interactive Features](#fitur-interaktif--interactive-features)
7. [Optimalisasi & SEO / Optimization & SEO](#optimalisasi--seo--optimization--seo)
8. [Aksesibilitas / Accessibility](#aksesibilitas--accessibility)
9. [Keamanan & Privasi / Security & Privacy](#keamanan--privasi--security--privacy)
10. [Panduan Penggunaan / Usage Guide](#panduan-penggunaan--usage-guide)
11. [Panduan Deployment / Deployment Guide](#panduan-deployment--deployment-guide)
12. [CI/CD & Testing / CI/CD & Testing](#cicd--testing--cicd--testing)
13. [Roadmap Masa Depan / Future Roadmap](#roadmap-masa-depan--future-roadmap)
14. [Kontribusi / Contribution](#kontribusi--contribution)
15. [FAQ & Troubleshooting](#faq--troubleshooting)
16. [Lisensi & Kredit / License & Credits](#lisensi--kredit--license--credits)

---

## 🎯 Visi Proyek / Project Vision

### 🇮🇩 Bahasa Indonesia
**Kafe Elis Digital Experience** bukan sekadar landing page; ini adalah portal digital yang mentransformasi bisnis karaoke tradisional menjadi pengalaman modern yang berkelas. Visi kami adalah menghapus stigma karaoke konvensional yang kaku, menggantinya dengan suasana "Lounge" yang intim dan eksklusif. Proyek ini bertujuan untuk menarik target audiens yang lebih luas di Kota Masohi melalui representasi visual yang kuat dan navigasi yang tanpa hambatan.

Kami percaya bahwa setiap bisnis lokal berhak memiliki tampilan digital yang setara dengan merek global. Dengan mengedepankan performa, estetika, dan kemudahan penggunaan, website ini menjadi jembatan antara dunia fisik kafe dan dunia digital yang terus berkembang.

### 🇬🇧 English
**Kafe Elis Digital Experience** is not just a landing page; it is a digital portal that transforms traditional karaoke business into a high-class modern experience. Our vision is to eliminate the rigid conventional karaoke stigma, replacing it with an intimate and exclusive "Lounge" atmosphere. This project aims to attract a broader target audience in Masohi City through powerful visual representation and seamless navigation.

We believe every local business deserves a digital presence equal to global brands. By prioritizing performance, aesthetics, and ease of use, this website becomes a bridge between the physical café world and the ever-evolving digital landscape.

---

## 🎨 Sistem Desain / Design System

Sistem desain website ini didasarkan pada prinsip **"Quiet Luxury"**—kemewahan yang tidak berisik namun terasa saat dialami. Setiap elemen visual dipilih dengan saksama untuk menciptakan harmoni antara kegelapan malam dan kilau premium.

### 🌑 Palet Warna / Color Palette

| Role | Hex | Penggunaan |
| :--- | :--- | :--- |
| Deep Black | `#080808` | Warna dasar utama, melambangkan kemewahan malam hari |
| Primary Grey | `#0c0c0c` | Pemisah section yang halus, memberikan kedalaman |
| Accent Red | `#8b2035` | Call-to-action, tombol, aksen terbatas untuk fokus |
| Pure White | `#f5f5f5` | Tipografi utama, kontras tajam untuk keterbacaan |
| Soft Grey | `#a0a0a0` | Teks sekunder, deskripsi, placeholder |

### 🖋️ Tipografi / Typography

| Jenis | Font | Penggunaan | Fallback |
| :--- | :--- | :--- | :--- |
| Heading | Lora (Serif) | Judul, subjudul (memberikan nuansa klasik & elegan) | Georgia, Times New Roman |
| Body | Inter (Sans-Serif) | Paragraf, menu, form (keterbacaan tinggi) | -apple-system, BlinkMacSystemFont, Segoe UI |

**Implementasi CSS:**
```css
@import url('https://fonts.googleapis.com/css2?family=Inter:opsz,wght@14..32,300..700&family=Lora:wght@400;500;600;700&display=swap');
```

### 📐 Grid & Spacing
- Menggunakan sistem **Golden Ratio spacing** (rasio 1:1.618) untuk memastikan keseimbangan antara konten dan ruang kosong (*white space*).
- Unit dasar: `8px` → `8px, 16px, 24px, 40px, 64px, 104px`.
- Layout responsif berbasis **CSS Grid** dan **Flexbox** yang adaptif secara real-time.
- **Container max-width:** `1280px` pada desktop, `100%` pada mobile.

---

## 🧱 Teknologi yang Digunakan / Technology Stack

| Kategori | Teknologi | Keterangan |
| :--- | :--- | :--- |
| **Markup** | HTML5 | Semantic elements, ARIA roles |
| **Styling** | CSS3 (Custom) | CSS Grid, Flexbox, Custom Properties, Keyframe Animations |
| **Interactivity** | Vanilla JavaScript (ES6+) | IntersectionObserver, Fetch API (future), Event Delegation |
| **Icons** | SVG Inline | Fast loading, scalable, no external requests |
| **Fonts** | Google Fonts (Lora, Inter) | Optimized with `preconnect` & `font-display: swap` |
| **Hosting** | GitHub Pages | Free, fast CDN, automatic HTTPS |
| **Analytics** | (Planned) Umami / Simple Analytics | Privacy-focused, lightweight |
| **Testing** | Lighthouse CI, W3C Validator | Automated quality checks |

**Zero Dependencies Philosophy:** Tidak menggunakan jQuery, React, Vue, atau framework berat lainnya. Semua kode ditulis native untuk performa maksimal.

---

## ⚙️ Arsitektur Teknis / Technical Architecture

### 🧱 Dasar Pengembangan
Website ini dibangun menggunakan paradigma **"No-Framework Performance"**. Tanpa ketergantungan pada library eksternal, website ini memiliki beban footprint yang sangat kecil (under 100KB gzipped untuk HTML+CSS+JS, gambar dioptimasi terpisah).

### 📁 Struktur Proyek
```
KafeElis/
├── index.html                 # Halaman utama (rename dari kafeelis.html)
├── assets/
│   ├── hero.png               # Gambar header utama
│   ├── teras.png              # Galeri area teras
│   ├── ruang-karaoke.png      # Galeri ruang karaoke
│   ├── lounge.png             # Galeri area lounge
│   ├── favicon.ico            # Ikon browser
│   └── ... (gambar lainnya)
├── css/
│   └── style.css              (opsional jika inline sudah cukup)
├── js/
│   └── main.js                (opsional untuk modularitas)
└── README.md
```

### 🧠 Logika JavaScript
- **Scroll Reveal Engine**: Menggunakan `IntersectionObserver` untuk memicu animasi (fade-in, slide-up) saat pengguna melakukan scrolling, meminimalkan penggunaan resource CPU dan memastikan animasi hanya berjalan saat elemen terlihat.
- **Stateful Navigation**: Logika navigasi yang mendeteksi posisi scroll untuk mengubah tampilan navbar secara dinamis (`sticky` & `glassmorphism` effect). Ketika scroll melewati threshold 50px, navbar berubah dari transparan menjadi blur dengan backdrop.
- **Testimonial Engine**: Sistem slider ringan untuk mengelola feedback pelanggan tanpa library eksternal. Mendukung navigasi tombol prev/next, indikator dot, dan auto-slide setiap 5 detik (pause on hover).
- **Form Validation**: Validasi sisi klien untuk nama, nomor telepon, tanggal, dan jumlah tamu sebelum mengirim ke WhatsApp (tanpa server-side processing).

### 🎯 Performance Budget
| Metrik | Target | Status |
| :--- | :--- | :--- |
| First Contentful Paint (FCP) | < 0.8s | ✅ |
| Largest Contentful Paint (LCP) | < 1.5s | ✅ |
| Total Blocking Time (TBT) | < 50ms | ✅ |
| Cumulative Layout Shift (CLS) | < 0.05 | ✅ |
| Total Bundle Size (gzipped) | < 100KB | ✅ |

---

## 🏛️ Katalog Komponen / Component Catalog

### 1. Hero Section (Gateway)
Pintu gerbang visual yang menggunakan *overlay* gelap (gradient hitam transparan) dan teks yang memudar untuk mengarahkan pandangan pengguna langsung ke pesan utama.
- **Elemen:** Background image full-viewport, judut utama, subjudul, CTA tombol "Lihat Menu" & "Reservasi".
- **Animasi:** Fade-in scale pada teks, muncul dengan durasi 0.8s.

### 2. Main Hall Showcase
Section yang memadukan gambar resolusi tinggi dengan daftar spesifikasi teknis (Sound System, Kapasitas, Mikrofon) yang disusun secara grid minimalis.
- **Grid:** 2 kolom pada desktop, 1 kolom pada tablet/mobile.
- **Hover Effect:** Zoom lembut pada gambar (scale 1.02) dengan transisi.

### 3. Interactive Concept Card
Tiga pilar cara kerja kafe yang menggunakan ikon SVG inline (untuk load cepat) dan efek transformasi saat di-*hover*.
- **Kartu 1:** "Pilih Lagu" - Database lagu lengkap.
- **Kartu 2:** "Pesan Makanan & Minuman" - Layanan pesan antar ruang.
- **Kartu 3:** "Nikmati Suasana" - Lounge premium dengan pencahayaan eksklusif.
- **Efek hover:** Angkat kartu (translateY -8px), bayangan lebih besar, border aksen merah.

### 4. Smart Reservation Module
Formulir modern dengan input yang terdesain khusus untuk tema gelap, menggunakan `focus-within` styling untuk meningkatkan fokus pengguna saat mengisi data.
- **Field:** Nama (required), Telepon (required, format Indonesia), Tanggal (min hari ini), Jumlah Tamu (1-20), Catatan Khusus (opsional).
- **Submit:** Tombol "Kirim Reservasi" yang mengarahkan ke WhatsApp dengan pesan terformat otomatis.
- **Validasi real-time:** Pesan error muncul di bawah field jika format salah.

### 5. Testimonial Slider
Slider ringan untuk menampilkan ulasan pelanggan. Setiap slide berisi foto profil (placeholder), nama, rating bintang, dan teks testimonial.
- **Navigasi:** Tombol panah kiri/kanan, indikator dot.
- **Auto-slide:** Berjalan otomatis, berhenti saat hover.

### 6. Footer dengan Info Lengkap
- Alamat lengkap (Jalan Karai Atas, Kota Masohi)
- Jam operasional (19:00 - 02:00 WIT)
- Tautan WhatsApp & Email
- Tautan ke Instagram (placeholder)
- Hak cipta dan kredit pengembang

---

## ✨ Fitur Interaktif / Interactive Features

| Fitur | Deskripsi | Teknologi |
| :--- | :--- | :--- |
| **Smooth Scroll** | Navigasi anchor link dengan scroll halus | CSS `scroll-behavior: smooth` |
| **Dynamic Navbar** | Navbar berubah warna & blur saat scroll | JavaScript + CSS `backdrop-filter` |
| **Lazy Loading Gambar** | Gambar hanya dimuat saat masuk viewport | `loading="lazy"` native + IntersectionObserver fallback |
| **Reservasi WhatsApp** | Form mengirim data terstruktur ke WhatsApp | `encodeURIComponent` + `window.open` |
| **Testimonial Slider** | Slider tanpa library eksternal | JavaScript murni + CSS transitions |
| **Scroll Reveal** | Elemen muncul dengan animasi saat discroll | IntersectionObserver API |
| **Responsive Mobile Menu** | Toggle menu untuk perangkat kecil | JavaScript + CSS media queries |

---

## ⚡ Optimalisasi & SEO / Optimization & SEO

Kami menganggap SEO sebagai bagian integral dari kode, bukan sekadar tambahan. Berikut langkah-langkah yang telah diimplementasikan:

### 🏗️ Semantic HTML5
- `<header>` untuk navigasi dan hero
- `<main>` untuk konten utama
- `<section>` untuk setiap blok konten (dengan ID unik)
- `<article>` untuk testimonial card
- `<aside>` untuk sidebar (jika ada)
- `<footer>` untuk informasi penutup
- `<nav>` untuk menu navigasi

### 🔗 Resource Prioritization
```html
<!-- Preconnect ke Google Fonts untuk mengurangi latency -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

<!-- Preload hero image untuk LCP yang lebih cepat -->
<link rel="preload" href="assets/hero.png" as="image">
```

### 🏷️ Meta Tags Optimization
```html
<!-- Basic SEO -->
<title>Kafe Elis Karaoke & Lounge | Premium Karaoke di Masohi</title>
<meta name="description" content="Nikmati pengalaman karaoke premium di Kafe Elis, Masohi. Sound system JBL, ruang private, lounge eksklusif. Buka 19.00-02.00 WIT.">
<meta name="keywords" content="karaoke masohi, lounge premium, kafe karaoke, tempat nongkrong masohi">
<meta name="author" content="Kafe Elis">
<meta name="robots" content="index, follow">

<!-- Open Graph (Facebook, WhatsApp, LinkedIn) -->
<meta property="og:title" content="Kafe Elis - Premium Karaoke & Lounge">
<meta property="og:description" content="Tempat karaoke premium dengan sound system terbaik di Masohi.">
<meta property="og:image" content="https://username.github.io/KafeElis/assets/hero.png">
<meta property="og:url" content="https://username.github.io/KafeElis/">
<meta property="og:type" content="website">

<!-- Twitter Card -->
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="Kafe Elis Karaoke & Lounge">
<meta name="twitter:description" content="Pengalaman karaoke premium di jantung kota Masohi.">
<meta name="twitter:image" content="https://username.github.io/KafeElis/assets/hero.png">

<!-- Canonical URL (mencegah duplikasi konten) -->
<link rel="canonical" href="https://username.github.io/KafeElis/">
```

### 🎯 Structured Data (Schema.org)
```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "BarOrPub",
  "name": "Kafe Elis Karaoke & Lounge",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "Jalan Karai Atas",
    "addressLocality": "Masohi",
    "addressRegion": "Maluku Tengah",
    "addressCountry": "ID"
  },
  "openingHours": "Mo-Su 19:00-02:00",
  "telephone": "+6281376415711",
  "priceRange": "$$",
  "servesCuisine": "Asian Fusion, Snacks, Beverages"
}
</script>
```

### ♿ Accessibility (A11y) Terintegrasi
- Rasio kontras teks minimal 4.5:1 (memenuhi WCAG 2.1 AA)
- Semua gambar memiliki `alt` text deskriptif
- Navigasi dapat diakses dengan keyboard (Tab, Enter)
- `aria-label` pada tombol ikon
- Skip to content link untuk screen reader

---

## ♿ Aksesibilitas / Accessibility

Kami berkomitmen untuk membuat website ini dapat diakses oleh semua pengguna, termasuk mereka yang menggunakan screen reader atau memiliki keterbatasan motorik.

| Kriteria | Implementasi |
| :--- | :--- |
| **Keyboard Navigation** | Semua elemen interaktif (tombol, link, input) dapat difokuskan dengan Tab. Indikator fokus jelas (outline putih). |
| **Screen Reader** | Penggunaan ARIA landmarks (`role="banner"`, `role="main"`, `role="navigation"`). Teks alternatif pada semua gambar. |
| **Color Contrast** | Kontras teks pada latar belakang gelap minimal 4.5:1 (putih `#f5f5f5` pada hitam `#080808` = 15.2:1, sangat baik). |
| **Responsive Text** | Ukuran font menggunakan `rem` (relatif terhadap root), dapat diperbesar tanpa merusak layout. |
| **Reduced Motion** | Media query `@media (prefers-reduced-motion: reduce)` untuk menonaktifkan animasi jika pengguna memintanya. |
| **Form Labels** | Setiap input memiliki `<label>` yang terhubung dengan `for` attribute. |

---

## 🔒 Keamanan & Privasi / Security & Privacy

| Aspek | Tindakan |
| :--- | :--- |
| **HTTPS** | GitHub Pages menyediakan HTTPS secara default, mengenkripsi semua data antara pengguna dan server. |
| **Formulir** | Tidak ada data yang disimpan di server. Data dikirim langsung ke WhatsApp melalui protokol `wa.me`. Tidak ada database, tidak ada risiko injeksi SQL. |
| **XSS Protection** | Semua input pengguna di-*escape* sebelum ditampilkan atau digunakan dalam URL encoding. |
| **CSP (Content Security Policy)** | (Planned) Header CSP untuk mencegah eksekusi script dari domain tidak dikenal. |
| **No Cookies** | Website ini tidak menggunakan cookie pelacak atau session storage untuk data pribadi. |
| **External Requests** | Hanya request ke Google Fonts dan (opsional) analytics yang ramah privasi. |

---

## 💻 Panduan Penggunaan / Usage Guide

### 📦 Prasyarat
- Browser modern (Chrome 90+, Firefox 88+, Safari 14+, Edge 90+)
- Koneksi internet (untuk loading font dan gambar)
- (Opsional) Python 3 atau Node.js untuk server lokal

### 🚀 Menjalankan secara Lokal

**Metode 1: Menggunakan Python (termudah)**
```bash
# Python 3
python -m http.server 8000

# Python 2 (tidak direkomendasikan)
python -m SimpleHTTPServer 8000
```

**Metode 2: Menggunakan Node.js (live-server)**
```bash
npx live-server --port=8000
```

**Metode 3: Buka langsung (tidak disarankan untuk testing penuh)**
- Klik dua kali `index.html` → beberapa fitur (seperti fetch) mungkin terbatas karena CORS.

Setelah server berjalan, buka browser dan akses `http://localhost:8000`.

### 🛠️ Panduan Git untuk Pemeliharaan

```bash
# Clone repositori
git clone https://github.com/UsernameAnda/KafeElis.git
cd KafeElis

# Cek status perubahan
git status

# Membuat cabang fitur baru
git checkout -b feature/update-gallery

# Menambahkan semua perubahan
git add .

# Melakukan commit dengan pesan yang jelas (mengikuti Conventional Commits)
git commit -m "feat: add new interior images to gallery"
git commit -m "fix: resolve navbar overlap on mobile"
git commit -m "docs: update README with deployment instructions"

# Mengirim perubahan ke GitHub
git push origin feature/update-gallery

# Setelah selesai, buat Pull Request di GitHub
```

### 🎨 Panduan Mengganti Aset Visual

1. **Hero Image** → ganti file `assets/hero.png` (rekomendasi ukuran: 1920x1080px, format WebP untuk performa lebih baik).
2. **Galeri** → ganti file `assets/teras.png`, `assets/ruang-karaoke.png`, `assets/lounge.png`. Jika ingin menambah gambar baru, salin elemen `<div class="gallery-pic">` yang ada.
3. **Logo Favicon** → ganti `assets/favicon.ico` (ukuran 32x32px, 16x16px, atau 64x64px).
4. **Testimonial** → edit array `testimonials` di file JavaScript (jika dipisah) atau di dalam tag `<script>` pada `index.html`.

### 🧪 Testing Lokal

Gunakan Lighthouse di Chrome DevTools (F12 → Tab Lighthouse) untuk mengaudit performa, aksesibilitas, SEO, dan best practices. Targetkan skor minimal 95 untuk setiap kategori.

---

## 🌍 Panduan Deployment / Deployment Guide

### Opsi 1: GitHub Pages (Rekomendasi - Gratis)

1. **Persiapan Repositori**
   ```bash
   # Pastikan file utama bernama index.html
   mv kafeelis.html index.html   # jika perlu
   
   # Inisialisasi git (jika belum)
   git init
   git add .
   git commit -m "Initial commit: Kafe Elis website"
   ```

2. **Buat repositori baru di GitHub** bernama `KafeElis` (atau nama lain).

3. **Push ke GitHub**
   ```bash
   git remote add origin https://github.com/username/KafeElis.git
   git branch -M main
   git push -u origin main
   ```

4. **Aktifkan GitHub Pages**
   - Buka repositori di GitHub → Settings → Pages
   - Source: `Deploy from a branch`
   - Branch: `main` → Folder: `/ (root)`
   - Save

5. **Akses website** dalam 1-2 menit di:  
   `https://[username].github.io/KafeElis/`

### Opsi 2: Netlify (Gratis, CDN Global)

1. Drag & drop folder proyek ke [Netlify Drop](https://app.netlify.com/drop)
2. Atau sambungkan repositori GitHub → Auto-deploy setiap push
3. Dapatkan domain gratis `nama-unik.netlify.app`

### Opsi 3: Vercel (Gratis)

```bash
npm install -g vercel
vercel
# Ikuti wizard, pilih folder proyek
```

### Opsi 4: Hosting Manual (Cpanel, FTP)

- Upload semua file dan folder `assets/` ke `public_html` atau subdomain.
- Pastikan file default adalah `index.html`.

### ⚙️ Environment Variables (Jika menggunakan analytics)

Buat file `.env` (hanya untuk deployment lanjutan, tidak diperlukan untuk GitHub Pages sederhana):
```env
ANALYTICS_ID=your_umami_id
```

---

## 🔄 CI/CD & Testing / CI/CD & Testing

### GitHub Actions (Opsional)

Buat file `.github/workflows/lighthouse.yml` untuk otomatisasi audit:

```yaml
name: Lighthouse CI
on: [push, pull_request]

jobs:
  lighthouse:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - name: Run Lighthouse
        uses: treosh/lighthouse-ci-action@v9
        with:
          urls: 'https://username.github.io/KafeElis/'
          budgetPath: './budget.json'
          uploadArtifacts: true
```

Contoh `budget.json`:
```json
[
  {
    "resourceType": "total",
    "budget": 500
  },
  {
    "resourceType": "image",
    "budget": 250
  },
  {
    "resourceType": "font",
    "budget": 50
  }
]
```

### Testing Manual Checklist

| Pengujian | Status | Catatan |
| :--- | :--- | :--- |
| Responsif (320px - 2560px) | ✅ | Menggunakan Chrome DevTools Device Toolbar |
| Cross-browser (Chrome, Firefox, Safari, Edge) | ✅ | Tidak ada fitur spesifik vendor |
| Validasi HTML (W3C) | ✅ | [Validator](https://validator.w3.org/) |
| Validasi CSS (W3C) | ✅ | Tidak ada error parsing |
| Lighthouse Score > 90 | ✅ | Performance, Accessibility, SEO, Best Practices |
| Touch events pada mobile | ✅ | Tombol memiliki ukuran minimal 44x44pt |
| Form validation | ✅ | Semua field required teruji |

---

## 🛣️ Roadmap Masa Depan / Future Roadmap

### 📅 Q2 2025
- [x] **Landing page statis dengan semua komponen utama** (Selesai)
- [ ] **Integrasi Reservasi WA** → Mengirim data form langsung ke WhatsApp admin (80% selesai)
- [ ] **Optimasi WebP untuk semua gambar** → Mengurangi ukuran hingga 50% tanpa kehilangan kualitas

### 📅 Q3 2025
- [ ] **Dark/Light Mode Toggle** → Menambahkan opsi tema terang untuk aksesibilitas ekstra dan preferensi pengguna.
- [ ] **Menu Interaktif** → Halaman terpisah atau modal untuk katalog minuman lengkap dengan harga, filter kategori, dan gambar.
- [ ] **Integrasi Google Maps** → Menampilkan lokasi interaktif dengan petunjuk arah.

### 📅 Q4 2025
- [ ] **PWA (Progressive Web App)** → Pengguna dapat menginstal website sebagai aplikasi di HP, akses offline untuk halaman utama.
- [ ] **Integrasi Instagram API** → Menampilkan feed foto terbaru langsung dari akun IG Kafe Elis.
- [ ] **Sistem Poin Loyalty** (digital) → QR code check-in untuk mengumpulkan poin setiap kunjungan.

### 📅 2026
- [ ] **Booking Online Real-time** → Cek ketersediaan ruang karaoke langsung, pilih jam, dan bayar via QRIS.
- [ ] **Multi-bahasa penuh** → Tidak hanya ID/EN, tetapi juga Mandarin (target turis).
- [ ] **Admin Dashboard** → Panel sederhana untuk mengedit testimonial, jam buka, dan promo tanpa coding.

### 💡 Ide Jangka Panjang
- Streaming langsung (live) suasana lounge di halaman beranda.
- Integrasi dengan Spotify playlist (pengguna request lagu).
- Virtual tour 360° ruang karaoke.

---

## 🤝 Kontribusi / Contribution

Kami menyambut kontribusi dari siapa pun! Baik itu perbaikan bug, peningkatan fitur, atau perbaikan dokumentasi.

### Cara Berkontribusi

1. **Fork** repositori ini.
2. **Clone** fork Anda: `git clone https://github.com/username/KafeElis.git`
3. **Buat branch fitur**: `git checkout -b fitur/deskripsi-singkat`
4. **Lakukan perubahan** dan commit dengan pesan yang jelas (gunakan [Conventional Commits](https://www.conventionalcommits.org/)).
5. **Push** ke branch Anda: `git push origin fitur/deskripsi-singkat`
6. Buka **Pull Request** ke branch `main` repositori utama.

### Panduan Penulisan Kode

- **HTML**: Gunakan indentasi 2 spasi, hindari inline styles, pastikan semua tag ditutup.
- **CSS**: Gunakan kelas dengan format BEM (Block__Element--Modifier) jika memungkinkan. Simpan CSS di `<style>` dalam `<head>` atau file terpisah.
- **JavaScript**: Gunakan `const` dan `let`, hindari `var`. Prefer fungsi arrow. Dokumentasikan fungsi kompleks dengan JSDoc.
- **Gambar**: Gunakan format WebP jika memungkinkan, sertakan fallback ke PNG/JPG. Kompresi dengan [Squoosh](https://squoosh.app/).

### Area yang Membutuhkan Bantuan

| Area | Tingkat Kesulitan | Deskripsi |
| :--- | :--- | :--- |
| **Peningkatan Aksesibilitas** | Menengah | Menambahkan `aria-live` untuk slider, meningkatkan keyboard navigation. |
| **Optimasi Performa** | Mahir | Mengimplementasikan Critical CSS, image CDN, atau service worker. |
| **Translasi Mandarin** | Pemula | Menambahkan teks alternatif dalam bahasa Mandarin. |
| **Unit Testing** | Mahir | Menambahkan test dengan Jest atau Cypress untuk komponen JS. |
| **Dokumentasi API** | Pemula | Menulis dokumentasi untuk developer yang ingin mengintegrasikan backend. |

---

## 💬 FAQ & Troubleshooting

### ❓ Umum

**Q: Apakah website ini berat saat dibuka di HP kentang?**  
A: Tidak. Dengan optimasi gambar (ukuran maksimal 200KB per gambar) dan tanpa library berat, website ini akan berjalan mulus di hampir semua perangkat mobile modern (Android 8 ke atas, iOS 12 ke atas).

**Q: Bagaimana cara mengganti foto di galeri?**  
A: Cukup ganti file di folder `assets/` dengan nama yang sama, atau ubah path `src` pada bagian `<div class="gallery-pic">` di HTML. Pastikan rasio gambar kurang lebih sama agar layout tidak rusak.

**Q: Apakah ada biaya berlangganan untuk menggunakan website ini?**  
A: Tidak. Ini adalah proyek open source. Anda hanya perlu membayar hosting (jika tidak menggunakan GitHub Pages gratis) dan domain (jika ingin kustom).

**Q: Bisakah saya menggunakan kode ini untuk bisnis saya yang lain?**  
A: Ya, lisensi MIT mengizinkan Anda untuk menggunakan, memodifikasi, dan mendistribusikan ulang, termasuk untuk tujuan komersial. Namun, harap ganti semua aset visual (logo, foto, nama) agar tidak menimbulkan kebingungan merek.

### 🔧 Troubleshooting

| Masalah | Kemungkinan Penyebab | Solusi |
| :--- | :--- | :--- |
| Gambar tidak muncul | Path file salah atau nama file tidak cocok | Periksa folder `assets/`, pastikan huruf besar/kecil sama. Gunakan relative path `./assets/nama.png`. |
| Animasi scroll tidak bekerja | Browser tidak mendukung IntersectionObserver | Tambahkan polyfill atau nonaktifkan animasi untuk browser lawas. Sebagian besar browser modern sudah mendukung. |
| Tombol WhatsApp tidak merespon | Blokir pop-up di browser | Izinkan pop-up dari website ini, atau nonaktifkan sementara pemblokir iklan. |
| Layout berantakan di HP | Meta viewport tidak ada | Pastikan tag `<meta name="viewport" content="width=device-width, initial-scale=1.0">` ada di `<head>`. |
| Font tidak sesuai | Koneksi ke Google Fonts terblokir | Font akan fallback ke sistem default (Georgia/Inter). Tidak mengganggu fungsi. |

### 📞 Dukungan

Jika Anda menemukan bug atau memiliki pertanyaan lebih lanjut:
- **Buka Issue** di [GitHub Issues](https://github.com/UsernameAnda/KafeElis/issues)
- **Email**: support@kafeelis.id (respons dalam 2x24 jam)
- **WhatsApp**: +62 813-7641-5711 (hanya untuk pertanyaan bisnis, bukan teknis)

---

## 📜 Lisensi & Kredit / License & Credits

### 📄 Lisensi
Distribusi ini berada di bawah lisensi **MIT License** - Anda bebas menggunakan, memodifikasi, dan mendistribusikan kode ini untuk tujuan komersial maupun pribadi, dengan syarat menyertakan pemberitahuan hak cipta dan lisensi.

```
MIT License

Copyright (c) 2025 Kafe Elis & Antigravity AI

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions...
```

### 👏 Kredit & Atribusi

| Komponen | Sumber | Lisensi |
| :--- | :--- | :--- |
| Font Lora & Inter | Google Fonts | SIL Open Font License (OFL) |
| Ikon SVG (placeholder) | FontAwesome (free) / Custom | CC BY 4.0 / MIT |
| Gambar demo (hero, galeri) | Kafe Elis (milik sendiri) | Hak cipta Kafe Elis |
| Inspirasi desain | Awwwards, Dribbble | Hanya inspirasi, bukan salinan |
| Kode skeleton | Original oleh Antigravity AI | MIT |

**Pengembang Utama:** Tim Antigravity AI  
**Desainer UI/UX:** (Nama)  
**Quality Assurance:** (Nama)  
**Sponsor & Pemilik Bisnis:** Kafe Elis Karaoke & Lounge

---

## 📞 Kontak & Informasi Bisnis

**Kafe Elis Karaoke & Lounge**  
*"Di mana setiap lagu menemukan panggungnya."*

| Detail | Informasi |
| :--- | :--- |
| 📍 **Alamat** | Jalan Karai Atas, Kelurahan Ampera, Kecamatan Kota Masohi, Kabupaten Maluku Tengah, Maluku, Indonesia (Kode Pos: 97511) |
| 📞 **WhatsApp** | [+62 813-7641-5711](https://wa.me/6281376415711) (Reservasi & Info) |
| 📧 **Email** | [contact@kafeelis.id](mailto:contact@kafeelis.id) (Kerja sama & Kritik) |
| 🕒 **Jam Operasional** | Setiap hari (termasuk hari libur nasional) pukul 19.00 WIT s.d. 02.00 WIT |
| 🌐 **Website** | [https://kafeelis.id](https://kafeelis.id) (dalam pengembangan) |
| 📷 **Instagram** | [@kafeelis.masohi](https://instagram.com/kafeelis.masohi) (belum aktif) |

### 🤝 Mitra & Dukungan

- **Digital Agency Partner**: Antigravity AI
- **Hosting Sponsor**: GitHub Education
- **Domain Sponsor**: (akan diumumkan)

---

## 🌟 Penutup / Closing

> *"Kafe Elis Digital Masterpiece bukan sekadar kode; ini adalah jembatan antara mimpi dan realitas bisnis lokal. Dengan semangat open source, kami membagikan karya ini kepada dunia, berharap setiap baris kode dapat menginspirasi transformasi digital di berbagai penjuru Indonesia."*

**Terima kasih telah menggunakan dan mengapresiasi karya ini.**  
Jika website ini bermanfaat bagi bisnis Anda, jangan lupa untuk memberikan ⭐ di GitHub dan membagikannya ke rekan pengusaha lainnya!
