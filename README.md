# basic-fundamental

<h1>Fase 1: Dasar-Dasar Logika dan Alat</h1><br>

1. Algoritma
Urutan langkah-langkah logis dan sistematis yang disusun untuk menyelesaikan suatu masalah tertentu. Ini adalah fondasi sebelum menulis kode apa pun.

2. Bahasa Pemrograman
Bahasa atau instruksi standar yang digunakan oleh manusia (programmer) untuk memberikan perintah kepada komputer agar menjalankan algoritma yang telah dibuat.

<h1>Fase 2: Elemen Dasar Program</h1><br>

3. Tipe Data
Klasifikasi jenis nilai yang akan digunakan dalam program, seperti bilangan bulat (Integer), teks (String), atau nilai kebenaran (Boolean).

4. Variabel
Tempat penyimpanan data di dalam memori komputer yang nilainya bisa diubah-ubah selama program berjalan.

5. Konstanta
Tempat penyimpanan data yang nilainya tetap (konstan) dan tidak dapat diubah lagi setelah pertama kali diisi.

<h1>Fase 3: Struktur Kontrol Alur (Control Flow)</h1><br>

6. Percabangan
Struktur logika yang memungkinkan program mengambil keputusan atau mengeksekusi blok kode tertentu hanya jika kondisi tertentu terpenuhi (contoh: if, else, switch).

7. Perulangan
Struktur logika yang digunakan untuk menjalankan suatu blok kode secara berulang kali selama kondisi tertentu masih bernilai benar (contoh: for loop, while loop).

<h1>Fase 4: Konsep Lanjutan dan OOP (Object-Oriented Programming)</h1><br>

8. Package
Sebuah folder atau wadah (namespace) yang digunakan untuk mengelompokkan kode atau kelas-kelas yang saling berhubungan agar program lebih rapi dan terstruktur.

9. Enkanpsulasi (Ditulis di gambar: Enkanpsulasi / Seharusnya: Enkapsulasi)
Konsep membungkus data (variabel) dan fungsi (metode) ke dalam satu kesatuan (kelas), serta membatasi akses dari luar untuk melindungi data dari perubahan yang tidak diinginkan.

10. Inheritance (Pewarisan)
Konsep di mana sebuah kelas baru dapat mewarisi properti dan metode dari kelas lain yang sudah ada, sehingga mencegah penulisan kode yang berulang.

11. Polimorphisme (Ditulis di gambar: Polimorphisme / Seharusnya: Polimorfisme)
Konsep yang memungkinkan suatu objek memiliki banyak bentuk, atau sebuah metode memiliki cara kerja yang berbeda-beda tergantung objek mana yang memanggilnya.

12. Interface
Sebuah kontrak atau kerangka kerja yang berisi metode-metode kosong. Kelas mana pun yang mengimplementasikan interface tersebut wajib membuat isi (detail kerja) dari metode-metode di dalamnya.

<h1>Fase 5: Penanganan Masalah dan Perbaikan</h1><br>

13. Error Heandling (Ditulis di gambar: Error Heandling / Seharusnya: Error Handling)
Mekanisme penanganan kesalahan (exception) yang terjadi saat program sedang berjalan (runtime) agar program tidak langsung crash atau berhenti secara tiba-tiba.

14. Debugging
Proses mencari, melacak, dan memperbaiki bug (kesalahan logika, sintaks, atau sistem) yang ada di dalam sebuah kode program agar aplikasi berjalan sesuai harapan.

<h1>Berikut adalah alasan logis mengapa urutan belajarnya harus seperti itu:</h1><br>

<h1>Fase 1: Mengapa Algoritma & Bahasa Pemrograman pertama?</h1><br>
Sebelum menulis satu baris kode pun, Anda harus tahu cara berpikir seorang programmer.

Algoritma melatih logika pemecahan masalah Anda. Komputer itu bodoh; ia hanya mengikuti instruksi. Jika logika instruksi Anda salah, hasilnya pasti salah.

Setelah tahu apa yang ingin diinstruksikan (Algoritma), Anda baru memilih Bahasa Pemrograman sebagai alat komunikasinya.

<h1>Fase 2: Mengapa Tipe Data, Variabel, & Konstanta setelahnya?</h1><br>

1. Ibarat belajar bahasa baru, ini adalah kosa kata dasar-nya.

2. Setiap program pada dasarnya hanya melakukan satu hal: memanipulasi data. Oleh karena itu, Anda harus tahu cara menyimpan data tersebut (Variabel dan Konstanta) dan mengenali bentuk/jenis datanya (Tipe Data). Tanpa komponen ini, program Anda tidak memiliki bahan baku untuk diproses.

<h1>Fase 3: Mengapa Percabangan & Perulangan di tengah?</h1><br>

1. Jika variabel adalah kata-kata, maka percabangan dan perulangan adalah tata bahasa (grammar) untuk membuat kalimat yang bermakna.

2. Kehebatan komputer terletak pada kemampuannya mengambil keputusan cepat (Percabangan) dan melakukan tugas berulang tanpa lelah (Perulangan). Setelah memiliki data (dari Fase 2), Anda menggunakan struktur kontrol ini untuk memproses data tersebut agar sesuai dengan algoritma (dari Fase 1) yang Anda buat.

<h1>Fase 4: Mengapa konsep OOP (Enkapsulasi, Inheritance, dll) di tahap lanjut?</h1><br>

1. Ketika Anda sudah mahir menggunakan variabel dan struktur kontrol (Fase 1-3), Anda akan menyadari bahwa menulis program yang sangat besar dengan cara biasa akan membuat kode menjadi berantakan, sulit dibaca, dan rentan rusak.

2. Di sinilah Anda butuh Paradigma Pemrograman Berorientasi Objek (OOP) dan pengelompokan folder (Package).

3. Enkapsulasi, Inheritance, Polimorfisme, dan Interface adalah aturan tingkat tinggi untuk mengorganisir kode yang kompleks agar lebih rapi, aman, bisa digunakan ulang (reusable), dan mudah dikelola oleh tim. Anda tidak akan bisa memahami konsep ini jika tidak paham konsep dasar variabel dan fungsi/metode.

<h1>Fase 5: Mengapa Error Handling & Debugging di akhir?</h1><br>
<h1>Ini adalah fase pemeliharaan:</h1>

1. Semakin kompleks program Anda (terutama setelah memakai konsep OOP), kemungkinan munculnya bug atau eror akan semakin besar.

2. Error Handling dipelajari agar program Anda tangguh saat menghadapi pengguna yang memasukkan input salah atau saat server bermasalah.

3. Debugging adalah skill bertahan hidup (survival skill) wajib bagi programmer untuk melacak kesalahan di tumpukan kode yang sudah ditulis dari Fase 1 hingga 4.

<h1>Singkatnya, urutan ini memastikan Anda belajar mulai dari berpikir logis -> menyimpan data -> memproses data -> mengelola kode skala besar -> memperbaiki masalah.</h1><br>