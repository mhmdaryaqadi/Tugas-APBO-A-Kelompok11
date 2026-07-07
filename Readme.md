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

#### *Bagian 2*
*P:* Kalau boleh tahu tuh di sini ada posisi jabatan apa aja nih di tempat bapak ini?

*S:* Kita cuma berdua, saya sama istri. Ya saya yang punya, saya yang melayani, yang ngerjain. Karena karyawan pulang waktu itu nggak balik lagi, itu aja sih.

*P:* Terus kalau sehari biasanya ini ada berapa yang pesen gitu? Ada berapa customer? Terus staff-nya yang lainnya berapa? Dua orang doang berarti?

*S:* Iya, kalau kita ngerjain tetap dua orang. Tapi walaupun banyak yang mesen tetap dua orang karena lagi nyari juga karyawan untuk bantu-bantu tapi belum ada lah gitu.

*P:* Terus kalau kendala yang biasa dialami oleh bapak dalam urusan bisnis ini apa nih biasanya kendalanya apa?

*S:* Ya kendalanya sih kalau pada jam istirahat kan istirahat semua sekaligus. Nah, yang mesen kan langsung ini (banyak), sementara... nah itu yang paling sulit sih ya ngerjainnya. Karena menu kita kan banyak, ada bakso, ada nasi goreng, kwetiau, katsu. Di situ yang sebenarnya kesulitannya. Tapi ya kita kerjain pelan-pelan, mahasiswa sabar nunggu lah gitu mas.
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

<img width="813" height="3046" alt="flowchartapbo" src="https://github.com/user-attachments/assets/fa7b5490-d5f2-4c6c-b1e7-a3d8648f63b5" />

Keterangan: Visualisasi alur bisnis sistem EconoMakan dari proses input pelanggan hingga pelaporan pendapatan.

### 6. Analisis Aktor & Use Case

**A. Aktor dalam Sistem**
*   **Pelanggan (Mahasiswa):** Bertugas memilih menu, mengisi catatan pesanan, **melakukan pembayaran di awal transaksi**, memantau status antrean dari jarak jauh, dan mengambil makanan saat pesanan siap.
*   **Penjual / Admin:** Bertugas mengelola katalog menu, memvalidasi pembayaran pelanggan, memantau daftar antrean masuk, dan memperbarui status pengerjaan masakan.
*   **Pemilik (Owner):** Bertugas melihat laporan transaksi, melihat total pendapatan kedai, serta melakukan autentikasi sistem.

**B. Daftar Fungsionalitas (Use Case)**
*   **UC-01 Autentikasi / Login:** Sistem validasi keamanan bagi Penjual, Pelanggan, dan Owner.
*   **UC-02 Pesan Menu & Catatan:** Pelanggan memilih makanan dan memberikan kustomisasi.
*   **UC-03 Lakukan Pembayaran:** Wajib dilakukan oleh pelanggan sesaat setelah memesan menu (<<include>> dari proses pesan).
*   **UC-04 Validasi Pembayaran:** Dilakukan oleh penjual untuk mengonfirmasi dana masuk.
*   **UC-05 Memantau Antrean Masuk:** Penjual melihat daftar pesanan yang sudah lunas.
*   **UC-06 Pantau Status Antrean:** Pelanggan melihat status pesanannya.
*   **UC-07 Update Status Masakan:** Penjual mengubah tahapan status pesanan.
*   **UC-08 Mengirim Notifikasi:** Sistem otomatis mengirimkan pemberitahuan (<<include>> dari update status).
*   **UC-09 Menerima Notifikasi Selesai:** Pelanggan mendapat sinyal makanan siap diambil.
*   **UC-10 Ambil Makanan:** Tahap akhir penyelesaian fisik oleh pelanggan.
*   **UC-11 Mengelola Katalog Menu:** Penjual mengatur ketersediaan menu dan harga.
*   **UC-12 Melihat Laporan Transaksi & Pendapatan:** Owner melihat rekapitulasi data penjualan.

<img width="539" height="1080" alt="diagramapbo2" src="https://github.com/user-attachments/assets/d5c1a4de-5738-4926-9db1-9e2f56cd1a81" />

*Keterangan: Diagram Use Case EconoMakan yang menggambarkan interaksi fungsional antara aktor Pelanggan, Penjual, dan Owner.*


---

Link Canva: https://canva.link/dgfeuvcim82kbly
