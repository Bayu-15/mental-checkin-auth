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
- **Hosting**: Vercel
- **AI**: IBM Granite 

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
- ✅ Export check-in ke CSV
- ✅ Kontrol akses pengguna
- ✅ Desain UI responsif dan modern

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
---
## AI Support Explanation
1. Berdiskusi terkait ide aplikasi dan struktur yang akan dibentuk
2. Mereview eror
3. Berdiskusi terkait permasalahan ketika membangun aplikasi
4. Memberikan kritik & saran dalam pengembangan
5. Menyusun strategi hosting (Firebase & Vercel)
6. Menyusun strategi hosting (Firebase & Vercel)
7. Mendampingi debugging saat deploy dan testing fitur
