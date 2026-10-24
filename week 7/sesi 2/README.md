Nama: Kristin Sihombing
NIM: 41426025
Prodi: D4 TRPL


<Pada praktikum Week 7 Sesi 2, saya mengerjakan integrasi beberapa halaman website agar dapat saling terhubung melalui navigasi. Saya juga mempelajari cara menggunakan satu file CSS untuk beberapa halaman supaya tampilannya tetap konsisten.
Selain itu, praktikum ini mengajarkan cara memeriksa tautan, lokasi file gambar, dan stylesheet. Website perlu diuji melalui browser untuk mengetahui apakah setiap halaman dapat dibuka dengan benar. Saya juga mempelajari penggunaan Git untuk mencatat perubahan kode dan memahami proses branch, merge, serta review.

<Penjelasan Perubahan yang Dikerjakan
Pada praktikum ini, perubahan yang perlu diperiksa dan didokumentasikan meliputi:
Penyiapan halaman Beranda, Kegiatan, dan Daftar.
Penambahan navigasi pada setiap halaman.
Penggunaan satu stylesheet bersama.
Penyesuaian path stylesheet dan gambar.
Penyesuaian penanda halaman aktif menggunakan aria-current.
Pemeriksaan tampilan pada ukuran layar berbeda.
Perbaikan kesalahan yang ditemukan selama pengujian.


<Fitur Website

Website ini memiliki beberapa fitur utama:
1. Halaman Beranda (index.html)
   Menampilkan informasi utama mengenai Komunitas Web Mahasiswa.
2. Halaman Kegiatan (kegiatan.html)
   Menampilkan jadwal kegiatan komunitas dalam bentuk tabel yang berisi tanggal, nama kegiatan, tempat, dan status kegiatan.
3. Halaman Kontak dan Pendaftaran (kontak&daftar.html)
   Menampilkan informasi sekretariat, alamat email, nomor telepon, jam layanan, dan formulir pendaftaran kegiatan.
4. CSS Eksternal (css/style.css)
   Digunakan untuk mengatur tampilan halaman agar lebih rapi dan konsisten.

   <Hasil Audit Website Komunitas Web Mahasiswa
