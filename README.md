
---

## 📌 README Frontend (React + Vite)

```markdown
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