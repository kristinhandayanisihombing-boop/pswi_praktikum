Nama: Kristin Sihombing
NIM: 41426025
Prodi: D4 TEKNOLOGI REKAYASA PERANGKAT LUNAK

 1. Tujuan Praktikum

Pada praktikum minggu ini, saya belajar tentang desain web responsif. Saya belajar bagaimana membuat tampilan website supaya bisa menyesuaikan ukuran layar, mengatur ukuran tulisan dan gambar, serta membuat tampilan card menyesuaikan ukuran container.

2. Yang Saya Kerjakan
<A. Fluid Font

Pada bagian ini, saya menggunakan `clamp()` untuk mengatur ukuran tulisan pada judul. Dengan cara ini, ukuran judul bisa menyesuaikan ukuran layar, tetapi tetap memiliki batas ukuran minimum dan maksimum.
<h1 { font-size: clamp(1.75rem, 1.2rem + 2vw, 3rem); }

Fungsinya adalah membuat ukuran teks judul (h1) menjadi dinamis dan responsif, artinya ukuran tulisan akan membesar atau mengecil secara halus mengikuti lebar layar, namun tetap memiliki batas aman agar tidak kekecilan atau kebesaran.

<Fungsi clamp() menerima tiga argumen penting:

• 1.75rem (Batas Minimum): Ukuran terkecil teks judul. Teks tidak akan pernah lebih kecil dari ini, meskipun dibuka di ponsel yang sangat kecil.
• 1.2rem + 2vw (Ukuran Ideal): Formula yang membuat teks berubah secara fleksibel. 2vw artinya ukuran teks akan bertambah seiring bertambahnya lebar layar (Viewport Width).
• 3rem (Batas Maksimum): Ukuran terbesar teks judul. Teks tidak akan pernah lebih besar dari ini, meskipun dibuka di monitor komputer yang sangat lebar.

.card-wrap { container-type: inline-size; }

<Fungsinya adalah mendaftarkan sebuah elemen (dalam hal ini kelas .card-wrap) sebagai sebuah "Wadah Utama" (Container).
• Dengan kode ini, browser akan memantau ukuran lebar (inline-size) dari elemen .card-wrap itu sendiri, bukan memantau ukuran layar browser secara keseluruhan. Ini adalah fondasi awal sebelum kita bisa menggunakan fitur Container Queries.
ode yang digunakan:

img {
    max-width: 100%;
    height: auto;
}

Kode ini digunakan supaya gambar tidak melebihi lebar tempatnya dan ukuran gambar tetap sesuai dengan rasio aslinya.
Hasil yang saya harapkan: gambar bisa menyesuaikan ukuran layar tanpa terlihat melebar atau gepeng.

<B. Responsive Image

img {
    max-width: 100%;
    height: auto;
}

Kode ini digunakan supaya gambar tidak melebihi lebar tempatnya dan ukuran gambar tetap sesuai dengan rasio aslinya.
Hasil yang saya harapkan: gambar bisa menyesuaikan ukuran layar tanpa terlihat melebar atau gepeng.
Saya mengatur gambar menggunakan CSS supaya gambar tidak keluar dari area yang sudah disediakan. Saya juga mempelajari penggunaan `srcset` dan `sizes` untuk membantu browser memilih gambar yang sesuai.  Dalam pembuatan gambar saya mengatur fotomenjadi 320px dan 640 px
penyesuaian ukuran gambar diatur oleh srcset dan sizes

<C. Container Query

Kode yang digunakan:

.card-wrap {
    container-type: inline-size;
}

@container (min-width: 30rem) {
    .card {
        padding: 1.5rem;
    }
}

Pada bagian ini, saya belajar bahwa container query mengatur tampilan berdasarkan lebar container, bukan hanya berdasarkan ukuran layar. Jika container memenuhi ukuran yang ditentukan, padding pada card akan berubah.
Pada bagian ini, saya menambahkan class `card-wrap` pada bagian yang membungkus card. Saya menggunakan `container-type: inline-size` agar container bisa menjadi acuan untuk aturan Container Query.
Saya juga menggunakan `@container` untuk mengatur padding card berdasarkan lebar container.

<D. Reduced Motion

Pada bagian ini, saya mempelajari cara mengatur tampilan website untuk pengguna yang memilih mengurangi gerakan atau animasi. Saya menggunakan `prefers-reduced-motion` pada CSS.

3. Pengujian
Saya melakukan pengujian pada beberapa bagian website untuk melihat apakah kode yang dibuat sudah berjalan sesuai dengan fungsinya.
- Memeriksa ukuran judul pada tampilan website.
- Memeriksa apakah gambar menyesuaikan area tampilannya.
- Memeriksa aturan Container Query pada card.
- Memeriksa pengaturan Reduced Motion.

<Pengujian :Hasil yang Diharapkan
Memeriksa gambar : Gambar berhasil dimuat
Mengubah ukuran layar: Gambar dan teks tetap menyesuaikan
Mengubah lebar container :Container query bekerja sesuai kondisi
Zoom browser: Teks tetap terbaca dan halaman tetap bisa digunakan
Reduced motion: Transisi berkurang tanpa menghilangkan fungsi

4. Kendala yang Saya Temui

Kendala yang saya alami adalah memahami cara kerja Container Query dan cara mengujinya. Saya masih perlu memahami bagian mana yang harus diubah untuk melihat perbedaan tampilan card.

Untuk mengatasinya, saya mempelajari kembali kode CSS dan mencoba memahami fungsi setiap aturan yang digunakan.

<Bagian materi	Kegunaannya
meta viewport	index.html → bagian <head>	Membuat halaman mengikuti lebar layar perangkat
srcset dan sizes	index.html → pada tag <img>	Membantu browser memilih sumber gambar
max-width: 100%; height: auto;	css/style.css	Menjaga gambar menyesuaikan lebar wadah
clamp()	css/style.css:	Membuat ukuran teks fleksibel
@media	css/style.css:	Mengubah tata letak sesuai lebar layar
container-type dan @container	css/style.css :	Menyesuaikan gaya berdasarkan lebar wadah
prefers-reduced-motion	css/style.css :	Mengurangi animasi jika pengguna memilih preferensi tersebut

 5. Kesimpulan

Dari praktikum ini, saya belajar bahwa membuat website responsif bukan hanya mengatur tampilan berdasarkan ukuran layar. Saya juga belajar mengatur ukuran tulisan, gambar, dan card supaya tampilannya lebih sesuai. Saya masih perlu berlatih agar lebih memahami fungsi setiap kode CSS yang digunakan.

6. AI Use Statement

Saya menggunakan AI sebagai alat bantu untuk memahami materi dan fungsi beberapa kode CSS yang digunakan dalam praktikum. Penjelasan dari AI membantu saya memahami langkah pengerjaan, tetapi saya tetap perlu memeriksa kode dan hasilnya sendiri.

 7. Bukti Praktikum

Screenshot yang akan saya lampirkan:

1. Tampilan website.
2. Tampilan website pada ukuran layar berbeda.
3. Hasil pengujian gambar responsif.
4. Hasil pengujian Container Query.
5. Hasil pengujian Reduced Motion.

8. Penambahan foto pada 