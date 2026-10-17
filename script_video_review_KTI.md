# SCRIPT VIDEO PRESENTASI UTS KONSEP TEKNOLOGI INFORMASI
**Mahasiswa:** Rochmad Djojo Oktabianto (NRP: 3126600126)  
**Program Studi:** D4 Teknik Informatika — PENS  
**Mata Kuliah:** Konsep Teknologi Informasi (Dosen: Iwan Syarif)  
**Batas Durasi:** Maksimal 15 Menit (Target Script: ~13–14 Menit)  

---

## ⏱️ MENIT 00:00 – 01:30 | BAGIAN 1: THE HOOK & PENDAHULUAN
**[Visual: Wajah di kamera webcam sejajar mata, slide judul presentasi di samping]**

> *"Banyak orang mengira, kalau punya budget 8 jutaan besar dan ingin membeli laptop kencang, cukup lihat nama prosesornya saja. Tapi benarkah demikian?*  
> 
> *Bagaimana jika ada dua laptop dengan prosesor yang sama, skor benchmark-nya sama-sama tembus 10.000 poin di Cinebench, tapi saat kita bongkar bodi dalamnya... yang satu RAM-nya bisa di-upgrade sampai 64 Gigabyte dan punya 2 slot SSD, sementara yang satu lagi RAM-nya disolder mati seumur hidup dan port USB-C nya cuma pajangan transfer data?*  
> 
> *Assalamualaikum Warahmatullahi Wabarakatuh. Selamat pagi/siang kepada Bapak Iwan Syarif selaku dosen pengampu mata kuliah Konsep Teknologi Informasi, dan rekan-rekan mahasiswa semuanya.*  
> 
> *Perkenalkan, saya **Rochmad Djojo Oktabianto**, mahasiswa D4 Teknik Informatika, Politeknik Elektronika Negeri Surabaya.*  
> 
> *Pada video reviu Ujian Tengah Semester kali ini, saya menetapkan budget spesifik di angka **Rp 8 hingga 9 jutaan**, dan saya tidak membandingkan merek secara umum, melainkan mengadu **5 model laptop spesifik secara head-to-head**:*  
> 1. *Pertama, **Axioo Hype 5 AMD X6** model H5A-6600.*  
> 2. *Kedua, **Advan WorkPlus** model 14-FHD+.*  
> 3. *Ketiga, **Lenovo IdeaPad Slim 3 14IAH8** model 83EQ004DID.*  
> 4. *Keempat, **Acer Aspire 5 Slim** model A514-56M-534E.*  
> 5. *Dan kelima, **ASUS Vivobook 14** model A1404VA-VIPS551.*  
> 
> *Mari kita bedah secara ilmiah: di balik performa yang tampak setara di atas kertas, brand mana yang memberikan keuntungan teknis paling nyata bagi mahasiswa informatika?"*

---

## ⏱️ MENIT 01:31 – 04:30 | BAGIAN 2: BEDAH MICROPROCESSOR, CACHE, & BENCHMARK
**[Visual: Tampilkan slide perbandingan CPU, diagram hierarki Cache L1-L2-L3, dan grafik batang Cinebench R23]**

