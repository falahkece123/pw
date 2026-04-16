Narasi Materi Pemrograman Web – Modul DOM & JavaScript Vanilla
Pada pertemuan mata kuliah Pemrograman Web ini, pembahasan difokuskan pada penggunaan DOM (Document Object Model) dan JavaScript Vanilla sebagai dasar dalam membangun website yang interaktif tanpa menggunakan framework tambahan.
1. Konsep Dasar Web (HTML, CSS, JavaScript)
Dalam pengembangan web, terdapat tiga komponen utama:
HTML (HyperText Markup Language) → berfungsi sebagai struktur dasar halaman web.
CSS (Cascading Style Sheets) → digunakan untuk mengatur tampilan/visual.
JavaScript (JS) → berfungsi sebagai logika untuk membuat website menjadi dinamis dan interaktif.
Ketiga komponen ini bekerja bersama, di mana JavaScript akan memanipulasi elemen HTML melalui DOM.
2. Pengertian DOM (Document Object Model)
DOM adalah representasi struktur HTML dalam bentuk objek yang dapat diakses dan dimanipulasi menggunakan JavaScript.
Fungsi utama DOM:
Mengakses elemen HTML
Mengubah isi (content)
Mengubah atribut atau style
Menambahkan atau menghapus elemen
3. DOM Selector (Memilih Elemen)
Untuk memanipulasi elemen, kita harus memilihnya terlebih dahulu menggunakan selector:
Contoh:
document.getElementById("id")
document.querySelector(".class")
document.querySelectorAll("tag")
Fungsi selector:
Mengambil elemen tertentu dari halaman
Menjadi dasar untuk manipulasi DOM
4. Manipulasi Elemen DOM
Setelah elemen dipilih, kita dapat melakukan berbagai perubahan, seperti:
Mengubah teks:
innerHTML
textContent
Mengubah nilai input:
value
Mengubah atribut:
setAttribute()
Mengubah style:
style.color, style.background
Contoh:
document.getElementById("judul").innerHTML = "Hello";
5. Event Listener (Interaksi Pengguna)
Event listener digunakan untuk menangani interaksi user.
Contoh event:
onclick → saat tombol diklik
onchange → saat input berubah
onkeyup → saat mengetik
Penulisan:
element.addEventListener("click", function() {
    alert("Tombol diklik");
});
Konsep penting:
Event bekerja dengan callback function
Function akan dijalankan saat event terjadi
6. Fungsi (Function) dalam JavaScript
Function digunakan untuk menjalankan kode tertentu.
Contoh:
function tampilkanPesan() {
    alert("Hello");
}
Jenis penggunaan:
Digunakan dalam event
Untuk memproses data
Untuk validasi
7. Validasi Input
Validasi digunakan untuk memastikan data yang dimasukkan benar.
Contoh validasi:
Tidak boleh kosong
Harus angka
Panjang karakter tertentu
Contoh:
if (input.value == "") {
    alert("Input tidak boleh kosong");
}
8. Pengambilan Nilai (Value Handling)
JavaScript dapat mengambil dan memproses nilai dari input user.
Contoh:
let nilai = document.getElementById("nama").value;
console.log(nilai);
9. Debugging (Pengecekan Error)
Untuk mengecek program:
console.log() → menampilkan data di console
alert() → menampilkan pesan popup
Fungsi:
Membantu menemukan error
Melihat alur program
10. Optimasi DOM
Agar program lebih efisien:
Gunakan selector yang tepat (id, class)
Hindari pemanggilan DOM berulang
Simpan elemen dalam variabel
Contoh:
let btn = document.getElementById("btn");
btn.addEventListener("click", function() {
    console.log("Klik");
});
11. Query Selector & Class
Penggunaan modern dalam DOM:
querySelector() → ambil 1 elemen
querySelectorAll() → ambil banyak elemen
Contoh:
document.querySelector(".container");
Kesimpulan
Materi DOM dan JavaScript Vanilla merupakan dasar penting dalam pemrograman web. Dengan memahami DOM, mahasiswa dapat:
Mengontrol dan memanipulasi elemen HTML
Membuat interaksi pengguna
Mengelola data input
Membangun website yang dinamis tanpa framework
