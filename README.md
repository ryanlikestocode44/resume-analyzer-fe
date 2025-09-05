# INDONESIAN
----------------------------------------
# 🎨 Resume Analyzer - Frontend

Frontend antarmuka **Resume Analyzer** dibangun menggunakan **React + Vite** dengan dukungan **Tailwind CSS** dan **ShadCN UI** untuk antarmuka modern, serta **Chart.js** untuk visualisasi data.

Antarmuka ini merupakan bagian dari **Tugas Akhir/Skripsi** dengan judul:  
**"Implementasi Ekstraksi Informasi, Penilaian, dan Rekomendasi Rule-Based dan Named Entity Recognition pada Antarmuka Web Resume Analyzer."**

---

## ✨ Fitur Frontend
- **Upload Resume**: form untuk unggah resume PDF (*ATS-friendly*).
- **Halaman Analisis**: menampilkan informasi ekstraksi, skor penilaian, serta rekomendasi bidang pekerjaan, skill, kursus, dan video.
- **Visualisasi**: grafik interaktif (Chart.js) untuk skor resume.
- **Halaman Tentang**: informasi mengenai tujuan & cara kerja antarmuka.
- **Error Page**: menampilkan pesan error jika file tidak valid.
- **Admin Dashboard**: akses data pengguna & statistik.

---

## 🛠️ Instalasi Frontend

1. **Masuk ke folder frontend**
   ```bash
   cd frontend
2. **Install dependencies**
   ```bash
   npm install
3. **Konfigurasi Environment**
   ```bash
   VITE_API_URL=http://localhost:5000
4. **Jalankan Antarmuka Frontend**
   ```bash
   npm run dev

📷 **Tampilan Antarmuka**
- Input berkas resume
- Hasil analisis (dengan sidebar navigation, section, resume preview)
- Menampilkan Informasi Pribadi
- Menampilkan Skor Pengalaman, Skor Kelengkapan Konten Resume, Skor Keseluruhan
- Rekomendasi skill, kursus, video

👨‍🎓 **Catatan**
Frontend ini dibuat sebagai bagian dari penyusunan Tugas Akhir/Skripsi dan terintegrasi dengan backend berbasis Flask.



# ENGLISH
----------------------------------------
# 🎨 Resume Analyzer - Frontend

The frontend interface of **Resume Analyzer** is built using **React + Vite** with support from **Tailwind CSS** and **ShadCN UI** for a modern design, as well as **Chart.js** for data visualization.

This interface is developed as part of a **Bachelor Thesis/Final Project** with the title:  
**"Implementation of Information Extraction, Evaluation, and Recommendations Using Rule-Based and Named Entity Recognition on a Web-Based Resume Analyzer Interface."**

---

## ✨ Frontend Features
- **Upload Resume**: Form to upload ATS-friendly PDF resumes.
- **Analysis Page**: Displays extracted information, evaluation scores, and recommendations for job roles, skills, courses, and tutorials.
- **Visualization**: Interactive charts (Chart.js) for resume scoring.
- **About Page**: Provides information on the purpose and workflow of the interface.
- **Error Page**: Displays error messages for invalid files.
- **Admin Dashboard**: Access to user data and statistics.

---

## 🛠️ Frontend Installation

1. **Navigate to the frontend folder**
   ```bash
   cd frontend
2. **Install Dependencies**
   ```bash
   npm install
3. **Configure Environment**
   ```bash
   VITE_API_URL=http://localhost:5000
4. **Run the Frontend Interface**
   ```bash
   npm run dev
