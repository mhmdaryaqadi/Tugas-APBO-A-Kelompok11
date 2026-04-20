# Tugas Analisis Perancangan Berorientasi Objek - A
**Dosen:** Adi Wahyu Pribadi, S.T M.T

##  Identitas Proyek
* **Nama Proyek:** EconoMakan
* **Deskripsi Proyek:** EconoMakan adalah aplikasi pemesanan makanan digital berbasis *web* yang dirancang khusus untuk mengoptimalkan pelayanan di salah satu warung pada Kantin FEB Universitas Pancasila. Aplikasi ini memecahkan masalah penumpukan antrian di depan etalase warung dengan menyediakan sistem *pre-order* dan manajemen antrian digital. Melalui EconoMakan, penjual mendapatkan daftar pesanan yang terstruktur secara *real-time* berdasarkan urutan masuk (sistem *First In First Out*), sementara mahasiswa (pembeli) dapat memesan makanan dari luar area kantin dan hanya perlu datang untuk mengambil pesanan (sistem *Pick-up*) setelah menerima notifikasi bahwa pesanan siap.

**Anggota Kelompok:**

    1. Muhammad Arya Alqadi (4524210058)
    
    2. Akbar Rais Fadilla (4524210007)
    
    3. Abdurrahman (4524210003)
    
    4. Khoiril Chandra Kurniawan (4524210049)
    
    5. Farash Adipati Mursalin (4524210036)

##  Analisis Kebutuhan Pengguna (Use Case)
* *Actor 01 - Penjual* --> Membutuhkan antarmuka manajemen pesanan yang rapi untuk menampilkan daftar urutan pesanan yang masuk beserta detail permintaan khusus (misal: pedas, tanpa sayur), sehingga proses memasak lebih terarah, mengurangi risiko salah buat, dan tidak perlu lagi mencatat manual di kertas saat jam padat.
* *Actor 02 - Pembeli* --> Membutuhkan kemudahan untuk melihat menu warung, melakukan pemesanan, dan mendapatkan nomor antrian digital dari jarak jauh. Pembeli juga membutuhkan fitur pemantauan status pesanan agar tidak perlu berdesakan menunggu di depan warung.
    
* *Use Case 01 - Registrasi/Login* --> Pengguna (Pembeli/Penjual) membuat akun baru dan masuk ke sistem menggunakan kredensial yang valid.
* *Use Case 02 - Mengelola Menu (Penjual)* --> Penjual dapat menambahkan, mengedit (harga/deskripsi), atau menonaktifkan menu jika stok habis.
* *Use Case 03 - Melihat Menu (Pembeli)* --> Pembeli melihat daftar menu warung yang sedang tersedia beserta harganya.
* *Use Case 04 - Memesan & Kustomisasi Menu (Pembeli)* --> Pembeli memilih makanan, menambahkan catatan khusus (opsional), dan mengonfirmasi pesanan.
* **Use Case 05 - Manajemen Antrian (Sistem/Penjual)** --> Sistem otomatis memberikan nomor urut pesanan. Penjual melihat pesanan masuk pada layar secara berurutan.
* **Use Case 06 - Update Status Pesanan (Penjual)** --> Penjual mengubah status pesanan (misal: "Sedang Diproses" menjadi "Siap Diambil").
* **Use Case 07 - Notifikasi Pick-up (Pembeli)** --> Pembeli menerima informasi atau melihat status bahwa makanan sudah siap diambil di warung.

### Use Case
- *UC-01 Login dan Registrasi:* Proses masuk ke sistem bagi penjual dan pembeli untuk memastikan data pesanan terekam dengan benar.
- *UC-02 Manajemen Data Menu:* Penjual dapat menambah menu baru, mengupdate harga/deskripsi, atau menonaktifkan menu jika stok habis di aplikasi.
- *UC-03 Pemesanan Digital:* Pembeli memilih menu dan mengirimkan data pesanan beserta catatan tambahan ke sistem.
- *UC-04 Manajemen Antrean:* Sistem menyusun daftar pesanan secara otomatis dan menampilkannya pada layar penjual berdasarkan urutan waktu.
- *UC-05 Update Status Pesanan:* Penjual melakukan pembaruan tahapan pesanan (Contoh: Menyiapkan ke Siap Diambil).
- *UC-06 Monitoring Status:* Pembeli melihat progres pesanan mereka di perangkat masing-masing hingga muncul status siap untuk diambil.