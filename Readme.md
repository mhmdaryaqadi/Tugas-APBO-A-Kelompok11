# Tugas Analisis Perancangan Berorientasi Objek - A

**Dosen Pengampu :** Adi Wahyu Pribadi, S.Si., M.Kom

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

#### *Bagian 1*
### *Transkrip Wawancara: Bakso Wonogiri (Kantin FEB)*
*Pewawancara (P):* Dengan bapak siapa ini?

*Pak Sapril (S):* Saya dengan Bapak Sapril.

*P:* Bapak Sapril ya. Pemilik kedai apa nih kalau boleh tahu?

*S:* Bakso Wonogiri.

*P:* Bakso Wonogiri ya, di kantin FEB berarti?

*S:* Iya, kantin Fakultas Ekonomi dan Bisnis.

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

#### *Bagian 4*
*P:* Kan kami dari jurusan IT nih, apa ini pertanyaan tambahan ya Pak. Kita tuh kalau misalkan nanti kita disuruh bikin aplikasi tentang ini bapak, kira-kira fitur apa aja yang membantu bisnis bapak nih? Kalau misal ada aplikasi nih, fitur apa aja yang membantu kira-kira?

*S:* Ya selama ini kan kita masih offline ya. Ya kalau bisa dibantu ya itu, bisa kita penjualan secara online.

*P:* Salah satunya tadi nih yang cara ngasih tahu kalau pesanannya udah kelar bisa lewat aplikasinya mungkin ya?

*S:* Iya mungkin seperti itu juga salah satunya. Mungkin kalau kayak di restoran kan dia bunyi ya customer datang, cuma kan ya mungkin kita enggak ngerti kayak gimana itu alatnya atau mungkin terlalu mahal mungkin, sementara kan kita apa... masih kecil lah ya, kalau terlalu mahal enggak ini juga gitu mas.

*P:* Ya udah gitu aja Pak dari kami Pak, terima kasih waktunya Pak.

*S:* Iya terima kasih mas.

### 4. Dokumentasi
Video wawancara langsung dengan narasumber dapat diakses melalui tautan berikut:
https://youtu.be/Iy0zI39q6hI?si=lSJEHfITxhOZz33n

### 5. Alur Bisnis Sistem EconoMakan
Sistem EconoMakan dibuat untuk merapikan transaksi pemesanan agar lebih terstruktur, mencegah antrean fisik yang menumpuk, serta menghindari pesanan palsu (ghost orders) dengan sistem pembayaran di awal.

**A. Pemesan Melakukan Order & Checkout**
Transaksi dimulai dengan mahasiswa memesan langsung melalui aplikasi web EconoMakan. Pelanggan memilih menu dan wajib mencantumkan instruksi khusus pada catatan pesanan.

**B. Proses Pembayaran (Di Awal)**
Setelah mengonfirmasi pesanan, pelanggan wajib langsung melakukan pembayaran (melalui QRIS atau Tunai). Pemesanan tidak akan diproses ke antrean dapur jika pembayaran belum dilakukan dan divalidasi.

**C. Pesanan Memasuki Daftar Antrean (Database FIFO)**
Data pesanan yang pembayarannya sudah divalidasi lunas otomatis masuk ke layar penjual dengan sistem FIFO (First In First Out).

**D. Proses Pengerjaan Masakan**
Penjual mulai memasak dan melakukan pembaruan (Update Status) pada sistem secara bertahap, mulai dari "Sedang Diproses" hingga "Siap Diambil".

**E. Pengiriman Notifikasi ke Pelanggan**
Apabila status diubah, sistem otomatis mengirimkan notifikasi real-time ke perangkat pelanggan untuk menghilangkan metode panggil teriak.

**F. Pengambilan Makanan**
Konsumen mendatangi kedai berdasarkan notifikasi. Karena pembayaran sudah diselesaikan di awal, pelanggan cukup mengambil pesanannya saja.

**G. Simpan Data Transaksi (Pemantauan Owner)**
Setelah pesanan diambil, data transaksi otomatis tersimpan untuk dipantau oleh Owner sebagai total pendapatan harian.

<img width="5301" height="2596" alt="Manusia Class Inheritance-2026-04-29-130645" src="https://github.com/user-attachments/assets/36e4fe1f-e2da-4ace-a31a-2dfd8da77613" />

*Keterangan: Flowchart alur bisnis EconoMakan (Fase pemesanan hingga pengambilan).*

<img width="1076" height="1878" alt="apbo5 (2)" src="https://github.com/user-attachments/assets/73aeeb9c-7f44-43d3-a0c2-b2eb324bebef" />

*Keterangan: Activity Diagram sistem EconoMakan.*

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

**C. Perancangan Struktur Kelas (Class Diagram)**

Class Diagram menggambarkan struktur statis serta arsitektur sistem EconoMakan dengan memetakan hubungan antar-kelas (*class*), atribut, metode (*method*), serta enkapsulasi objek yang akan diimplementasikan ke dalam kode program.

<img width="2641" height="902" alt="class diagram" src="https://github.com/user-attachments/assets/f237fdc0-3ab1-4289-908d-2f8fec046d9f" />

*Keterangan: Class Diagram sistem EconoMakan yang menunjukkan struktur data, pewarisan, dan relasi antar-komponen sistem.*

