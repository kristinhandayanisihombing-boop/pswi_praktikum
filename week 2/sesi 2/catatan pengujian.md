1. Pemeriksaan DevTools

| Pemeriksaan |Bukti yang dicatat |Hasil
| Bahasa dokumen | Elemen `<html>` mempunyai `lang="id"` | Lulus |
| Judul halaman | `<title>` tampil pada tab browser | Lulus |
| Hierarki heading | Terdapat h1, h2, dan h3 dengan urutan logis | Lulus |
| Landmark | header, nav, main, section, article, aside, footer ditemukan | Lulus |
| Navigasi | href seperti `#tentang` mempunyai id tujuan yang sesuai | Lulus |

Jika elemen semantik diganti dengan div, apakah arti setiap bagian masih langsung terlihat dari nama elemennya?
Tidak. Jika semua bagian menggunakan `div`, nama elemen tersebut tidak langsung menjelaskan fungsi atau arti bagian halaman. Elemen semantik seperti `header`, `nav`, `main`, `section`, `article`, `aside`, dan `footer` membuat struktur halaman lebih mudah dipahami oleh browser, mesin pencari, pembaca layar, dosen, dan pengembang.


 
`main` digunakan untuk menandai isi utama yang khas dari sebuah halaman.

 3. Mengapa menggunakan section?

`section` digunakan untuk mengelompokkan isi berdasarkan topik tertentu dan sebaiknya mempunyai heading.

 4. Mengapa menggunakan article?

`article` digunakan untuk bagian konten yang masih masuk akal jika dibaca secara terpisah, misalnya berita atau artikel.

 5. Mengapa menggunakan heading secara berurutan?

Heading digunakan berdasarkan struktur isi, bukan berdasarkan ukuran tulisan. `h1` menjelaskan halaman, `h2` menjelaskan bagian utama, dan `h3` menjadi subbagian dari `h2]

Validasi HTML

Validator dilakukan menggunakan W3C Nu HTML Checker.

**Sebelum perbaikan:** Jika validator menemukan error, error dicatat berdasarkan pesan dan nomor baris yang diberikan validator.

**Sesudah perbaikan:** Kode diperiksa kembali sampai tidak ada error yang berasal dari kode sendiri.

> Catatan: tangkapan layar hasil validator harus diambil sendiri setelah file `index.html` dijalankan dan divalidasi

AI Statement:
saya menggunakan AI pada tugas ini untuk memberi pemahaman dalam instruksi praktikum 