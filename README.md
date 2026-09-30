# Kalkulator Penyusutan & Penilaian Properti (ZNT 2026)

Aplikasi web *client-side* komprehensif yang dirancang khusus untuk membantu proses analisis penilaian properti, penghitungan penyusutan bangunan, hingga evaluasi **Standar Deviasi Relatif (RSD)** multi-sampel untuk proyek **Zona Nilai Tanah (ZNT) 2026**.

Versi terbaru ini telah ditingkatkan dengan **opsi pemilihan skala project ZNT dinamis** dan **validasi ambang batas RSD otomatis**.

Dilengkapi dengan antarmuka modern bertema **Neumorphism** yang elegan serta dukungan *Dark Mode*.

---

## ✨ Fitur Utama

1. **Multi-Sampel Properti**: Mendukung penambahan beberapa sampel pembanding sekaligus dengan berbagai jenis properti (**Rumah**, **Ruko**, dan **Lahan Kosong**).
2. **Penyesuaian Otomatis (Adjustment)**:
* Penyesuaian jenis data (Penawaran vs Transaksi).
* Perhitungan umur efektif bangunan berdasarkan tahun pembuatan, tahun renovasi, kondisi fisik, dan tabel penyusutan standar.
* Penyesuaian waktu (proyeksi hingga tahun 2026) dan status kepemilikan (HM, HGB, TMA, HP).


3. **Pilihan Skala Project ZNT & Threshold Dinamis**:
* **Skala 1:2.500** (Batas Maksimal RSD: **15%**)
* **Skala 1:10.000** (Batas Maksimal RSD: **25%**)
* **Skala 1:25.000** (Batas Maksimal RSD: **30%**)


4. **Indikator Peringatan RSD Otomatis**: Kartu hasil RSD akan secara otomatis mendeteksi apakah deviasi melampaui ambang batas skala yang dipilih. Jika melebihi batas, kartu hasil akan berubah menjadi warna merah (*danger state*) sebagai peringatan visual.
5. **Neumorphic & Dark Mode UI**: Tampilan visual yang lembut, responsif, dan ramah mata dengan transisi mode gelap otomatis.

---

## 🛠️ Teknologi yang Digunakan

* **HTML5** (Struktur markup semantik)
* **CSS3** (Desain Neumorphism, Flexbox, CSS Grid)
* **Vanilla JavaScript (ES6+)** (Logika perhitungan matematis, manipulasi DOM, dan penyimpanan lokal tema)

---

## 🚀 Cara Menjalankan (Lokal)

Aplikasi ini berjalan sepenuhnya di sisi peramban (*browser*) tanpa memerlukan server atau instalasi *build tools*.

1. Clone repositori ini atau unduh *source code* dalam bentuk ZIP:
```bash
git clone https://github.com/ekabudiku/kalkulator-penyusutan.git

```


2. Buka folder proyek hasil unduhan.
3. Buka file `index.html` menggunakan *browser* favorit Anda (Chrome, Edge, Firefox, Safari).

---

## 🌐 Live Demo

Akses versi online melalui GitHub Pages:

👉 [https://ekabudiku.github.io/kalkulator-penyusutan/](https://www.google.com/search?q=https://ekabudiku.github.io/kalkulator-penyusutan/)

---

## 👨‍💻 Author

* **Eka Budi**
* Instagram: [@ekabudiku](https://instagram.com/ekabudiku)
