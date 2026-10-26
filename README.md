# Livora — Live Well, Be You
Website Edukasi Hidup Sehat dan Kesejahteraan (Mendukung SDG 3: Kehidupan Sehat dan Sejahtera).

---

## 👥 Anggota Kelompok (Kelompok 7)
1. **Anak Agung Ratih Hardi Maheswari** — NIM: 2515091021  
   *Tugas:*
2. **I Komang Yusa Katmandu** — NIM: 2515091096  
   *Tugas:*
3. **Komang Alvin Diksajaya** — NIM: 2515091045  
   *Tugas:* 
4. **I Dewa Gede Surya Palguna** — NIM: 2515091148  
   *Tugas:*

---

## 📖 Deskripsi Website
**Livora** adalah platform web edukasi interaktif yang dirancang untuk meningkatkan kesadaran generasi muda dan mahasiswa terhadap pentingnya pola hidup sehat. Website ini dikembangkan sebagai bentuk dukungan nyata terhadap **Sustainable Development Goals (SDG) Target ke-3 (Kehidupan Sehat dan Sejahtera)**. Sasaran utama pengguna website ini adalah pelajar, mahasiswa, dan masyarakat umum agar dapat menerapkan kebiasaan hidup sehat dari hal-hal kecil sehari-hari.

---

## 📄 Struktur Halaman Website
Website ini terdiri dari 5 halaman utama yang saling terhubung secara konsisten[cite: 11, 13]:
1. **Beranda (`index.html`)**: Halaman utama yang memuat sambutan (*hero section*), pengenalan target SDG 3, serta ringkasan data kesehatan nasional[cite: 1, 12].
2. **Edukasi (`edukasi.html`)**: Pusat pengetahuan yang mengupas tiga pilar utama hidup sehat: nutrisi & pola makan, rutinitas gerak aktif, serta manajemen stres.
3. **Panduan (`panduan.html`)**: Halaman interaktif yang dilengkapi Kalkulator BMI (Body Mass Index) mandiri, panduan "Isi Piringku", serta tips aktivitas fisik dan waktu tidur[cite: 1, 12].
4. **Artikel (`artikel.html`)**: Rubrik wawasan khusus yang membahas statistik penting seputar kesehatan mental remaja, pentingnya berani mencari bantuan profesional, serta kiat merawat kewarasan[cite: 1, 12].
5. **Tentang (`tentang.html`)**: Berisi informasi profil anggota kelompok pengembang, tujuan pembuatan website untuk UTS Pemrograman Web, serta daftar referensi pustaka[cite: 1, 12].

---

## 💻 Teknologi yang Digunakan
* **HTML5**: Menggunakan elemen semantik seperti `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, dan `<footer>`.
* **CSS3**: Menggunakan stylesheet eksternal terpisah untuk setiap halaman dengan penerapan variabel warna (`:root`).
* **Layout & Responsivitas**: Menggunakan **Flexbox** dan **CSS Grid** untuk penyusunan tata letak kartu dan struktur halaman yang fleksibel[cite: 12, 13].
* **Media Queries**: Mengatur penyesuaian tampilan agar optimal pada perangkat Desktop, Tablet, dan Smartphone[cite: 12, 13].
* **JavaScript**: Digunakan secara sederhana untuk fungsi interaktif perhitungan BMI pada halaman Panduan[cite: 1, 11].

---

## ⚙️ Penjelasan Implementasi Teknis

### 1. Navigasi Konsisten & Sticky Navbar
Navigasi pada seluruh halaman dibuat tetap (*sticky*) di bagian atas layar agar mudah diakses pengguna saat melakukan *scrolling*[cite: 12, 13]:
```css
.navbar {
  position: sticky;
  top: 0;
  z-index: 50;
  background: var(--putih);
  border-bottom: 3px solid var(--kuning);
}
