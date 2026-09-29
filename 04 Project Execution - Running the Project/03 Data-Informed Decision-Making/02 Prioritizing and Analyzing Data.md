# Prioritizing and Analyzing Data

Memprioritaskan dan menganalisis data secara sistematis memungkinkan manajer proyek mengenali sinyal-sinyal penting terkait kesehatan proyek, menjaga kepatuhan terhadap etika dan privasi data, serta menghindari bias dalam pengambilan keputusan. Dengan menerapkan metodologi analisis enam tahap (Ask, Prepare, Process, Analyze, Share, Act), manajer proyek dapat mengubah kumpulan data mentah menjadi tindakan strategis yang berdampak nyata bagi keberhasilan proyek.

---

### 1. Discerning Important Data and Recognizing Signals

Dalam pelaksanaan proyek, manajer proyek dibanjiri oleh volume data yang sangat besar. Keterampilan utama yang dibutuhkan adalah memisahkan informasi umum dari sinyal kritis (*signals*):

- **Konsep Sinyal (*Signal*)**: Perubahan atau indikator teramati yang menunjukkan adanya kondisi khusus, potensi risiko, atau perubahan kesehatan proyek (seperti analogi suhu tubuh di atas 100.4°F yang memberi sinyal infeksi atau demam).
- **Menyelaraskan dengan Prioritas Pemangku Kepentingan (*Stakeholder Priorities*)**: Tidak semua metrik memiliki bobot yang sama bagi setiap pemangku kepentingan. Manajer proyek harus memprioritaskan data yang menjawab kekhawatiran utama pemangku kepentingan:
  - Jika prioritas utama adalah **jadwal/waktu**, fokuskan pelacakan pada *milestone completion* dan durasi tugas kritis.
  - Jika prioritas utama adalah **anggaran**, fokuskan pada *cost variance* dan laju penyerapan dana (*burn rate*).
  - Jika prioritas utama adalah **kualitas/kepuasan**, pantau *defect rate* dan skor kepuasan pengguna (CSAT).
- **Menilai Kelayakan Rencana Proyek**: Ketika sinyal data menunjukkan ketidaksesuaian (misalnya waktu yang dibutuhkan tim nyata melebihi estimasi jadwal), manajer proyek harus segera meninjau ulang rencana kerja, mengevaluasi *trade-off* (cakupan, waktu, anggaran), dan mengomunikasikan penyesuaian kepada tim.

---

### 2. Data Ethics Principles (Prinsip Etika Data)

Etika data adalah studi dan evaluasi mengenai tantangan moral serta tanggung jawab yang timbul dalam proses pengumpulan, penyimpanan, pengolahan, dan pembagian data:

- **Alasan Penerapan Etika Data**:
  - **Kepatuhan Regulasi (*Regulatory Compliance*)**: Mematuhi undang-undang perlindungan data (seperti GDPR atau regulasi privasi lokal).
  - **Membangun Kepercayaan (*Trustworthiness*)**: Menjaga integritas hubungan dengan pengguna, klien, dan pemangku kepentingan.
  - **Penggunaan yang Adil dan Wajar (*Fair & Reasonable Usage*)**: Memastikan data hanya digunakan sesuai tujuan yang telah disetujui secara transparan.
  - **Meminimalkan Bias (*Minimizing Biases*)**: Mencegah diskriminasi atau ketidakadilan sistemik dalam pengambilan keputusan berbasis algoritma atau data.
  - **Reputasi Publik yang Positif (*Positive Public Perception*)**: Melindungi citra dan reputasi organisasi dari skandal penyalahgunaan data.

---

### 3. Data Privacy (Privasi Data)

Privasi data berkaitan erat dengan penanganan dan perlindungan informasi identitas pribadi (*Personally Identifiable Information* / PII). Tanggung jawab manajer proyek meliputi:

- **Peningkatan Kesadaran Privasi (*Increasing Data Privacy Awareness*)**: Memastikan seluruh anggota tim inti, kontraktor eksternal, dan vendor memahami protokol kerahasiaan dan kepatuhan privasi data.
- **Pemanfaatan Alat Keamanan (*Using Security Tools*)**: Menggunakan platform penyimpanan terenkripsi (*encrypted storage*), autentikasi multifaktor (MFA), dan pengelola kata sandi (*password managers*).
- **Anonimisasi Data (*Data Anonymization*)**: Menghapus atau mengaburkan elemen identitas personal dari kumpulan data melalui teknik:
  - **Blanking**: Mengosongkan atau menghapus bidang data sensitif (misalnya kolom nama atau nomor telepon).
  - **Hashing**: Mengubah teks asli menjadi kode karakter unik melalui algoritma kriptografi yang tidak dapat dibalik.
  - **Masking**: Menyembunyikan sebagian karakter dengan simbol khusus (misalnya: xxxx-xxxx-1234 pada nomor kartu kredit).

---

### 4. Identifying and Minimizing Data Bias (Mengidentifikasi dan Meminimalkan Bias Data)

