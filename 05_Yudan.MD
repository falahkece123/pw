P: Point (Titik Utama)
Pada pertemuan mata kuliah Pemrograman Web ini, materi yang dibahas berfokus pada penggunaan DOM (Document Object Model) dan JavaScript Vanilla sebagai dasar dalam membuat halaman web yang interaktif, dinamis, dan mampu merespons tindakan pengguna secara langsung. Papan tulis tersebut menjelaskan hubungan antara HTML, CSS, dan JavaScript, kemudian dilanjutkan dengan cara JavaScript mengakses elemen halaman melalui DOM, menangani event, mengambil data input, hingga menerapkan optimasi kode. Inti dari materi ini adalah memahami bagaimana JavaScript bekerja di sisi browser untuk mengendalikan tampilan halaman web.R: Reason (Alasan)
Dalam pengembangan website, HTML dan CSS saja belum cukup untuk menghasilkan halaman yang interaktif. HTML hanya berfungsi sebagai kerangka atau struktur halaman, sedangkan CSS bertugas mempercantik tampilan. Tanpa JavaScript, halaman web hanya bersifat statis dan tidak dapat merespons aksi pengguna. Misalnya tombol tidak memiliki fungsi, form tidak dapat divalidasi secara langsung, dan isi halaman tidak bisa berubah otomatis tanpa memuat ulang halaman.

Oleh karena itu, JavaScript dibutuhkan sebagai komponen logika yang menghubungkan pengguna dengan halaman web. Melalui DOM, JavaScript dapat mengenali setiap elemen HTML sebagai objek yang bisa dimanipulasi. Dengan memahami DOM, mahasiswa akan mampu membuat fitur-fitur penting seperti menu interaktif, validasi form, notifikasi, perubahan konten otomatis, hingga animasi sederhana. Materi ini menjadi pondasi utama sebelum mempelajari framework modern seperti React, Vue, maupun Angular.E: Explanation (Penjelasan Rinci)

1. Hubungan HTML, CSS, dan JavaScript

Papan tulis menunjukkan konsep dasar bahwa website tersusun dari tiga komponen utama, yaitu HTML, CSS, dan JavaScript. Ketiganya memiliki peran berbeda namun saling melengkapi.

HTML (HyperText Markup Language) digunakan untuk menyusun struktur halaman, seperti judul, paragraf, gambar, tombol, tabel, dan form input.
CSS (Cascading Style Sheets) digunakan untuk mengatur tampilan visual, seperti warna, ukuran huruf, tata letak, margin, animasi, dan desain responsif.
JavaScript digunakan untuk mengatur logika program dan menambahkan interaksi pada halaman web.

Secara sederhana, HTML dapat diibaratkan sebagai kerangka bangunan, CSS sebagai cat dan dekorasi, sedangkan JavaScript sebagai sistem listrik dan mesin yang membuat bangunan berfungsi.2. Pengertian DOM (Document Object Model)

DOM adalah representasi dokumen HTML dalam bentuk struktur objek yang dibentuk browser ketika halaman dibuka. Setiap elemen HTML seperti <div>, <p>, <button>, dan <input> akan dianggap sebagai objek yang dapat diakses oleh JavaScript.

Melalui DOM, programmer dapat melakukan banyak hal, seperti:

Mengubah isi teks suatu elemen.
Menambahkan elemen baru ke halaman.
Menghapus elemen tertentu.
Mengubah atribut seperti src, href, dan class.
Mengatur style elemen secara langsung.
Membaca data dari input pengguna.

DOM menjadi jembatan antara struktur HTML dengan logika JavaScript.3. DOM Selector (Memilih Elemen)

Sebelum elemen dimanipulasi, JavaScript harus mengetahui elemen mana yang akan diakses. Karena itu digunakan selector.

Beberapa selector dasar yang dijelaskan antara lain:

getElementById() → memilih elemen berdasarkan atribut id. Cocok digunakan jika elemen hanya satu dan unik.
querySelector() → memilih elemen pertama yang sesuai selector CSS.
querySelectorAll() → memilih semua elemen yang sesuai selector dan mengembalikan daftar elemen.

Contohnya elemen dengan id judul, class box, atau tag p dapat diambil untuk dimanipulasi lebih lanjut.

Selector merupakan tahap pertama dalam bekerja dengan DOM.4. Manipulasi Elemen DOM

Setelah elemen berhasil dipilih, JavaScript dapat mengubah kondisi elemen tersebut sesuai kebutuhan.

Beberapa manipulasi yang umum dilakukan:

Mengubah teks menggunakan innerHTML atau textContent.
Mengubah nilai input menggunakan value.
Mengubah warna, ukuran, dan style elemen.
Menambah class CSS tertentu.
Menampilkan atau menyembunyikan elemen.
Membuat elemen baru dan menambahkannya ke halaman.

