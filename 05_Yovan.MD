Modul Pembelajaran: Interaksi DOM dengan Vanilla JavaScript
1. Fondasi Web: Hubungan HTML, CSS, dan JS
Dalam membangun sebuah halaman web, kita bekerja dengan tiga pilar utama yang memiliki peran berbeda namun saling melengkapi:

HTML (Bentuk/Struktur): Sebagai kerangka dasar atau "badan" dari sebuah halaman web.

CSS (Tampilan): Sebagai pemberi gaya, estetika, dan tata letak agar tampilan menjadi menarik.

JavaScript (Otak): Sebagai logika yang memberikan fungsionalitas dan interaktivitas pada halaman.

2. Memahami DOM (Document Object Model)
DOM adalah antarmuka pemrograman untuk dokumen HTML. Ketika browser memuat halaman, ia membuat representasi objek dari dokumen tersebut, yang memungkinkan JavaScript untuk mengakses dan memanipulasi konten, struktur, dan gaya secara dinamis.

A. DOM Selector: Menemukan Elemen
Untuk memanipulasi elemen, kita harus "menangkapnya" terlebih dahulu menggunakan Selector. Ada dua cara umum yang sering digunakan:

getElementById: Digunakan untuk mengambil elemen secara spesifik berdasarkan atribut id. Contoh: getElementById("nama_id").

querySelector: Metode yang lebih fleksibel karena bisa memilih berdasarkan:

Class (menggunakan tanda titik .)

ID (menggunakan tanda pagar #)

Elemen/Tag (langsung memanggil nama tag seperti div, h1, atau p).

B. Event Listener: Memberikan Aksi
Setelah elemen ditemukan, kita bisa memberikan "pendengar" atau Event Listener. Ini berfungsi untuk menjalankan fungsi tertentu (callback) ketika terjadi interaksi dari pengguna (seperti klik, ketik, atau hover).

Fungsi/Action: Apa yang akan dilakukan sistem?

Contoh Output: Memberikan respon berupa alert (pesan munculan) atau mencetak data ke dalam console browser untuk pengecekan.

C. Data Mining & Value
Dalam tahap ini, kita belajar bagaimana mengambil data (value) dari elemen yang ada di web, misalnya mengambil teks yang diketikkan pengguna dalam kolom input untuk diproses lebih lanjut oleh logika JavaScript.

3. Optimasi Kode
Penting bagi seorang pengembang untuk memahami kapan harus menggunakan getElementById vs querySelector.

getElementById cenderung lebih cepat secara performa jika kita hanya mencari satu elemen spesifik dengan ID.

querySelector lebih unggul dalam fleksibilitas jika kita perlu melakukan seleksi kompleks yang melibatkan struktur bertingkat atau class.
