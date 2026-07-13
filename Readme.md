<div align="center">

# LAPORAN TUGAS BESAR
## MATA KULIAH: ANALISIS PERANCANGAN BERORIENTASI OBJEK

<br>

### RANCANG BANGUN SISTEM MANAJEMEN ANTREAN DAN PEMESANAN DIGITAL BERBASIS WEB
## "ECONOMAKAN"
### STUDI KASUS: KEDAI BAKSO WONOGIRI, KANTIN FEB UNIVERSITAS PANCASILA

<br>

<img width="470" height="351" alt="image" src="https://github.com/user-attachments/assets/071a26bb-b0e8-410e-868b-fce1184ecc7d" />

<br>

### Disusun Oleh Kelompok 11:

| Nama Anggota | NPM |
| :--- | :--- |
| Muhammad Arya Alqadi | 4524210058 |
| Akbar Rais Fadilla | 4524210007 |
| Abdurrahman | 4524210003 |
| Khoiril Chandra Kurniawan | 4524210049 |
| Farash Adipati Mursalin | 4524210036 |

<br>

**Dosen Pengampu:** Adi Wahyu Pribadi, S.Si., M.Kom

<br>

## PROGRAM STUDI TEKNIK INFORMATIKA
## FAKULTAS TEKNIK UNIVERSITAS PANCASILA
## 2026

</div>

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

### 4. Dokumentasi & Presentasi Proyek
Seluruh rangkaian pembuktian data lapangan, proses wawancara narasumber, hingga pemaparan arsitektur sistem EconoMakan oleh Kelompok 11 dapat diakses melalui tautan media digital berikut:

*   **Video Wawancara Lapangan (Narasumber: Bapak Sapril):**
    https://youtu.be/Iy0zI39q6hI?si=lSJEHfITxhOZz33n
*   **Video Presentasi (Kelompok 11):**
    https://youtu.be/rzZVO4qy74s

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

<img width="813" height="3046" alt="flowchartapbo" src="https://github.com/user-attachments/assets/fa7b5490-d5f2-4c6c-b1e7-a3d8648f63b5" />

*Keterangan: Visualisasi alur bisnis sistem EconoMakan dari proses input pelanggan hingga pelaporan pendapatan.*

### 6. Analisis Aktor & Kebutuhan Fungsional

**A. Analisis Aktor Sistem**
Perancangan sistem EconoMakan membagi hak akses dan tanggung jawab pengguna ke dalam 3 peran (aktor) utama guna menjamin keamanan data dan efisiensi operasional kedai:
*   **Pelanggan (Mahasiswa):** Bertugas memilih menu, mengisi catatan pesanan, melakukan pembayaran di awal transaksi, memantau status antrean dari jarak jauh, dan mengambil makanan saat pesanan siap.
*   **Penjual / Admin:** Bertugas mengelola katalog menu, memvalidasi pembayaran pelanggan, memantau daftar antrean masuk, dan memperbarui status pengerjaan masakan.
*   **Pemilik (Owner):** Bertugas melihat laporan transaksi, melihat total pendapatan kedai, serta melakukan autentikasi sistem secara independen.

**B. Daftar Fungsionalitas (Use Case Diagram)**
Fungsionalitas sistem telah disesuaikan murni berdasarkan interaksi perangkat lunak, membuang interaksi fisik manusia. Terdapat 10 Use Case utama:
*   **UC-01 Autentikasi / Login:** Sistem validasi keamanan bagi Penjual, Pelanggan, dan Owner.
*   **UC-02 Pesan Menu & Catatan:** Fungsionalitas antarmuka bagi Pelanggan untuk memilih makanan dan memberikan kustomisasi.
*   **UC-03 Lakukan Pembayaran QRIS:** Sistem *payment gateway* wajib yang dipicu (`<<include>>`) langsung setelah proses pemesanan menu.
*   **UC-04 Validasi Callback Pembayaran:** Sistem secara otomatis maupun manual oleh Penjual memvalidasi status dana masuk.
*   **UC-05 Memantau Antrean FIFO:** Fitur bagi Penjual untuk melihat daftar pesanan yang sudah berstatus lunas.
*   **UC-06 Update Status Pesanan:** Fungsionalitas Penjual untuk memajukan tahapan status (*State*) objek pesanan di database.
*   **UC-07 Kirim Notifikasi Sistem:** Sistem secara *backend* mengirimkan pemberitahuan (`<<include>>`) ke perangkat pelanggan akibat adanya *trigger* dari perubahan status pesanan.
*   **UC-08 Validasi Bukti Antrean Pelanggan:** Sistem verifikasi akhir oleh Penjual untuk mencocokkan nomor antrean digital pelanggan sebelum mengubah status transaksi menjadi selesai.
*   **UC-09 Mengelola Katalog Menu:** Akses bagi Penjual untuk mengatur ketersediaan menu.
*   **UC-10 Melihat Laporan Pendapatan:** Fitur rekapitulasi data penjualan khusus untuk hak akses Owner.