Contohnya saat tombol ditekan, teks judul berubah, warna background berganti, atau menu dropdown muncul.

Manipulasi DOM inilah yang membuat website terasa hidup dan dinamis.5. Event Listener (Interaksi Pengguna)

Event listener adalah mekanisme yang memungkinkan JavaScript mendeteksi tindakan pengguna. Saat pengguna melakukan aksi tertentu, JavaScript dapat menjalankan perintah yang telah dibuat sebelumnya.

Contoh event yang umum digunakan:

click → ketika tombol diklik.
input → ketika pengguna mengetik.
change → ketika nilai form berubah.
submit → ketika form dikirim.
mouseover → ketika kursor diarahkan ke elemen.
keydown / keyup → ketika tombol keyboard ditekan.

Event listener biasanya dipasangkan dengan function sebagai callback, yaitu fungsi yang akan berjalan saat event terjadi.Contohnya: tombol login ditekan lalu sistem mengecek username dan password.

6. Function dalam JavaScript

Function adalah sekumpulan perintah yang dibungkus dalam satu blok agar bisa dipanggil kapan saja. Function sangat penting karena membantu kode menjadi lebih rapi, singkat, dan mudah digunakan kembali.

Manfaat function:

Mengurangi pengulangan kode.
Memisahkan tugas program menjadi bagian kecil.
Digunakan dalam event listener.
Membantu proses validasi dan perhitungan.

Misalnya function untuk menghitung total harga, menampilkan pesan, atau mengecek form.7. Pengambilan Data Input (Value Handling)

Website sering berinteraksi dengan data yang dimasukkan pengguna melalui form. JavaScript dapat mengambil isi input menggunakan properti value.

Contoh data yang bisa diambil:

Nama pengguna.
Password.
Email.
Angka perhitungan.
Pilihan dropdown.

Data ini kemudian dapat diproses lebih lanjut, misalnya ditampilkan kembali, disimpan, atau dikirim ke server.8. Validasi Input

Validasi bertujuan memastikan data yang dimasukkan pengguna sudah benar sebelum diproses. Hal ini penting untuk menjaga kualitas data dan mencegah kesalahan.

Contoh validasi:

Kolom nama tidak boleh kosong.
Password minimal 8 karakter.
Email harus memiliki format yang benar.
Umur harus berupa angka.
Nomor telepon hanya boleh berisi digit.

Validasi dapat dilakukan langsung di browser menggunakan JavaScript sebelum data dikirim.

9. Debugging dan Pengujian Program

Dalam proses coding, kesalahan program sering terjadi. Karena itu programmBeberapa alat dasar yang dibahas:

console.log() untuk menampilkan isi variabel atau alur program pada console browser.
alert() untuk menampilkan pesan popup sederhana.

Dengan debugging, programmer bisa mengetahui letak error dan memperbaikinya lebih cepat.

10. Optimasi Penggunaan DOM

Manipulasi DOM yang berlebihan dapat memperlambat performa website. Karena itu diperlukan optimasi.

Contoh optimasi:Gunakan selector yang tepat.
Simpan elemen dalam variabel agar tidak dicari berulang kali.
Hindari manipulasi DOM terlalu sering dalam loop.
Tulis kode yang rapi dan terstruktur.
Pisahkan fungsi berdasarkan tugas masing-masing.

Optimasi penting terutama saat website semakin kompleks.

11. Pentingnya JavaScript Vanilla

Sebelum menggunakan framework modern, mahasiswa perlu memahami JavaScript murni terlebih dahulu. Framework seperti React atau Vue tetap bekerja menggunakan konsep dasar JavaScript dan DOM. Jika dasar ini kuat, proses belajar teknologi lanjutan akan jauh lebih mudah.P: Point (Kesimpulan)
Secara keseluruhan, materi pada pertemuan ini menjelaskan fondasi penting dalam pengembangan web interaktif. Mahasiswa mempelajari bagaimana JavaScript menggunakan DOM untuk memilih elemen, mengubah isi halaman, menangani event pengguna, memproses data input, melakukan validasi, serta mengoptimalkan performa kode. Penguasaan materi ini sangat penting karena menjadi langkah awal menuju pembuatan website modern yang dinamis, responsif, dan profesional.
P: Point (Kesimpulan)
Secara keseluruhan, materi pada pertemuan ini menjelaskan fondasi penting dalam pengembangan web interaktif. Mahasiswa mempelajari bagaimana JavaScript menggunakan DOM untuk memilih elemen, mengubah isi halaman, menangani event pengguna, memproses data input, melakukan validasi, serta mengoptimalkan performa kode. Penguasaan materi ini sangat penting karena menjadi langkah awal menuju pembuatan website modern yang dinamis, responsif, dan profesional.
