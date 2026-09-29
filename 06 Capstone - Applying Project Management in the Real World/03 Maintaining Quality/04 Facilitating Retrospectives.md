# Facilitating Retrospectives

Dokumentasi catatan pembelajaran, ringkasan konsep inti, dan pembahasan materi mengenai fasilitasi pertemuan retrospektif (*retrospectives*) sebagai mekanisme Pengendalian Mutu (Quality Control / QC) dan perbaikan proses berkelanjutan pada proyek Sauce and Spoon. Catatan ini menguraikan teknik membangun keamanan psikologis (*psychological safety*), mendorong akuntabilitas tanpa menyalahkan (*blameless culture*), mentransformasikan keluhan menjadi rencana aksi SMART, menangani resistensi atau kenegatifan tim, hingga wawasan Site Reliability Manager Google dalam memimpin evaluasi pasca-proyek (*postmortems*).

---

### 1. Nilai Strategis dan Tujuan Pertemuan Retrospektif (*The Value of Retrospectives*)

Retrospektif adalah lokakarya refleksi terstruktur di mana tim proyek meninjau kembali apa yang telah berjalan baik, apa yang mengalami kendala, dan apa yang dapat diperbaiki:
- **Waktu Pelaksanaan**: Tidak hanya dilakukan pada akhir proyek (*project closeout*), melainkan sangat efektif diselenggarakan setiap kali tim menyelesaikan suatu milestone penting (contoh: pasca pengujian beta tablet di restoran).
- **Tiga Tujuan Utama Retrospektif**:
  1. *Membangun Soliditas Tim (*Team Building*)*: Memberikan ruang bagi anggota tim untuk saling memahami perspektif rekan kerja lintas fungsi.
  2. *Meningkatkan Kolaborasi Masa Depan*: Menghilangkan sekat komunikasi dan menyepakati alur kerja yang lebih lancar.
  3. *Mendorong Perubahan Proses Positif*: Mengidentifikasi kelemahan sistemik dan memperbarui SOP kerja.

---

### 2. Teknik Mendorong Partisipasi Aktif Tim (*Encouraging Participation*)

Menghilangkan rasa cemas atau intimidasi agar anggota tim berani berbicara jujur:
- **Membangun Lingkungan Aman (*Safe Space / Psychological Safety*)**: Menegaskan norma kerahasiaan: *"Apa yang dibicarakan di sini tetap di sini, apa yang dipelajari di sini dibawa keluar"* (*what's said here stays here, what's learned here leaves*). Retrospektif internal diadakan tanpa kehadiran klien atau eksekutif senior agar tim bebas bersuara.
- **Memodelkan Keterbukaan (*Modeling Vulnerability*)**: Manajer proyek memulai sesi dengan mengakui kesalahan atau kekurangan dari kepemimpinannya sendiri (contoh: keterlambatan pengurusan dokumen pengiriman tablet) guna memberikan teladan bahwa mengakui kesalahan adalah hal yang wajar.
- **Mengajukan Pertanyaan Terstruktur**: Menggunakan kerangka kerja alternatif seperti *"Start, Stop, Continue"* atau meminta setiap peserta menyebutkan tepat satu keberhasilan dan satu tantangan.
- **Meninjau Garis Waktu Proyek (*Timeline Review*)**: Membuka kembali riwayat jadwal sejak awal proyek untuk menyegarkan ingatan tim terhadap peristiwa yang terjadi beberapa minggu sebelumnya.

---

### 3. Menegakkan Akuntabilitas Tanpa Budaya Menyalahkan (*Encouraging Accountability*)

Membedakan secara tegas antara rasa tanggung jawab kolektif dan penghakiman personal:

#### A. Akuntabilitas versus Menyalahkan (*Accountability vs Blame*)
- **Menyalahkan (*Blame*)**: Mencari kesalahan individu, memicu defensif, dan membunuh kejujuran tim.
- **Akuntabilitas (*Accountability*)**: Mendorong tim untuk berpikir holistik mengenai celah sistemik yang menyebabkan masalah dan bersama-sama merancang solusinya.

#### B. Mengubah Keluhan Menjadi Tindakan SMART (*Complaints into SMART Action Items*)
- Menghentikan keluhan pasif dan mengubahnya menjadi rencana aksi nyata:
  - *Keluhan*: "Manajer dapur merasa tidak pernah dilibatkan dalam rapat keputusan operasional harian."
  - *Tindakan SMART*: "Menambahkan perwakilan manajer dapur ke dalam agenda rapat mingguan staf manajemen selama 10 menit mulai Senin depan, dan meninjau kembali tingkat kepuasan koordinasi dapur setelah dua bulan."

#### C. Mengidentifikasi Peran Internal Tim
- Mengajak tim merefleksikan rangkaian peristiwa saat terjadi masalah eksternal (contoh keterlambatan pengiriman vendor) dan menemukan peluang internal yang terlewatkan (seperti perlunya jadwal panggilan koordinasi rutin mingguan dengan vendor).

---

### 4. Menangani Sikap Negatif dalam Retrospektif (*Addressing Negativity*)

Strategi menjaga nada pertemuan tetap konstruktif dan solutif:
- **Membuka dengan Sorotan Positif**: Memulai rapat dengan merayakan pencapaian milestone dan membagikan kartu indeks hijau untuk apresiasi sebelum membahas kartu merah untuk tantangan.
- **Pendekatan Empat Mata Pra-Rapat**: Menemui anggota tim yang terindikasi frustrasi sebelum retrospektif dimulai untuk mendengarkan kekhawatiran mereka dan memberikan rasa aman.
- **Menghentikan Dominasi Negatif**: Mengalihkan pertanyaan kepada anggota tim lain secara individual untuk memodelkan pola pikir solutif jika ada satu peserta yang mendominasi percakapan dengan nada negatif.
- **Mengambil Jeda Waktu (*Meeting Timeout*)**: Menghentikan rapat sejenak untuk mendinginkan suasana saat emosi mulai memanas.

---

### 5. Wawasan Praktis Kepemimpinan Retrospektif (Perspektif Dana - Google SRE Manager)

Prinsip keandalan sistem (*Site Reliability Engineering*) dalam retrospektif:
- **Retrospektif Tanpa Menyalahkan (*Blameless Postmortems*)**: Fokus menyelidiki kegagalan proses dan kelemahan alat bantu, bukan menghukum manusia.
- **Penyebab Utama Keheningan Tim**: Tim tidak bersuara biasanya bukan karena tidak ada masalah, melainkan karena ketiadaan rasa aman psikologis atau perasaan apatis bahwa masukan mereka tidak akan membawa perubahan.
- **Menjamin Dampak Nyata**: Memastikan hasil retrospektif benar-benar diterapkan ke dalam perencanaan proyek berikutnya sehingga tim merasa kontribusi suara mereka dihargai dan membawa dampak nyata.
