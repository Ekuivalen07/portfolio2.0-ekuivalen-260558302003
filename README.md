# Personal Portfolio Website — Ekuivalen

Website portofolio personal multi-halaman bertema monokrom modern yang dirancang untuk menampilkan profil, kumpulan tulisan blog, galeri sertifikat, serta arsip 10 proyek pilihan dengan animasi interaktif yang halus.

🌐 **Live Demo:** [https://portfolio.ekuivalen.my.id/](https://portfolio.ekuivalen.my.id/)

---

## Deskripsi Singkat Project

Project ini merupakan situs portofolio web statis yang menggabungkan desain editorial bersih dengan berbagai interaksi modern berbasis **JavaScript** dan **GSAP**. Seluruh halaman dirancang responsif agar nyaman diakses melalui desktop maupun perangkat mobile, dilengkapi *animated sticky navbar* yang menyesuaikan ukuran saat halaman digulir.

### Fitur Utama
- **Beranda (`index.html`):** Hero section personal, *animated sticky navbar*, cuplikan artikel terbaru, galeri karya dengan efek *hover zoom*, etalase proyek unggulan, serta footer monokrom.
- **Blog (`blog.html`):** Daftar artikel dengan fitur pencarian langsung (*live search*) dan filter kategori interaktif.
- **Halaman Baca Artikel (`artikel1.html` – `artikel3.html`):** Tampilan baca berfokus pada keterbacaan dilengkapi hero gelap, tipografi editorial, serta daftar isi otomatis (*auto-generated Table of Contents*) dengan *scroll-spy*.
- **Tentang Saya (`about.html`):** Profil singkat, animasi pembesaran teks layar penuh (*full-screen text zoom*) menggunakan GSAP ScrollTrigger menuju galeri sertifikat melengkung 3D yang bergerak otomatis (dengan *lightbox preview*), serta bagian penutup *scroll-expand*.
- **Arsip Proyek (`projects.html`):** Menampilkan 10 proyek dalam bentuk tumpukan folder arsip interaktif dengan animasi **membuka buku 3D** dan efek balik halaman (*page turn*), berisi pratinjau foto, spesifikasi *tech stack*, ringkasan, deskripsi proses, dan tautan repositori.

---

## Teknologi yang Digunakan

- **HTML5** — Struktur semantik multi-halaman.
- **Tailwind CSS (CDN)** — *Utility-first styling* dan tata letak responsif.
- **JavaScript (Vanilla JS)** — Logika pencarian blog, filter kategori, *auto-TOC*, *lightbox* gambar, dan manajemen data proyek.
- **GSAP 3 & ScrollTrigger (CDN)** — Animasi *full-screen text zoom*, *scroll-expand*, buka buku 3D (*180° hinge flip*), dan transisi balik halaman.
- **Google Fonts & FontAwesome 6 (CDN)** — Tipografi (`Inter`, `Instrument Serif`, `JetBrains Mono`, `Caveat`) dan ikon antarmuka.

---

## Struktur Folder

```text
Portofolio/
├── Image/                  # Aset gambar profil, blog, portofolio, dan sertifikat
├── project/                # Screenshot 10 proyek (prj1.png - prj10.png)
├── index.html              # Halaman utama (Beranda)
├── blog.html               # Halaman daftar artikel blog
├── artikel1.html           # Halaman baca artikel 1
├── artikel2.html           # Halaman baca artikel 2
├── artikel3.html           # Halaman baca artikel 3
├── about.html              # Halaman profil, sertifikat 3D, dan penutup
├── projects.html           # Halaman arsip 10 proyek (3D Book Viewer)
└── README.md               # Dokumentasi project
