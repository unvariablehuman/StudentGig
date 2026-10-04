# StudentGig

StudentGig adalah platform papan lowongan kerja (job board) berbasis web yang dirancang khusus untuk menghubungkan mahasiswa dengan peluang kerja part-time dan freelance. Platform ini dikembangkan sebagai proyek mata kuliah Web Programming (COMP6821001) di Universitas Bina Nusantara.

---

## Ringkasan Proyek

- **Mata Kuliah:** COMP6821001 - Web Programming
- **Kelas / Kelompok:** LC01 - Kelompok 2
- **Fokus SDG:** SDG 8 - Decent Work and Economic Growth (Pekerjaan Layak dan Pertumbuhan Ekonomi)

StudentGig bertujuan untuk mendorong pertumbuhan ekonomi yang inklusif serta memberikan akses pekerjaan yang layak bagi mahasiswa yang ingin mencari pengalaman kerja, membangun portofolio, dan mengembangkan keterampilan selama masa perkuliahan.

---

## Tim Pengembang (Kelompok 2)

1. Maureen Calista Surjo - 2802536392
2. Jessica Eileen Handakara - 2802479426
3. Sabrina Arfanindia Devi - 2802448755
4. Savero Aurelio Armanto - 2802479754
5. Muadz Arfan - 2802522424

---

## Target Pengguna

- **Mahasiswa:** mahasiswa aktif yang sedang mencari pekerjaan part-time atau freelance, ingin mendapatkan pengalaman kerja, dan mengembangkan keterampilan.
- **Perusahaan / HR:** perusahaan, UMKM, dan startup yang membutuhkan tenaga kerja part-time atau freelance, serta perekrut yang ingin mencari kandidat mahasiswa.

---

## Fitur Utama

### 1. Peran Mahasiswa

- **Papan Lowongan (Job Board):** Menjelajahi daftar pekerjaan part-time dan freelance beserta deskripsi, persyaratan, dan profil perusahaan.
- **Pencarian & Filter:** Mencari dan menyaring lowongan berdasarkan minat dan kebutuhan.
- **Etalase Profil:** Menampilkan keahlian, pengalaman, dan profil singkat mahasiswa untuk dilirik oleh perekrut.
- **Tombol Hubungi:** Menghubungkan mahasiswa dengan perusahaan secara langsung melalui kontak yang tertera (Email / WhatsApp).

### 2. Peran Perusahaan / HR

- **Manajemen Lowongan:** Membuat, mengedit, dan mempublikasikan lowongan pekerjaan baru.
- **Dashboard Pelamar:** Melihat daftar kandidat mahasiswa yang tertarik atau melamar lowongan.
- **Profil Perusahaan:** Menampilkan informasi singkat, deskripsi, dan kontak perusahaan atau UMKM.

### 3. Otentikasi & Antarmuka

- Pemilihan peran saat registrasi: Mahasiswa atau Perusahaan/HR.
- Login menggunakan email, dengan pengarahan ke dashboard sesuai peran pengguna.

---

## Limitasi Sistem

Platform StudentGig tidak menyediakan fitur *payment gateway* atau transaksi pembayaran langsung di dalam aplikasi. Proses negosiasi gaji, pembayaran, dan kesepakatan kerja dilakukan secara langsung antara pihak mahasiswa dan perusahaan di luar platform.

---

## Teknologi yang Digunakan

- **Framework:** Laravel
- **Bahasa Pemrograman:** PHP, HTML, CSS, JavaScript
- **Database:** MySQL
- **Build Tool:** Vite

---

## Panduan Instalasi Lokal

Jika ingin menjalankan proyek ini di lingkungan lokal:

1. **Kloning repositori:**

```bash
   git clone https://github.com/unvariablehuman/StudentGig.git
   cd StudentGig
```

2. **Install dependensi PHP & JavaScript:**

```bash
   composer install
   npm install
```

3. **Pengaturan berkas lingkungan (.env):**

```bash
   cp .env.example .env
   php artisan key:generate
```

4. **Jalankan server lokal:**

```bash
   php artisan serve
```

Aplikasi akan berjalan di `http://127.0.0.1:8000`.
