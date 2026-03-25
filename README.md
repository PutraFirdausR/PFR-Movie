# 🎬 PFR-Movie App

Selamat datang di proyek **PFR-Movie**!  
Ini adalah aplikasi web sederhana untuk mencari data film. Aplikasi ini dibuat untuk mempraktikkan konsep **Asynchronous JavaScript** (seperti `fetch` atau `AJAX`) dengan mengambil data film secara *real-time* dari *Application Programming Interface* (API) publik.

🔗 **Live Demo:** [Coba Cari Film di Sini!](https://putra-movie.vercel.app)

## ✨ Fitur
- **Pencarian Judul Film:** Pengguna dapat mengetikkan judul film dan aplikasi akan menampilkan hasilnya.
- **Data Dinamis:** Data yang ditampilkan (seperti poster, tahun rilis, dll) diambil langsung dari *database* pihak ketiga (OMDB API).
- **Ringan & Cepat:** Dibangun dengan *Vanilla JavaScript* tanpa *framework* yang berat.

## 🛠️ Teknologi yang Digunakan
- **HTML5** (`index.html` untuk kerangka antarmuka pengguna)
- **Vanilla JavaScript** (`script.js` untuk menangani *event listener* dan *fetching data* dari API)
- **OMDB API** (The Open Movie Database - sebagai sumber data film)

## 📂 Struktur File
Berdasarkan repositori ini, struktur filenya sangat minimalis dan fokus pada fungsionalitas:
```text
PFR-Movie/
├── index.html          # Tampilan utama web dan form pencarian
├── script.js           # Logika pengambilan data (Fetch API) dan manipulasi DOM
└── README.md           # Dokumentasi proyek (file ini)
```

## 💻 Cara Menjalankan Secara Lokal
Jika kamu ingin menjalankan atau memodifikasi kode ini di komputermu:

1. Clone repositori ini:

```Bash
git clone [https://github.com/PutraFirdausR/PFR-Movie.git](https://github.com/PutraFirdausR/PFR-Movie.git)
```

2. Buka folder proyek:

```Bash
cd PFR-Movie
```

3. Jalankan Aplikasi:
Cukup klik dua kali pada file index.html untuk membukanya di browser.

⚠️ Catatan API Key: > Proyek ini menggunakan OMDB API. Jika kamu ingin mengembangkannya lebih lanjut, kamu mungkin perlu mendaftar di omdbapi.com untuk mendapatkan API Key milikmu sendiri dan memasukkannya ke dalam file script.js.