Bias data terjadi ketika data yang dikumpulkan atau diinterpretasikan condong secara tidak adil ke arah hasil tertentu, menghasilkan keputusan yang keliru atau diskriminatif:

- **Sampling Bias (Bias Pengambilan Sampel)**: Terjadi ketika sampel data yang diambil tidak mewakili keseluruhan populasi target secara proporsional (contoh: survei aplikasi seluler yang hanya disebarkan pada kelompok usia muda sehingga mengabaikan kebutuhan pengguna lansia).
- **Observer Bias (Bias Pengamat)**: Kecenderungan pengamat yang berbeda untuk mencatat atau melihat fenomena yang sama secara berbeda berdasarkan latar belakang, pengalaman, atau ekspektasi pribadi masing-masing.
- **Interpretation Bias (Bias Interpretasi)**: Kecenderungan untuk menafsirkan situasi ambigu atau hasil yang belum pasti ke arah kesimpulan ekstrem yang selalu positif atau selalu negatif.
- **Confirmation Bias (Bias Konfirmasi)**: Kecenderungan untuk hanya mencari, mempercayai, dan menonjolkan data yang mendukung hipotesis awal atau keyakinan yang sudah ada sebelumnya, sembari mengabaikan bukti yang bertentangan.

---

### 5. Quantitative vs. Qualitative Data

Pengambilan keputusan yang komprehensif menggabungkan kedua jenis data berikut:

#### A. Quantitative Data (Data Kuantitatif)
- Bersifat numerik, statistik, objektif, dan dapat dihitung secara matematis.
- Contoh: Jumlah pesanan harian, durasi waktu tunggu pelanggan, persentase keterlambatan tugas, dan nilai varians anggaran.
- Menjawab pertanyaan: "Berapa banyak?", "Seberapa sering?", dan "Seberapa cepat?".

#### B. Qualitative Data (Data Kualitatif)
- Bersifat deskriptif, naratif, kontekstual, dan subjektif berdasarkan pengamatan serta pengalaman manusia.
- Contoh: Komentar wawancara pelanggan, keluhan tertulis, ulasan pengguna, dan catatan observasi budaya kerja tim.
- Menjawab pertanyaan: "Mengapa hal ini terjadi?" dan "Bagaimana perasaan pengguna?".

---

### 6. The Six Steps of Data Analysis (Enam Tahap Analisis Data)

Metodologi sistematis untuk mengubah data mentah menjadi keputusan bisnis terukur:

```
Ask  -->  Prepare  -->  Process  -->  Analyze  -->  Share  -->  Act
```

#### 1. Ask (Bertanya)
- Mendefinisikan masalah inti secara spesifik dan menetapkan batasan analisis.
- Mengidentifikasi ekspektasi pemangku kepentingan dan menyusun pertanyaan panduan yang relevan (misalnya: "Mengapa tingkat pembatalan keanggotaan meningkat pada kuartal ini?").

#### 2. Prepare (Mempersiapkan)
- Mengumpulkan, mengelompokkan, dan menyimpan data relevan dari sumber-sumber tepercaya.
- Menentukan populasi sasaran, instrumen pengumpulan (survei, log sistem, database penjualan), dan format penyimpanan yang aman.

#### 3. Process (Memproses / Membersihkan Data)
- Melakukan pembersihan data (*data cleaning*) untuk memastikan keakuratan dan konsistensi.
- Menghapus duplikasi, mengoreksi salah ketik, menangani data yang hilang (*missing values*), dan memvalidasi kelengkapan kumpulan data.

#### 4. Analyze (Menganalisis)
- Meneliti data secara mendalam untuk menemukan tren, anomali, pola musiman, dan korelasi antar-variabel.
- Menghitung metrik statistik, menguji hipotesis, dan menarik kesimpulan berbasis fakta empiris.

#### 5. Share (Membagikan)
- Menyusun laporan visual dan menyajikan temuan utama kepada pemangku kepentingan.
- Menggunakan visualisasi data (grafik, dasbor) dan teknik bercerita (*data storytelling*) agar hasil analisis mudah dipahami oleh audiens non-teknis.

#### 6. Act (Bertindak)
- Mengambil keputusan bisnis dan mengeksekusi rencana tindakan konkret berdasarkan wawasan yang diperoleh.
- Melakukan penyesuaian proses operasional, alokasi sumber daya, atau revisi rencana proyek untuk menyelesaikan masalah yang ditemukan.

---

### 7. Key Takeaways

- Manajer proyek harus peka terhadap sinyal data yang mencerminkan kesehatan proyek serta menyelaraskannya dengan prioritas pemangku kepentingan.
- Praktik etika data, perlindungan privasi (PII), dan mitigasi empat jenis bias (sampling, observer, interpretation, confirmation) menjamin integritas pengambilan keputusan.
- Kerangka kerja 6 langkah analisis data (Ask, Prepare, Process, Analyze, Share, Act) menjembatani pemahaman masalah hingga eksekusi solusi nyata.
