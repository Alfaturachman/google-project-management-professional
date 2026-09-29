# Risk Identification Tools, Fishbone Analysis, Single Point of Failure, and Dependency Mapping

Dokumen ini berisi rangkuman komprehensif mengenai teknik identifikasi risiko, diagram sebab-akibat (*fishbone diagram*), matriks probabilitas dan dampak (*probability and impact matrix*), klasifikasi risiko proyek, mitigasi titik kegagalan tunggal (*single point of failure*), serta pemetaan empat jenis dependensi tugas (*task dependencies*).

---

### 1. Alat dan Teknik Identifikasi Risiko (Risk Identification Tools)

Identifikasi risiko adalah langkah proaktif untuk memetakan seluruh potensi masalah sebelum berdampak pada kelangsungan proyek.

#### Sesi Curah Pendapat Bersama Tim yang Beragam (Diverse Brainstorming)
- Mengundang tim lintas divisi berdasarkan matriks RACI (menggabungkan anggota senior berpengalaman dan anggota baru untuk menghadirkan perspektif segar).
- Menciptakan suasana diskusi yang terbuka dan bebas dari penghakiman (*judgment-free zone*).

#### Daftar Risiko (Risk Register)
- Dokumen atau tabel repositori utama tempat seluruh risiko yang teridentifikasi dicatat, dinilai skor risikonya, dan dipantau status penanganannya.

#### Matriks Probabilitas dan Dampak (Probability and Impact Matrix)
Alat visual untuk menentukan skala prioritas risiko berdasarkan dua variabel:
- **Dampak (Impact / Severity):** Tingkat kerusakan jika risiko terjadi (*High*, *Medium*, *Low*). *High impact* berarti risiko dapat mengacaukan keseluruhan proyek.
- **Probabilitas (Probability / Likelihood):** Tingkat kemungkinan terjadinya risiko (*High*, *Medium*, *Low*).
- **Peringkat Risiko Inheren (Inherent Risk Rating):** Nilai gabungan dari probabilitas dan dampak. Risiko dengan peringkat *Medium* hingga *High* wajib memiliki rencana mitigasi detail.
- **Prinsip Aksesibilitas Desain:** Menggunakan kombinasi warna, teks, dan bentuk geometris yang berbeda agar matriks mudah dibaca oleh semua anggota tim.
- **Selera Risiko Organisasi (Risk Appetite):** Tingkat kesediaan perusahaan untuk mentoleransi atau menanggung konsekuensi dari suatu risiko.

---

### 2. Analisis Akar Masalah dengan Diagram Tulang Ikan (Fishbone / Ishikawa Diagram)

Dikembangkan oleh Kaoru Ishikawa pada tahun 1960-an untuk kendali mutu, diagram tulang ikan (*cause-and-effect diagram*) digunakan untuk melacak akar penyebab masalah (*root cause*).

#### Empat Langkah Membangun Diagram Fishbone (Studi Kasus: Office Supply Inc. - Miguel)
- **Langkah 1: Mendefinisikan Masalah Utama (Kepala Ikan):**
  - Masalah: Keterlambatan pengiriman produk ke gedung perkantoran di pusat kota.
- **Langkah 2: Mengidentifikasi Kategori Penyebab (Tulang Utama):**
  - Kategori umum: *People, Technology, Materials, Transportation, Money, Time, Environment, Procedures*.
- **Langkah 3: Menemukan Potensi Penyebab di Setiap Kategori (Tulang Kecil):**
  - *People:* Kurangnya pelatihan staf pengemudi.
  - *Technology:* Sistem pelacakan rute yang usang.
  - *Materials:* Kemasan barang yang terlalu rapuh.
  - *Transportation:* Ukuran truk tidak sesuai dan jumlah armada terbatas.
  - *Environment:* Kemacetan lalu lintas kota, antrean lift gedung perkantoran.
- **Langkah 4: Menganalisis Akar Masalah (Root Cause Analysis):**
  - Miguel menemukan bahwa kurangnya forklift di gudang memang memperlambat muat barang, tetapi bukan akar masalah utama keterlambatan.
  - **Akar Masalah Sebenarnya:** Ketiadaan jadwal pengiriman teratur yang menyebabkan truk pengantar selalu terjebak pada jam sibuk (*rush hour*) lalu lintas pusat kota. Mengubah jadwal keberangkatan sebelum jam sibuk menjadi solusi mitigasi yang tepat.

---

### 3. Klasifikasi Jenis Risiko Proyek (Types of Project Risks)

#### Risiko Kendala Inti Proyek (Triple Constraints Risks)
- **Risiko Waktu (Time Risks):** Kemungkinan durasi aktivitas meleset dari estimasi sehingga memicu keterlambatan peluncuran proyek.
- **Risiko Anggaran (Budget Risks):** Potensi pembengkakan biaya akibat perencanaan yang lemah atau inflasi harga vendor.
- **Risiko Ruang Lingkup (Scope Risks):** Potensi kegagalan menghasilkan *deliverable* yang memenuhi spesifikasi tujuan proyek, termasuk ancaman pemuaian ruang lingkup (*scope creep*).

