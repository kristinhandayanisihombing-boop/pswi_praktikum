Nama: KRistin HAndayani Sihombing
Prodi: D4 TRPL

1. <Penggunaan AI
Dalam mengerjakan praktikum ini, saya menggunakan AI untuk membantu memahami perintah Git, menjelaskan langkah-langkah pengerjaan, memberikan contoh petunjuk format formulir HTML.
Saya tetap perlu memeriksa kode, menjalankan pengujian, dan menyesuaikan dokumentasi dengan hasil pekerjaan yang benar-benar saya lakukan.
Materi yang saya pelajari dan dapatkan dari sesi # ini adalah bagaimanacra untuk git ke repository saya.

2. | Branch | Pekerjaan |
|---|---|
| `master` | Versi utama website |
| `fitur-petunjuk` | Memperbaiki petunjuk formulir |
| `perbaikan-kegiatan` | Memperbaiki halaman kegiatan |

3. git init → membuat repository untuk proyek.
git branch → melihat branch yang tersedia.
git switch → berpindah branch.
git add → menyiapkan perubahan file.
git commit → mencatat perubahan.
git merge → menggabungkan perubahan dari satu branch ke branch lain.

4. <branch berhasil dibuat
* fitur-petunjuk
  master
saya berhasil membuat branch fitur-petunjuk

<Commit awal berhasil
9546a3f Menyimpan kondisi awal proyek PSW
Git sudah menyimpan kondisi awal website saya.
Perintah git status berhasil
On branch fitur-petunjuk
nothing to commit, working tree clean
Artinya, tidak ada perubahan baru yang belum dicatat oleh Git.
Menggabungkan Branch

5. <Setelah perubahan fitur diperiksa dan siap digabungkan, saya berpindah ke branch utama terlebih dahulu.

git switch master
git merge fitur-petunjuk

Saya mempelajari bahwa merge dilakukan untuk menggabungkan perubahan dari branch fitur ke branch utama.

Sebelumnya, saya pernah menjalankan merge ketika masih berada di branch fitur-petunjuk dan mendapatkan pesan Already up to date. Dari percobaan tersebut, saya memahami bahwa saya perlu berpindah ke branch tujuan terlebih dahulu sebelum menjalankan merge.

Setelah merge, saya memeriksa kembali status dan riwayat commit menggunakan:

git status
git log --oneline --graph --all

6. Pengujian Website

Pengujian dilakukan untuk mengetahui apakah website dan formulir sudah berjalan sesuai harapan.
Hal-hal yang perlu saya uji adalah:
Halaman utama dapat dibuka melalui browser.
Navigasi antarhalaman dapat digunakan.
Halaman kegiatan dapat dibuka.
Halaman kontak dan pendaftaran dapat dibuka.
File CSS dan JavaScript dapat digunakan dengan baik.
Petunjuk format formulir tampil dengan jelas.
Kode peserta mengikuti format enam angka.
Alamat email mengikuti format yang benar.
Jumlah tiket mengikuti batas yang ditentukan.
Tidak terdapat error yang mengganggu fungsi website.
Perubahan kode tercatat dengan benar di Git.
Branch fitur berhasil digabungkan ke branch utama.

7. <Kendala yang Ditemukan

Kendala yang saya temukan adalah ketika menjalankan perintah merge pada branch fitur yang sedang aktif.

Saya menjalankan perintah:

git merge fitur-petunjuk

Kemudian muncul pesan Already up to date.

Dari kejadian tersebut, saya memahami bahwa saya harus berpindah ke branch utama terlebih dahulu agar perubahan dari branch fitur dapat digabungkan ke branch utama.

Perintah yang digunakan adalah:

git switch master
git merge fitur-petunjuk

Saya juga belajar bahwa sebelum melakukan commit, saya harus memeriksa perubahan kode terlebih dahulu agar perubahan yang disimpan sesuai dengan yang diinginkan.

8. <kesimpulan
<dari praktikum Week 7 Sesi 3 ini, saya belajar cara menggunakan Git untuk mengelola perubahan pada proyek website. Saya juga belajar membuat branch, melakukan commit, memeriksa perubahan kode, melakukan code review, dan menggabungkan branch.
Saya memahami bahwa penggunaan branch membantu memisahkan pengerjaan fitur dari branch utama. Selain itu, pemeriksaan kode sebelum commit dan merge penting dilakukan agar perubahan dapat diperiksa dengan baik.
Melalui praktikum ini, saya menjadi lebih memahami proses pengelolaan kode menggunakan Git dan pentingnya melakukan pengujian serta dokumentasi selama mengerjakan proyek website.




