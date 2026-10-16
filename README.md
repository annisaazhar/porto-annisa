# 🌟 Web Portofolio - Annisa Fadilah Azhar

Portofolio data diri pribadi yang dirancang **super ringan (ultra lightweight)**, responsif di semua perangkat (HP, Tablet, Laptop), memiliki tampilan modern dengan fitur mode Gelap/Terang (Dark/Light mode), dan siap di-upload ke **GitHub** serta di-hosting secara **100% gratis di Vercel**.

---

## 🚀 Keunggulan Portofolio Ini

1. **Super Ringan & Cepat**: Dibangun dengan HTML5, Vanilla CSS3, dan Vanilla JavaScript (ES6+). Tanpa framework berat sehingga skor kecepatan Google Lighthouse mendekati 100!
2. **Desain Modern & Estetik**:
   - Skema warna gradien elegan dengan aksen Indigo & Cyan.
   - Glassmorphism backdrop-filter blur.
   - Efek mengetik dinamis (*typewriter effect*).
   - Filter interaktif untuk proyek dan keahlian teknis.
   - Toggle switch **Mode Gelap 🌙 & Mode Terang ☀️** yang tersimpan otomatis di browser (LocalStorage).
3. **Formulir Kontak Siap Pakai**: Mendukung tombol salin email satu klik (*one-click copy*) dan integrasi pengiriman email instan.
4. **Zero-Config Hosting Vercel**: Dilengkapi file `vercel.json` sehingga langsung aktif tanpa perlu konfigurasi build yang rumit.

---

## 📁 Struktur File Proyek

```text
c:/porto-annisa/
│
├── index.html          # Halaman utama portofolio
├── vercel.json         # Konfigurasi caching dan optimasi hosting Vercel
├── .gitignore          # File pengecualian saat upload ke Git/GitHub
├── README.md           # Panduan lengkap instalasi dan deployment
│
├── css/
│   └── style.css       # Sistem desain CSS variabel, responsif & animasi
│
├── js/
│   └── main.js         # Logika interaktif: typewriter, dark mode, filter proyek
│
└── assets/
    ├── favicon.svg     # Ikon logo website
    ├── avatar.svg      # Ilustrasi avatar profesional modern
    ├── project-1.svg   # Thumbnail sampel proyek 1 (Analytics Dashboard)
    ├── project-2.svg   # Thumbnail sampel proyek 2 (E-Commerce Store)
    ├── project-3.svg   # Thumbnail sampel proyek 3 (Productivity Kanban)
    └── project-4.svg   # Thumbnail sampel proyek 4 (Data Visualizer)
```

---

## 🛠️ Cara Menyesuaikan Data Diri Anda

1. **Mengganti Foto Profil**:
   - Jika ingin memakai foto asli Anda, masukkan foto berformat `.jpg` atau `.png` ke dalam folder `assets/` (misalnya `assets/foto-annisa.jpg`).
   - Buka `index.html`, cari baris `<img src="assets/avatar.svg"` dan ubah menjadi `<img src="assets/foto-annisa.jpg"`.
2. **Mengubah Kontak & Tautan Medsos**:
   - Buka `index.html`, cari bagian `<!-- Social Links -->` atau bagian `<!-- Kontak -->`.
   - Ganti link GitHub, LinkedIn, Instagram, dan alamat email sesuai dengan akun Anda.
3. **Menambahkan / Mengedit Proyek**:
   - Buka `index.html` pada bagian `<section id="proyek">`, Anda bisa mengedit judul, deskripsi, tag teknologi, serta link live demo / GitHub.

---

## 📤 Panduan Upload ke GitHub & Hosting Gratis di Vercel

### Langkah 1: Inisialisasi Git & Upload ke GitHub

1. Buka browser dan login ke akun [GitHub](https://github.com/).
2. Buat repository baru:
   - Klik tombol **New** (atau ikon `+` di kanan atas).
   - Beri nama repository, misalnya: `porto-annisa` atau `portfolio`.
   - Pilih **Public**.
   - Biarkan opsi lain default (jangan centang Add README karena sudah ada di lokal), lalu klik **Create repository**.
3. Buka terminal (PowerShell atau Git Bash) di folder proyek ini (`c:\porto-annisa`), lalu jalankan perintah berikut:

```bash
# 1. Inisialisasi git lokal
git init

# 2. Tambahkan semua file
git add .

# 3. Buat commit pertama
git commit -m "feat: initial commit modern portfolio website"

# 4. Ubah branch utama menjadi main
git branch -M main

# 5. Hubungkan ke repository GitHub Anda (ganti USERNAME_GITHUB dengan username Anda)
git remote add origin https://github.com/USERNAME_GITHUB/porto-annisa.git

# 6. Push kode ke GitHub
git push -u origin main
```

---

### Langkah 2: Hosting Gratis di Vercel (Hanya 1 Menit!)

1. Buka situs [Vercel](https://vercel.com/) dan login menggunakan akun **GitHub** Anda.
2. Di halaman Dashboard Vercel, klik tombol **"Add New..."** lalu pilih **"Project"**.
3. Pada daftar repository GitHub Anda, cari repository `porto-annisa` yang baru saja di-push, lalu klik tombol **"Import"**.
4. Di bagian pengaturan:
   - **Framework Preset**: Pilih `Other` (atau biarkan default terdeteksi otomatis).
   - **Root Directory**: `./` (biarkan default).
   - **Build and Output Settings**: Tidak perlu diubah karena situs ini murni HTML/CSS/JS statis yang sangat cepat.
5. Klik tombol **"Deploy"** 🚀.
6. Tunggu sekitar 10 - 20 detik. Website portofolio Anda sudah aktif dan live di internet dengan URL gratis seperti:
   `https://porto-annisa.vercel.app/`!

> **Tips:** Setiap kali Anda mengupdate kode dan melakukan `git push` ke GitHub, Vercel akan secara otomatis memperbarui website Anda dalam hitungan detik! 🎉
