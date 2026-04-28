# 🚀 Portofolio Website Modern & Kompleks

Sebuah website portofolio modern yang dibangun dengan HTML5, CSS3, dan JavaScript vanilla. Website ini menampilkan desain yang cantik, responsif, dan interaktif dengan berbagai fitur profesional.

## 📋 Fitur Utama

### 1. **Navigasi Responsive**

- Navigation bar sticky dengan backdrop blur
- Mobile hamburger menu
- Active link indicator on scroll

### 2. **Hero Section**

- Animated floating card
- Call-to-action buttons
- Scroll indicator dengan animasi bounce

### 3. **About Section**

- Profile information
- Professional highlights dengan 4 kategori
- Responsive layout

### 4. **Skills Section**

- 4 kategori skill: Frontend, Backend, Tools & DevOps, Soft Skills
- Animated progress bars
- Smooth loading animations

### 5. **Experience Section**

- Timeline vertical yang elegan
- Multiple job positions
- Tech stack untuk setiap pekerjaan
- Detailed job descriptions

### 6. **Projects Section**

- Grid layout responsif
- Project cards dengan hover effects
- Tech stack display
- Project statistics (rating & users)
- Overlay dengan link

### 7. **Certificates Section**

- Certificate cards dengan border gradient
- Year badges
- Certificate issuer info
- External links untuk verifikasi

### 8. **Contact Section**

- Contact form dengan validation
- Contact information dengan icons
- Social media links
- Success/error notifications

### 9. **Footer**

- Multi-column layout
- Social links
- Quick navigation
- Copyright information

## 🎨 Desain & UX

### Color Scheme

```css
Primary Color: #6366f1 (Indigo)
Secondary Color: #8b5cf6 (Purple)
Accent Color: #ec4899 (Pink)
Dark Background: #0f172a
Light Background: #f8fafc
```

### Typography

- Font Family: Segoe UI, Tahoma, Geneva, Verdana, Sans-serif
- Responsive font sizes (desktop, tablet, mobile)
- Proper line-height untuk readability

### Animations

- Fade-in on scroll
- Floating animations
- Progress bar animations
- Hover effects pada cards
- Smooth transitions

## 📱 Responsive Design

Website fully responsive dengan breakpoints:

- **Desktop**: 1200px dan keatas
- **Tablet**: 768px - 1024px
- **Mobile**: 480px - 768px
- **Small Mobile**: 480px ke bawah

## 🔧 Cara Menggunakan

### 1. **Setup Dasar**

```bash
# Buka file index.html di browser
# Atau gunakan Live Server di VS Code
```

### 2. **Kustomisasi Data**

Edit bagian-bagian berikut di `index.html`:

#### About Section

```html
<h3>Web Developer & Full Stack Engineer</h3>
<p>Deskripsi Anda di sini...</p>
```

#### Skills

Update skill items dengan keahlian Anda:

```html
<div class="skill-item">
  <span class="skill-name">Bahasa/Tool Anda</span>
  <div class="skill-bar">
    <div class="skill-progress" style="width: 90%"></div>
  </div>
</div>
```

#### Experience

Tambah/edit pengalaman kerja:

```html
<div class="timeline-item">
  <div class="timeline-marker"></div>
  <div class="timeline-content">
    <h3>Posisi Anda</h3>
    <p class="company">Nama Perusahaan</p>
    <!-- Isi detail pengalaman -->
  </div>
</div>
```

#### Projects

Update project cards:

```html
<div class="project-card">
  <div class="project-image">
    <div class="image-placeholder">
      <i class="fas fa-icon"></i>
    </div>
  </div>
  <div class="project-content">
    <h3>Nama Project</h3>
    <!-- Isi project details -->
  </div>
</div>
```

#### Contact Information

```html
<a href="mailto:email@anda.com">email@anda.com</a>
<a href="tel:+6281234567890">+62 812 345 678</a>
```

### 3. **Menambah Gambar**

Ganti placeholder images dengan gambar Anda:

- Replace folder `assets/` dengan gambar Anda
- Update image paths di HTML

### 4. **Update Social Links**

Edit social media links di footer dan contact section:

```html
<a href="https://github.com/username" class="social-link" title="GitHub">
  <i class="fab fa-github"></i>
</a>
```

## 📁 Struktur File

```
portfolio/
├── index.html              # File HTML utama
├── css/
│   └── styles.css         # Stylesheet lengkap
├── js/
│   └── script.js          # JavaScript functionality
├── assets/                # Folder untuk gambar (opsional)
│   ├── profile.jpg
│   ├── project1.jpg
│   └── ...
└── README.md              # Documentation
```

## 🚀 Deployment

### Option 1: GitHub Pages

```bash
# 1. Create repository di GitHub
# 2. Push file ke repository
# 3. Go to Settings > Pages
# 4. Select main branch sebagai source
# 5. Website akan live di: https://username.github.io/portfolio
```

### Option 2: Netlify

```bash
# 1. Drag & drop folder ke Netlify
# atau gunakan Netlify CLI
# 2. Website akan langsung live
```

### Option 3: Vercel

```bash
# Similar dengan Netlify
# Deploy langsung dari folder
```

## 📊 Optimasi Performance

Website sudah dioptimasi dengan:

- ✅ CSS Grid & Flexbox untuk layout
- ✅ CSS Variables untuk theming
- ✅ Smooth animations & transitions
- ✅ Lazy loading readiness
- ✅ Mobile-first responsive design
- ✅ Minimal JavaScript dependencies
- ✅ Font Awesome icons (CDN)

## 🎯 Features yang Bisa Ditambah

- [ ] Dark mode toggle
- [ ] Multi-language support
- [ ] Blog section
- [ ] Testimonials section
- [ ] Email functionality (backend)
- [ ] Admin panel
- [ ] CMS integration
- [ ] Analytics tracking
- [ ] PWA capabilities
- [ ] Search functionality

## 🔒 Browser Support

- ✅ Chrome/Edge (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Mobile browsers

## 📝 License

Free to use dan modify sesuai kebutuhan Anda.

## 💡 Tips

1. **Personalisasi warna**: Edit CSS variables di `:root`
2. **Tambah animasi**: Update `styles.css` dengan keyframes baru
3. **Social links**: Update semua link sosial media Anda
4. **Content**: Replace semua placeholder text dengan info asli Anda
5. **Form handler**: Integrate dengan Formspree atau email service lain

## 🤝 Support

Jika ada pertanyaan atau issue, silakan contact atau buat issue di repository.

---

**Made with ❤️ for Portfolio**

Last Updated: 2024