<img width="507" height="961" alt="usecaseapbo (1)" src="https://github.com/user-attachments/assets/b837bd11-a8f2-4bc4-bff5-d2fab17a5cce" />

*Keterangan: Diagram Use Case EconoMakan yang menggambarkan interaksi fungsional antara aktor Pelanggan, Penjual, dan Owner.*

### 7. Perancangan Struktur Kelas (Class Diagram)
Class Diagram menggambarkan struktur statis serta arsitektur sistem EconoMakan dengan memetakan hubungan antar-kelas, atribut, dan metode (*method*). Perancangan ini menggunakan pendekatan *Boundary-Control-Entity* (MVC) agar siap diimplementasikan ke dalam kode program yang terstruktur.

Adapun rincian arsitektur kelas pada sistem EconoMakan adalah sebagai berikut:
*   **Layer Antarmuka (`KatalogUI`):** Bertindak sebagai *Boundary Class* yang mengatur tampilan antarmuka (UI). Kelas ini memiliki metode *void* seperti `menampilkanKatalogMenu()` dan `tampilkanPesanError()` yang berfungsi menampilkan data tanpa melakukan manipulasi logika inti.
*   **Layer Pengendali (`OrderController`):** Bertindak sebagai otak sistem (*Control Class*). Kelas ini menjadi pusat *routing* yang menerima *request* dari UI, seperti `reqCheckout()`, lalu melakukan kalkulasi logika (`kalkulasiTotalHarga()`), dan mengeksekusi perubahan data (`updateStatus()`).
*   **Layer Entitas & Basis Data (`Pesanan`, `DatabaseFIFO`, `LaporanPendapatan`):** Bertindak sebagai representasi tabel database (*Entity Class*). Kelas `OrderController` mengelola objek `Pesanan` secara langsung, serta mengirimkan log data (seperti ID antrean dan total pendapatan) ke `DatabaseFIFO` dan `LaporanPendapatan`.
*   **Integrasi Pihak Ketiga (`PaymentGateway`):** Memisahkan fungsi eksternal ke dalam kelas tersendiri untuk menangani siklus pembuatan *invoice* (`requestQRIS()`) and pengecekan status bayar, menjaga agar logika inti EconoMakan tetap independen.

<img width="1725" height="726" alt="classapbo" src="https://github.com/user-attachments/assets/134d721f-b63c-4cd2-b46d-fd4f3272a71b" />

*Keterangan: Class Diagram sistem EconoMakan yang menunjukkan struktur data arsitektur MVC, komponen tipe data, dan relasi logika antar-kelas.*

### 8. Perancangan Interaksi & Perilaku Sistem (Behavioral Diagrams)

