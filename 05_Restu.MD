
P: Point (Titik Utama)
Papan tulis tersebut merangkum bagaimana JavaScript berinteraksi dengan HTML dan CSS melalui DOM untuk menciptakan halaman web yang interaktif. Intinya adalah memahami tiga pilar: Selektor (mengambil elemen), Event Listener (menunggu aksi), dan Optimasi (cara terbaik melakukannya).

R: Reason (Alasan)
Tanpa pemahaman DOM, sebuah website hanyalah tampilan statis. Seperti catatan di papan tulis: "HTML + CSS + JS" adalah kombinasi "Badan + Tampilan + Otak". JavaScript bertindak sebagai "otak" yang memanipulasi elemen agar web bisa merespons tindakan pengguna (seperti klik atau input data).

E: Explanation (Penjelasan Rinci)
Berdasarkan struktur di papan tulis, kita bisa membaginya menjadi tiga bagian utama:

1. Konsep Dasar & Selektor (Bagian Kiri)

Analogi: HTML adalah badan, CSS adalah tampilan/pakaian, dan JS adalah otak.

DOM Selector: Cara JS "menangkap" elemen HTML. Di papan tulis tertulis getElementById("cari"). Ini adalah cara paling umum untuk mengambil satu elemen spesifik berdasarkan ID-nya.

Data Mining (Value): Setelah elemen didapat, kita bisa mengambil datanya (misalnya mengambil teks yang diketik pengguna dalam kolom pencarian).

2. Interaktivitas (Bagian Tengah)

Event Listener: Ini adalah mekanisme "menunggu". Contohnya, ketika tombol diklik, fungsi tertentu akan dijalankan (callback).

Output Aksi: Catatan menyebutkan alert dan console. Ini adalah cara paling dasar untuk melihat apakah interaksi berhasil:

alert: Memunculkan kotak pesan di layar.

console.log: Menampilkan pesan di panel pengembang (developer tools) browser.

3. Optimasi: getElementById vs querySelector (Bagian Kanan)
Papan tulis membandingkan dua metode pemilihan elemen:

getElementById: Sangat cepat dan efisien jika Anda sudah tahu ID spesifik elemennya.

querySelector: Lebih fleksibel karena bisa mengambil elemen berdasarkan:

Class (ditandai dengan titik, misal: .tombol)

ID (ditandai dengan pagar, misal: #cari)

Element/Tag (misal: div, h1, p)

P: Point (Kesimpulan)
Secara keseluruhan, catatan ini adalah panduan teknis untuk membangun alur kerja web interaktif: Pilih elemennya (Selector), Tentukan pemicunya (Event Listener), dan Lakukan aksinya (Fungsi/Output). Penggunaan querySelector disarankan untuk fleksibilitas, sementara getElementById tetap unggul untuk kecepatan pada elemen tunggal yang 
