# Data-Informed Decision-Making

Dokumentasi catatan pembelajaran, ringkasan konsep inti, dan pembahasan materi untuk modul **03 Data-Informed Decision-Making** yang merupakan bagian dari kursus ke-4 (**Project Execution: Running the Project**) pada program sertifikasi **Google Project Management Professional**. Modul ini berfokus pada pengumpulan berbagai kategori metrik proyek (produktivitas, kualitas, kepuasan, adopsi, dan keterlibatan), penyaringan sinyal data kritis, penerapan etika dan privasi data (PII & anonimisasi), mitigasi 4 bias data, kerangka kerja 6 tahap analisis data (Ask, Prepare, Process, Analyze, Share, Act), teknik *data storytelling*, pemilihan visualisasi grafik yang tepat, serta standar penyampaian presentasi yang presisi dan aksesibel.

---

### 1. Nilai Data dan Metrik dalam Manajemen Proyek

Data menjadi aset strategis yang memampukan manajer proyek beralih dari sekadar asumsi menuju pengambilan keputusan berbasis fakta empiris (*data-informed decision-making*):
- **Data**: Kumpulan informasi, angka, fakta, dan umpan balik mentah mengenai berbagai aspek pelaksanaan proyek.
- **Metrik (*Metrics*)**: Tolok ukur terkuantifikasi (*quantifiable measurement*) yang digunakan untuk melacak kemajuan, memantau kinerja tim, dan mengevaluasi status kesehatan proyek terhadap target acuan.
- **Analitika (*Analytics*)**: Proses pengolahan, pemodelan, dan analisis data untuk menemukan tren, anomali, pola tersembunyi, serta merumuskan wawasan strategis dan proyeksi masa depan (*forecasting*).

---

### 2. Kategori Utama Metrik Proyek

Pengukuran komprehensif mengintegrasikan lima kategori metrik utama:

#### A. Productivity Metrics (Metrik Produktivitas)
- Mengukur output kerja dan laju kemajuan tim terhadap linimasa proyek.
- Komponen: Jumlah *milestone* dan tugas yang selesai, *on-time completion rate* (persentase penyerahan tepat waktu), durasi aktual pengerjaan tugas, kecepatan tim (*velocity*), serta estimasi tanggal penyelesaian proyek (*forecasting*).

#### B. Quality Metrics (Metrik Kualitas)
- Menilai pemenuhan standar dan pencapaian hasil serah terima yang dapat diterima (*acceptable outcomes*).
- Komponen: Jumlah perubahan dalam log perubahan (*change log* untuk mendeteksi *scope creep*), jumlah masalah atau cacat (*defects/bugs*), serta varians biaya (*cost variance* / CV) antara anggaran terencana vs biaya aktual.
  - Formula: $\text{Cost Variance (CV)} = \text{Budgeted Cost} - \text{Actual Cost}$

#### C. Happiness & Satisfaction Metrics (Metrik Kebahagiaan dan Kepuasan)
- Mengukur sikap, persepsi subjektif, dan tingkat kepuasan pengguna maupun tim internal.
- Komponen: *Customer Satisfaction Score* (CSAT), tingkat kemudahan penggunaan (*perceived ease of use*), daya tarik visual antarmuka, dan kesediaan merekomendasikan produk (*Net Promoter Score* / NPS).

#### D. Adoption Metrics (Metrik Adopsi)
- Menilai seberapa baik produk, layanan, atau sistem baru diterima dan mulai digunakan oleh target audiens.
- Komponen: Rasio konversi (*conversion rate*), *Time to Value* (TTV: waktu yang dibutuhkan pengguna baru merasakan manfaat pertama kali), persentase penyelesaian orientasi (*onboarding completion rate*), dan kelengkapan profil pengguna.

#### E. Engagement Metrics (Metrik Keterlibatan)
- Menilai frekuensi dan intensitas penggunaan produk atau sistem secara berkelanjutan.
- Komponen: Frekuensi penggunaan harian/bulanan, durasi sesi (*session duration*), partisipasi ulasan/rating, serta keterlibatan aktif tim proyek pada platform kolaborasi (seperti Jira atau Asana).

---

### 3. Sinyal Data, Etika, dan Privasi Data

Pengelolaan data menuntut kepekaan analitis dan tanggung jawab moral yang tinggi:

#### A. Mengenali Sinyal (*Recognizing Signals*)
- Sinyal adalah indikator atau deviasi teramati yang mencerminkan kesehatan proyek (seperti analogi suhu tubuh di atas 100.4°F yang menandakan demam).
- Manajer proyek harus menyelaraskan data dengan prioritas pemangku kepentingan (fokus jadwal vs anggaran vs cakupan).

#### B. Prinsip Etika Data (*Data Ethics*)
- Penerapan standar etika untuk mematuhi regulasi perlindungan data, menjaga kepercayaan (*trustworthiness*), memastikan penggunaan data yang adil (*fair usage*), meminimalkan bias, dan melindungi citra publik organisasi.

#### C. Privasi Data (*Data Privacy*) dan Anonimisasi
- Melindungi informasi identitas pribadi (*Personally Identifiable Information* / PII) melalui kesadaran tim, alat keamanan penyimpanan terenkripsi, dan teknik anonimisasi:
  - **Blanking**: Mengosongkan kolom data sensitif (nama, alamat, nomor kontak).
  - **Hashing**: Mengonversi teks asli menjadi kode acak kriptografi satu arah.
  - **Masking**: Menyembunyikan sebagian karakter (misalnya: xxxx-xxxx-1234).

---

### 4. Mitigasi Empat Jenis Bias Data

