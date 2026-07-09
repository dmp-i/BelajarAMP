# 📚 Belajar AMP

Repository untuk belajar tentang **AMP (Accelerated Mobile Pages)** - perbedaan antara page asli dan page AMP.

## 📖 Deskripsi

Repository ini mendemonstrasikan perbedaan antara:
- **📄 Page Asli (index.html)** - HTML5 standar dengan fitur lengkap
- **⚡ Page AMP (amp.html)** - Halaman yang dioptimalkan dengan standar AMP untuk performa maksimal

## 🚀 Fitur

### Page Asli (Original)
- ✓ HTML5 penuh dengan JavaScript modern
- ✓ CSS3 unlimited dengan styling kompleks
- ✓ Semua fitur web modern
- ✓ Pengalaman desktop yang lengkap
- ✓ Loading tergantung optimisasi

### Page AMP
- ⚡ Valid AMP (Accelerated Mobile Pages)
- ⚡ Loading instan dan very fast
- ⚡ CSS inline dibatasi max 75KB
- ⚡ Hanya menggunakan AMP JavaScript
- ⚡ Dioptimalkan untuk Core Web Vitals
- ⚡ Terjamin performa mobile yang baik

## 📝 Cara Menggunakan

### Akses Halaman

1. **Page Asli (Original)**
   - File: `index.html`
   - Buka di browser dengan URL: `index.html`
   - Versi desktop full dengan semua fitur

2. **Page AMP**
   - File: `amp.html`
   - Buka di browser dengan URL: `amp.html`
   - Versi yang dioptimalkan untuk mobile

### Membandingkan Kedua Halaman

Buka kedua halaman di browser tab berbeda dan bandingkan:
- Kecepatan loading
- Ukuran file
- Fitur-fitur yang tersedia
- Tampilan dan responsivitas

## 🔍 Perbedaan Utama

| Aspek | Page Asli | Page AMP |
|-------|-----------|---------|
| **HTML** | HTML5 standar | HTML AMP strict |
| **JavaScript** | Custom JS allowed | Hanya AMP JS |
| **CSS** | Unlimited external | Max 75KB inline |
| **Ukuran** | Bisa besar | Minimal & optimal |
| **Loading** | Bervariasi | Instan/sangat cepat |
| **SEO Boost** | Standar | Ada boost dari Google |
| **Mobile UX** | Perlu optimisasi | Guaranteed optimal |

## 📚 Apa itu AMP?

**AMP (Accelerated Mobile Pages)** adalah:
- Inisiatif open-source dari Google
- Framework untuk membuat halaman web super cepat
- Fokus pada pengalaman mobile yang optimal
- Menggunakan subset dari HTML/CSS/JS yang dioptimalkan
- Memberikan boost ranking di Google Search

### Keuntungan AMP
- 📊 Loading 2-8x lebih cepat
- 📱 Sempurna untuk mobile
- 📈 SEO ranking boost
- 😊 Pengalaman pengguna lebih baik
- 💰 Bounce rate lebih rendah
- 🚀 Akses lebih cepat dari cache Google

## 🎯 Kapan Menggunakan AMP?

Gunakan AMP untuk:
- 📰 Website berita
- 📱 Blog dengan traffic tinggi
- 🛒 E-commerce dengan fokus mobile
- 📚 Content-heavy websites
- 🔍 Website yang peduli SEO ranking

## ⚙️ Technical Details

### Page Asli (index.html)
```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>...</title>
    <style>/* CSS standar */</style>
</head>
<body>
    <!-- HTML standar dengan semua fitur -->
    <script>/* Custom JavaScript */</script>
</body>
</html>
```

### Page AMP (amp.html)
```html
<!doctype html>
<html ⚡ lang="id">
<head>
    <meta charset="utf-8">
    <script async src="https://cdn.ampproject.org/v0.js"></script>
    <style amp-custom>/* CSS inline dibatasi */</style>
</head>
<body>
    <!-- HTML AMP yang valid -->
    <!-- Tidak ada custom JavaScript -->
</body>
</html>
```

## 🔧 Validasi AMP

Untuk memvalidasi halaman AMP:
1. Buka browser DevTools (F12)
2. Buka Console tab
3. Halaman AMP akan otomatis validasi
4. Lihat hasilnya di console

Atau gunakan [AMP Validator Online](https://validator.ampproject.org/)

## 📖 Resources

- [AMP Project Official](https://amp.dev/)
- [AMP Documentation](https://amp.dev/documentation/)
- [AMP Validator](https://validator.ampproject.org/)
- [AMP by Example](https://ampbyexample.com/)

## 🤝 Kontribusi

Silakan fork repository ini dan buat improvements:
1. Fork repository
2. Buat branch untuk fitur Anda
3. Commit changes
4. Push ke branch
5. Buat Pull Request

## 📄 Lisensi

Repository ini open source. Silakan gunakan untuk belajar.

## 💬 Pertanyaan & Diskusi

Jika ada pertanyaan tentang AMP atau repository ini:
- Buka [Issues](../../issues)
- Diskusikan implementasi AMP
- Share feedback dan saran

---

**Happy Learning! 🚀**

Selamat belajar tentang AMP dan performa web yang optimal! 

Buka `index.html` untuk page asli atau `amp.html` untuk page AMP.