> *"Kita mulai dari komponen paling vital: **Microprocessor atau CPU**.*  
> 
> *Di sini terjadi pertarungan dua filosofi arsitektur silikon:*  
> *Di kubu AMD, **Axioo Hype 5** dan **Advan WorkPlus** dipersenjatai **AMD Ryzen 5 6600H**. Ini adalah arsitektur Zen 3+ dengan fabrikasi 6 nanometer, membawa **6 Core murni dan 12 Thread** dengan TDP tinggi, yaitu 45 Watt.*  
> 
> *Sedangkan di kubu Intel, **Lenovo IdeaPad Slim 3** menggunakan **Intel Core i5-12450H** arsitektur Alder Lake H 45 Watt dengan konfigurasi hybrid: 4 Performance Core dan 4 Efficient Core.*  
> 
> *Sementara **Acer Aspire 5** dan **ASUS Vivobook 14** menggunakan **Intel Core i5-1335U** Raptor Lake dengan 10 Core, tetapi merupakan seri U hemat daya dengan TDP hanya 15 Watt.*  
> 
> *Pertanyaan pentingnya: **Apakah prosesor 10 Core pada Acer dan ASUS otomatis lebih cepat daripada 6 Core pada Ryzen?**  
> Secara teknis: **Tentu tidak.**  
> Kinerja prosesor ditentukan oleh jumlah core dikalikan nilai IPC (Instructions Per Cycle) dan frekuensi clock, serta dibatasi oleh hukum Amdahl dan batas daya termal (TDP). Dari 10 core milik Core i5-1335U, 8 di antaranya adalah Efficient-core berkecepatan rendah. Saat kompilasi program berat dijalankan di semua thread, Ryzen 5 6600H dengan 6 Core performa penuh pada TDP 45 Watt sustained jauh lebih stabil dan tidak mengalami penurunan clock sedalam seri U.*  
> 
> *Sekarang kita beralih ke aspek yang sering dilupakan: **CPU Cache**.*  
> *Dalam sistem komputer, cache berfungsi mereduksi apa yang disebut sebagai 'Von Neumann Bottleneck'—yaitu jeda waktu tunggu CPU saat mengambil data dari RAM utama. Cache L1 berada tepat di dalam unit eksekusi core dengan latensi hanya sekitar 1 nanodetik. Cache L2 mendampingi per-core atau kluster core, dan Cache L3 adalah memori bersama di dalam die prosesor.*  
> 
> *Ryzen 5 6600H dibekali **Cache L3 monolitik sebesar 16 Megabyte**, sedangkan Intel i5 memiliki Smart Cache 12 Megabyte. Semakin besar Cache L3, semakin tinggi rasio Cache Hit, sehingga saat kita meng-compile kode sumber proyek berukuran gigabyte, instruksi tidak perlu bolak-balik di-fetch dari RAM.*  
> 
> *Buktinya terlihat jelas pada **Benchmark Cinebench R23 Multi-Core**:*  
> * **Advan WorkPlus** memimpin di skor **10.150 poin**.  
> * **Axioo Hype 5** di angka **9.820 poin**.  
> * **Lenovo IdeaPad Slim 3** di angka **9.250 poin**.  
> * Sementara **Acer** dan **ASUS** seri U berada di kisaran **7.900 hingga 8.100 poin**."*

---

## ⏱️ MENIT 04:31 – 07:30 | BAGIAN 3: DILEMA RAM & STORAGE EXPANSION
**[Visual: Slide foto perbandingan jeroan laptop: SODIMM slot vs chip tersolder, dan ilustrasi dual M.2 slot]**

> *"Nah, jika performa CPU-nya bersaing ketat, sekarang mari kita lihat aspek pembeda paling krusial: **RAM dan Storage Upgradability**.*  
> 
> *Semua laptop ini hadir dengan kapasitas awal **16 Gigabyte Dual-Channel**.  
> Pertanyaannya: **Apakah 16 GB cukup untuk mahasiswa IT?**  
> Ya, untuk saat ini cukup. Menjalankan Windows 11, browser puluhan tab, VS Code, dan satu container Docker ringan memakan sekitar 10 sampai 12 GB.*  
> 
> *Tetapi, bagaimana jika tahun depan Anda harus menjalankan multi-VM untuk praktikum jaringan, emulator Android Studio, atau data science dataset besar? Di sinilah RAM 32 GB menjadi mutlak menguntungkan.*  
> 
> *Dan di sinilah kita menemukan pemenang mutlak:  
> 🏆 **Axioo Hype 5 AMD X6** adalah satu-satunya laptop yang menyediakan **2 slot SODIMM DDR5**. RAM bawaannya tidak disolder sama sekali! Anda bisa mencabutnya dan melakukan upgrade hingga **64 Gigabyte**.*  
> 
> *ASUS Vivobook berada di posisi kedua karena masih menyisakan 1 slot SODIMM tambahan.*  
> 
> *Sebaliknya, **Advan WorkPlus, Lenovo IdeaPad Slim 3, dan Acer Aspire 5** menggunakan RAM jenis **LPDDR5 Soldered (Onboard)**. Kecepatannya memang tinggi, mencapai 4.800 hingga 6.400 MHz, tetapi tersolder mati di motherboard. Konsekuensi jangka panjangnya: jika suatu saat Anda butuh RAM lebih besar, sistem akan terpaksa melakukan 'swapping memory' ke SSD yang memperlambat kinerja dan memperpendek umur SSD.*  
> 
> *Lalu bagaimana dengan **Storage atau Penyimpanan**?  
> Kelimanya sudah menggunakan **SSD M.2 NVMe PCIe**, bukan lagi SATA SSD apalagi HDD mekanikal. Kecepatan baca-tulisnya mencapai 2.400 hingga 4.500 Megabyte per detik, membuat booting Windows hanya butuh 8 detik.*  
> 
> *Namun perhatikan slot ekspansinya:  
> **Axioo Hype 5 dan Advan WorkPlus** memiliki **2 Slot M.2 NVMe**. Jika memori 512 GB bawaan penuh, Anda tinggal membeli SSD kedua 1 TB, colok ke slot kosong, dan selesai.  
> 
> Sedangkan **Lenovo, Acer, dan ASUS HANYA MEMILIKI 1 SLOT M.2**. Mau upgrade? Anda harus membeli SSD baru, melepas SSD lama, membeli enclosure tambahan, dan melakukan proses cloning sistem operasi dari nol yang memakan waktu."*

