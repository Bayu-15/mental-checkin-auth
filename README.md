# 🧠 Mental Health Daily Check-in Web App

Aplikasi web yang membantu pengguna melakukan check-in harian terkait kondisi mental mereka, dengan fitur pelacakan mood, catatan pribadi, statistik mingguan, serta motivasi otomatis.

---

## 🧾 Project Overview

Masalah kesehatan mental sering kali tidak terlihat secara langsung, namun berdampak besar terhadap produktivitas dan kesejahteraan seseorang. Aplikasi ini bertujuan memberikan ruang pribadi bagi pengguna untuk merefleksikan perasaannya setiap hari, membantu mereka menyadari pola emosionalnya, dan mengembangkan kesadaran diri yang lebih baik.

---

## 🧰 Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Backend**: Firebase (Authentication & Firestore Database)
- **Charting**: Chart.js
- **Export**: html2pdf.js
- **Others**: Dark/Light Mode Toggle, Responsive Design

Alasan penggunaan:

- Firebase dipilih untuk kecepatan dan kemudahan implementasi autentikasi serta penyimpanan data real-time.
- Chart.js memberikan visualisasi statistik mingguan yang menarik dan mudah dibaca.
- html2pdf.js memudahkan pengguna menyimpan hasil check-in sebagai laporan pribadi.

---

## ✨ Features

- ✅ Login/Register dengan Firebase Authentication
- ✅ Verifikasi email
- ✅ Input mood harian (emoji + deskripsi)
- ✅ Tambah catatan pribadi
- ✅ Statistik mingguan (bar chart)
- ✅ Filter tanggal (manual)
- ✅ Dark mode / Light mode toggle
- ✅ Motivasi harian otomatis
- ✅ Export check-in ke PDF
- ✅ Kontrol akses pengguna
- ✅ Desain UI responsif dan modern

---

## 🧠 AI Support Explanation

Aplikasi ini menggunakan **AI secara sederhana** dengan:

- **Motivasi otomatis harian**: Skrip menampilkan motivasi berbeda setiap hari secara acak, membantu menjaga semangat pengguna.
- **Rencana pengembangan selanjutnya**: Integrasi AI untuk memberikan rekomendasi aktivitas berdasarkan pola mood pengguna.

Penggunaan AI berfungsi sebagai dukungan personalisasi dan peningkatan pengalaman pengguna (UX), yang menunjukkan penerapan teknologi secara relevan.

---

## 🚀 Setup Instructions

1. Clone repo ini
2. Buat project di [Firebase Console](https://console.firebase.google.com/)
3. Aktifkan **Authentication** (Email/Password) dan **Cloud Firestore**
4. Tambahkan file `firebase-config.js`:
   ```js
   const firebaseConfig = {
     apiKey: "...",
     authDomain: "...",
     projectId: "...",
     storageBucket: "...",
     messagingSenderId: "...",
     appId: "...",
   };
   firebase.initializeApp(firebaseConfig);
   ```
