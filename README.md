## PRAKTIKUM 7 PEMROGRAMAN SERVER SIDE DENGAN PHP <br>
## Nama: Varel Nico Ramadhan <br>
## NIM: 312510156 <br>
## Kelas: I251B <br>
## Mata Kuliah: Pemrograman Web <br>

### Deskripsi Praktikum <br>

Praktikum 7 membahas tentang pemrograman server-side menggunakan bahasa pemrograman PHP. Pada praktikum ini, mahasiswa mempelajari dasar-dasar PHP, penggunaan variabel, operator, percabangan, perulangan, array, function, serta pemrosesan data melalui form menggunakan metode GET dan POST. <br>

Selain latihan praktikum, terdapat mini project berupa aplikasi formulir data mahasiswa yang dapat menerima input, melakukan validasi, dan menampilkan kembali data yang telah dimasukkan oleh pengguna. <br>

### Latihan Praktikum <br>

#### Menjalankan PHP <br>

Pada latihan pertama, dilakukan pengenalan dasar pemrograman PHP dengan membuat file index.php. Program menggunakan perintah echo untuk menampilkan teks ke halaman browser serta fungsi `date()` untuk menampilkan waktu server saat program dijalankan. <br>

Latihan ini bertujuan untuk memastikan bahwa PHP telah berhasil dijalankan melalui server lokal menggunakan localhost. <br>

Output Code: <br>

<img width="774" height="504" alt="image" src="https://github.com/user-attachments/assets/bd73fb50-f46c-4aef-a414-9aa15313802f" /> <br>

Output Gambar: <br>

<img width="774" height="504" alt="image" src="https://github.com/user-attachments/assets/72a5d647-b5dc-42eb-aa42-d1ef1d52131c" /> <br>

### Varibabel, Operator, dan Percabangan <br>

Pada latihan kedua, dilakukan penggunaan variabel untuk menyimpan data mahasiswa berupa nama, nilai tugas, UTS, dan UAS. Selanjutnya, program menghitung nilai akhir berdasarkan bobot masing-masing komponen, yaitu 30% untuk tugas, 30% untuk UTS, dan 40% untuk UAS. <br>

Program juga menggunakan percabangan `if, elseif,` dan `else` untuk menentukan predikat berdasarkan nilai akhir yang diperoleh mahasiswa. <br>

Output Code: <br>

<img width="707" height="432" alt="image" src="https://github.com/user-attachments/assets/8f25e59b-f06f-4e94-bfc0-ec042b08dfff" /> <br>

Output Gambar:

<img width="216" height="126" alt="image" src="https://github.com/user-attachments/assets/2d6b2e5b-c9d6-41e5-a589-2cc3b5c54b86" /> <br>

### Perulangan dan Array <br>

Pada latihan ketiga, dilakukan penerapan array untuk menyimpan beberapa nama mahasiswa dalam satu variabel. Selanjutnya, digunakan perulangan foreach untuk membaca dan menampilkan seluruh data mahasiswa ke dalam halaman browser. <br>

Latihan ini bertujuan untuk memahami cara menyimpan sekumpulan data dan menampilkan setiap elemen array menggunakan perulangan. <br>

Output Code: <br>

<img width="528" height="170" alt="image" src="https://github.com/user-attachments/assets/69f6c9f5-aa92-4202-9862-8cd8b4934984" /> <br>

Output Gambar: <br>

