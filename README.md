# DuckFarm Manager - Website Aplikasi Manajemen Peternakan Bebek

Yo, ini website pribadi gw buat showcase aplikasi **DuckFarm Manager**, sebuah aplikasi mobile berbasis Android untuk memudahkan pengelolaan peternakan bebek.

## Tentang Aplikasi

**DuckFarm Manager** adalah solusi digital yang gw develop buat para peternak bebek modern. Aplikasi ini membantu dalam:

- **Pencatatan Populasi** - Catat berapa banyak bebek yang kita punya dengan mudah dan akurat
- **Manajemen Pakan** - Track stok pakan, jadwal feeding, dan biaya pakan
- **Pemeliharaan Ternak** - Catat riwayat kesehatan, vaksinasi, dan perawatan hewan
- **Laporan & Analytics** - Generate laporan untuk analisis bisnis yang lebih baik
- **Notifikasi** - Inget-ingetin jadwal pakan dan perawatan otomatis

Singkatnya, aplikasi ini bikin hidup peternak lebih mudah karena nggak perlu lagi catat-catatan manual di buku. Semua digital, terstruktur, dan bisa diakses kapan aja dari HP.

## Website

Website ini gw buat sebagai landing page untuk showcase aplikasi. Di sini ada:

- **Halaman Utama (Hero)** - Penjelasan singkat aplikasi
- **Fitur** - Detil tentang apa aja yang bisa dilakukan aplikasi
- **Tentang** - Info lebih detail tentang keunggulan aplikasi
- **Spek Teknis** - Detail teknologi yang dipakai
- **Kontak** - Form untuk hubungi gw, plus link social media

## Gimana Cara Pakenya?

1. Pastikan XAMPP udah running
2. Buka folder `c:\xampp\htdocs\website`
3. Akses di browser: `http://localhost/website/`
4. Done! Website udah siap

Atau kalau pake live server atau tools lainnya, tinggal buka folder ini aja.

## File-file yang Ada

```
website/
├── index.html      <- File utama HTML-nya
├── styles.css      <- Semua styling dan desain
├── script.js       <- JavaScript buat interaktivitas
└── README.md       <- File ini (dokumentasi)
```

## Desain dan Tema

Website ini pake tema professional dengan:

- **Warna Utama**: Hijau cerah (#2ecc71) buat primary action
- **Warna Sekunder**: Biru (#3498db) buat accent
- **Icons**: Font Awesome icons di mana-mana buat visual yang bagus
- **Responsive**: Bisa diakses dari desktop, tablet, atau mobile tanpa masalah
- **Animasi**: Smooth transitions dan hover effects biar keliatan profesional

## Fitur-Fitur yang Ada

### Navbar
- Sticky navigation di top
- Hamburger menu buat mobile
- Link smooth scroll ke setiap section
- Active indicator saat scroll

### Hero Section
- Banner utama dengan gradient background
- CTA buttons (Call to Action)
- Animasi masuk yang keren

### Feature Cards
- 6 kartu fitur utama
- Icon Font Awesome untuk setiap fitur
- Hover animation yang interaktif
- Responsive grid layout

### About Section
- Penjelasan mengapa harus pake aplikasi ini
- Checklist benefits dengan icon
- Image placeholder

### Technical Section
- Detail spesifikasi teknis
- Technology stack (Android, SQLite, dll)
- Glass morphism design yang modern

### Contact Section
- Informasi kontak (email, phone, location)
- Social media links
- Contact form yang bisa diisi
- Form validation buat user experience lebih baik

### Footer
- Copyright info
- Links ke privacy policy dan terms

## Kustomisasi

Kalau mau customize website ini, berikut yang bisa diubah:

### Di `index.html`:
- Ganti nama dan title sesuai yang lo mau
- Update email di contact section: `info@duckfarmmanager.com`
- Update nomor telepon: `+62 812-3456-7890`
- Edit link social media (Facebook, Instagram, Twitter, LinkedIn)

### Di `styles.css`:
- **Warna**: Cek bagian `:root` di atas CSS
  ```css
  --primary-color: #2ecc71;    /* Warna hijau utama */
  --secondary-color: #3498db;  /* Warna biru */
  --dark-color: #2c3e50;       /* Dark color */
  ```
- **Font**: Ganti di `body` section
- **Spacing**: Adjust padding dan margin sesuai preferensi

### Di `script.js`:
- Customize perilaku form submission
- Tambah event listener baru kalau perlu
- Modify animasi dan scroll behavior

## Kontak & Social Media

Buat yang mau tanya atau discuss tentang aplikasi ini:

- **Email**: info@duckfarmmanager.com
- **Phone**: +62 812-3456-7890
- **Social Media**: (Sesuaiin di contact section)

## Browser Support

Website ini bisa diakses di:

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile, Firefox Mobile)

## Notes

- Website ini fully responsive, jadi bisa diakses dari device apapun
- Font Awesome CDN dipake, jadi pastiin internet connection stabil biar icons muncul
- Form submission di contact section masih bersifat demo (gw belum integrate ke backend)
- Kalau mau integrate ke real email service, bisa pake backend seperti Node.js, PHP, atau service lain

## Security

- Nggak ada sensible data yang dipake di hardcode
- Form belum connected ke backend, jadi aman dari injection
- HTTPS recommended kalau di-deploy ke production

## Future Improvements

Beberapa improvement yang bisa ditambahin:

- [ ] Backend integration buat contact form
- [ ] Blog section buat tips peternakan
- [ ] Gallery section dengan screenshot aplikasi
- [ ] Video tutorial embedded
- [ ] Multi-language support
- [ ] Dark mode toggle
- [ ] Testimonial section dari user
- [ ] FAQ section

---