**A. State Machine Diagram**
Diagram ini menggambarkan siklus hidup (perubahan nilai atribut `status`) dari objek data `Pesanan` secara sekuensial berdasarkan *event* atau *method* yang dieksekusi oleh sistem perangkat lunak, bebas dari unsur aksi fisik manusia:
*   **`PENDING`:** Status awal saat data pesanan terinisialisasi melalui *method* `userMelakukanCheckout()`. Sistem menahan pesanan di *state* ini (`Menunggu_Pembayaran`) selama proses transaksi *invoice* QRIS digenerate. Jika gagal, status dihancurkan melalui `callbackPaymentFailed()`.
*   **`IN_QUEUE`:** Objek pesanan otomatis beralih ke status ini hanya jika menerima *event* `callbackPaymentSuccess()`. Sistem melakukan instansiasi objek dan memasukkan ID pesanan ke dalam *array* `DatabaseFIFO`.
*   **`PROCESSING`:** Status berubah menjadi `'Processing'` saat penjual mengeksekusi *method* `ubahStatusDiproses()`. Pada tahapan ini, sistem memicu *asynchronous event* `KirimNotifikasi(Dimasak)`.
*   **`READY_FOR_PICKUP`:** Status beralih ke `'Ready'` ketika penjual mengeksekusi *method* `ubahStatusSiapDiambil()`, yang secara otomatis memicu *event* `KirimNotifikasi(Siap)`. Di status ini, sistem mengunci alur: jika *method* `validasiBuktiAntrean()` menghasilkan kondisi `[Tidak Cocok]`, status berputar kembali ke dirinya sendiri (`tolakPenyerahan`).
*   **`COMPLETED`:** Titik akhir (*final state*) objek pesanan. Status resmi berubah menjadi `'Completed'` hanya jika `validasiBuktiAntrean()` menghasilkan kondisi `[Cocok]`. Sistem kemudian menutup siklus hidup objek dengan menjalankan query *insert* ke `LaporanPendapatan`.

<img width="1157" height="1123" alt="stateapbo" src="https://github.com/user-attachments/assets/627a2106-f9d0-4b2e-9852-92a57d91efd9" />

*Keterangan: Transisi status pemesanan EconoMakan dengan penerapan sistem bayar di awal (Anti-Ghost Order).*
  
**B. Sequence Diagram**
Sequence Diagram merinci interaksi pengiriman pesan (*message call*) secara kronologis dari atas ke bawah antar komponen arsitektur sistem perangkat lunak:
*   **Fase Pemesanan & Pembayaran QRIS:** `Pelanggan` mengirimkan pesan `memilihMenu()` ke `KatalogUI`, yang diteruskan sebagai `reqCheckout()` ke `OrderController`. Controller melakukan operasi internal `kalkulasiTotalHarga()` and meminta *invoice* ke `PaymentGateway` via `requestQRIS()`. Sistem memotong alur menggunakan blok `alt` jika pembayaran `[Gagal / Timeout]`.
*   **Fase Antrean FIFO:** Jika pembayaran `[Sukses / Lunas]`, `OrderController` melakukan `instansiasiObjek()` ke kelas entitas `Pesanan` dan menyimpan ID datanya ke `DatabaseFIFO` melalui fungsi `insertIDPesanan()`.
*   **Fase Perubahan State & Notifikasi Paralel:** `Penjual` melakukan interaksi dengan mengirim pesan `updateStatus('Diproses')` and `updateStatus('Siap Diambil')` melalui `KatalogUI` ke `OrderController`. Setiap perubahan nilai ini langsung dikirim ke objek `Pesanan` lewat `setStatus()` dan memicu *method* internal `memicuEventKirimNotifikasi()` untuk mengirimkan respon balik berupa pesan *asynchronous* ke layar `Pelanggan`.
*   **Fase Validasi Akhir & Log Transaksi:** Penjual mengirimkan data bukti melalui `memvalidasiBuktiNomorAntrean()`. Sistem memprosesnya di dalam blok `loop` dan `alt`. Jika `[Tidak Cocok]`, sistem memicu `menolakAksiPenyerahan()`. Jika `[Cocok]`, objek `Pesanan` diubah menjadi `'Selesai'`, dan data keuangan disimpan ke tabel `LaporanPendapatan` melalui fungsi `insertLaporanPendapatan()`.

<img width="1503" height="1781" alt="sequenceapbo" src="https://github.com/user-attachments/assets/1323ec94-d9ba-4325-9408-3af12ee0f334" />

*Keterangan: Sequence Diagram EconoMakan yang merinci pertukaran data secara kronologis dari inisiasi pesanan hingga transaksi selesai.*

---

### 9. Perancangan Antarmuka Aplikasi (Web Wireframe)
Perancangan antarmuka (*user interface*) sistem EconoMakan dirancang menggunakan pendekatan *Responsive Web Design* dengan representasi *blueprint (low-fidelity)* monokromatik. Penggunaan tanda kotak bersilang (`[X]`) berfungsi sebagai *placeholder* aset visual untuk memastikan fokus utama perancangan terletak pada kematangan fungsionalitas dan alur interaksi data, sebelum masuk ke dalam tahap penulisan kode program (*framework development*). 