Bias data dapat memicu kesimpulan yang keliru dan merugikan proyek:
- **Sampling Bias (Bias Pengambilan Sampel)**: Sampel data tidak mewakili keseluruhan populasi sasaran (contoh: survei yang mengecualikan kelompok usia tertentu).
- **Observer Bias (Bias Pengamat)**: Perbedaan catatan atau interpretasi pengamat terhadap data yang sama akibat latar belakang atau preferensi personal.
- **Interpretation Bias (Bias Interpretasi)**: Kecenderungan menafsirkan data ambigu secara ekstrem ke arah kesimpulan yang selalu positif atau selalu negatif.
- **Confirmation Bias (Bias Konfirmasi)**: Hanya mencari dan mempercayai data yang mendukung keyakinan awal sembari mengabaikan bukti yang bertentangan.

---

### 5. Enam Tahap Analisis Data (The Six Steps of Data Analysis)

Metodologi terstruktur untuk mengolah data mentah menjadi keputusan bisnis:

```
[1. Ask]  -->  [2. Prepare]  -->  [3. Process]
                                      v
[6. Act]  <--  [5. Share]    <--  [4. Analyze]
```

1. **Ask (Bertanya)**: Merumuskan masalah inti secara spesifik, menetapkan batasan analisis, dan menyelaraskan ekspektasi pemangku kepentingan.
2. **Prepare (Mempersiapkan)**: Mengumpulkan dan menyimpan data yang relevan dari sumber-sumber tepercaya secara terstruktur dan aman.
3. **Process (Memproses / Membersihkan)**: Melakukan pembersihan data (*data cleaning*), menghapus duplikasi, mengoreksi ketidakkonsistenan, dan memvalidasi kelengkapan data.
4. **Analyze (Menganalisis)**: Meneliti data secara mendalam untuk menemukan tren, korelasi, dan pola guna menarik kesimpulan berbasis bukti.
5. **Share (Membagikan)**: Menyajikan temuan utama dan wawasan secara visual dan persuasif (*data storytelling*) kepada pemangku kepentingan.
6. **Act (Bertindak)**: Mengambil keputusan strategis, mengeksekusi tindakan nyata, atau melakukan penyesuaian proses proyek berdasarkan temuan.

---

### 6. Visualisasi Data dan Seni Data Storytelling

Mengubah angka menjadi cerita yang memikat dan menggerakkan tindakan:

#### A. Enam Langkah Data Storytelling
1. *Define Audience*: Menyesuaikan pesan untuk pimpinan eksekutif (*high-level bottom line*) atau tim teknis (*granular details*).
2. *Collect Data*: Mengambil data yang akurat dan kredibel.
3. *Filter & Analyze*: Memilah pola terpenting dan menghilangkan gangguan (*noise*).
4. *Choose Visuals*: Memilih grafik yang tepat sesuai karakteristik data.
5. *Shape Story*: Membangun narasi dengan alur terpadu (Awal: Masalah $\rightarrow$ Tengah: Bukti Data $\rightarrow$ Akhir: Rekomendasi Aksi).
6. *Gather Feedback*: Menguji coba alur presentasi kepada pihak netral sebelum sesi utama.

#### B. Pemilihan Grafik yang Tepat
- **Project Dashboard**: Ringkasan visual terpusat untuk KPI dan kesehatan proyek *real-time*.
- **Scatter Plot**: Menunjukkan korelasi antara dua variabel kontinu (sumbu Y mulai dari 0, sertakan garis tren).
- **Bar / Column Chart**: Membandingkan nilai antar-kategori (gunakan label horizontal dan warna konsisten).
- **Pie Chart**: Menunjukkan komposisi bagian terhadap keseluruhan (total 100%, maksimal 5-7 irisan diurutkan dari yang terbesar).
- **Line Graph**: Melacak tren data dari waktu ke waktu (maksimal 4 garis untuk mencegah kekacauan visual).
- **Infographics / One-Pagers**: Ringkasan visual mandiri untuk pemahaman instan tanpa butuh narasi lisan panjang.

---

### 7. Teknik Presentasi Efektif dan Standar Aksesibilitas

Panduan penyampaian komunikasi proyek yang profesional dan inklusif:

#### A. Karakteristik Presentasi Efektif
- **Precise (*Designing for Five Seconds*)**: Setiap slide memiliki 1 kalimat judul utama (*headline*) yang dapat dipahami audiens dalam 5 detik.
- **Flexible**: Kesiapan memangkas durasi paparan (misal: 60 menit menjadi 15 atau 5 menit) dan menyiapkan *backup slides* untuk pertanyaan mendalam.
- **Memorable**: Pembuka yang kuat, penggunaan frasa transisi (*signposts*), dan tempo bicara tenang dengan jeda intensional.
- **Delivery & Follow-Up**: Melakukan latihan simulasi (*mock presentation*), antisipasi sesi tanya jawab (Q&A), penyampaian lugas di awal rapat, serta pengiriman email tindak lanjut (*action items*).

#### B. Standar Aksesibilitas Universal (Universal Accessibility)
- Menghindari animasi berkedip cepat yang berisiko memicu kejang.
- Tidak mengandalkan warna semata untuk menandai status kritis (sertakan label teks pendukung).
- Menyediakan deskripsi teks alternatif (*Alt Text*) pada semua grafik dan gambar.
- Menyediakan takarir (*captions*) pada video dan transkripsi langsung.
- Menerapkan kontras teks minimal 7:1, ukuran font besar, dan menghindari huruf kapital semua (*ALL CAPS*).
- Membagikan materi presentasi lebih awal (*share in advance*) untuk mendukung juru bahasa isyarat dan peserta dengan kebutuhan khusus.
