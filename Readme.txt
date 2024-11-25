# Mangrove Gunung Anyar Website Project

Ini adalah proyek halaman web untuk situs Mangrove Gunung Anyar. Proyek ini terdiri dari tiga file utama: `index.html`, `main.css`, dan `main.js`. Setiap file memiliki peran yang berbeda dalam membangun halaman web yang interaktif dan menarik.

## 1. index.html
File `index.html` adalah file HTML utama yang berfungsi sebagai struktur halaman. File ini mencakup berbagai bagian dari halaman, termasuk:

- **Header**: Bagian atas halaman yang berisi logo, menu navigasi, dan informasi kontak.
- **Hero Section**: Bagian utama halaman yang menampilkan carousel gambar untuk promosi destinasi.
- **About Section**: Bagian ini berisi informasi tentang Mangrove Gunung Anyar dan tujuan destinasi.
- **Gallery Section**: Galeri gambar yang menampilkan koleksi foto destinasi.
- **Events Section**: Bagian ini menampilkan acara-acara terkait konservasi mangrove.
- **About Us Section**: Informasi tentang sejarah, visi, misi, dan keunggulan Kebun Raya Mangrove.
- **Contact Section**: Formulir kontak dan informasi alamat, telepon, serta email.
- **Footer**: Bagian bawah halaman yang berisi informasi tambahan dan tautan ke media sosial.

Semua elemen di halaman ini diatur dalam struktur HTML yang bersih dan menggunakan class untuk styling dari `main.css`.

## 2. main.css
File `main.css` bertanggung jawab untuk memberikan gaya visual pada halaman. Beberapa poin penting dalam file ini meliputi:

- **Font dan Warna**: Mendefinisikan variabel font dan warna yang digunakan di seluruh halaman.
- **Layout**: Mengatur tata letak header, navigasi, hero section, galeri, dan bagian-bagian lain di halaman.
- **Efek Animasi**: Menambahkan efek transisi dan animasi halus seperti efek hover, tombol, dan animasi gambar.
- **Responsiveness**: CSS ini sudah mendukung responsif untuk memastikan tampilan yang baik di berbagai ukuran layar, termasuk perangkat mobile.

File ini menggunakan Bootstrap untuk grid layout dan gaya elemen dasar, namun juga memiliki banyak kustomisasi CSS.

## 3. main.js
File `main.js` adalah file JavaScript yang mengelola interaktivitas halaman, beberapa fitur yang diatur oleh JavaScript termasuk:

- **Scroll Event**: Mengubah gaya halaman (seperti menambahkan kelas `scrolled`) ketika halaman di-scroll.
- **Mobile Navigation**: Mengatur navigasi pada tampilan mobile dengan toggle untuk menampilkan/menyembunyikan menu.
- **Carousel Indicator**: Menghasilkan indikator carousel secara otomatis untuk hero section.
- **Lightbox & Swiper**: Inisialisasi GLightbox untuk galeri gambar dan Swiper untuk slider gambar di beberapa bagian.
- **Isotope Filtering**: Menyediakan filter untuk tata letak galeri gambar menggunakan library Isotope.
- **Preloader**: Menghapus elemen preloader setelah halaman sepenuhnya dimuat.
- **Scroll to Top**: Menampilkan tombol "scroll ke atas" saat halaman di-scroll ke bawah.

## Cara Menggunakan
1. Buka file `index.html` di browser untuk melihat tampilan halaman web.
2. File `main.css` sudah dihubungkan dalam `index.html` untuk menampilkan gaya halaman.
3. File `main.js` juga sudah dihubungkan di bagian bawah `index.html` untuk mengaktifkan fungsionalitas interaktif.

Pastikan bahwa seluruh aset (gambar, vendor, dll.) yang diperlukan berada pada folder yang benar sesuai struktur file di dalam HTML.

## Dependencies
- **Bootstrap**: Untuk layout dan elemen UI dasar.
- **GLightbox**: Untuk lightbox di galeri.
- **Swiper**: Untuk slider di hero section.
- **Isotope**: Untuk tata letak dinamis galeri.

## Lisensi
Proyek ini menggunakan template dari **BootstrapMade**. Silakan lihat lisensi template di: https://bootstrapmade.com/license/
