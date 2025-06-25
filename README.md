# ✨ Ytdl

[![HTML](https://img.shields.io/badge/language-HTML-blue.svg)](https://www.w3.org/html/)


> Pengunduh YouTube sederhana yang dibangun menggunakan HTML dan Node-fetch.

## ✨ Fitur Utama

* **Pengunduhan Video YouTube:**  Aplikasi web ini memungkinkan pengguna untuk mengunduh video YouTube.  Fungsionalitas inti berpusat pada integrasi `node-fetch` untuk mengambil data video.  Implementasi spesifiknya masih perlu dikaji lebih lanjut untuk menentukan metode pengunduhan yang tepat (misalnya, menggunakan URL langsung atau API pihak ketiga).

## 🛠️ Tumpukan Teknologi

| Kategori         | Teknologi      | Catatan                                     |
|-----------------|-----------------|---------------------------------------------|
| Bahasa Pemrograman | HTML            | Bahasa markup utama untuk antarmuka pengguna |
| Manajemen Paket   | npm             | Digunakan untuk mengelola dependensi          |
| Perpustakaan      | node-fetch     | Untuk membuat permintaan HTTP ke YouTube      |


## 🏛️ Tinjauan Arsitektur

Arsitektur aplikasi ini sederhana dan berpusat pada antarmuka pengguna HTML tunggal (`index.html`). Logika pengunduhan kemungkinan besar terintegrasi langsung ke dalam HTML atau diimplementasikan dengan cara yang sangat sederhana mengingat hanya `node-fetch` yang digunakan sebagai dependensi.  Uji coba lebih lanjut diperlukan untuk memberikan gambaran arsitektur yang lebih tepat.

## 🚀 Memulai

Berikut adalah langkah-langkah untuk menjalankan proyek ini secara lokal:

1. Klon repositori:
   ```bash
   git clone https://github.com/Fiisya/ytdl.git
   cd ytdl
   ```
2. Instal dependensi:
   ```bash
   npm install
   ```
3. Jalankan server pengembangan:
   ```bash
   npm run dev
   ```
   *(Perintah `npm run dev` diasumsikan berdasarkan informasi yang tersedia.  File `package.json` mungkin berisi skrip yang berbeda.)*

## 📂 Struktur File

```
/
├── index.html
└── package.json
```

* **/:** Direktori akar proyek.
* **index.html:**  File HTML utama yang berisi antarmuka pengguna.
* **package.json:** File yang mendefinisikan dependensi proyek dan skrip.

