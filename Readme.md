# Laporan Analisis Perancangan Berorientasi Objek - Kelas A
**Dosen Pengampu:** Adi Wahyu Pribadi, S.T., M.T.

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
- **Penjual:** Pengguna yang bertugas mengelola daftar menu, menerima pesanan yang masuk sesuai urutan, dan memperbarui status progres pembuatan makanan di aplikasi.
- **Pembeli (Mahasiswa):** Pengguna yang dapat melihat daftar menu melalui aplikasi, melakukan pemesanan dari jarak jauh, dan memantau status pesanan mereka secara real-time.

### B. SOP (Standard Operating Procedure) Sistem
1. **Akses Menu:** Pembeli mengakses aplikasi **EconoMakan** untuk melihat ketersediaan menu pada warung tersebut.
2. **Input Pesanan:** Pembeli memilih menu, menambahkan catatan pesanan jika diperlukan, dan melakukan konfirmasi pemesanan di aplikasi.
3. **Penerimaan Pesanan:** Sistem mengirimkan data pesanan ke layar penjual secara otomatis berdasarkan urutan waktu masuk (Metode FIFO - First In First Out).
4. **Proses Pembuatan:** Penjual memproses pesanan sesuai urutan pada layar dan mengubah status pesanan menjadi "Sedang Dimasak".
5. **Notifikasi Siap Ambil:** Setelah makanan selesai disiapkan, penjual mengubah status pesanan menjadi "Siap Diambil", yang secara otomatis akan ter-update pada layar perangkat pembeli.
6. **Pengambilan & Pembayaran:** Pembeli datang ke warung untuk mengambil pesanan dan melakukan transaksi pembayaran (tunai atau QRIS) secara langsung di tempat.

### C. Use Case
- *UC-01 Login dan Registrasi:* Proses masuk ke sistem bagi penjual dan pembeli untuk memastikan data pesanan terekam dengan benar.
- *UC-02 Manajemen Data Menu:* Penjual dapat menambah menu baru, mengupdate harga/deskripsi, atau menonaktifkan menu jika stok habis di aplikasi.
- *UC-03 Pemesanan Digital:* Pembeli memilih menu dan mengirimkan data pesanan beserta catatan tambahan ke sistem.
- *UC-04 Manajemen Antrean:* Sistem menyusun daftar pesanan secara otomatis dan menampilkannya pada layar penjual berdasarkan urutan waktu.
- *UC-05 Update Status Pesanan:* Penjual melakukan pembaruan tahapan pesanan (Contoh: Menyiapkan ke Siap Diambil).
- *UC-06 Monitoring Status:* Pembeli melihat progres pesanan mereka di perangkat masing-masing hingga muncul status siap untuk diambil.

## 4. Tujuan Proyek

- Menyediakan asisten digital bagi penjual yang memiliki keterbatasan staf agar manajemen pesanan lebih terorganisir.
- Menggantikan metode pemanggilan manual (teriak) dengan sistem notifikasi yang lebih tenang dan efektif.
- Meningkatkan volume penjualan melalui fitur pemesanan daring yang dapat diakses mahasiswa sebelum tiba di kantin.

## 5. Batasan Sistem (Scope)

- **Lingkup Implementasi:** Khusus digunakan untuk operasional kedai Bakso Wonogiri di Kantin FEB.
- **Fungsionalitas Utama:** Fokus pada pencatatan antrean dan notifikasi status pesanan (bukan sistem pembayaran terintegrasi pihak ketiga).
- **Aksesibilitas:** Berbasis web browser agar dapat digunakan oleh berbagai jenis perangkat tanpa instalasi aplikasi tambahan.