#### Risiko Eksternal (External Risks)
- Faktor di luar kendali langsung tim proyek, seperti bencana alam/cuaca ekstrem (*environmental risks*) atau perubahan regulasi perizinan dan hukum (*legal risks*).

---

### 4. Mengelola Titik Kegagalan Tunggal (Single Point of Failure / SPOF)

Titik kegagalan tunggal (*Single Point of Failure*) adalah risiko kritis di mana kegagalan pada satu komponen, sumber daya, atau individu dapat menghentikan seluruh operasional proyek secara total.

- **Contoh SPOF:** Hanya memiliki satu tenaga ahli (*Subject Matter Expert* / SME) yang menguasai sistem basis data inti tanpa ada dokumentasi atau personel pengganti; atau ketergantungan pada server tunggal tanpa cadangan *cloud*.

#### Empat Strategi Mitigasi Risiko SPOF (Studi Kasus: Pajak Ekspor Benih Plant Pals)
- **1. Menghindari (Avoid):**
  - Menghilangkan risiko sepenuhnya dengan mengubah rencana (contoh: beralih menggunakan jenis benih tanaman lain yang tersedia luas secara lokal).
- **2. Meminimalkan / Mitigasi (Minimize / Workaround):**
  - Mengurangi kemungkinan atau tingkat keparahan dampak (contoh: membagi pesanan benih ke pemasok Amerika Selatan dan pemasok negara tetangga secara paralel).
- **3. Mengalihkan (Transfer):**
  - Memindahkan tanggung jawab penanganan risiko kepada pihak ketiga (contoh: membeli benih melalui distributor regional Amerika Utara yang menanggung seluruh risiko kepabeanan dan regulasi impor).
- **4. Menerima (Accept):**
  - *Penerimaan Aktif (Active Acceptance):* Menyiapkan dana cadangan kontinjensi untuk membayar biaya tak terduga bila masalah muncul.
  - *Penerimaan Pasif (Passive Acceptance):* Tidak melakukan tindakan pencegahan dan siap menanggung risiko bila terjadi (hanya cocok untuk risiko berkategori minor, sangat tidak disarankan untuk risiko SPOF).

---

### 5. Pemetaan Hubungan Dependensi Tugas (Task Dependencies)

Dependensi adalah hubungan keterkaitan antara dua tugas di mana permulaan atau penyelesaian suatu tugas bergantung pada tugas lainnya.

#### Empat Jenis Ketergantungan Tugas
- **1. Finish to Start (FS) - Paling Umum:**
  - Tugas A harus selesai sebelum Tugas B dapat dimulai.
  - *Contoh:* Anda harus selesai memakai kaus kaki (Tugas A) sebelum mulai memakai sepatu (Tugas B).
- **2. Finish to Finish (FF):**
  - Tugas A harus selesai sebelum Tugas B dapat diselesaikan.
  - *Contoh:* Anda harus selesai membuat krim lapisan kue (Tugas A) sebelum dapat menyelesaikan dekorasi kue (Tugas B).
- **3. Start to Start (SS):**
  - Tugas B tidak dapat dimulai sebelum Tugas A dimulai (berjalan secara paralel).
  - *Contoh:* Anda harus mulai membayar tiket kereta (Tugas A) sebelum dapat mulai menaiki gerbong kereta (Tugas B).
- **4. Start to Finish (SF) - Sangat Jarang:**
  - Tugas A harus dimulai sebelum Tugas B dapat diselesaikan.
  - *Contoh:* Rekan kerja sif berikutnya harus mulai bertugas (Tugas A) sebelum penjaga sif saat ini dapat mengakhiri jam kerjanya (Tugas B).

#### Kategori Dependensi
- **Dependensi Internal:** Keterkaitan tugas yang berada di bawah kendali penuh tim proyek (contoh: persetujuan desain UI harus selesai sebelum pengkodean dimulai).
- **Dependensi Eksternal:** Keterkaitan tugas yang bergantung pada pihak luar di luar kendali tim (contoh: cuaca panen petani pemasok atau keterlambatan kurir kargo).

#### Pemodelan Grafik Dependensi (Dependency Graph)
- **Studi Kasus Pembuatan Roti Lapis (PB&J Sandwich):**
  - *Tugas A:* Mengumpulkan bahan dan peralatan (roti, selai, piring).
  - *Tugas B & C (Paralel):* Mengoleskan selai stroberi pada roti pertama (Tugas B) dan mengoleskan selai kacang pada roti kedua (Tugas C) setelah Tugas A selesai.
  - *Tugas D:* Menyatukan kedua lembar roti (hanya bisa dimulai setelah Tugas B dan C selesai).
  - *Tugas E:* Meletakkan di piring dan menyajikan kepada tamu (setelah Tugas D selesai).
