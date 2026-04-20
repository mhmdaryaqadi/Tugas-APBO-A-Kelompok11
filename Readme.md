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
**EconoMakan**: Perancangan Sistem Manajemen Antrean dan Pemesanan Digital Berbasis Web (Sistem Pre-Order dan Pick-up) pada Warung Kantin FEB Universitas Pancasila.

## 2. Problem
- **Kepadatan Area Warung:** Terjadi penumpukan mahasiswa di depan etalase warung yang menunggu pesanan secara manual, sehingga mengganggu kenyamanan dan mobilitas di area kantin.
- **Kesalahan Manajemen Pesanan:** Proses pencatatan manual pada jam sibuk sering mengakibatkan pesanan tertukar atau salah urutan antrean, terutama saat terdapat permintaan khusus dari pembeli (seperti tingkat kepedasan atau penyesuaian bahan).
- **Efisiensi Waktu Mahasiswa:** Mahasiswa kehilangan waktu istirahat yang cukup banyak hanya untuk berdiri mengantre di lokasi, yang berisiko pada keterlambatan masuk ke jam perkuliahan berikutnya.

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
