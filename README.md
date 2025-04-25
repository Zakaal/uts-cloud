# 📘 HRIS - Human Resource Information System  
### cmlabs DEV Ecosystem x JTI Polinema  
🚀 *Project Based Learning 2025 Collaboration*

---

## 🧾 Overview

HRIS (Human Resource Information System) adalah aplikasi web dan mobile yang dirancang untuk mempermudah aktivitas tim HR dalam mengelola data kepegawaian. Fitur utama mencakup manajemen data karyawan, surat menyurat, absensi, lembur, serta langganan berbayar berbasis payment gateway (Xendit). Aplikasi ini diharapkan menjadi solusi modern dan efisien yang dapat bersaing dengan produk HRIS populer seperti Talenta, Gajihub, dan LinovHR.

---

## 🎯 Tujuan Akhir

1. ✅ Membangun aplikasi berbasis web dan mobile untuk pengelolaan HR modern.
2. 🧩 Mengimplementasikan fitur-fitur utama:
   - Manajemen data karyawan (data pribadi dan pekerjaan)
   - Manajemen dokumen legal dan riwayat kerja
   - Pengaturan dan pelaporan absensi
   - Pengaturan dan pelaporan lembur
   - Langganan berbayar dengan Xendit
3. ⚙️ Menyesuaikan penggunaan teknologi:
   - Frontend: **Next.js** + **TailwindCSS**
   - Backend: **Laravel**
   - Database: **MySQL**
   - Payment Gateway: **Xendit**
4. 📱 Menyediakan versi mobile berbasis **Flutter**

---

## 🧱 Struktur Proyek

```mermaid
graph TD
    A[HRIS Project] --> B[Frontend (Next.js)]
    A --> C[Backend (Laravel)]
    A --> D[Mobile App (Flutter)]
    A --> E[Database (MySQL)]
    A --> F[Payment Integration (Xendit)]

    B --> B1[Authentication (Login/Register)]
    B --> B2[Dashboard (Admin/Employee)]
    B --> B3[Employee Management]
    B --> B4[Letter Management]
    B --> B5[Absensi & Check-Clock]
    B --> B6[Lembur (Over-Time)]
    B --> B7[Subscription & Pricing]

    C --> C1[REST API]
    C --> C2[Business Logic]
    C --> C3[Database Handling]

    D --> D1[Login]
    D --> D2[View & Edit Employee Data]
    D --> D3[Mobile Absensi (Face/Fingerprint)]
    D --> D4[Extra Features]
```

---

## 📦 Modul-Modul Utama

- **Authentication**: Login via email, ID karyawan, nomor telepon, dan Google OAuth.
- **Employee Management**: Manajemen data diri & pekerjaan karyawan.
- **Letter Management**: Dokumen legal, sertifikasi, evaluasi, dll.
- **Absensi (Check-Clock)**: Lokasi, jadwal kerja, laporan absensi otomatis.
- **Lembur (Overtime)**: Pengelolaan dan laporan lembur sesuai kebijakan perusahaan/pemerintah.
- **Pricing**: Sistem langganan Pay-as-you-go dengan Xendit.
- **Mobile App**: Versi ringan untuk karyawan yang mendukung absensi dan editing data.