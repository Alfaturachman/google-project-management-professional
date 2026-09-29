# Defining and Managing Project Scope

Dokumen ini memuat panduan komprehensif mengenai penentuan ruang lingkup proyek (*project scope*), identifikasi *in-scope* dan *out-of-scope*, pengendalian *scope creep*, serta penerapan *Triple Constraint Model* dalam pengambilan keputusan *trade-offs*.

---

## 1. Definisi dan Pentingnya Project Scope

*Project scope* adalah batas-batas yang disepakati secara resmi mengenai pekerjaan apa saja yang termasuk (*included*) dan tidak termasuk (*excluded*) dalam suatu proyek.

### Fungsi Utama Project Scope
* Memberikan batasan yang jelas bagi tim pelaksana, manajemen, dan *stakeholders*.
* Mengidentifikasi pihak penerima hasil proyek (*deliverable recipients*) serta pengguna akhir.
* Menentukan tingkat kompleksitas proyek, estimasi jadwal (*timeline*), kebutuhan anggaran (*budget*), dan alokasi sumber daya (*resources*).
* Memitigasi risiko pembengkakan biaya, keterlambatan jadwal, dan kegagalan hasil kerja akibat ketidakjelasan ekspektasi.

---

## 2. Pengumpulan Informasi untuk Menentukan Scope

Penetapan *scope* dilakukan sejak tahap awal inisiasi dan perencanaan melalui diskusi mendalam dengan *project sponsor* dan pemangku kepentingan.

### Pertanyaan Kunci Penentuan Scope (5W1H)
* **Stakeholders**: Dari mana asal usul permintaan proyek? Siapa yang memiliki wewenang menyetujui *scope* akhir?
* **Goals**: Apa alasan utama pelaksanaan proyek? Masalah apa yang ingin diselesaikan? Apa hasil akhir yang diharapkan?
* **Deliverables**: Produk, fitur, atau layanan apa saja yang secara spesifik harus dihasilkan? Bagian mana yang memerlukan pembaruan atau perombakan?
* **Resources**: Material, peralatan, dan tenaga kerja apa yang dibutuhkan? Apakah diperlukan vendor atau kontraktor eksternal? Apakah ada kebutuhan perizinan khusus?
* **Budget**: Berapa total anggaran yang dialokasikan? Apakah anggaran bersifat tetap (*fixed*) atau fleksibel?
* **Schedule**: Kapan batas waktu penyelesaian (*deadline*) proyek? Berapa lama durasi waktu yang tersedia?
* **Flexibility & Priorities**: Aspek mana yang menjadi prioritas utama: kepatuhan tenggat waktu (*time*), pembatasan biaya (*cost*), atau pemenuhan seluruh standar spesifikasi/kualitas (*quality/scope*)?

---

## 3. In-Scope, Out-of-Scope, dan Scope Creep

### A. In-Scope vs. Out-of-Scope
* **In-Scope**: Seluruh tugas, fitur, dan aktivitas yang disetujui secara tertulis untuk dikerjakan karena berkontribusi langsung pada pencapaian tujuan proyek.
* **Out-of-Scope**: Segala tugas, fitur, atau permintaan tambahan yang tidak termasuk dalam kesepakatan awal dan tidak didukung oleh alokasi anggaran maupun jadwal yang ada.

### B. Definisi Scope Creep
*Scope creep* adalah fenomena perubahan, perluasan, atau penambahan ruang lingkup pekerjaan secara tidak terkontrol yang terjadi setelah proyek dimulai.

### C. Sumber Utama Scope Creep
1. **Sumber Eksternal (*External Sources*)**
   * Permintaan perubahan mendadak dari klien atau pelanggan.
   * Pergeseran strategi bisnis organisasi atau perubahan tren pasar.
   * Perubahan pada teknologi atau regulasi eksternal.
   * Penyebab utama: Kebutuhan dan spesifikasi proyek yang tidak didefinisikan secara tegas sebelum penandatanganan kesepakatan.

