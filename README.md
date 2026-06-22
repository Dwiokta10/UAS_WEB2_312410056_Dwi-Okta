# Projek UAS PEMROGRAMAN WEB 2 SEMESTER 4
|                |                    |
| -------------- | ------------------ |
|      _Nama_    | Dwi Okta Ramadhani |
|      _NIM_     |      312410056     |
|     _Kelas_    |      TI.24.A1      |
|  _Mata Kuliah_ | Pemrograman Web 2  |
| _Dosen Pengampu_ | Bapak Agung Nugroho, S.Kom., M.Kom. |
|  _Link Youtube_ | https://youtu.be/dRdA3LH-X_8 |

## Deskripsi Proyek

SI PENA (Sistem Inventaris Peralatan Pramuka) merupakan aplikasi berbasis web yang dirancang untuk membantu proses pengelolaan inventaris peralatan Pramuka secara digital. Sistem ini memudahkan administrator dalam melakukan pendataan perlengkapan Pramuka, pengelompokan kategori peralatan, pengelolaan stok, serta pencatatan histori barang masuk dan barang keluar secara terstruktur dan terdokumentasi.

Aplikasi ini dikembangkan sebagai proyek Ujian Akhir Semester (UAS) Mata Kuliah Pemrograman Web 2 dengan menerapkan konsep Decoupled Architecture, yaitu pemisahan antara Backend API dan Frontend SPA. Dengan arsitektur ini, sistem menjadi lebih fleksibel, mudah dikembangkan, dan mampu memberikan performa yang lebih baik dalam pengelolaan data inventaris.

Sistem informasi manajemen inventaris ini dibangun dengan arsitektur *Decoupled* (terpisah) untuk mendigitalisasi pencatatan aset institusi pendidikan, meliputi pendataan barang, kategori, serta histori barang masuk dan keluar.

## 🎯 Tujuan Pengembangan

Adapun tujuan dari pengembangan aplikasi SI PENA adalah:

Mempermudah proses pendataan inventaris peralatan Pramuka.
Menyediakan informasi stok barang secara cepat dan akurat.
Mengurangi risiko kesalahan pencatatan data inventaris.
Mendokumentasikan aktivitas barang masuk dan barang keluar secara sistematis.
Membantu administrator dalam melakukan pengelolaan dan monitoring inventaris.
Mendukung digitalisasi administrasi kegiatan kepramukaan.

## 🛠 Teknologi Utama
- **Backend:** CodeIgniter 4 (RESTful API, Resource Controller, Filters untuk Token/CORS)
- **Frontend:** VueJS 3 (SPA, Vue Router), Axios (Interceptors)
- **UI:** TailwindCSS via CDN
- **Database:** MySQL

##  Panduan Instalasi
1. **Backend:** Buka terminal pada direktori `backend-api`, sesuaikan koneksi database di `.env`, lalu jalankan `C:\xampp\php\php.exe spark serve`.
2. **Frontend:** Buka direktori `frontend-spa` dan jalankan `index.html` menggunakan Live Server.
3. Akses aplikasi melalui browser dan login sebagai Administrator.

## Dokumentasi Visual

### 1. Skema Relasi Database
![Relasi Database](docs/relasi_db.png)

### 2. Keamanan API (Uji Coba Error 401 via Postman)
![Error 401 Postman](docs/error_401.png)

### 3. Halaman Login
![Halaman Login](docs/login.png)

### 4. Halaman Dashboard Admin
![Dashboard Admin](docs/dashboard.png)

### 5. Visualisasi Tabel Data 
![Tabel Data](docs/tabel_data.png)

### 6. Form Modal Interaktif (Tambah/Edit)
![Form Modal](docs/form_modal.png)

Demikian proyek **SI PENA (Sistem Inventaris Peralatan Pramuka)** yang dikembangkan sebagai pemenuhan tugas Ujian Akhir Semester (UAS) Mata Kuliah Pemrograman Web 2 Tahun Akademik 2026.

Penulis menyadari bahwa aplikasi ini masih memiliki keterbatasan dan kekurangan. Oleh karena itu, kritik dan saran yang membangun sangat diharapkan sebagai bahan evaluasi dan pengembangan sistem di masa mendatang.

Ucapan terima kasih disampaikan kepada Bapak Agung Nugroho, S.Kom., M.Kom. selaku dosen pengampu Mata Kuliah Pemrograman Web 2 yang telah memberikan ilmu, arahan, dan bimbingan selama proses perkuliahan serta pengerjaan proyek ini.

Semoga aplikasi yang dikembangkan dapat memberikan manfaat dan menjadi salah satu bentuk implementasi ilmu yang telah diperoleh selama perkuliahan.

Terima kasih.
