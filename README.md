# 📌 Meeting Room Booking System (Frontend)

Frontend reservasi ruangan meeting berbasis web menggunakan **React.js + Vite**.
Aplikasi ini terhubung dengan backend Laravel untuk mengelola autentikasi, booking, dan data ruangan.

---

## 🚀 Features

* 🔐 Login & Register
* 🏢 Booking ruang meeting
* 📅 Manajemen jadwal
* 📊 Histori booking
* ⚡ API integration (Axios + React Query)
* 🎨 UI dengan Tailwind CSS
* 🧠 State management (Zustand)

---

## 🛠️ Tech Stack

* React 19
* Vite
* Tailwind CSS
* React Router DOM
* React Query
* Axios
* Zustand
* React Hook Form + Yup
* React Toastify

---

## 📂 Repository

* 💻 Frontend (this repo):
  https://github.com/Magang-Hotel-Murah/meeting-room-booking-frontend.git

* ⚙️ Backend (oleh tim):
  https://github.com/Magang-Hotel-Murah/backend.git

---

## 📂 Project Structure

```id="str1"
frontendhotelmurah/
│
├── src/
│   ├── components/
│   ├── pages/
│   ├── services/      # API calls (axios)
│   ├── store/         # Zustand
│   ├── routes/
│   └── App.jsx
│
├── public/
├── index.html
├── package.json
└── vite.config.js
```

---

## ⚙️ Installation & Setup

### 1. Clone Repository

```bash id="cmd1"
git clone https://github.com/Magang-Hotel-Murah/meeting-room-booking-frontend.git
cd meeting-room-booking-frontend
```

---

### 2. Install Dependencies

Pastikan sudah install **Node.js (v18 atau lebih baru)**

```bash id="cmd2"
npm install
```

atau jika pakai yarn:

```bash id="cmd3"
yarn install
```

---

### 4. Jalankan Project (Development)

```bash id="cmd4"
npm run dev
```

Aplikasi akan berjalan di:

```id="url1"
http://localhost:5173
```

---

### 5. Build untuk Production

```bash id="cmd5"
npm run build
```

---

### 6. Preview Build

```bash id="cmd6"
npm run preview
```

---

## 🤝 Contributors

* **Sultan Maulana Ichiro** - Frontend Developer
* **Muhammad Amir Shafwan** - Backend Developer

---

## 📌 Notes

* Pastikan backend berjalan sebelum frontend
* Gunakan `.env` untuk konfigurasi API
* Jangan hardcode URL API di dalam code
