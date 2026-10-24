NAMA: KRISTIN HANDAYANI SIHOMBING
NIM : 41426025
PRODI: D4 TEKNOLOGI REKAYSA PERANGKAT LUNAK (trpl2)

peran id, name, dan type pada README
1. Peran id: Sebagai penerapan dan penggabungan kepada label web yang dibuat,dan untuk menargetkan setiap elemen yang dibuat
percobaan yang saya buat: mengubah nama mmenjadi namE, dan yang terjadi yaitu kolom tidak dapat diiisi.
2. name: berfungsi sebagai identifikasi data formulir yang dikirimkan ke server, misalnya saya mengetik nama saya, email, prodi dll. Ketika saya sudah mengisi tabel formulir tersebut maka <name> tersebut akan mengirimkannya ke server
tanpa kita membuat name maka data yang kita input tidak akan diproses.
3. peran type : berfungsi untuk menentukan jenis kotak input dan format data yang bisa dimasukkan oleh pengguna.
Misalnya kotak pengisian nama dan email yang dibuat kotak input sebagai tempat yang diisi oleh pengguna
4. Query URL : bagian dari alamat web yang digunakan untuk mengirim data atau parameter tambahan ke server, yang diakhiri oleh tanda (?)  <http://127.0.0.1:5500/sesi%202/index.html?nama=kristin

5. nama-nilai yang terlihat: <nama=kristin+baik&email=hayolo2m2%40gmail.com&prodi=trpl&mode=luring&catatan=

6. Eksperiman pada deevtools bagian console saya uji coba dengan menghapus name,dan sesuai dengan tabel dan pasangan kontrol tidak tampil. Saya mengetik kode yang pertama <const form = document.querySelector("form");> lalu melanjut  [...new FormData(form).entries()];

7. Hasil dari menambahkan input telepon dengan type tel, label, dan autocomplete tel.
   2 Tambahkan jumlah tiket dengan type number, min 1, max 5, dan step 1.
   3 Tambahkan checkbox minat topik HTML dan Aksesibilitas dalam fieldset terpisah. Gunakan label berbeda dan value jelas
http://127.0.0.1:5500/pswi-week-03/sesi%202/index.html?nama=kristin+baik&email=hayolo2m2%40gmail.com&prodi=trpl&mode=luring&catatan=&telepon=089766e56546&tiket=3&minat=html
8. Validasi yang membuat error berada di line 12 <""> saya buat menjadi <"#">

<PENGGUNAAN AI>
Saya menngunakan AI untuk membantu pengerjaan seperti
-TAhapan dan proses pengerjaan
-Membantu mencari dimana error pada kode saya
- Membantu dalam pembentukan kodingan, seperti membuat telepon, tiket dll
-Membantu menjelaskan bagaimana cara pengerjaan tugas saya

<PERNYATAAN LAPORAN KEGIATAN>
• Telepon bukan number: Karena nomor telepon tidak dipakai untuk berhitung, butuh angka 0 di awal (yang akan hilang jika memakai tipe angka), dan sering mengandung karakter seperti + atau -.
• Beda Label vs Legend: Label adalah nama untuk satu kotak/tombol input, sedangkan Legend adalah judul untuk satu kelompok input (di dalam <fieldset>).
• Beda id vs name: id adalah identitas unik untuk CSS/JavaScript di browser, sedangkan name adalah nama variabel data yang dikirim ke server backend.
• Checkbox tidak dicentang: Datanya tidak dikirim sama sekali ke server saat formulir disubmit (namanya tidak akan muncul di backend).