Berikut merupakan pemetaan modul antarmuka berdasarkan peran aktor sistem:

#### A. Sisi Pelanggan (Mahasiswa)

1. **Halaman Otentikasi & Seleksi Akses**
   Antarmuka awal yang memfasilitasi gerbang masuk pengguna ke dalam sistem. Menyediakan fitur *multirole selection* (Pelanggan, Penjual, Owner) berbasis *radio button* untuk membagi token otentikasi sesi secara presisi.
   
   <img width="2200" height="1480" alt="Buat Login" src="https://github.com/user-attachments/assets/732daca3-5389-4888-bf3f-23b7c3f87c8e" />
   
   *Keterangan: Antarmuka form login multi-aktor terpusat.*

2. **Halaman Katalog & Detail Pemesanan**
   Halaman utama mahasiswa untuk melakukan transaksi. Memuat kartu daftar menu, informasi harga, tombol aksi manipulasi keranjang belanja, ringkasan transaksi, serta kolom teks dinamis (*Text Area*) untuk menangani input catatan kustomisasi menu langsung ke basis data.
   
   <img width="2200" height="1812" alt="catalog" src="https://github.com/user-attachments/assets/f5a1acc9-17ac-4c13-ab9d-e29594914539" />
   
   *Keterangan: Tampilan katalog menu dinamis beserta modul ringkasan pesanan dan instruksi khusus.*

3. **Halaman Transaksi Invoice QRIS**
   Antarmuka *payment gateway* wajib di awal sesi *checkout*. Halaman ini memuat ID invoice unik, kalkulasi total biaya, tombol unduh berkas gambar, serta *placeholder status box* yang menahan alur transaksi selama menanti proses validasi lunas dari server.
   
   <img width="2200" height="1480" alt="Buat Pembayaran" src="https://github.com/user-attachments/assets/1f18187d-4e18-4d81-8b61-173828163908" />
   
   *Keterangan: Modul invoice pembayaran QRIS otomatis (Anti-Ghost Order).*

4. **Halaman Lacak Status Antrean**
   Halaman monitor jarak jauh bagi mahasiswa setelah melakukan pembayaran. Menampilkan visualisasi garis waktu (*timeline tracker status*) secara vertikal untuk melacak perpindahan nilai atribut objek data dari status `In Queue`, `Processing` (Sedang Dimasak), hingga `Ready` secara *real-time*.
   
   <img width="2200" height="1480" alt="Buat Liat antrian" src="https://github.com/user-attachments/assets/52c30454-41ad-4c23-a165-ec8f3df9bb82" />
   
   *Keterangan: Layar lacak estimasi waktu tunggu dan pergerakan status pesanan secara real-time.*

#### B. Sisi Penjual (Admin Dapur) & Pemilik (Owner)

1. **Halaman Dashboard Dapur Penjual (FIFO Monitor)**
   Antarmuka khusus panel penjual menggunakan struktur navigasi samping (*sidebar navigation panel*). Berfungsi menampilkan tumpukan data antrean pesanan masuk secara kronologis berdasarkan *timestamp* waktu lunas (FIFO), dilengkapi tombol kendali transisi status objek dapur.
   
   <img width="2200" height="1687" alt="penjual" src="https://github.com/user-attachments/assets/c8d55007-b706-4fad-8336-96bc5ca3db23" />
   
   *Keterangan: Dashboard kendali produksi dapur penjual berbasis urutan First In First Out.*

2. **Halaman Statistik Finansial & Log Transaksi Owner**
   Antarmuka eksklusif manajerial bagi pemilik untuk memantau metrik performa bisnis kedai secara mandiri. Menyajikan rangkuman omzet harian, total volume transaksi, menu terlaris, visualisasi grafik pendapatan mingguan, serta tabel log riwayat transaksi lunas yang dapat dicetak.
   
   <img width="2200" height="1532" alt="owner" src="https://github.com/user-attachments/assets/2f202635-da93-4ca8-8570-fe758fd819e1" />
   
   *Keterangan: Dashboard pelaporan otomatis rekapitulasi data keuangan harian bagi Owner.*

---
   
Link Canva Presentasi: https://canva.link/3q2coyvmxysshb4
