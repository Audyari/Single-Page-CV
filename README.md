# Single Page CV Project

## Deskripsi Proyek

Ini adalah proyek **Curriculum Vitae (CV) Online** yang dibuat menggunakan HTML murni. Halaman ini dirancang untuk menampilkan profil profesional seseorang dengan format single page (satu halaman).

## Struktur Konten

- **Header**: Menampilkan nama lengkap, jabatan (Junior Frontend Developer), dan informasi kontak
- **Skills**: Daftar kemampuan teknis dan soft skills
- **Experience**: Pengalaman kerja dengan deskripsi tanggung jawab
- **Education**: Informasi pendidikan terakhir
- **Social Links**: Tautan ke profil media sosial profesional

## Teknologi yang Digunakan

- HTML5 (semantic HTML)
- CSS3 (responsive design)
- Struktur yang accessible dan SEO-friendly

## Fitur-Fitur Unggulan

### 1. Semantic HTML

- Menggunakan tag HTML5 semantic (`<header>`, `<main>`, `<section>`, `<article>`, `<address>`)
- Struktur yang jelas dan bermakna untuk mesin pencari dan screen reader
- Aksesibilitas yang lebih baik untuk pengguna disabilitas

### 2. SEO Meta Tags

- **Meta Description**: Deskripsi singkat tentang CV untuk hasil pencarian
- **Meta Keywords**: Kata kunci relevan untuk optimasi SEO
- **Meta Author**: Nama pemilik CV
- **Meta Robots**: Instruksi untuk search engine crawler

### 3. Open Graph (OG) Tags

- **og:title**: Judul yang ditampilkan di media sosial
- **og:description**: Deskripsi untuk share di media sosial
- **og:type**: Tipe konten website
- **og:url**: URL referensi
- **og:image**: Gambar preview untuk media sosial

### 4. Favicon

- **Multiple sizes**: Mendukung 48x48, 32x32, 16x16 pixels
- **Apple Touch Icon**: Untuk iOS devices
- **Web App Manifest**: Support Progressive Web App (PWA)
- **File**: Menggunakan `icons8-favicon-48.png` yang terletak di folder `images/`

### 5. Responsive Design

- Mobile-first approach
- Grid layout untuk skills section
- Flexbox untuk social links
- Print-friendly styles

### 6. Responsive Design

- Mobile-first approach
- Grid layout untuk skills section
- Flexbox untuk social links
- Print-friendly styles

## Informasi Pemilik

- **Nama**: Audyari Wiyono
- **Email**: audy123ari@gmail.com
- **Posisi**: Junior Frontend Developer

## Struktur Folder

```
single-page-cv/
├── index.html              # File utama HTML dengan semua meta tags
├── README.md              # Dokumentasi proyek
├── css/
│   └── style.css         # Semua styles CSS (responsive design)
├── images/
│   └── icons8-favicon-48.png  # Favicon utama
```

## Struktur File Utama

### index.html

- Semantic HTML5 structure
- SEO Meta Tags (description, keywords, author, robots)
- Open Graph Tags (og:title, og:description, og:type, og:url, og:image)
- Social Media Links (LinkedIn, GitHub)
- Favicon links (multiple sizes)
- Link ke CSS

### css/style.css

- Responsive design (mobile-first)
- Grid layout untuk skills
- Flexbox untuk social links
- Print styles
- Animations dan transitions

## Penggunaan

1. **Edit Konten**: Ubah informasi di `index.html` sesuai profil Anda
2. **Styling**: Sesuaikan tampilan di `css/style.css`
3. **Ganti Favicon**: Ganti `images/icons8-favicon-48.png` dengan icon Anda
4. **Update OG Tags**: Sesuaikan URL dan gambar di meta tags

## Validasi

- HTML: Gunakan [W3C Validator](https://validator.w3.org/)
- SEO: Gunakan [Google Rich Results Test](https://search.google.com/test/rich-results)
- Accessibility: Gunakan [WAVE Tool](https://wave.webaim.org/)

## Sumber Referensi

- [roadmap.sh - Single Page CV Project](https://roadmap.sh/projects/single-page-cv)
