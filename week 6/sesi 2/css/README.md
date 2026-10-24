Nama: Kristin HAndayani Sihombing
NIM: 41426025
Prodi: D4 TEKNOLOGI REKAYASA PERANGKAT LUNAK

1. <Mobile-First
Saya memulai tampilan dari layar kecil dengan ukuran 320px agar website tetap nyaman digunakan di HP.
<meta name="viewport" content="width=device-width, initial-scale=1">
Kegunaan: width=device-width menyesuaikan lebar viewport dengan perangkat, sedangkan initial-scale=1 mengatur skala awal halaman.

.catalog {
  display: grid;
  grid-template-columns: 1fr;
  gap: 1rem;
}

<Kegunaan:
display: grid menyusun katalog menggunakan Grid.
grid-template-columns: 1fr membuat satu kolom.
gap: 1rem memberi jarak antaritem.
Hasil: Katalog menggunakan satu kolom sebagai tampilan dasar untuk layar kecil.

2.  <Media Query

@media (min-width: 48rem) {
  .catalog {
    grid-template-columns: repeat(2, 1fr);
  }
}

<Kegunaan: @media mengatur CSS berdasarkan kondisi viewport. min-width: 48rem menentukan batas minimal, sedangkan repeat(2, 1fr) membuat dua kolom dengan lebar sama.
Hasil: Dengan asumsi 1rem = 16px, pada 767px katalog satu kolom, sedangkan mulai 768px katalog menjadi dua kolom.

3. <Navigasi dan Form

.nav-list {
  display: flex;
  flex-wrap: wrap;
  gap: .75rem;
}

input, select, textarea {
  max-width: 100%;
}
<Kegunaan: display: flex menyusun navigasi, flex-wrap: wrap memungkinkan navigasi turun ke baris berikutnya, dan gap memberi jarak. max-width: 100% membatasi lebar elemen form agar tidak melebihi wadah.
Hasil: Navigasi dan form diperiksa agar tetap muat pada layar kecil. Saya juga menguji fokus keyboard menggunakan tombol Tab.

4. <Mengatur Lebar Kartu

.card {
  min-width: 0;
}

<Kegunaan: Memungkinkan kartu menyusut mengikuti ruang yang tersedia sehingga membantu mencegah layout melebar.
Hasil: Saya memeriksa apakah kartu tetap berada dalam wadahnya pada berbagai ukuran layar.

5. <Pengujian Viewport dan Overflow

Saya menguji viewport 320px, 768px, dan 1200px serta zoom 200%. Saya juga mencoba width: 900px pada sebuah elemen untuk melihat dampaknya terhadap layar kecil.
<Kegunaan width: 900px pada percobaan ini adalah membuat lebar tetap untuk menemukan masalah overflow. Setelah pengujian, aturan tersebut diperbaiki agar supaya elemen menyesuaikan ruang yang tersedia.
Hasil: Saya membandingkan tampilan sebelum dan sesudah perbaikan serta memeriksa apakah masih ada scroll horizontal yang tidak diperlukan.
Menguji Keyboard dan Fokus

<Saya mencoba menggunakan tombol Tab dan Shift + Tab untuk berpindah dari satu kolom ke kolom lainnya. Saya juga mencoba menggunakan keyboard untuk memilih pilihan dan mengirim form.
Pada bagian CSS, saya menggunakan :focus-visible supaya elemen yang sedang dipilih dengan keyboard mempunyai tanda fokus yang terlihat.

6. <Latihan Mandiri

Uji layar 320px: Saya memeriksa apakah katalog dan navigasi masih terlihat. Tujuannya memastikan website dapat digunakan di layar kecil.
Uji breakpoint: Saya membandingkan 767px, 768px, dan 769px untuk melihat perubahan jumlah kolom.
Uji teks panjang: Saya menambahkan teks panjang pada kartu untuk memeriksa apakah teks menyebabkan layout melebar.
Uji zoom 200%: Saya memeriksa apakah konten tetap bisa dibaca dan digunakan saat diperbesar.
Uji overflow: Saya mencoba lebar 900px, mengamati masalahnya, memperbaiki CSS, lalu menguji kembali halaman.

7. <Kesimpulan

Dari praktikum ini, saya jadi lebih paham cara membuat form yang benar dan cara memeriksa apakah data yang dimasukkan sudah sesuai. Saya juga belajar kalau setiap kolom harus punya label dan petunjuk yang jelas supaya pengguna tidak bingung. Selain itu, saya mencoba menggunakan keyboard untuk berpindah antar kolom. Dari sini saya sadar bahwa hal kecil seperti validasi dan fokus juga penting saat membuat sebuah website.

8. <AI Use Statement
Saya menggunakan AI untuk membantu memahami materi praktikum dan mencari penjelasan dari beberapa bagian kode yang belum saya pahami. Dari bantuan tersebut, saya belajar tentang validasi form dan aksesibilitas. Saya tetap memeriksa kembali kode dan hasilnya supaya sesuai dengan praktikum yang saya kerjakan.