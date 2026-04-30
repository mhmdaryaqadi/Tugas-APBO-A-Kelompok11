# Tugas Analisis Perancangan Berorientasi Objek - A

**Dosen Pengampu :** Adi Wahyu Pribadi, S.T., M.T.

**KELOMPOK 11:**
1. Muhammad Arya Alqadi - 4524210058
2. Akbar Rais Fadilla - 4524210007
3. Abdurrahman - 4524210003
4. Khoiril Chandra Kurniawan - 4524210049
5. Farash Adipati Mursalin - 4524210036

---

### 1. Topik
Sistem Manajemen Antrean dan Pemesanan Digital Berbasis Web (EconoMakan) pada Kedai Bakso Wonogiri Kantin FEB Universitas Pancasila.

### 2. Literasi Bacaan & Problem (Konteks Permasalahan)
Berdasarkan hasil observasi dan wawancara di lapangan, ditemukan beberapa kendala operasional pada Kedai Bakso Wonogiri yang menjadi landasan perancangan sistem ini:
*   **Keterbatasan SDM:** Kedai hanya dikelola oleh 2 orang, sehingga penjual kewalahan saat jam istirahat mahasiswa terjadi bersamaan.
*   **Kompleksitas Manajemen Waktu:** Waktu pengerjaan menu berbeda-beda (bakso vs nasi goreng), sehingga penjual kesulitan mengatur prioritas pesanan tanpa sistem antrean.
*   **Pemanggilan Manual:** Cara memanggil pelanggan masih manual (teriak) yang tidak efisien dan berisiko salah antar pesanan.
*   **Miskomunikasi Pesanan:** Sering terlupanya catatan tambahan dari pembeli (contoh: pedas, tanpa sayur) karena pencatatan masih manual/dihafal.
*   **Kepadatan Lokasi:** Area depan kedai penuh sesak oleh antrean mahasiswa yang menunggu pesanannya, mengganggu mobilitas kantin.
*   **Rekapitulasi Manual:** Belum ada integrasi antara proses pemesanan dengan rekapitulasi data penjualan harian.

### 3. Pertanyaan Wawancara
Narasumber: Bapak Sapril (Owner Kedai Bakso Wonogiri)
1. Bapak di sini posisinya sebagai apa?
2. Sehari biasanya ada berapa pelanggan dan staf yang menangani ada berapa?
3. Kendala yang biasa dialami oleh Bapak dalam urusan operasional kedai apa saja?
4. Kira-kira sistem pembayaran di sini bisa menggunakan QRIS atau hanya tunai?
5. Bagaimana cara pihak kedai memberitahu kepada pelanggan bahwa pesanannya sudah siap diambil atau diantar?
6. Jika ada aplikasi digital, kira-kira fitur apa saja yang bisa membantu bisnis Bapak?

#### *Bagian 3*
**P:** Ini pertanyaan keempat, kira-kira di kedai bapak tuh sistem pembayarannya cash doang apa bisa QRIS?

**S:** Kita ada cash, ada QRIS juga. Kalau dia mau transfer bank juga ada gitu. Tapi biasanya umumnya lebih banyak QRIS ya.

**P:** Oh QRIS ya? Daripada cash lebih banyak QRIS berarti?

**S:** Iya, lebih banyak QRIS malah dibanding cash.

**P:** Terus ini cara bapak ngasih tahu ke customer yang pesen, cara kasih tahu kalau pesanannya udah kelar nih, udah selesai pesanannya nih gimana cara ngasih tahunya?

**S:** Biasanya pada saat dia membeli kita nanya dulu duduknya di mana kira-kira. Jadi emang kita antar gitu. Kecuali dia yang minuman ambil sendiri kan atau yang seduh-seduh gitu kan dia nunggu, biasanya kita bikin langsung ambil. Kalau yang kayak ayam goreng, nasi goreng kan kita kerjain dulu, jadi customer ya entar kita antar lah gitu ke tempatnya. Kira-kira di sana entar kan kita teriak, "Nasi goreng!"

### 4. Dokumentasi
Video wawancara langsung dengan narasumber dapat diakses melalui tautan berikut:
https://youtu.be/Iy0zI39q6hI?si=lSJEHfITxhOZz33n

### 5. Alur Bisnis Sistem EconoMakan
Sistem EconoMakan dibuat untuk merapikan transaksi pemesanan agar lebih terstruktur dan mengurangi miskomunikasi antara mahasiswa dengan penjual.

**A. Pemesan Melakukan Order**
Transaksi dimulai dengan mahasiswa memesan langsung melalui aplikasi web EconoMakan. Pelanggan dapat memilih kategori layanan menu yang disediakan, seperti:
*   Makanan Kuah (Bakso, dll)
*   Makanan Masak/Goreng (Nasi Goreng, Katsu, Kwetiau)
*   Minuman (Es Teh, Jeruk, dll)
*   *Catatan Khusus:* Pelanggan wajib mencantumkan instruksi (misal: "pedas", "jangan pakai seledri") untuk mencegah miskomunikasi.

