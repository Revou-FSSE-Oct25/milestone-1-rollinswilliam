# Milestone 1 – Personal Portfolio Website

## 1) Overview of the website
- Halaman utama: kalimat pengantar, foto, sosial media, short biodata, CV, dan skill yang saya miliki saat ini.
- Navigasi ke setiap halaman:
  - Home: halaman utama
  - About/Project: ringkasan mini assignment (W0–W2) beserta tautan repository dan deployment terkait.
  - Testimoni/saran/kritik: halaman form sederhana untuk mengirimkan testimoni/masukan (teks, email, nomor telp, unggah gambar) dengan tombol Submit/Reset.
- Struktur halaman konsisten dengan elemen html; head, body (header, main, dan Footer), footer.

---

## 2) Features implemented
1. Navigasi multi-halaman: Home, Project (About), dan Testimonials yang saling terhubung, serta anchor kembali ke bagian atas halaman (untuk halaman utama saja):
  -Navigasi home ke project dan testimonials akan membuka halaman baru, namun home ke home akan merefresh halaman.
  -Navigasi project ke testimonials akan membuka halaman baru, namun project ke project akan merefresh halaman, project ke home akan membuka dihalaman yang sama.
  -Navigasi testimonials ke project akan membuka halaman baru, namun testimonials ke testimonials akan merefresh halaman, testimonials ke home akan membuka dihalaman yang sama.
2. Komponen hero/pengenalan dengan foto profil berbentuk bulat dan sapaan singkat.
3. Tautan media sosial lengkap dengan ikon (LinkedIn, Facebook, Instagram).
4. Biodata dalam bentuk TABEL yang memuat nama lengkap, tanggal lahir, pendidikan, peran, hobi, dan core skills.
5. Tombol DOWNLOAD untuk CV yang mengarah ke mendownload berkas PDF di folder assets/dokumen.
6. Daftar Skills ditampilkan menggunakan list di dalam FIELDSET yang telah diberi label/legend.
7. Halaman Project (About) yang merangkum progres tugas dan menyediakan link repo + deployment eksternal.
8. Halaman Testimonials berisi form input (teks, email, dan nomor telpon), kotak komentar (textarea), unggah berkas gambar, tombol Submit/Reset, serta catatan kecil untuk persetujuan penggunaan data.
9. Atribut seperti alt pada gambar untuk aksesibilitas dasar.

---

## 3) Technologies used
- HTML5 sebagai teknologi utama untuk struktur dan konten.
- Aset statis: gambar (images) dan dokumen PDF CV (assets).

---
[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/KTVBmApB)
