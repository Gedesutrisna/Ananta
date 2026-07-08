# 🏛️ Ananta – Menjaga Kekayaan Budaya Nusantara

[![Vercel Deployment](https://img.shields.io/badge/Vercel-Deployed-success?style=for-the-badge&logo=vercel&logoColor=white)](https://ananta-iota.vercel.app/)
![Tech Stack](https://img.shields.io/badge/Stack-Vanilla_JS_|_HTML5_|_CSS3-blue?style=for-the-badge)

> **"Ananta"** (Bahasa Sanskerta: *Ananta*) berarti *tanpa batas* atau *keabadian*. 

**Ananta** adalah sebuah platform digital interaktif yang dirancang untuk menjembatani pesona warisan budaya Indonesia dengan gerak maju era modern. Kami percaya bahwa teknologi bukanlah lawan dari tradisi, melainkan sebuah megapelantang (amplifier) yang mampu memperkenalkan kearifan lokal, seni tradisional, sejarah, hingga kuliner Nusantara ke cakrawala yang lebih luas tanpa batas waktu.

🌐 **Live Demo:** [ananta-iota.vercel.app](https://ananta-iota.vercel.app/)

---

## ✨ Fitur Utama

- 📖 **Artikel Budaya Mendalam:** Eksplorasi komprehensif mulai dari keunikan Batik, seni tari Bali, hingga sejarah aksara kuno Nusantara.
- 🎬 **Video Dokumenter & Galeri Visual:** Menampilkan esensi seni pertunjukan Indonesia secara audiovisual (didukung integrasi pemutar video interaktif).
- 👥 **Komunitas & Ruang Diskusi:** Halaman interaktif untuk menghubungkan para pencinta seni, penggiat sejarah, dan masyarakat umum (Komunitas Gamelan, Workshop Batik, dll).
- 📅 **Manajemen Acara (Event Hub):** Cari, ikuti, dan pantau riwayat keikutsertaan Anda dalam berbagai lokakarya, festival rasa, dan pentas seni kebudayaan.
- 🌓 **Mode Adaptif (Light & Dark Mode):** Pengalaman membaca yang nyaman dan inklusif. Pilih *Light Mode* untuk nuansa yang bersih atau *Dark Mode* untuk estetika malam yang elegan, menjaga kenyamanan mata Anda saat mendalami filosofi Nusantara.
- 📱 **Responsif & Animasi Halus:** Dioptimalkan sepenuhnya untuk berbagai perangkat menggunakan pendekatan tata letak modern dan efek *Animate On Scroll* (AOS).

---

## 🛠️ Arsitektur & Teknologi

Aplikasi web ini dibangun dengan pendekatan performa tinggi melalui kode *native* demi menghasilkan pemuatan halaman yang instan, bersih, dan tanpa *overhead* framework yang berat.

- **Struktur Utama:** `HTML5` (Semantik untuk SEO & Aksesibilitas terbaik).
- **Gaya & Layout:** `CSS3 Vanilla` (Tata letak grid kustom, sistem responsif adaptif tanpa framework CSS pihak ketiga).
- **Logika & Interaktivitas:** `Vanilla JavaScript` murni untuk penanganan status aplikasi, autentikasi berbasis klien, interaksi alert kustom, dan mekanisme *theme switching*.
- **Paket & Pihak Ketiga:**
  - **[SwiperJS (v5.3.7)](https://swiperjs.com/):** Untuk navigasi *carousel* serta slider artikel dan testimoni yang mulus di perangkat sentuh.
  - **[FontAwesome (v6.7.2)](https://fontawesome.com/):** Penyedia ikonografi modern bernuansa budaya dan utilitas sistem.
  - **Google Fonts (Urbanist):** Tipografi sans-serif modern yang memberikan keterbacaan tinggi di berbagai resolusi layar.

---

## 📂 Struktur Repositori

Proyek ini memiliki struktur multi-halaman (*Multi-Page Application*) yang terorganisasi dengan baik:

```text
├── CWC2666_Bahan/               # Aset gambar (.webp), logo, pustaka SwiperJS & FontAwesome
├── CWC2666_Website/
│   ├── css/
│   │   └── style.css       # Pusat manajemen gaya dan variabel tema (Light/Dark)
│   └── js/
│       └── script.js      # Logika interaktivitas, pemutar video, slider, & dark mode
├── index.html              # Halaman Beranda / Landing Page
├── artikel.html            # Halaman katalog artikel budaya
├── batik.html              # Detail artikel: Mengenal Batik
├── tari-bali.html          # Detail artikel: Filosofi Tari Bali
├── event.html              # Pusat informasi acara & workshop budaya
├── komunitas.html          # Direktori grup penggiat budaya Nusantara
├── login.html / register.html # Antarmuka autentikasi pengguna
└── ... (Halaman pendukung profil dan riwayat aktivitas lainnya)