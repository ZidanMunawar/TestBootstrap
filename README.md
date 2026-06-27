<div align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Status-Production%20Ready-success?style=for-the-badge" />
  
  <h1>☕ COFFEE RACER</h1>
  <p><i>Pacu Nikmatnya Kopi Hingga Garis Finish! 🏎️💨</i></p>
  
  <a href="#-tentang-proyek">Tentang</a> •
  <a href="#-fitur-unggulan">Fitur</a> •
  <a href="#-tech-stack">Tech Stack</a> •
  <a href="#-cara-menjalankan">Cara Menjalankan</a>
</div>

---

## 🏁 Tentang Proyek
**COFFEE RACER** adalah sebuah *landing page* kedai kopi modern dengan konsep *Dark Racing Theme*. Website ini dirancang untuk memberikan pengalaman visual yang elegan, cepat, dan interaktif bagi para pecinta kopi. 

Tidak hanya sekadar profil perusahaan, halaman ini dilengkapi dengan **sistem keranjang belanja interaktif** (berbasis LocalStorage), menu dinamis, animasi scroll yang halus, dan desain yang sepenuhnya responsif di semua perangkat.

## ✨ Fitur Unggulan

### 🎨 UI/UX & Desain
- **Dark Mode Aesthetic:** Tema gelap elegan dengan aksen kuning *racing* (`#ffc107`) yang mencolok.
- **Custom Preloader:** Animasi cangkir kopi beruap yang unik saat halaman pertama kali dimuat.
- **Smooth Animations:** Menggunakan library **AOS (Animate On Scroll)** untuk efek *fade, flip,* dan *zoom* yang memukau.
- **Fully Responsive:** Tampilan sempurna dari Desktop, Tablet, hingga Mobile.

### 🛒 E-Commerce Interaktif (Frontend)
- **Smart Shopping Cart:** Keranjang belanja yang menyimpan data di `localStorage` (tidak hilang saat refresh).
- **Dynamic Menu Rendering:** Menu minuman dan makanan di-render secara dinamis menggunakan JavaScript.
- **Product Detail Modal:** Pop-up detail produk saat tombol "Detail" diklik.
- **Checkout Simulation:** Simulasi proses checkout dengan notifikasi Toast.

### 📑 Section Lengkap
- **Hero Section:** Banner besar dengan *counter animation* (Varian Menu, Pelanggan, Rating).
- **About & Founders:** Profil kedai dan kartu interaktif para pendiri (Bang Rotz, Mr.Zang, Daprut, ZDN).
- **Menu Showcase:** Grid menu untuk *Drinks* dan *Foods*.
- **Testimonials:** Ulasan pelanggan dengan rating bintang.
- **Promo Banner:** Section khusus promo dengan kode kupon (`RACER20`).
- **Contact & Map:** Form kontak interaktif dan integrasi *iframe* Google Maps.

---

## 🛠️ Tech Stack
Proyek ini dibangun menggunakan teknologi web modern tanpa perlu backend yang rumit:
- **Structure:** HTML5 Semantic
- **Styling:** Custom CSS3 (dengan CSS Variables), Bootstrap 5.3
- **Icons:** Font Awesome 6.5
- **Animations:** AOS (Animate On Scroll) 2.3.1
- **Logic:** Vanilla JavaScript (ES6+)
- **Typography:** Google Fonts (Oswald & Poppins)

---

## 📂 Struktur File
```text
testbootstrap/
│
├── index.html          # File utama HTML landing page
├── style.css           # Custom CSS untuk styling dan animasi
└── images/             # Folder aset gambar (menu, founders, background)
    ├── coffee-cup-hero.png
    ├── mocha.jpg
    ├── dapex.jpg
    └── ... (aset lainnya)
