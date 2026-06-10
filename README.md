# SIRT-GWK-Sistem-Informasi-Restoran-Terpadu-Gubug-Watu-Kali-
SIRT GWK adalah prototype sistem informasi restoran berbasis Streamlit untuk Gubug Watu Kali yang berfokus pada digitalisasi input pesanan, tampilan antrean kitchen/bar, monitoring operasional, laporan, dan akses pengguna berdasarkan role.

Prototype SIRT GWK terdiri dari beberapa halaman utama yang dirancang sesuai kebutuhan operasional Gubug Watu Kali. Setiap halaman memiliki fungsi yang berbeda dan disesuaikan dengan role pengguna.

1. Login Page

Login Page merupakan halaman awal aplikasi. Pengguna dapat masuk ke sistem menggunakan username dan password yang sudah terdaftar. Selain login, halaman ini juga menyediakan fitur pendaftaran akun baru. Pada saat membuat akun, pengguna dapat memilih role sesuai tugasnya, seperti Owner, Manager, Kasir, Waiter, atau Kitchen/Bar.

Halaman login dibuat dengan tampilan split layout. Bagian kiri menampilkan identitas SIRT GWK dengan nuansa hijau gelap, sedangkan bagian kanan berisi form masuk sistem dan daftar akun baru. Tujuan desain ini adalah agar halaman login terlihat profesional, tetapi tetap mudah digunakan.

2. Executive Dashboard

Executive Dashboard digunakan oleh Owner dan Manager untuk melihat ringkasan performa restoran. Dashboard ini menampilkan informasi seperti total nilai order, jumlah order yang masuk, jumlah order selesai, order yang masih menunggu, dan order yang sedang diproses.

Pada halaman ini juga terdapat grafik garis untuk melihat perkembangan performa dari waktu ke waktu. Jika terdapat kenaikan performa, indikator ditampilkan dengan warna hijau. Jika terjadi penurunan, indikator ditampilkan dengan warna merah. Hal ini membantu Owner dan Manager memahami kondisi operasional restoran secara cepat.

3. Pintu POS Order

Pintu POS Order digunakan untuk mencatat pesanan pelanggan secara digital. Halaman ini menggantikan proses pencatatan pesanan manual yang sebelumnya menggunakan nota kertas tiga rangkap.

Pada halaman ini, pengguna dapat memilih meja atau lokasi pelanggan, memilih tipe layanan seperti Ala Carte atau Prasmanan, memilih kategori menu, mengatur jumlah pesanan, menambahkan catatan khusus, dan memasukkan item ke dalam Ringkasan Cart. Setelah pesanan sudah benar, pengguna dapat menekan tombol Submit Order.

Setelah order dikirim, sistem akan menyimpan data pesanan dan meneruskannya ke Antrean Kitchen Board. Dengan demikian, kitchen atau bar dapat langsung melihat pesanan yang masuk tanpa perlu menunggu kertas order fisik.

4. Antrean Kitchen Board

Antrean Kitchen Board adalah salah satu fitur utama dalam prototype. Halaman ini digunakan oleh Kitchen Staff atau Barista untuk melihat daftar pesanan yang masuk secara real-time.

Setiap pesanan menampilkan informasi seperti nomor order, meja, item pesanan, jumlah, catatan khusus, dan status pesanan. Kitchen atau bar dapat mengubah status pesanan menjadi Menunggu, Diproses, atau Selesai. Status ini membantu bagian operasional mengetahui pesanan mana yang belum dikerjakan, sedang dikerjakan, atau sudah selesai.

Fitur ini menjadi jawaban atas masalah utama restoran, yaitu penggunaan kertas karbon tiga rangkap yang kurang efisien. Dengan Kitchen Board, proses distribusi order menjadi lebih cepat, lebih rapi, dan lebih mudah dipantau.

5. Pengeluaran & Closing

Halaman Pengeluaran & Closing digunakan untuk mencatat pengeluaran operasional dan melakukan closing shift. Pada tab Input Pengeluaran, pengguna dapat mencatat tanggal, kategori biaya, nominal, metode pembayaran, dan keterangan pengeluaran.

Pada tab Closing Shift, pengguna dapat mencatat rekap akhir shift atau akhir hari. Data closing membantu restoran mengetahui kondisi operasional per periode tertentu. Fitur ini mendukung kebutuhan pencatatan laporan harian agar lebih rapi dibandingkan proses manual.

6. Laporan Terinci

Halaman Laporan Terinci digunakan untuk melihat data operasional dalam bentuk tabel dan ringkasan. Laporan yang tersedia mencakup laporan order, laporan menu, laporan pengeluaran, dan laporan closing.

Pengguna dapat menggunakan filter tanggal untuk melihat data pada periode tertentu. Laporan juga dapat diunduh dalam format tertentu, seperti CSV atau Excel, sehingga dapat digunakan sebagai dokumentasi atau bahan evaluasi.

7. Perbandingan Laju

Halaman Perbandingan Laju digunakan untuk membandingkan performa restoran antara dua periode. Owner dan Manager dapat memilih dua periode yang berbeda, kemudian sistem akan menampilkan perbandingan performa dalam bentuk metrik dan grafik garis.

Fitur ini membantu manajemen mengetahui apakah performa restoran mengalami kenaikan atau penurunan. Dengan begitu, pengambilan keputusan dapat dilakukan berdasarkan data, bukan hanya berdasarkan perkiraan.

8. Konfigurasi Sistem

Konfigurasi Sistem digunakan untuk mengelola data dasar aplikasi. Pada halaman ini, Manager atau Owner dapat mengelola menu, user, role, activity log, dan analytics snapshot.

Fitur pengelolaan menu memungkinkan data makanan dan minuman diperbarui jika terdapat perubahan harga atau status ketersediaan. Fitur User & Role memungkinkan pengelolaan akun pengguna sesuai hak akses masing-masing. Activity Log digunakan untuk memantau jejak aktivitas pengguna dalam sistem.

9. Data & Backup

Halaman Data & Backup digunakan untuk mengunduh data dan melakukan clear data jika diperlukan. Pengguna dapat mengunduh data order atau database backup. Fitur Clear Data dilengkapi dengan konfirmasi agar pengguna tidak menghapus data secara tidak sengaja.

Halaman ini penting untuk mendukung kebutuhan dokumentasi data dan simulasi ulang prototype.
