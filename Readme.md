# Laporan Analisis Perancangan Berorientasi Objek - Kelas A
**Dosen Pengampu:** Adi Wahyu Pribadi, S.Si., M.Kom

---

## Anggota Kelompok
1. Muhammad Arya Alqadi (4524210058)
2. Akbar Rais Fadilla (4524210007)
3. Abdurrahman (4524210003)
4. Khoiril Chandra Kurniawan (4524210049)
5. Farash Adipati Mursalin (4524210036)

---

## 1. Topik
**EconoMakan**: Perancangan Sistem Manajemen Antrean dan Pemesanan Digital Berbasis Web (Sistem Pre-Order dan Pick-up) pada Kedai Bakso Wonogiri Kantin FEB Universitas Pancasila.

## 2. Problem
- **Keterbatasan Sumber Daya Manusia:** Operasional kedai hanya dikelola oleh dua orang (pemilik dan istri), sehingga proses pelayanan terhambat saat terjadi lonjakan pesanan secara simultan.
- **Kompleksitas Menu pada Jam Sibuk:** Variasi menu yang beragam (bakso, nasi goreng, kwetiau, katsu) memerlukan waktu pengerjaan yang berbeda-beda, sehingga penjual kesulitan mengatur prioritas urutan pesanan saat jam istirahat mahasiswa.
- **Metode Pemanggilan Manual:** Saat ini, penjual masih menggunakan cara manual (teriak) atau mencari meja tempat mahasiswa duduk untuk mengantarkan makanan. Hal ini tidak efisien dan sering menimbulkan kebingungan saat kondisi kantin sedang ramai.
- **Kebutuhan Digitalisasi Pembayaran:** Meski QRIS sudah mendominasi, belum ada sistem yang mengintegrasikan pencatatan transaksi dengan status pesanan.

## 3. Analisis

### A. Aktor
- **Penjual (Pak Sapril/Istri):** Mengelola ketersediaan banyak varian menu dan memantau antrean pesanan yang masuk secara sistematis agar dapat membagi tugas memasak dengan lebih baik.
- **Pembeli (Mahasiswa):** Melakukan pemesanan dan memantau progres masakan dari meja masing-masing atau dari luar kantin untuk menghindari kerumunan di depan kedai.

### B. SOP (Standard Operating Procedure) Sistem
1. **Pemilihan Menu:** Pembeli mengakses aplikasi EconoMakan untuk melihat daftar menu (Bakso, Nasi Goreng, Katsu, dll) yang tersedia di kedai Bakso Wonogiri.
2. **Input Pesanan & Lokasi:** Pembeli memilih menu dan menyertakan catatan khusus jika diperlukan.
3. **Penyusunan Antrean Otomatis:** Sistem menyusun pesanan berdasarkan urutan waktu masuk (FIFO) agar penjual dapat memasak secara teratur meski hanya dikelola oleh dua orang.
4. **Proses Produksi:** Penjual melihat pesanan di layar dan mengubah status menjadi "Sedang Dimasak".
5. **Notifikasi Selesai:** Setelah makanan siap, penjual mengubah status di aplikasi. Sistem akan memberikan informasi ke perangkat pembeli bahwa makanan siap diambil atau segera diantarkan.
6. **Finalisasi & Pembayaran:** Pembeli melakukan pengambilan makanan dan menyelesaikan pembayaran melalui QRIS atau tunai sesuai dengan total yang tertera di aplikasi.

### C. Use Case
- **UC-01 Autentikasi Pengguna:** Login bagi penjual dan pembeli untuk validasi data pemesanan.
- **UC-02 Manajemen Menu Variatif:** Penjual mengupdate ketersediaan berbagai kategori menu (Minuman, Makanan Berat, Makanan Seduh).
- **UC-03 Pemesanan Jarak Jauh:** Pembeli mengirimkan data pesanan tanpa harus berdiri mengantre di depan kedai.
- **UC-04 Manajemen Progres Masakan:** Penjual memperbarui tahapan pengerjaan menu di aplikasi.
- **UC-05 Notifikasi Pengambilan/Antar:** Sistem menginformasikan pembeli bahwa pesanan telah selesai diproses.

## 4. Tujuan Proyek

- Menyediakan asisten digital bagi penjual yang memiliki keterbatasan staf agar manajemen pesanan lebih terorganisir.
- Menggantikan metode pemanggilan manual (teriak) dengan sistem notifikasi yang lebih tenang dan efektif.
- Meningkatkan volume penjualan melalui fitur pemesanan daring yang dapat diakses mahasiswa sebelum tiba di kantin.

## 5. Batasan Sistem (Scope)

- **Lingkup Implementasi:** Khusus digunakan untuk operasional kedai Bakso Wonogiri di Kantin FEB.
- **Fungsionalitas Utama:** Fokus pada pencatatan antrean dan notifikasi status pesanan (bukan sistem pembayaran terintegrasi pihak ketiga).
- **Aksesibilitas:** Berbasis web browser agar dapat digunakan oleh berbagai jenis perangkat tanpa instalasi aplikasi tambahan.

## 6. Target Hasil
- Penurunan tingkat stres penjual dalam mengelola lonjakan pesanan di jam istirahat.
- Hilangnya kendala miskomunikasi urutan pesanan antara penjual dan pembeli.
- Tercapainya proses pelayanan yang lebih modern dan profesional bagi unit usaha kecil di lingkungan universitas.

Link Video YT: https://youtu.be/Iy0zI39q6hI?si=725uWzFJrmPL2FkI
