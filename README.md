REGISTER, AUTHENTICATION DAN AUTHORIZATION
------------------------------------------------
Langkah 1) Untuk membuat user baru dengan PHP, kita perlu memastikan bahwa tabel user sudah
ada. Kemudian, kita membuat file AuthController.php untuk mendaftarkan user baru.
Terakhir, kita menambahkan router baru di file routes/web.php untuk mengarahkan
permintaan ke fungsi register() di dalam kelas AuthController.

<img src="1.jpg">
<img src="2.jpg">
<img src="3.jpg">

Langkah 2) Dengan menambahkan fungsi login() pada file AuthController.php dan router baru pada
file routes/web.php, kita bisa membuat fungsi login untuk membaca user dengan email
scaramouche@fatui.org dan password wanderer ke dalam database pada Postman.

<img src="4.jpg">
<img src="5.jpg">
<img src="6.jpg">

Langkah 3) Dengan mengikuti langkah-langkah di atas, kita dapat menambahkan kolom token ke
tabel users dan menggunakannya untuk menyimpan token login user.

<img src="7.jpg">
<img src="8.jpg">
<img src="9.jpg">
<img src="10.jpg">
<img src="11.jpg">

Langkah 4) Dengan mengikuti langkah-langkah di atas, kita dapat membuat middleware "auth" untuk
memeriksa apakah user sudah login. Kita juga dapat menambahkan route "/home" yang
hanya dapat diakses oleh user yang sudah login.

<img src="12.jpg">
<img src="13.jpg">
<img src="14.jpg">
<img src="15.jpg">
<img src="16.jpg">
<img src="17.jpg">
<img src="18.jpg">
