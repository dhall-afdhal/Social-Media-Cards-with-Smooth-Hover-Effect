# 🎨 Social Media Cards with Smooth Hover Effect

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Font Awesome](https://img.shields.io/badge/Font_Awesome-339AF0?style=for-the-badge&logo=fontawesome&logoColor=white)

**Proyek kartu media sosial interaktif dengan efek hover yang menakjubkan dan animasi yang halus**

[Demo](#-preview) • [Fitur](#-fitur) • [Instalasi](#-instalasi--penggunaan) • [Kontribusi](#-kontribusi)

</div>

---

## 📋 Deskripsi Proyek

**Social Media Cards with Smooth Hover Effect** adalah proyek web modern yang menampilkan kartu profil media sosial dengan efek hover interaktif yang menarik. Proyek ini dirancang dengan fokus pada pengalaman pengguna yang smooth dan visual yang menawan.

Proyek ini menampilkan:
- ✨ **Efek hover dinamis** yang mengikuti pergerakan mouse
- 🎭 **Animasi entrance** yang halus saat halaman dimuat
- 🎨 **Background image** yang dapat dikustomisasi
- 📱 **Desain responsif** untuk semua perangkat
- 🌈 **Gradient effects** dan **glassmorphism** untuk tampilan modern

---

## ✨ Fitur

### 🎯 Fitur Utama

- **🎨 Hover Effect Interaktif**
  - Efek radial gradient yang mengikuti pergerakan mouse
  - Transisi halus pada semua elemen
  - Shadow dan glow effects yang dinamis

- **🎭 Animasi & Transisi**
  - Entrance animation dengan staggered delay
  - Smooth hover transitions
  - Icon rotation effects
  - Transform animations (scale, translate)

- **🎨 Desain Modern**
  - Glassmorphism effect dengan backdrop blur
  - Gradient overlays yang elegan
  - Custom background image support
  - Modern typography dengan Poppins font

- **📱 Responsive Design**
  - Mobile-first approach
  - Breakpoints untuk tablet dan desktop
  - Flexible grid layout
  - Touch-friendly interactions

- **⚡ Performance**
  - Optimized CSS animations
  - Efficient JavaScript event handling
  - Preload background images
  - Smooth 60fps animations

### 🎨 Platform Media Sosial yang Didukung

- 📸 **Instagram** - Dengan warna gradient pink/red
- 💻 **GitHub** - Dengan warna putih/abu-abu
- 💼 **LinkedIn** - Dengan warna biru profesional

---

## 🖼️ Preview

### Desktop View
```
┌─────────────────────────────────────────────────┐
│         Social Media Profiles                   │
│      Follow me on social media                  │
│                                                 │
│  ┌──────────┐  ┌──────────┐  ┌──────────┐       │
│  │          │  │          │  │          │       │
│  │ Instagram│  │  GitHub  │  │ LinkedIn │       │
│  │          │  │          │  │          │       │
│  │ 625k     │  │  150k    │  │  100k    │       │
│  │          │  │          │  │          │       │
│  │ [Follow] │  │ [Follow] │  │ [Connect]│       │
│  └──────────┘  └──────────┘  └──────────┘       │
└─────────────────────────────────────────────────┘
```

### Fitur Hover Effect
- 🖱️ **Mouse Tracking**: Efek gradient mengikuti posisi kursor
- ✨ **Glow Effect**: Radial gradient yang muncul saat hover
- 📈 **Lift Animation**: Card naik dengan shadow yang lebih dalam
- 🔄 **Icon Animation**: Icon membesar dan berputar saat hover

---

## 🛠️ Teknologi yang Digunakan

### Frontend Technologies
- **HTML5** - Struktur semantik dan markup
- **CSS3** - Styling modern dengan:
  - CSS Custom Properties (Variables)
  - CSS Grid & Flexbox
  - CSS Animations & Transitions
  - Backdrop Filter (Glassmorphism)
  - Gradient Effects
- **JavaScript (ES6+)** - Interaktivitas dan animasi:
  - Event Listeners
  - DOM Manipulation
  - CSS Custom Properties API
  - Animation Control

### External Libraries & Resources
- **Font Awesome 6.7.2** - Icon library untuk social media icons
- **Google Fonts (Poppins)** - Modern typography
- **CDN Resources** - Untuk performa optimal

---

## 📦 Instalasi & Penggunaan

### Prasyarat
- Web browser modern (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, dll)
- Web server lokal (opsional, untuk testing)

### Langkah Instalasi

1. **Clone Repository**
   ```bash
   git clone https://github.com/dhall-afdhal/Social-Media-Card-Hover.git
   cd Social-Media-Card-Hover
   ```

2. **Struktur File**
   ```
   Social-Media-Card-Hover/
   │
   ├── index.html      # File HTML utama
   ├── style.css       # Stylesheet dengan semua styling
   ├── script.js       # JavaScript untuk interaktivitas
   └── README.md       # Dokumentasi proyek
   ```

3. **Menjalankan Proyek**

   **Opsi 1: Langsung Buka File**
   - Buka `index.html` langsung di browser
   - ⚠️ Catatan: Beberapa fitur mungkin tidak berfungsi dengan `file://` protocol

   **Opsi 2: Menggunakan Live Server (Recommended)**
   ```bash
   # Menggunakan VS Code Live Server Extension
   # Klik kanan pada index.html > Open with Live Server
   
   # Atau menggunakan Python
   python -m http.server 8000
   
   # Atau menggunakan Node.js (http-server)
   npx http-server
   ```

4. **Akses di Browser**
   - Buka `http://localhost:8000` (atau port yang digunakan)
   - Nikmati efek hover yang menakjubkan!

---

## 🎨 Kustomisasi

### Mengubah Background Image

Edit di `style.css` atau `index.html`:

```css
/* Di style.css */
body {
  background-image: url('URL_GAMBAR_ANDA');
}

/* Atau di index.html */
<body style="background-image: url('URL_GAMBAR_ANDA');">
```

### Mengubah Warna Card

Edit CSS variables di `style.css`:

```css
.card:nth-child(1) {
  --color: 348 80% 60%; /* Instagram - Pink/Red */
}

.card:nth-child(2) {
  --color: 0 0% 100%;   /* GitHub - White */
}

.card:nth-child(3) {
  --color: 220 100% 35%; /* LinkedIn - Blue */
}
```

### Menambah Card Baru

1. Tambahkan HTML structure di `index.html`:
   ```html
   <div class="card">
       <div class="card_content">
           <i class="fa-brands fa-twitter"></i>
           <h2>Twitter</h2>
           <p>Followers : <span>200k</span></p>
           <a href="#">
               <i class="fa-solid fa-link"></i>
               <span>Follow me</span>
           </a>
       </div>
   </div>
   ```

2. Tambahkan warna custom di `style.css`:
   ```css
   .card:nth-child(4) {
     --color: 195 100% 50%; /* Twitter Blue */
   }
   ```

### Mengubah Animasi Speed

Edit timing di `script.js`:
```javascript
setTimeout(() => {
    card.style.transition = "opacity 0.6s ease, transform 0.6s ease";
    // Ubah 0.6s untuk mengubah kecepatan
}, index * 150); // Ubah 150 untuk delay antar card
```

---

## 📁 Struktur Kode

### HTML Structure
```html
<body>
  <header>          <!-- Header dengan judul -->
  <div id="cards">  <!-- Container untuk semua cards -->
    <div class="card">
      <div class="card_content">
        <!-- Icon, Title, Stats, Button -->
      </div>
    </div>
  </div>
</body>
```

### CSS Architecture
- **Reset & Base Styles** - Normalize dan base styling
- **Layout Styles** - Grid dan flexbox layouts
- **Component Styles** - Card, header, button components
- **Animation Styles** - Keyframes dan transitions
- **Responsive Styles** - Media queries untuk mobile/tablet

### JavaScript Functionality
- **Mouse Tracking** - Mengikuti posisi mouse untuk hover effect
- **Animation Control** - Entrance animations dengan staggered delay
- **Image Preloading** - Memastikan background image dimuat

---

## 🎯 Fitur Teknis Detail

### CSS Custom Properties
```css
--mouse-x: 0px;  /* Posisi X mouse relatif terhadap card */
--mouse-y: 0px;  /* Posisi Y mouse relatif terhadap card */
--color: hsl();  /* Warna gradient untuk setiap card */
```

### Event Handling
- `mousemove` - Tracking posisi mouse untuk radial gradient
- `DOMContentLoaded` - Trigger entrance animations
- `hover` - CSS hover states untuk interaksi

### Performance Optimizations
- ✅ Hardware-accelerated CSS transforms
- ✅ Efficient event delegation
- ✅ Optimized reflow/repaint
- ✅ Image preloading untuk background

---

## 🌐 Browser Support

| Browser | Version | Support |
|---------|---------|---------|
| Chrome  | 90+     | ✅ Full |
| Firefox | 88+     | ✅ Full |
| Safari  | 14+     | ✅ Full |
| Edge    | 90+     | ✅ Full |
| Opera   | 76+     | ✅ Full |

**Catatan**: Beberapa fitur modern seperti `backdrop-filter` mungkin tidak didukung di browser lama.

---

## 🐛 Troubleshooting

### Background Image Tidak Tampil
- Pastikan URL gambar dapat diakses
- Gunakan web server (bukan `file://`)
- Cek console browser untuk error CORS
- Pastikan koneksi internet aktif

### Animasi Tidak Smooth
- Pastikan browser support CSS animations
- Cek apakah ada extension yang memblokir JavaScript
- Update browser ke versi terbaru

### Hover Effect Tidak Bekerja
- Pastikan JavaScript diaktifkan
- Cek console untuk error JavaScript
- Pastikan `script.js` ter-load dengan benar

---

## 🚀 Roadmap & Future Improvements

- [ ] Tambah lebih banyak platform media sosial
- [ ] Dark/Light mode toggle
- [ ] Animasi loading screen
- [ ] Sound effects (opsional)
- [ ] Konfigurasi melalui JSON file
- [ ] PWA support
- [ ] Analytics integration

---

## 🤝 Kontribusi

Kontribusi sangat diterima! Jika Anda ingin berkontribusi:

1. Fork repository ini
2. Buat branch fitur (`git checkout -b feature/AmazingFeature`)
3. Commit perubahan (`git commit -m 'Add some AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Buka Pull Request

### Guidelines
- Ikuti struktur kode yang ada
- Tambahkan komentar untuk kode kompleks
- Test di berbagai browser
- Update dokumentasi jika diperlukan

---

## 📞 Contact & Support

<div align="center">

### 💼 DHA Production Engineering

**📧 Email:** [dhaproductionengineering@gmail.com](mailto:dhaproductionengineering@gmail.com)

**👨‍💻 Developer:** Afdhal

**🏢 Organization:** DHA Production

---

### 💬 Follow & Support

<a href="https://github.com/dhall-afdhal">
  <img src="https://img.shields.io/github/followers/dhall-afdhal?label=Follow&style=social" alt="Follow on GitHub">
</a>

<br><br>

<blockquote>

✨ Jika kamu menyukai proyek ini, jangan lupa untuk memberi ⭐ <b>Star</b> dan <b>Follow</b> <a href="https://github.com/dhall-afdhal">@dhall-afdhal</a> agar tidak ketinggalan update terbaru!

</blockquote>

</div>

---

## 🪪 Lisensi & Hak Cipta

<div align="center">

<h2>🪪 Lisensi & Hak Cipta</h2>

<p>

© <b>2020 - 2025</b> <a href="https://github.com/dhall-afdhal"><b>𝘈𝘧𝘥𝘩𝘢𝘭 & 𝘋𝘏𝘈 𝘗𝘳𝘰𝘥𝘶𝘤𝘵𝘪𝘰𝘯</b></a> — All rights reserved.

</p>

<blockquote>

🧠 <i>Diciptakan dengan semangat belajar, keamanan, dan inovasi oleh Afdhal.</i><br>

💻 <i>Powered by <b>Modern Web Technologies</b> — JavaScript ES6+, SVG, CSS3 Animations.</i>

</blockquote>

</div>

---

<div align="center">

**⭐ Jika proyek ini membantu Anda, jangan lupa berikan Star! ⭐**  

Made with ❤️ by <a href="https://github.com/dhall-afdhal">Afdhal</a> | DHA Production

</div>

---

## 📚 Referensi & Resources

- [MDN Web Docs](https://developer.mozilla.org/)
- [CSS-Tricks](https://css-tricks.com/)
- [Font Awesome Icons](https://fontawesome.com/)
- [Google Fonts](https://fonts.google.com/)
- [Can I Use](https://caniuse.com/) - Browser compatibility

---

## 🙏 Acknowledgments

- Terima kasih kepada semua kontributor
- Inspirasi dari komunitas web development
- Font Awesome untuk icon library
- Google Fonts untuk typography

---

<div align="center">

**Happy Coding! 🚀**

Jika ada pertanyaan atau saran, jangan ragu untuk membuka issue atau menghubungi kami!

</div>