Adapun rincian arsitektur kelas pada sistem EconoMakan adalah sebagai berikut:
*   **Penerapan Konsep OOP (Inheritance):** Kelas `Pengguna` bertindak sebagai *abstract class* (kelas induk) yang menyimpan atribut umum seperti `id`, `nama`, `email`, dan `kataSandi`. Kelas `Pelanggan`, `Penjual`, dan `Owner` merupakan *subclass* (kelas turunan) yang mewarisi fungsi `login()` dan `logout()`, namun memiliki metode spesifik sesuai dengan hak akses masing-masing.
*   **Keterikatan Kuat Pembayaran di Awal (Composition):** Relasi antara kelas `Pesanan` dengan kelas `Pembayaran` dan `DetailPesanan` menggunakan hubungan *Composition* (simbol belah ketupat hitam penuh). Hal ini menegaskan aturan bisnis sistem bahwa objek `Pembayaran` dan `DetailPesanan` tidak dapat berdiri sendiri atau tercipta tanpa adanya objek `Pesanan` yang sah dan lunas di awal transaksi.
*   **Struktur Data Antrean Berurut (`DatabaseFIFO`):** Kelas `DatabaseFIFO` dirancang sebagai pengendali data antrean dapur dengan metode utama `simpanPesananLunas()` dan `ambilAntreanTeratas()`. Kelas ini menjamin bahwa setiap pesanan lunas akan diproses oleh penjual secara adil berdasarkan urutan kronologis waktu masuk.
*   **Fleksibilitas Kustomisasi Menu (`DetailPesanan`):** Kelas `DetailPesanan` membawa atribut `catatanKhusus` dan `jumlahPorsi` yang merujuk langsung ke kelas `Menu`. Struktur ini memastikan instruksi kustomisasi dari pelanggan (seperti tingkat kepedasan atau variasi porsi) tersimpan secara presisi di dalam database dan tampil di layar penjual.

---

### 7. Perancangan Interaksi & Perilaku Sistem (Behavioral Diagrams)

**A. State Machine Diagram**
Menggambarkan siklus hidup (perubahan status) dari sebuah objek pesanan secara sekuensial, mulai dari tahap inisialisasi keranjang hingga pesanan selesai diserahkan kepada pelanggan. 

Adapun tahapan status (*state*) pada sistem EconoMakan berjalan dengan alur berikut:
*   **Keranjang Dibuat:** Objek pesanan terinisialisasi setelah pelanggan memilih menu.
*   **Menunggu Pembayaran:** Pelanggan melakukan *checkout* dan bersiap menyelesaikan pembayaran.
*   **Dalam Antrean FIFO:** Ini merupakan titik kontrol utama sistem. Objek pesanan **hanya** akan beralih ke status antrean ini apabila validasi pembayaran (QRIS/Tunai) telah berhasil. Pesanan yang belum lunas tidak akan diproses lebih lanjut.
*   **Sedang Diproses:** Penjual mulai memasak pesanan sesuai dengan urutan kedatangan data (*First In First Out*).
*   **Siap Diambil:** Makanan telah selesai dibuat dan dibungkus/disajikan.
*   **Pesanan Selesai:** Titik akhir (*final state*) di mana pelanggan telah mengambil makanannya dan siklus objek pesanan resmi ditutup.

<img width="241" height="823" alt="apbo3" src="https://github.com/user-attachments/assets/92d8c92b-17ab-4b6d-b520-d25a50fd6e42" />

*Keterangan: Transisi status pemesanan EconoMakan dengan penerapan sistem bayar di awal (Anti-Ghost Order).*
  
**B. Sequence Diagram**
Menjabarkan interaksi pengiriman pesan (alur waktu operasional) secara *real-time* antar aktor dan objek di dalam sistem—yaitu Pelanggan, Sistem EconoMakan, Database FIFO, dan Penjual—dalam satu skenario transaksi yang utuh.

Alur interaksi waktu (*lifelines*) direpresentasikan sebagai berikut:
1.  **Fase Pemesanan & Eksekusi Pembayaran:** Pelanggan berinteraksi dengan antarmuka sistem untuk memilih menu, menginput catatan khusus, dan menekan tombol *checkout*. Sistem merespons dengan memunculkan rincian total harga beserta QRIS, yang kemudian langsung dibayar oleh pelanggan.
2.  **Fase Perekaman Data Berurut:** Sistem meneruskan data pesanan yang berstatus lunas tersebut ke dalam Database FIFO, lalu menerima konfirmasi balik bahwa data sukses tersimpan.
3.  **Fase Pengerjaan & Paralel Notifikasi:** Database FIFO menampilkan urutan pesanan di layar Penjual. Setiap kali Penjual menekan tombol *update* status ("Sedang Diproses" dan "Siap Diambil"), sistem merespons dengan mengirimkan pesan asinkron berupa notifikasi ke perangkat Pelanggan.
4.  **Fase Penyelesaian Transaksi:** Pelanggan menunjukkan notifikasi di perangkatnya sebagai bukti pengambilan makanan. Setelah pesanan diserahkan, Penjual menyimpan log penyelesaian transaksi untuk dicatat sebagai pendapatan harian.

<img width="949" height="914" alt="apbo4" src="https://github.com/user-attachments/assets/3f310e4a-8f9c-46cc-a4ce-b36883e7b62c" />

*Keterangan: Sequence Diagram EconoMakan yang merinci pertukaran data secara kronologis dari inisiasi pesanan hingga transaksi selesai.*

---
 
Link Canva: https://canva.link/dgfeuvcim82kbly