2. **Sumber Internal (*Internal Sources*)**
   * Anggota tim pelaksana yang berinisiatif menambah fitur atau memodifikasi proses dengan alasan penyempurnaan kualitas tanpa persetujuan formal.
   * Modifikasi alur kerja oleh satu divisi yang berdampak pada peningkatan beban kerja divisi lain.
   * Dampak: Pemborosan jam kerja, peningkatan risiko operasional, dan gangguan terhadap jadwal keseluruhan.

---

## 4. Strategi Pengendalian Scope Creep

Penerapan praktik terbaik (*best practices*) untuk menjaga integritas ruang lingkup:

* **Dokumentasi Persyaratan Sejak Awal (*Define Requirements*)**: Mencatat seluruh kebutuhan fungsional dan teknis secara terperinci serta meminta konfirmasi tertulis dari *stakeholders*.
* **Penyusunan Jadwal yang Jelas (*Set a Clear Schedule*)**: Memetakan seluruh paket pekerjaan ke dalam linimasa tugas yang terstruktur.
* **Penetapan Batas *Out-of-Scope* Secara Eksplisit**: Mendokumentasikan hal-hal yang tidak akan dikerjakan agar seluruh pihak memiliki ekspektasi yang sama.
* **Penyediaan Solusi Alternatif (*Provide Alternatives*)**: Memberikan opsi pengganti beserta analisis dampak biaya-manfaat (*cost-benefit analysis*) ketika muncul usulan perubahan dari *stakeholders*.
* **Proses Kontrol Perubahan Formal (*Change Control Process*)**: Menetapkan alur baku pengajuan, evaluasi dampak, serta persetujuan resmi (*approval/rejection*) untuk setiap usulan perubahan.
* **Kemampuan Mengambil Sikap Tegas (*Learn to Say No*)**: Menolak penambahan tugas jika dinilai membahayakan anggaran, jadwal, atau kualitas inti proyek, disertai penjelasan berbasis data.
* **Pencatatan Biaya Tambahan (*Collect Costs for Out-of-Scope Work*)**: Menghitung secara transparan seluruh biaya langsung maupun tidak langsung yang timbul jika pekerjaan di luar lingkup harus disetujui.

---

## 5. Model Batasan Tiga Serangkai (*The Triple Constraint Model*)

*The Triple Constraint Model* (dikenal juga sebagai Segitiga Manajemen Proyek) adalah kerangka kerja yang menggambarkan hubungan saling ketergantungan antara tiga batasan utama proyek: **Scope**, **Time**, dan **Cost**, dengan **Quality** sebagai hasil integrasi ketiganya.

```
                  Quality
                /    |    \
               /     |     \
          Scope ---- + ---- Time
               \     |     /
                \    |    /
                   Cost
```

### Prinsip Kerja Triple Constraint
Ketiga elemen saling terikat secara dinamis. Perubahan pada salah satu elemen akan berdampak langsung pada satu atau kedua elemen lainnya:

* **Perluasan Scope**: Jika lingkup pekerjaan atau fitur bertambah, maka durasi pengerjaan harus diperpanjang (*increase time*) atau anggaran harus dinaikkan (*increase cost*) guna mempertahankan standar kualitas.
* **Pemangkasan Anggaran (Cost)**: Jika anggaran dikurangi, maka ruang lingkup pekerjaan harus dikurangi (*decrease scope*) atau jadwal penyelesaian harus diperpanjang (*extend time*).
* **Percepatan Jadwal (Time)**: Jika tenggat waktu dimajukan, maka anggaran harus ditambah untuk lembur/penambahan personel (*increase cost*) atau sebagian fitur/pekerjaan harus dipangkas (*reduce scope*).

### Pengambilan Keputusan *Trade-offs*
*Project manager* tidak dapat menetapkan ketiga batasan secara kaku tanpa kompromi. Manajer proyek harus berkolaborasi dengan *project sponsor* untuk menentukan batasan mana yang bersifat mutlak (*inflexible priority*) dan batasan mana yang dapat disesuaikan (*flexible trade-off*).