**B. Input Identitas dan Data Pesanan**
Setelah pesanan dikonfirmasi, sistem otomatis mencatat data pemesan yang meliputi:
*   Nama Akun/Pemesan
*   Detail menu dan jumlah porsi
*   Waktu (jam & menit) pemesanan masuk
*   Catatan kustomisasi pesanan

**C. Pesanan Memasuki Daftar Antrean**
Data pesanan otomatis masuk ke layar penjual. Antrean ini dibedakan secara sistematis berdasarkan metode FIFO (*First In First Out*) agar penjual tahu pesanan mana yang masuk lebih dulu dan harus diprioritaskan.

**D. Proses Pengerjaan Masakan**
Penjual melakukan pengerjaan makanan berdasarkan layar antrean. Penjual juga akan melakukan *Update Status* pada sistem:
*   *Sedang Diproses:* Penjual mulai memasak hidangan.
*   *Siap Diambil:* Makanan sudah selesai dibungkus atau disajikan.

**E. Pengiriman Notifikasi ke Pelanggan**
Apabila status diubah menjadi "Siap Diambil", sistem langsung mengirimkan notifikasi *real-time* ke perangkat pelanggan. Tujuannya adalah mencegah kerumunan di depan kedai dan menghilangkan metode teriak.

**F. Pengambilan & Pembayaran**
Konsumen mendatangi kedai berdasarkan notifikasi. Pelanggan mengambil pesanan dan menyelesaikan pembayaran dengan cara:
*   QRIS (Metode paling sering digunakan)
*   Kas (Tunai)

**G. Simpan Data Transaksi (Pemantauan Owner)**
Setelah pembayaran selesai, data transaksi disimpan di sistem. Owner dapat memantau kegiatan bisnis, meliputi: total pesanan harian dan total estimasi pemasukan.

<img width="5301" height="2596" alt="Manusia Class Inheritance-2026-04-29-130645" src="https://github.com/user-attachments/assets/36e4fe1f-e2da-4ace-a31a-2dfd8da77613" />
Keterangan: Visualisasi alur bisnis sistem EconoMakan dari proses input pelanggan hingga pelaporan pendapatan.

### 6. Analisis Aktor & Use Case

**A. Aktor dalam Sistem**
*   **Pelanggan (Mahasiswa):** Bertugas melakukan pemesanan, memilih menu, mengisi catatan pesanan, memantau status antrean dari jarak jauh, dan melakukan pembayaran di tempat saat pesanan diambil.
*   **Penjual / Admin:** Bertugas mengelola ketersediaan data menu di aplikasi, memantau daftar pesanan masuk secara berurutan, mengubah status pengerjaan makanan, dan memvalidasi pesanan yang sudah diambil.
*   **Pemilik (Owner):** Bertugas memantau total transaksi harian, total pemasukan kedai, serta mengelola harga dan penambahan menu baru.

**B. Daftar Fungsionalitas (Use Case)**
*   **UC-01 Autentikasi Pengguna:** Login bagi penjual, pelanggan, dan pemilik untuk validasi dan keamanan data transaksi.
*   **UC-02 Pengelolaan Katalog Menu (Penjual/Owner):** Penjual memperbarui status ketersediaan menu (Aktif/Habis), menambah, atau mengubah detail harga.
*   **UC-03 Transaksi Pemesanan (Pelanggan):** Pelanggan memilih menu, mengisi detail catatan (kustomisasi), dan mengirimkan pesanan ke sistem.
*   **UC-04 Manajemen Antrean Berurut (Sistem):** Sistem secara otomatis menerima pesanan dan menampilkannya secara berurutan (*FIFO*) di perangkat penjual.
*   **UC-05 Pembaruan Status Produksi (Penjual):** Penjual mengubah tahapan status pesanan dari "Sedang Diproses" menjadi "Siap Diambil".
*   **UC-06 Notifikasi Siap Ambil (Sistem/Pelanggan):** Sistem menampilkan peringatan pembaruan status di layar perangkat pelanggan bahwa pesanan sudah selesai diproses.
*   **UC-07 Laporan Pendapatan (Owner):** Sistem merangkum seluruh transaksi pesanan yang sudah selesai menjadi laporan penjualan harian untuk dipantau oleh pemilik kedai.

<img width="5502" height="4831" alt="Manusia Class Inheritance-2026-04-29-071059" src="https://github.com/user-attachments/assets/4e056cd8-a645-447e-bdc3-28b1d41bf8ca" />
Keterangan: Diagram Use Case yang menggambarkan hubungan fungsional antara aktor Pelanggan, Penjual, dan Owner dengan sistem EconoMakan.

---

Link Canva: https://canva.link/dgfeuvcim82kbly
