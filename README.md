# tsumitate-toples-impian
Aplikasi penabung digital bertema Jepang — kumpulkan koin ke dalam toples visual untuk setiap target impianmu. 100% client-side, tanpa server.

# 積立 Tsumitate — Toples Impian 🏺

> Aplikasi penabung digital bertema Jepang. Setiap koin yang kamu tabung mengisi toples kaca virtual, sedikit demi sedikit, menuju target impianmu.

![License](https://img.shields.io/badge/license-MIT-B9903D)
![No Backend](https://img.shields.io/badge/backend-none-28495E)
![Made with](https://img.shields.io/badge/made%20with-HTML%20%2B%20jQuery-B23A2E)

## ✨ Tentang

**Tsumitate (積立)** — dalam bahasa Jepang berarti "menabung sedikit demi sedikit secara konsisten" — adalah aplikasi pelacak tabungan yang mengubah target finansialmu menjadi toples kaca yang perlahan terisi koin emas. Dibuat sepenuhnya dengan HTML, CSS, dan jQuery, tanpa server atau database — semua data tersimpan aman di browser kamu sendiri (`localStorage`).

Desainnya terinspirasi estetika Jepang: washi cream, tinta sumi, indigo ai, merah shu, dan emas koban, lengkap dengan tipografi Shippori Mincho & Zen Maru Gothic.

## 🎯 Fitur

- **Multi-goal savings jar** — buat banyak celengan/target sekaligus, masing-masing dengan toples SVG animasi yang terisi sesuai progres
- **Setor & riwayat** — catat setiap setoran dengan catatan opsional, lihat riwayat lengkap per celengan
- **Countdown target** — hitung mundur hari/jam/menit/detik ke tanggal target yang kamu tentukan
- **Tag & filter** — kelompokkan celengan berdasarkan kategori (Impian, Darurat, Gadget, dll.), filter & urutkan dengan mudah
- **Pin celengan penting** ke bagian atas daftar
- **Mode terang & gelap** dengan palet warna yang disesuaikan
- **Backup & restore** data dalam format JSON
- **Cetak / simpan sebagai PDF**
- **Kutipan harian** — petuah, tips praktis, motivasi, dan psikologi uang yang berganti-ganti untuk menyemangati perjalanan menabungmu
- 100% **client-side**, privasi terjaga, tidak ada data yang dikirim ke server manapun

## 🚀 Cara Menjalankan

Tidak perlu instalasi apa pun.

1. Clone atau download repo ini
2. Buka file `index.html` langsung di browser

   ```bash
   git clone https://github.com/USERNAME/tsumitate-toples-impian.git
   cd tsumitate-toples-impian
   open index.html   # atau klik dua kali file-nya
   ```

Atau coba langsung secara online lewat **GitHub Pages**:
👉 `https://USERNAME.github.io/tsumitate-toples-impian/`

## 🛠️ Dibuat dengan

- HTML5 & CSS3 (custom properties untuk theming)
- [jQuery 3.7.1](https://jquery.com/)
- SVG untuk animasi toples & koin
- Google Fonts: Shippori Mincho, Zen Maru Gothic, Noto Sans JP
- `localStorage` API — tanpa backend, tanpa database

## 💾 Struktur Data

Semua data celengan disimpan di `localStorage` browser pada key `tsumitate_goals_v1`. Gunakan fitur **Backup (Unduh JSON)** di menu Pengaturan secara berkala agar data tidak hilang saat membersihkan cache browser.

## 📸 Screenshot

> Tambahkan screenshot aplikasi kamu di sini, misalnya:
>
> ```markdown
> ![Screenshot Tsumitate](./screenshot.png)
> ```

## 🗺️ Rencana Pengembangan

- [ ] Sinkronisasi cloud (opsional, tetap privasi-first)
- [ ] Grafik tren tabungan bulanan
- [ ] Ekspor riwayat setoran ke CSV
- [ ] Dukungan multi-bahasa (EN/ID/JP)

## 🤝 Kontribusi

Pull request terbuka untuk siapa saja. Untuk perubahan besar, silakan buka issue terlebih dahulu untuk mendiskusikan apa yang ingin diubah.

## 📄 Lisensi

Proyek ini dilisensikan di bawah [MIT License](./LICENSE) — bebas digunakan, dimodifikasi, dan dibagikan.

---

<p align="center">手作り with 心 — dibuat untuk menemani perjalanan menabungmu ✨</p>