---

## ⏱️ MENIT 07:31 – 10:00 | BAGIAN 4: LAYAR, PORT KONEKTIVITAS, & BATERAI
**[Visual: Slide rasio layar 16:10 vs 16:9, close-up port Thunderbolt 4 Acer vs USB-C biasa, dan grafik daya baterai]**

> *"Sekarang kita beralih ke aspek fisik: **Layar, Port I/O, dan Daya Baterai**.*  
> 
> *Pertama, **Kualitas Layar**.*  
> *Kelima laptop ini menggunakan panel IPS Full HD yang nyaman di mata. Namun, **Axioo dan Advan** memberikan keunggulan teknis berupa **Layar Berasio 16:10 (resolusi 1920x1200 piksel)**.  
> Mengapa rasio 16:10 lebih disukai programmer? Karena layar vertikalnya lebih panjang 120 piksel dibanding rasio 16:9 milik Lenovo, Acer, dan ASUS, sehingga kita bisa melihat baris kode lebih banyak tanpa harus sering scrolling.*  
> 
> *Kedua, **Port Konektivitas**.*  
> *Di sinilah **Acer Aspire 5 Slim** membalas telak. Laptop ini adalah satu-satunya di bawah 9 juta yang memiliki port **Thunderbolt 4 berkecepatan 40 Gigabits per detik**! Port ini mendukung PCIe tunneling, pengisian daya Power Delivery, display out ke monitor 4K, hingga koneksi ke external GPU.*  
> 
> *Advan, Axioo, dan Lenovo berada di posisi kedua dengan port **USB-C Full Function** yang bisa dipakai untuk cas laptop dengan charger HP berteknologi Power Delivery dan menyambung monitor eksternal.*  
> 
> *Sedangkan ASUS Vivobook varian ini berada di posisi paling bawah karena USB-C nya masih berstatus 'Data Only'—tidak bisa untuk mengecas baterai laptop.*  
> 
> *Ketiga, **Daya Tahan Baterai**.*  
> *Jika Anda mahasiswa yang suka kerja di kafe atau perpustakaan tanpa repot mencari colokan listrik:  
> **Acer Aspire 5 Slim adalah rajanya.** Berkat prosesor Intel seri U 15 Watt dan baterai 50 Watt-hour, ia mampu bertahan **hingga 8,5 jam pemakaian riil**!  
> 
> Sedangkan laptop dengan prosesor seri H 45 Watt seperti Advan, Axioo, dan Lenovo bertahan di kisaran **5,5 hingga 7 jam**."*

---

## ⏱️ MENIT 10:01 – 12:30 | BAGIAN 5: ANALISIS TCO (TOTAL COST OF OWNERSHIP) & DURABILITAS
**[Visual: Slide Tabel Perbandingan Bagian F dan rincian formula kalkulasi TCO 3 tahun]**

> *"Bapak dosen dan teman-teman sekalian, sekarang kita masuk ke analisis finansial teknik yang sangat penting: **Total Cost of Ownership (TCO)**.*  
> 
> *Seringkali konsumen tertipu dengan menganggap laptop termurah saat dibeli adalah laptop paling hemat. Mari kita buktikan secara matematis!*  
> 
> *Mari kita hitung biaya kepemilikan riil selama 3 tahun masa kuliah:*  
> 
> * **Advan WorkPlus** dijual seharga **Rp 7.999.000** (paling murah). Tetapi Advan **belum menyertakan lisensi Microsoft Office permanen**, sehingga kita harus membeli Office Home & Student asli seharga Rp 1,4 juta. Ditambah membeli SSD kedua 1 TB seharga Rp 850 ribu, dikurangi estimasi resale value... TCO 3 tahunnya menjadi **Rp 8.050.000**.*  
> 
> * **Axioo Hype 5** dijual seharga **Rp 8.499.000**. Ditambah biaya Office dan upgrade, TCO 3 tahunnya berkisar **Rp 8.550.000**.*  
> 
> *Sekarang mari kita lihat **Lenovo IdeaPad Slim 3**:*  
> *Harga belinya memang sedikit lebih mahal, yaitu **Rp 8.599.000**.  
> TETAPI, Lenovo sudah menyertakan **Windows 11 asli DAN Microsoft Office Home & Student asli permanen seumur hidup**. Kita hemat Rp 1,4 juta sejak hari pertama!  
> Selain itu, sasis Lenovo lolos **uji ketahanan standar militer MIL-STD-810H** dan keyboard AccuType-nya sangat awet, sehingga meminimalkan biaya servis keyboard atau engsel patah. Di pasar barang bekas, brand Lenovo memiliki depresiasi harga yang jauh lebih stabil dibanding brand lokal.*  
> 
> *Hasil perhitungan TCO 3 tahun membuktikan: **Lenovo IdeaPad Slim 3 justru keluar sebagai laptop yang paling hemat secara kepemilikan jangka panjang (Rp 6.650.000)**."*

