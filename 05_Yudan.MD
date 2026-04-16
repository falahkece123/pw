Modul Pembelajaran: Dasar DOM dengan JavaScript Vanilla
Fondasi Web: HTML, CSS, dan JavaScript

Dalam pembuatan halaman web terdapat tiga komponen utama yang saling melengkapi:

HTML (Struktur) berfungsi sebagai kerangka dasar halaman web, seperti judul, paragraf, tombol, gambar, dan form.

CSS (Tampilan) digunakan untuk mengatur desain, warna, ukuran, dan tata letak agar halaman terlihat menarik.

JavaScript (Logika) berfungsi menambahkan interaksi dan fitur dinamis pada halaman web.Memahami DOM (Document Object Model)

DOM adalah representasi dokumen HTML dalam bentuk objek yang dibuat oleh browser. Dengan DOM, JavaScript dapat mengakses, membaca, dan memanipulasi elemen pada halaman web secara langsung.

Fungsi DOM antara lain:

Mengubah isi teks
Mengubah style atau atribut
Menambah atau menghapus elemen
Mengambil data dari input pengguna
A. DOM Selector: Memilih Elemen

Sebelum elemen diubah, JavaScript harus memilih elemen tersebut menggunakan selector.

getElementById()
Digunakan untuk mengambil elemen berdasarkan id tertentu.querySelector()
Lebih fleksibel karena dapat memilih elemen berdasarkan:

Class (.)
ID (#)
Tag HTML (div, p, h1, dll)
B. Event Listener: Menangani Aksi

Setelah elemen ditemukan, JavaScript dapat memberikan event listener untuk mendeteksi aksi pengguna.

Contoh event:

klik tombol
mengetik input
perubahan data
hover mouse

Saat event terjadi, JavaScript akan menjalankan fungsi tertentu.
C. Pengambilan Data (Value)

JavaScript dapat mengambil nilai dari input pengguna, misalnya teks pada kolom form, lalu memproses data tersebut sesuai kebutuhan program.

D. Output dan Debugging

Untuk melihat hasil program dapat digunakan:

alert() → menampilkan pesan popup
console.log() → menampilkan data di console browser

Keduanya berguna untuk pengujian dan pengecekan kode.

E. Optimasi Kode

Dalam penggunaan DOM, penting memilih metode yang tepat.

getElementById() lebih cepat jika mengambil satu elemen berdasarkan id.
querySelector() lebih fleksibel jika menggunakan class, tag, atau selector yang lebih kompleks.
