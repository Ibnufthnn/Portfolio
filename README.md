# 🚀 Portofolio Personal — Ibnu Fathan

Website portofolio personal yang minimalis, modern, dan responsif — dibangun dengan HTML5 dan CSS3 murni tanpa framework eksternal.

## ✨ Fitur

- **Animasi CSS** — fade-in, slide-in, stagger, scroll-triggered animations
- **Dark Mode** — toggle otomatis + tersimpan di localStorage
- **Fully Responsive** — mobile-first, breakpoint 768px & 1024px
- **Loading Screen** — animasi loader saat pertama kali buka
- **Progress Bar Skills** — animasi saat elemen masuk viewport
- **Project Filter** — filter proyek berdasarkan kategori
- **Custom Scrollbar** — scrollbar berwarna biru elegan
- **Smooth Scroll** — navigasi halus antar section
- **SEO Optimized** — meta tags, semantic HTML, heading hierarchy

## 📁 Struktur File

```
portfolio/
├── index.html           # File utama
├── css/
│   └── style.css        # Semua styling & animasi
├── images/
│   ├── profile.jpg      # Foto profil (ganti dengan foto Anda)
│   └── projects/
│       ├── project1.jpg
│       ├── project2.jpg
│       └── project3.jpg
└── README.md
```

## 🎨 Palet Warna

| Variable | Warna | Hex |
|---|---|---|
| Primary | Biru Medium | `#2563EB` |
| Primary Light | Biru Muda | `#DBEAFE` |
| Text | Abu Gelap | `#1F2937` |
| Text Secondary | Abu Medium | `#6B7280` |

Ubah warna cukup dengan mengedit CSS Variables di bagian `:root` di file `css/style.css`.

## 📝 Cara Kustomisasi

### 1. Ganti Informasi Pribadi
Edit file `index.html` dan ubah:
- `Alex Pratama` → nama Anda
- `alex.pratama@email.com` → email Anda
- `+62 812 3456 7890` → nomor WhatsApp Anda
- `Jakarta, Indonesia` → lokasi Anda
- Deskripsi About, Skills, Projects sesuai kebutuhan

### 2. Ganti Foto
- Ganti `images/profile.jpg` dengan foto Anda (rasio 1:1 direkomendasikan)
- Ganti `images/projects/project1.jpg` dst. dengan screenshot proyek Anda

### 3. Ubah Warna Tema
Buka `css/style.css`, cari bagian `:root {` dan ubah nilai CSS variables:
```css
:root {
  --color-primary: #2563EB;     /* Warna utama */
  --color-secondary: #60A5FA;   /* Warna sekunder */
  /* ... */
}
```

## 🚀 Deploy ke GitHub Pages

### Langkah 1: Buat Repository GitHub
1. Login ke [github.com](https://github.com)
2. Klik tombol **"New"** untuk membuat repository baru
3. Beri nama repository: `username.github.io` (ganti `username` dengan username GitHub Anda)
   - Contoh: `alexpratama.github.io`
4. Pilih **"Public"**
5. Klik **"Create repository"**

### Langkah 2: Upload File
**Cara A — Melalui GitHub Web (Mudah):**
1. Buka repository yang baru dibuat
2. Klik **"uploading an existing file"** atau **"Add file > Upload files"**
3. Drag & drop semua file portfolio (index.html, folder css/, folder images/)
4. Klik **"Commit changes"**

**Cara B — Melalui Git CLI:**
```bash
# Di folder portfolio Anda
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/username/username.github.io.git
git push -u origin main
```

### Langkah 3: Aktifkan GitHub Pages
1. Buka repository > **Settings**
2. Scroll ke bagian **"Pages"** di sidebar kiri
3. Di bagian **Source**, pilih:
   - Branch: `main`
   - Folder: `/ (root)`
4. Klik **"Save"**
5. Tunggu 1-2 menit

### Langkah 4: Akses Website
Website Anda akan tersedia di:
```
https://username.github.io
```

> **Note:** Jika nama repository bukan `username.github.io`, website akan tersedia di:
> `https://username.github.io/nama-repository`

## 🔧 Tips Optimasi

### Optimasi Gambar
Compress gambar sebelum upload untuk performa lebih baik:
- Gunakan [Squoosh](https://squoosh.app/) (gratis, online)
- Format: WebP untuk ukuran lebih kecil
- Resolusi profil: 600x600px
- Resolusi project thumbnail: 800x500px

### Custom Domain (Opsional)
Jika ingin menggunakan domain sendiri (misal: `alexpratama.com`):
1. Beli domain di Niagahoster, Dewaweb, atau Namecheap
2. Di Settings GitHub Pages, masukkan custom domain Anda
3. Di pengaturan DNS domain, tambahkan CNAME record:
   - Type: `CNAME`
   - Name: `www`
   - Value: `username.github.io`

## 📱 Browser Support

| Browser | Support |
|---|---|
| Chrome 90+ | ✅ |
| Firefox 88+ | ✅ |
| Safari 14+ | ✅ |
| Edge 90+ | ✅ |
| IE 11 | ❌ |

## 📄 Lisensi

MIT License — bebas digunakan dan dimodifikasi untuk keperluan pribadi maupun komersial.

---

Made with ❤️ by Alex Pratama | [Website](https://alexpratama.github.io)