![<img width="582" height="330" alt="image" src="https://github.com/user-attachments/assets/b7a1cc2a-c55a-47aa-a221-d0b4a8d3e902" /> <br>

### Membuat Function <br>

Pada latihan keempat, dilakukan pembuatan function menggunakan PHP untuk menghitung harga setelah mendapatkan diskon. Function `hitungDiskon()` menerima dua parameter, yaitu harga awal dan persentase diskon. <br>

Program kemudian menghitung jumlah potongan harga dan mengembalikan hasil berupa harga akhir menggunakan return. Hasil perhitungan ditampilkan dalam format mata uang Rupiah. <br>

Output Code: <br>

<img width="1157" height="789" alt="image" src="https://github.com/user-attachments/assets/b8bfd311-2108-49ec-ab45-240a51b35042" /> <br>

Output Gambar: <br>

<img width="327" height="61" alt="image" src="https://github.com/user-attachments/assets/61f5ded8-f1d1-41e4-80e0-4a00255e1b6c" /> <br>

### Memproses Form dengan GET <br>

Pada latihan kelima, dilakukan pemrosesan data form menggunakan metode GET. Pengguna dapat memasukkan kata kunci melalui sebuah form, kemudian PHP mengambil data tersebut menggunakan variabel `$_GET`. <br>

Setelah form dikirim, kata kunci akan ditampilkan kembali pada halaman browser. Data yang dikirim menggunakan GET juga akan terlihat pada parameter URL. <br>

Program menggunakan `htmlspecialchars()` untuk membantu mengamankan tampilan input pengguna. <br>

Output Code: <br>

<img width="773" height="296" alt="image" src="https://github.com/user-attachments/assets/0d3a329a-88a9-4d2e-8c6b-5ac6c5962401" /> <br>

Output Gambar: <br>

<img width="2170" height="725" alt="image" src="https://github.com/user-attachments/assets/2b8eba41-d28b-4660-8b3d-16e00574db1b" /> /> <br>

### Memproses Form dengan POST <br>

Pada latihan keenam, dilakukan pemrosesan data form menggunakan metode POST. Form terdiri dari dua input, yaitu nama mahasiswa dan program studi. <br>

Data yang dikirim akan diterima oleh PHP melalui variabel `$_POST`. Program juga melakukan pemeriksaan menggunakan `trim()` untuk memastikan bahwa input tidak kosong. <br>

Apabila seluruh data telah diisi, program akan menampilkan informasi bahwa data berhasil diterima beserta nama dan program studi pengguna. <br>

Output Code: <br>

<img width="844" height="503" alt="image" src="https://github.com/user-attachments/assets/b03f482e-ff21-4a27-a265-d389d68cf514" /> <br>

Output Gambar: <br>

<img width="2169" height="725" alt="image" src="https://github.com/user-attachments/assets/264a0a52-8661-4004-933e-5dc5dc00663e" /> <br>

### Pengolahan Data Sederhana <br>

Pada latihan ketujuh, dibuat program pengolahan data transaksi sederhana menggunakan PHP. Form yang tersedia digunakan untuk memasukkan nama barang, harga, dan jumlah barang. <br>

Setelah data dikirim, PHP akan melakukan validasi terhadap input yang diberikan. Apabila data sesuai, program menghitung subtotal dengan mengalikan harga barang dan jumlah barang. <br>

Program juga menampilkan pesan kesalahan apabila nama barang kosong, harga tidak valid, atau jumlah barang tidak memenuhi ketentuan. <br>

Output Code: <br>

<img width="780" height="648" alt="image" src="https://github.com/user-attachments/assets/fe9d75d7-1f70-4685-ad1f-3eba8a6ab3cf" /> <br>

Output Gambar: <br>

<img width="844" height="104" alt="image" src="https://github.com/user-attachments/assets/2caa3cd3-b73a-4db8-8204-8443af57d5df" /> <br>

## MINI PROJECT Aplikasi Formulir Data Mahasiswa <br>

Mini project pada Praktikum 7 adalah pembuatan aplikasi formulir data mahasiswa menggunakan bahasa pemrograman PHP. <br>

Aplikasi ini dirancang untuk menerima data mahasiswa melalui form, kemudian melakukan validasi pada sisi server sebelum menampilkan ringkasan data yang telah dimasukkan. <br>

Formulir terdiri dari beberapa informasi, yaitu: <br>

- Nama mahasiswa. <br>
- NIM. <br>
- Program studi. <br>
- Semester. <br>
- Email. <br>

Pengiriman data menggunakan metode POST agar data dikirim melalui body permintaan HTTP dan tidak ditampilkan sebagai parameter URL. <br>

### Proses dan Validasi Data <br>

Pada aplikasi ini, PHP digunakan untuk melakukan beberapa proses validasi, antara lain: <br>

1. Memastikan nama mahasiswa telah diisi. <br>
2. Memastikan NIM telah diisi. <br>
3. Memastikan program studi telah diisi. <br>
4. Memeriksa format email menggunakan `filter_var()` dengan `FILTER_VALIDATE_EMAIL` <br>
5. Memastikan semester berupa bilangan bulat dalam rentang 1 sampai 14. <br>

Apabila terdapat kesalahan input, aplikasi akan menampilkan pesan kesalahan. Jika seluruh data valid, aplikasi akan menampilkan ringkasan data mahaiswa. <br>

Data yang ditampilkan kembali menggunakan `htmlspecialchars()` untuk membantu mencegah injeksi HTML atau script. <br>

Output Gambar: <br>

<img width="1226" height="1283" alt="Formulir Data Mahasiswa Berhasil Diterima" src="https://github.com/user-attachments/assets/678a41d2-f71f-46d7-8620-5025aca94cfb" /> <br>
