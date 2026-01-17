# 🚀 Rocket Avoider

|              Tampilan Desktop              |         Tampilan Mobile (D-Pad)          |
| :----------------------------------------: | :--------------------------------------: |
| ![Desktop Version](images/preview-web.png) | ![Mobile Version](images/preview-hp.png) |

**[MAIN SEKARANG (LIVE DEMO)](hhttps://nurjamilahh.github.io/nur-rocket-game/)**

**Rocket Avoider** adalah game arcade berbasis web yang menantang pemain untuk bertahan hidup di luar angkasa. Hindari meteor yang datang dan raih skor tertinggi!

## 🛠️ Teknologi yang Digunakan

- **TypeScript**: Untuk logika game yang aman dan terstruktur.
- **Tailwind CSS v4**: Untuk desain antarmuka (UI) yang modern dan responsif.
- **HTML5 Canvas/DOM**: Untuk rendering elemen game.

## 📱 Fitur Mobile-Friendly

Game ini telah dioptimalkan untuk perangkat seluler:

- **On-Screen Controls**: Tersedia tombol navigasi panah di layar untuk memudahkan pemain mobile.
- **Responsive Layout**: Antarmuka game (UI) akan menyesuaikan ukuran layar secara otomatis.

## 🛡️ Security & Safety Features

Keamanan data pemain adalah prioritas dalam pengembangan game ini:

- **XSS Protection (Sanitization):** Nama pilot yang dimasukkan melalui callsign telah melalui proses sanitization menggunakan fungsi this.sanitize(). Ini memastikan tidak ada kode berbahaya (script injection) yang bisa dijalankan melalui sistem leaderboard.

- **Secure JSON Parsing:** Menggunakan blok JSON.parse dengan mekanisme fallback untuk mencegah aplikasi crash jika terjadi kerusakan format data pada Local Storage.

- **Data Integrity:** Sistem secara otomatis memvalidasi dan membatasi jumlah data skor hanya untuk 5 pilot terbaik, menjaga penyimpanan browser tetap bersih dan efisien.

## 📁 Struktur Project

- `src/`: Berisi file sumber TypeScript (.ts).
- `dist/`: Berisi file JavaScript (.js) hasil compile yang dijalankan di browser.
- `audio/`: Efek suara dan musik latar game.
- `images/`: Aset grafis game.

## 🚀 Cara Menjalankan Project di VS Code

1. **Clone repository ini:**

   ```bash
   git clone [https://github.com/nurjamilahh/nur-rocket-game.git](https://github.com/nurjamilahh/nur-rocket-game.git)
   ```

2. **Instal dependensi:**

   ```bash
   npm install
   ```

3. **Compile TypeScript:** Untuk melakukan build sekali jalan.

   ```bash
   npm run build
   ```

   Atau untuk mode otomatis (watch mode):

   ```bash
   npm run watch
   ```

4. **Mainkan Game:** Klik kanan pada file `index.html` lalu pilih "Open with Live Server" agar game berjalan lancar lengkap dengan suara dan gambarnya.

🎮 Cara Bermain

- Isi Callsign (nama pilot) kamu.
- Klik tombol INITIALIZE untuk memulai misi.
- Hindari rintangan dan kumpulkan skor sebanyak mungkin untuk masuk ke daftar **Top Pilots**!

## 📬 Saran & Kendala

Saya sangat menghargai setiap saran dari para Pilot! Jika Anda menemukan kendala atau ingin menyampaikan feedback, silakan kirim ke:

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:worknurjam@gmail.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-Nurjam_Projects-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/6285782602672)
Project Link: [https://github.com/nurjamilahh/nur-rocket-game](https://github.com/nurjamilahh/nur-rocket-game)

---

_This is part of the **Nurjam Projects** collection — exploring code, one experiment at a time._