1. Halaman Beranda (index.html)
- Kasus: Membuka halaman Beranda.
- Harapan: Halaman dapat dibuka dengan benar dan menampilkan informasi komunitas.
- Hasil nyata: Halaman dibuat menggunakan HTML. Tampilan akhirnya perlu diperiksa melalui browser.
- Status: Perlu diuji.
- Kasus: Memuat CSS eksternal.
- Harapan: Tampilan halaman mengikuti aturan dalam css/style.css.
- Hasil nyata: File HTML menggunakan pemanggilan CSS eksternal.
- Status: Sesuai kode, perlu diuji di browser.
- Kasus: Menggunakan navigasi menuju halaman Kegiatan dan Kontak.
- Harapan: Setiap tautan membuka halaman yang sesuai.
- Hasil nyata: Keberhasilan navigasi bergantung pada alamat tautan dan nama file yang digunakan.
- Status: Perlu diuji.
2. Halaman Kegiatan (kegiatan.html)
- Kasus: Membuka halaman Kegiatan.
- Harapan: Judul dan jadwal kegiatan dapat ditampilkan dengan baik.
- Hasil nyata: Kode HTML sudah memuat judul dan tabel jadwal kegiatan.
- Status: Sesuai kode, perlu diuji di browser.
- Kasus: Menampilkan tabel jadwal kegiatan.
- Harapan: Tabel memiliki empat kolom, yaitu tanggal, kegiatan, tempat, dan status, serta empat baris data.
- Hasil nyata: Kode yang diperbaiki sudah memiliki empat kolom dan empat baris data kegiatan.
- Status: Sesuai kode.
- Kasus: Menampilkan desain tabel menggunakan CSS.
- Harapan: Tabel memiliki garis, jarak antarkonten, dan tampilan yang rapi.
- Hasil nyata: File CSS sudah dipanggil, tetapi tampilan tabel bergantung pada aturan CSS yang digunakan.
- Status: Perlu diuji.
- Kasus: Menggunakan navigasi ant halaman.
- Harapan: Menu Beranda dan Kontak dan Daftar dapat membuka halaman tujuan.
- Hasil nyata: Tautan sudah ditulis dalam kode, tetapi perlu diperiksa apakah nama file dan alamat tautannya cocok.
- Status: Perlu diuji.
3. Halaman Kontak dan Pendaftaran (kontak&daftar.html)
- Kasus: Membuka halaman kontak dan pendaftaran.
- Harapan: Informasi kontak dan formulir pendaftaran tampil dalam satu halaman.
- Hasil nyata: Kedua bagian sudah disusun dalam satu dokumen HTML.
- Status: Sesuai kode, perlu diuji di browser.
- Kasus: Menampilkan informasi kontak.
- Harapan: Alamat sekretariat, email, nomor telepon, dan jam layanan dapat dibaca.
- Hasil nyata: Informasi tersebut sudah ditulis dalam kode HTML.
- Status: Sesuai kode.
- Kasus: Mengirim formulir dalam keadaan kosong.
- Harapan: Browser menolak pengiriman jika kolom wajib belum diisi.
- Hasil nyata: Atribut required sudah digunakan pada kolom wajib.
- Status: Sesuai kode, perlu diuji di browser.
- Kasus: Memeriksa kode peserta.
- Harapan: Kode peserta harus terdiri dari enam angka.
- Hasil nyata: Atribut pattern="[0-9]{6}" sudah digunakan untuk memvalidasi format kode.
- Status: Sesuai kode.
- Kasus: Memeriksa jumlah tiket.
- Harapan: Jumlah tiket berada di antara satu sampai lima.
- Hasil nyata: Input sudah menggunakan atribut min="1" dan max="5".
- Status: Sesuai kode.
- Kasus: Memilih mode kehadiran.
- Harapan: Pengguna dapat memilih luring atau daring.
- Hasil nyata: Dua pilihan radio sudah tersedia dalam formulir.
- Status: Sesuai kode.
- Kasus: Menekan tombol Daftar.
- Harapan: Formulir dapat divalidasi dan data pendaftaran diproses.
- Hasil nyata: Formulir menggunakan action="#", sehingga belum mengirim dan menyimpan data ke server sungguhan.
- Status: Perlu pengembangan.
4. Validasi Semua Halaman
- Kasus: Memeriksa struktur HTML menggunakan validator.
- Harapan: Tidak ada error HTML yang belum diperbaiki.
- Hasil nyata: Kode sudah dirapikan, tetapi hasil validasi terbaru belum tersedia.
- Status: Belum diuji.
- Kasus: Memeriksa tampilan pada layar kecil.
- Harapan: Konten dapat dibaca dan tidak terpotong pada perangkat dengan layar kecil.
- Hasil nyata: Belum ada hasil pengujian pada berbagai ukuran layar.
- Status: Belum diuji.
- Kasus: Memeriksa seluruh tautan dan aset.
- Harapan: Semua tautan berfungsi dan CSS serta gambar dapat dimuat.
- Hasil nyata: Perlu dilakukan pemeriksaan langsung pada browser.
- Status: Belum diuji.

<AI STEATMENT>
Dalam proses pengerjaan proyek ini, ChatGPT digunakan sebagai alat bantu untuk memahami struktur HTML, menemukan kemungkinan penyebab error, memperbaiki penulisan kode, dan menyusun dokumentasi README.
Kode akhir tetap perlu diperiksa, dijalankan, dan divalidasi oleh mahasiswa. Penggunaan AI dicantumkan secara transparan sebagai bagian dari proses pengerjaan.
<Sumber dan Aset
Sumber referensi:
W3C Nu HTML Checker: https://validator.w3.org/nu/

<Kesimpulan

Melalui praktikum ini, saya mempelajari cara menyusun website multipage, menghubungkan halaman melalui navigasi, menggunakan CSS eksternal, membuat tabel jadwal, dan menyusun formulir pendaftaran.
Proyek ini juga membantu saya memahami pentingnya struktur HTML yang benar, validasi kode, pengujian fitur, dokumentasi, dan pencatatan perubahan sebelum website dikumpulkan.
