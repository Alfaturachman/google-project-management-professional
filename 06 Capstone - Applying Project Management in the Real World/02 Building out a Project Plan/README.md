# Building out a Project Plan

Dokumentasi catatan pembelajaran, ringkasan konsep inti, dan pembahasan materi untuk modul **02 Building out a Project Plan** yang merupakan bagian kedua dari kursus ke-6 (**Capstone: Applying Project Management in the Real World**) pada program sertifikasi **Google Project Management Professional**. Modul ini berfokus pada dekonstruksi ruang lingkup kerja menjadi rencana proyek yang terstruktur secara rinci, penetapan dependensi antar-tugas, penghitungan jalur kritis (*Critical Path*), serta penerapan teknik estimasi waktu probabilistik yang akurat.

---

### 1. Gambaran Umum Modul

Fase perencanaan proyek (*project planning*) adalah tahap perancangan peta jalan komprehensif untuk memandu eksekusi kerja tim. Modul ini mengajarkan pendekatan terstruktur dalam:
- Mengembangkan *Work Breakdown Structure* (WBS) dan paket kerja (*work packages*) yang terukur.
- Memetakan titik pencapaian utama (*milestones*) sebagai penanda kemajuan strategis.
- Mengidentifikasi empat jenis hubungan ketergantungan antar-tugas (*task dependencies*).
- Menghitung durasi tugas menggunakan formula estimasi *PERT* dan *Triangular* berbasis matematis KaTeX.
- Mengelola cadangan waktu kontinjensi (*contingency buffer*) dan alokasi kapasitas sumber daya tim.

---

### 2. Konsep Kunci dan Topik Pembelajaran

#### A. Identifikasi Tugas dan Milestones
- **Work Breakdown Structure (WBS)**: Memecah sasaran besar menjadi aktivitas-aktivitas operasional yang dapat dikelola secara mandiri (*manageable tasks*).
- **Milestones**: Titik acuan waktu berdurasi nol yang menandai penyelesaian fase kritis atau paket kerja penting (misalnya: instalasi tablet selesai, pelatihan staf tuntas).
- **Analisis Ketergantungan (*Task Dependencies*)**:
  - *Finish-to-Start* (FS): Tugas B baru dapat dimulai setelah Tugas A selesai.
  - *Start-to-Start* (SS): Tugas B dimulai bersamaan dengan dimulainya Tugas A.
  - *Finish-to-Finish* (FF): Tugas B selesai bersamaan dengan selesainya Tugas A.
  - *Start-to-Finish* (SF): Tugas B selesai sebelum Tugas A dimulai.

#### B. Jalur Kritis dan Manajemen Durasi (*Critical Path Method*)
- Menentukan rangkaian tugas berurutan terpanjang yang menentukan durasi total proyek.
- Mengidentifikasi *float* atau *slack time* (kelonggaran waktu penundaan tugas tanpa memengaruhi tanggal akhir proyek).

#### C. Teknik Estimasi Waktu Presisi (*Accurate Time Estimates*)
- **Three-Point Estimation**: Memadukan tiga skenario estimasi: Optimis ($O$), *Most Likely* ($M$), dan Pesimis ($P$).
- **Distribusi Segitiga (*Triangular Distribution*)**:
  $$\text{E} = \frac{\text{O} + \text{M} + \text{P}}{3}$$
- **Distribusi Beta (*PERT Formula*)**:
  $$\text{E} = \frac{\text{O} + 4\text{M} + \text{P}}{6}$$
- **Standar Deviasi PERT (*PERT Standard Deviation*)**:
  $$\sigma = \frac{\text{P} - \text{O}}{6}$$
- **Cadangan Kontinjensi (*Contingency Reserves*)**: Alokasi waktu tambahan untuk mengantisipasi risiko yang teridentifikasi (*known-unknowns*).

---

### 3. Struktur Berkas Pembelajaran

Modul ini terdiri dari beberapa catatan pembelajaran mendalam:

1. **01 Identifying Tasks and Milestones.md**
   - Pembahasan dekonstruksi WBS, penetapan *milestones*, analisis ketergantungan 4 tipe, pemetaan *Critical Path*, serta manajemen beban kerja sumber daya (*resource leveling*).
2. **02 Making Accurate Time Estimates.md**
   - Pembahasan teknik estimasi analogis, parametrik, *bottom-up*, formula matematis PERT dan Triangular, kalkulasi *standard deviation*, serta manajemen cadangan kontinjensi.
3. **Module 2 Challenge.md**
   - Latihan dan penilaian skenario perancangan rencana proyek dan estimasi jadwal.

---

### 4. Key Takeaways Modul 2

- Rencana proyek bukan sekadar daftar tugas statis, melainkan model dinamis yang menghubungkan ruang lingkup, dependensi, dan kapasitas sumber daya secara terintegrasi.
- Menggunakan formula estimasi probabilistik (seperti PERT) memberikan rentang keyakinan yang jauh lebih realistis bagi tim dan sponsor dibandingkan estimasi skenario tunggal.
