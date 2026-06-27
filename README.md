# FAF Grind & Learn – Barista Training Management System

FAF Grind & Learn adalah proyek akademik berupa platform pelatihan barista berbasis web. Sistem ini dirancang untuk membantu proses pembelajaran barista agar lebih terstruktur, fleksibel, dan terdokumentasi melalui materi pembelajaran, video praktik, pelacakan progres, serta sertifikasi.

Project ini dikembangkan secara kolaboratif sebagai bagian dari proyek akademik Program Studi Teknik Informatika, Politeknik Caltex Riau.

## Deskripsi Project

FAF Grind & Learn dikembangkan untuk menjawab kebutuhan pelatihan barista yang lebih konsisten dan mudah diakses. Dalam praktiknya, pelatihan barista sering dilakukan secara manual, tidak terdokumentasi dengan baik, dan terbatas oleh tempat serta waktu.

Melalui platform ini, pengguna dapat mengakses materi pembelajaran barista, melihat video praktik, mengikuti progres pelatihan, serta memperoleh sertifikasi setelah menyelesaikan pembelajaran. Sistem ini juga dirancang untuk mendukung kebutuhan pelatihan offline bersama mitra café.

## Tujuan Project

Tujuan utama dari project ini adalah membangun sistem pelatihan barista berbasis web yang dapat membantu pengguna belajar secara mandiri maupun melalui pelatihan terstruktur.

Tujuan khusus project ini meliputi:

* Menyediakan platform pembelajaran barista berbasis web.
* Menyediakan materi teori dan video praktik.
* Membantu pengguna memantau progres pembelajaran.
* Menyediakan fitur sertifikasi setelah pelatihan selesai.
* Mendukung integrasi pelatihan online dan offline.
* Membantu café atau pelaku industri kopi dalam proses onboarding dan pelatihan karyawan baru.

## Fitur Utama

* Landing page platform pelatihan barista
* Autentikasi pengguna
* Dashboard pengguna
* Materi pembelajaran barista
* Video praktik
* Tracking progres pembelajaran
* Sertifikasi
* Jadwal pelatihan offline
* Integrasi database menggunakan Supabase
* Visualisasi data/progres pembelajaran

## Teknologi yang Digunakan

* React.js
* Vite
* JavaScript
* Tailwind CSS
* Supabase
* Axios
* React Router DOM
* React Icons
* React Tooltip
* Framer Motion
* Recharts
* Git & GitHub

## Struktur Repository

Source code utama aplikasi berada di folder `ProjectBPF-app`.

```bash
FAF_Grind-Learn/
├── ProjectBPF-app/
│   ├── public/
│   ├── src/
│   ├── .env.example
│   ├── .gitignore
│   ├── package.json
│   ├── package-lock.json
│   ├── vite.config.js
│   └── README.md
└── README.md
```

## Peran Saya

**Farizy Rahman Hidayat**
**Role:** Backend Development Contributor / Supabase Integration Contributor / Project Documentation Contributor

Kontribusi saya dalam project ini meliputi:

* Mengembangkan dan menyesuaikan bagian backend aplikasi untuk mendukung kebutuhan fitur sistem.
* Membantu integrasi Supabase sebagai backend-as-a-service untuk kebutuhan database dan autentikasi.
* Mendukung perancangan struktur database yang digunakan pada fitur utama sistem.
* Mengelola alur data antara frontend dan backend.
* Membantu implementasi fitur yang membutuhkan koneksi API dan database.
* Melakukan pengujian pada fitur yang berhubungan dengan backend dan integrasi data.
* Berkontribusi dalam penyusunan dokumentasi project seperti Project Charter, Business Case, Risk Analysis, Matrix Risk, Work Breakdown Structure, dan laporan akhir.
* Membantu dokumentasi kebutuhan sistem, ruang lingkup project, risiko, dan alur kerja aplikasi.

## Pembagian Tugas Kelompok

| Nama Anggota          | Kontribusi                                                                                                         |
| --------------------- | ------------------------------------------------------------------------------------------------------------------ |
| Albert Christian      | Frontend development, UI implementation, project documentation, business case, risk analysis, dan laporan          |
| Farizy Rahman Hidayat | Backend development, Supabase integration, database support, system documentation, WBS, risk analysis, dan laporan |
| Febriana              | Project documentation, WBS, business case, risk analysis, dan laporan                                              |

## Catatan Kolaborasi

Project ini dikerjakan secara kolaboratif oleh anggota kelompok. Selama proses pengembangan, sebagian pekerjaan dilakukan pada perangkat masing-masing anggota sebelum digabungkan ke dalam repository utama. Oleh karena itu, riwayat commit pada repository ini tidak sepenuhnya merepresentasikan seluruh pembagian tugas dan kontribusi setiap anggota.

Repository ini merupakan hasil integrasi dari pekerjaan kelompok dan digunakan sebagai dokumentasi portofolio akademik.

## Dokumentasi Manajemen Project

Dokumen manajemen project yang disusun dalam project ini meliputi:

* Project Charter
* Business Case
* Risk Identification
* Matrix Risk
* Cost Benefit Analysis
* Work Breakdown Structure
* Laporan Project

## Ruang Lingkup Project

Ruang lingkup project meliputi:

* Pengembangan antarmuka web
* Integrasi backend dan database
* Autentikasi pengguna
* Fitur materi pembelajaran
* Fitur video praktik
* Fitur tracking progres
* Fitur sertifikasi
* Fitur jadwal pelatihan offline
* Pengujian fungsionalitas sistem
* Deployment prototype

Ruang lingkup yang tidak termasuk:

* Maintenance jangka panjang setelah project selesai
* Pengembangan sistem dalam skala produksi penuh
* Pemasaran dan distribusi platform secara luas

## Cara Menjalankan Project

1. Clone repository:

```bash
git clone https://github.com/ApolloVeritas/FAF_Grind-Learn.git
```

2. Masuk ke folder repository:

```bash
cd FAF_Grind-Learn
```

3. Masuk ke folder aplikasi:

```bash
cd ProjectBPF-app
```

4. Install dependencies:

```bash
npm install
```

5. Buat file environment dari contoh yang tersedia:

```bash
cp .env.example .env
```

6. Isi konfigurasi Supabase pada file `.env`.

```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

7. Jalankan project:

```bash
npm run dev
```

8. Buka aplikasi di browser:

```bash
http://localhost:5173
```

## Script yang Tersedia

| Command           | Fungsi                                     |
| ----------------- | ------------------------------------------ |
| `npm run dev`     | Menjalankan aplikasi pada mode development |
| `npm run build`   | Membuat build production                   |
| `npm run preview` | Menjalankan preview hasil build            |
| `npm run lint`    | Menjalankan proses linting                 |

## Status Project

Status: **Academic Project / Prototype**

Project ini dibuat untuk kebutuhan akademik dan pembelajaran. Sistem dirancang sebagai prototype platform pelatihan barista berbasis web dan belum ditujukan sebagai sistem produksi penuh.

## Anggota Kelompok

* Albert Christian
* Farizy Rahman Hidayat
* Febriana

## Catatan Keamanan

File `.env` digunakan untuk menyimpan konfigurasi environment seperti URL dan key Supabase. Jangan menyimpan API key asli, password, token, atau credential sensitif secara langsung di repository publik.

## Lisensi

Project ini dibuat untuk kebutuhan akademik. Penggunaan ulang kode atau dokumen dapat disesuaikan dengan persetujuan anggota kelompok.
