Nmaa: Kristin Handayani Sihombing
NIM: 41426025
Prodi: D4 Teknologi Rekayasa Perangkat Lunak


<Pada percobaan ini saya menggunakan index.html untuk membuat struktur halaman.
style.css digunakan untuk mengatur tampilan dan Flexbox.
main.js digunakan untuk JavaScript sederhana.
README.md digunakan untuk menjelaskan proses pengerjaan dan hasil pengujian.
Folder bukti digunakan untuk menyimpan screenshot hasil pengujian.

<AI Use Statement>
Dalam pengerjaan praktikum ini saya menggunakan AI sebagai bantuan untuk memahami materi Flexbox, membantu menjelaskan kode.
Saya tidak langsung menggunakan hasil dari AI tanpa mencoba. Saya tetap menjalankan kode sendiri melalui browser dan melakukan pengujian pada ukuran layar yang berbeda.

1. STARTER KATALOG
Pada bagian awal saya membuat halaman dengan navigasi dan tiga card.
Navigasi yang saya buat adalah:
<Kegiatan
Kontak>
Kemudian saya membuat tiga card:
-Lokakarya HTML
-Diskusi CSS
-Audit Web
Saya juga membuat link menggunakan #kegiatan dan #kontak, sehingga ketika link ditekan halaman akan menuju bagian yang sesuai

2. NAVIGASI FLEKSIBEL

<.nav-list { display: flex; flex-wrap: wrap; gap: 1rem;
 list-style: none; padding: 0;>
 
Saya mencoba mengubah <flex-direction> menjadi <column> untuk melihat perbedaannya.
Ketika menggunakan row, item navigasi tersusun ke arah samping.
Sedangkan ketika menggunakan column, item navigasi tersusun ke bawah.
Setelah mencoba keduanya, saya mengembalikannya menjadi row.
Saya juga mengecilkan ukuran browser untuk melihat apakah navigasi bisa menyesuaikan ketika ruangnya tidak cukup. Dengan flex-wrap: wrap, item bisa pindah ke baris berikutnya

3. <CARD FLEKSIBEL
Card dengan Flexbox
Dengan menggunakan flex-wrap, card dapat pindah ke baris berikutnya jika ukuran layar tidak cukup.
Saya kemudian menambahkan card keempat untuk melihat apakah semua card tetap bisa ditampilkan dengan baik.


4. <Pengujian Ukuran Layar
 <.cards { display: flex; flex-wrap: wrap; gap: 1rem; }
.card { flex: 1 1 15rem; padding: 1rem;
 border: 1px solid #ccd; min-width: 0; }>

<Saya melakukan pengujian pada dua ukuran layar, yaitu sekitar 1200px dan 360px.
Pada ukuran 1200px, ruang yang tersedia lebih besar sehingga card dapat tersusun lebih lebar.
Pada ukuran 360px, ruang lebih sempit sehingga card menyesuaikan dan berpindah ke baris berikutnya.
Dari percobaan ini saya bisa melihat bahwa Flexbox membantu membuat tampilan menjadi lebih 
fleksibel.

5. <KONTEN PANJANG DAN PENGUKURAN
Pengujian Judul Panjang
Saya juga mencoba memberikan judul yang lebih panjang pada salah satu card.
Setelah itu saya melihat bahwa tulisan yang panjang dapat turun ke baris berikutnya sehingga tidak keluar dari kotak card.
Saya juga mencoba zoom browser sampai 200% untuk melihat apakah masih ada informasi yang terpotong.

6. <Latihan Mandiri dan Matriks Uji
Kasus Normal
Kondisi:
Saya menjalankan halaman dengan ukuran layar normal dan card yang sudah dibuat.
Tindakan:
Saya membuka halaman melalui browser dan melihat susunan navigasi serta card.
Hasil:
Navigasi dan card tampil sesuai dengan yang dibuat.
status: berhasil
Kasus Batas
Kondisi:
Saya menggunakan ukuran layar 360px dan menampilkan empat card.
Tindakan:
Saya mengecilkan ukuran browser dan melihat apakah card masih bisa ditampilkan.
Hasil:
Card dapat berpindah ke baris berikutnya dan tidak keluar dari area halaman.
Status: Berhasil.
Kasus Gagal
Kondisi:
Saya mencoba mengubah bagian Flexbox untuk melihat apa yang terjadi jika pengaturan yang digunakan tidak sesuai.
Tindakan:
Saya mengubah pengaturan CSS, menjalankan halaman, lalu melihat hasilnya. Setelah menemukan masalah, saya mengembalikan pengaturan Flexbox dan melakukan pengujian lagi.
Hasil:
Setelah diperbaiki, tampilan kembali sesuai dan card dapat menyesuaikan ukuran layar.
Status: Berhasil setelah diperbaiki.

7. <Hasil Pengujian
Kasus:	Hasil
Ukuran 360px : Card dapat wrap
Ukuran 1200px	: Card tersusun dengan baik
Empat card	: Semua card dapat tampil
Judul panjang	: Tulisan tidak keluar dari card
Zoom 200%	 : Tampilan masih dapat dibaca

8. <Catatan Saat Menemukan Masalah>
Saat melakukan praktikum, saya tidak langsung menghapus semua kode ketika menemukan masalah.
Saya mencoba melihat bagian mana yang menyebabkan masalah. Misalnya, kalau CSS tidak berubah, saya mengecek apakah file CSS sudah terhubung dengan HTML.
Kalau card terlalu sempit atau tampilannya tidak sesuai, saya mengecek bagian flex, flex-wrap, dan ukuran card.
Untuk judul yang terlalu panjang, saya menggunakan overflow-wrap: anywhere.
Setelah melakukan perubahan, saya menjalankan kembali halaman untuk memastikan masalahnya sudah diperbaiki.

<Kesimpulan
Setelah mengerjakan praktikum ini, saya lebih memahami cara menggunakan Flexbox untuk membuat navigasi dan card.
Saya juga jadi lebih mengerti fungsi display: flex, flex-wrap, gap, dan flex.
Selain itu, saya belajar bahwa sebuah halaman web tidak cukup hanya terlihat bagus pada satu ukuran layar. Halaman juga perlu diuji pada ukuran layar yang berbeda supaya tampilannya tetap bisa digunakan.




