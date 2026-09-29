# Building a Project Plan

Dokumentasi catatan pembelajaran, ringkasan konsep inti, dan pembahasan materi untuk modul **02 Building a Project Plan** yang merupakan bagian dari kursus ke-3 (**Project Planning: Putting It All Together**) pada program sertifikasi profesional **Google Project Management Professional**. Modul ini membahas perakitan rencana proyek secara terperinci dan komprehensif, mencakup lima elemen inti penyusun rencana proyek, teknik estimasi waktu dan kapasitas kerja, mitigasi bias optimisme, perhitungan jalur kritis (Critical Path Method / CPM), hingga penyusunan jadwal visual menggunakan Gantt Chart dan papan Kanban.

---

### 1. Struktur dan Elemen Dasar Rencana Proyek (*Project Plan Fundamentals*)

Rencana proyek (*project plan*) adalah dokumen hidup terpusat yang berfungsi sebagai cetak biru (*blueprint*) operasional dan sumber kebenaran tunggal (*single source of truth*) bagi seluruh tim:

#### Lima Elemen Inti Penyusun Project Plan
1. **Tugas (*Tasks*)**: Rincian aktivitas spesifik yang harus diselesaikan untuk menghasilkan deliverable.
2. **Tonggak Capaian (*Milestones*)**: Titik-titik evaluasi penting penanda penyelesaian deliverable utama tanpa memakan durasi.
3. **Orang dan Peran (*People & Roles*)**: Alokasi sumber daya manusia yang bertanggung jawab (*assignee*) atas eksekusi setiap tugas.
4. **Dokumentasi Terkait (*Documentation*)**: Tautan langsung ke dokumen pendukung seperti spesifikasi teknis, pedoman desain, dan kriteria penerimaan.
5. **Waktu dan Garis Waktu (*Time & Schedule*)**: Tanggal mulai, tanggal jatuh tempo, estimasi durasi, dan keterkaitan dependensi antar tugas.

---

### 2. Estimasi Waktu, Upaya, dan Perencanaan Kapasitas (*Time Estimation & Capacity Planning*)

Akurasi jadwal proyek sangat bergantung pada keandalan metode estimasi dan pemahaman terhadap kapasitas kerja tim:

#### A. Mengatasi Bias Perencanaan (*Planning Fallacy & Optimism Bias*)
- **Planning Fallacy**: Kecenderungan psikologis manusia untuk meremehkan jumlah waktu, biaya, dan risiko yang dibutuhkan dalam menyelesaikan suatu tugas di masa depan.
- **Strategi Mitigasi**:
  - Menggunakan data historis dari proyek serupa di masa lalu sebagai tolok ukur objektif.
  - Memecah tugas menjadi unit-unit mikro yang lebih konkret.
  - Menerapkan estimasi tiga titik (*Three-Point Estimating*) dengan menghitung skenario Optimis ($O$), Paling Mungkin ($M$), dan Pesimis ($P$).
  - Melibatkan langsung anggota tim pelaksana teknis yang akan mengerjakan tugas tersebut.

#### B. Perencanaan Kapasitas Kerja (*Capacity Planning*)
- Menghitung ketersediaan waktu kerja nyata anggota tim dengan memperhitungkan faktor non-proyek seperti libur, cuti, rapat rutin organisasi, dan jeda antar tugas (*buffer time*).
- Menghindari asumsi produktivitas 100% penuh selama 8 jam kerja sehari (standar produktivitas realistis berkisar antara 70% hingga 80% dari total jam kerja).

---

### 3. Analisis Jalur Kritis (*Critical Path Method* / CPM)

Metode Jalur Kritis (CPM) adalah teknik pemodelan jadwal proyek matematis untuk mengidentifikasi urutan aktivitas terpanjang yang menentukan durasi total proyek:

#### A. Karakteristik Utama Jalur Kritis
- Jalur kritis adalah rangkaian tugas dengan nilai kelonggaran waktu (*float* atau *slack*) sama dengan nol ($	ext{Float} = 0$).
- Keterlambatan satu hari pada aktivitas yang berada di jalur kritis akan langsung menyebabkan keterlambatan satu hari pada penyelesaian seluruh proyek.
- Proyek dapat memiliki lebih dari satu jalur kritis, yang meningkatkan risiko kompleksitas manajemen jadwal.

#### B. Konsep Kelonggaran Waktu (*Float / Slack Time*)
- **Float/Slack**: Jumlah waktu suatu tugas dapat ditunda tanpa memengaruhi tanggal penyelesaian tugas berikutnya atau tanggal akhir proyek.
- Rumus dasar kelonggaran waktu:
  $$	ext{Float} = 	ext{Late Start} - 	ext{Early Start} = 	ext{Late Finish} - 	ext{Early Finish}$$

#### C. Lima Langkah Membangun Jalur Kritis
1. Daftarkan seluruh aktivitas dan tugas proyek yang bersumber dari WBS.
2. Petakan dependensi dan urutan logis antar tugas (identifikasi tugas pendahulu / *predecessors*).
3. Buat diagram jaringan proyek (*network diagram*).
4. Lakukan perhitungan maju (*Forward Pass*) untuk menentukan waktu mulai/selesai tercepat (*Early Start / Early Finish*).
5. Lakukan perhitungan mundur (*Backward Pass*) untuk menentukan waktu mulai/selesai terlambat (*Late Start / Late Finish*) dan hitung nilai float.

---

### 4. Penjadwalan Visual: Gantt Chart dan Kanban Board (*Visual Scheduling*)

Memilih representasi visual yang tepat untuk mendukung pemantauan dan kolaborasi harian:

#### A. Bagan Gantt (*Gantt Chart*)
- Representasi grafis batang horizontal yang memetakan daftar tugas pada sumbu vertikal dan garis waktu kalender pada sumbu horizontal.
- Menampilkan panjang durasi, tumpang tindih aktivitas, tonggak capaian (*milestone diamonds*), dan panah dependensi antar tugas secara gamblang.
- Sangat ideal untuk pelaporan status kepada pemangku kepentingan dan pengelolaan proyek prediktif (*Waterfall*).

#### B. Papan Kanban (*Kanban Board*)
- Alat visualisasi aliran kerja (*workflow*) berbasis kolom status (misal: *To Do*, *In Progress*, *In Review*, *Done*).
- Menggunakan batas kerja dalam proses (*Work In Progress / WIP Limits*) untuk mencegah hambatan (*bottlenecks*) dan membatasi *multitasking* yang berlebihan.
- Mendukung pembaruan status harian yang dinamis dan fleksibel pada proyek adaptif (*Agile*).

---

### 5. Lima Praktik Terbaik dalam Membangun Rencana Proyek (*Project Plan Best Practices*)

Pedoman teruji Google dalam memastikan rencana proyek dapat dieksekusi secara realistis:
1. **Meninjau Deliverable dan Milestone Secara Teliti (*Careful Review*)**: Pastikan seluruh deliverable memiliki kriteria penerimaan yang jelas sebelum diturunkan menjadi tugas operasional.
2. **Memberikan Waktu yang Cukup untuk Merencanakan (*Give Yourself Time to Plan*)**: Jangan terburu-buru memulai eksekusi sebelum fondasi rencana dan dependensi dipahami dengan baik.
3. **Mengakui dan Merencanakan Hal yang Tak Terduga (*Plan for the Inevitable*)**: Sisipkan cadangan waktu (*buffer*) dan kontinjensi untuk mengantisipasi ketidakhadiran tim atau kendala teknis.
4. **Tetap Ingin Tahu dan Banyak Bertanya (*Stay Curious*)**: Diskusikan secara mendalam bersama pakar teknis (*subject matter experts*) mengenai asumsi-asumsi tersembunyi.
5. **Berkomunikasi Secara Konsisten (*Communicate Constantly*)**: Validasi rencana proyek bersama seluruh pemangku kepentingan kunci dan minta persetujuan resmi (*sign-off*) sebelum baseline dikunci.