---

## ⏱️ MENIT 12:31 – 14:30 | BAGIAN 6: PENGAMBILAN KEPUTUSAN & REKOMENDASI AKHIR
**[Visual: Tampilkan foto Lenovo IdeaPad Slim 3 dengan badge juara dan 5 poin alasan teknis]**

> *"Berdasarkan seluruh analisis teknis, pengujian benchmark, dan perhitungan TCO, tibalah kita pada **Bagian Pengambilan Keputusan**.*  
> 
> *Satu laptop terbaik pilihan saya untuk tugas UTS KTI ini jatuh kepada:*  
> 🏆 **LENOVO IDEAPAD SLIM 3 14IAH8 (Nomor Model: 83EQ004DID)**  
> *dengan konfigurasi resmi Intel Core i5-12450H, RAM 16 GB LPDDR5, dan SSD 512 GB NVMe di harga **Rp 8.599.000**.*  
> 
> *Berikut **5 Alasan Teknis Utama Pemilihannya**:*  
> 1. *Keseimbangan CPU Seri H: Memiliki 4 P-Core berkecepatan 4.4 GHz yang sangat tangguh untuk kompilasi kode dan 4 E-Core untuk efisiensi.*  
> 2. *Ergonomi Keyboard Terbaik di Industri: Tombol melengkung dengan jarak travel 1.5 mm yang sangat presisi, krusial bagi mahasiswa IT yang mengetik ribuan baris kode.*  
> 3. *Durabilitas Standar Militer MIL-STD-810H: Struktur bodi tahan benturan dan getaran harian.*  
> 4. *Nilai TCO Paling Rendah: Paket lengkap Windows + Office Home & Student resmi permanen.*  
> 5. *Kesiapan Port: Memiliki slot Full-size SD Card Reader dan jaringan service center paling merata di Indonesia.*  
> 
> *Meski menjadi juara, laptop ini tentu memiliki **3 Kompromi Riil**:*  
> * Pertama, RAM-nya disolder mati (terkunci di 16 GB).  
> * Kedua, hanya memiliki 1 slot SSD M.2.  
> * Dan ketiga, akurasi warna layarnya masih standar 45% NTSC.  
> 
> *Lalu **mengapa dua kandidat terdekatnya tidak terpilih?**  
> * **Advan WorkPlus** tidak terpilih karena belum memiliki paket Office resmi, keyboard-nya tidak seergonomis Lenovo untuk sesi coding berjam-jam, dan rekam jejak after-sales jangka panjangnya belum sekuat Lenovo.  
> * Sedangkan **Axioo Hype 5** tidak terpilih karena bodi plastiknya terasa paling ringkih dan belum bersertifikasi uji militer.*  
> 
> *Laptop Lenovo ini **SANGAT COCOK** untuk mahasiswa Teknik Informatika, programmer, web developer, dan pengguna kantor yang mengutamakan keandalan harian.*  
> *Namun **KURANG COCOK** untuk mahasiswa DKV yang membutuhkan akurasi warna 100% DCI-P3 atau hardcore gamer yang butuh GPU diskrit RTX."*

---

## ⏱️ MENIT 14:31 – 15:00 | BAGIAN 7: PENUTUP
**[Visual: Wajah presenter kembali full-screen, tampilkan slide penutup dengan link repositori GitHub]**

> *"Kesimpulannya: dalam memilih perangkat komputasi, jangan hanya terpaku pada angka spesifikasi di brosur iklan. Pahami arsitektur prosesornya, periksa modularitas jeroannya, dan hitung Total Cost of Ownership-nya.*  
> 
> *Seluruh laporan tertulis, tabel komparasi teknis, dan naskah presentasi ini telah saya unggah secara terbuka ke repositori GitHub saya di **github.com/kycjojo/bahanKTI**.*  
> 
> *Demikian presentasi Ujian Tengah Semester Konsep Teknologi Informasi dari saya. Terima kasih banyak atas perhatian Bapak Iwan Syarif dan teman-teman sekalian. Mohon maaf atas segala kekurangan.*  
> 
> *Wabillahi taufiq wal hidayah, Wassalamualaikum Warahmatullahi Wabarakatuh."*
