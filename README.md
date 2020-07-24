# ReBus
Sistem Pemesanan Rental Bus Pariwisata di Daerah Istimewa Yogyakarta yang bernama ReBus

Spesifikasi:
1. Laravel (Any version)
2. Composer (Any version)
3. XAMPP

Dikarenakan website menggunakan laravel dan composer, maka spesifikasi minimal yang harus dipenuhi:

#Server requirements
PHP >= 7.2.5
BCMath PHP Extension
Ctype PHP Extension
Fileinfo PHP extension
JSON PHP Extension
Mbstring PHP Extension
OpenSSL PHP Extension
PDO PHP Extension
Tokenizer PHP Extension
XML PHP Extension

Cara Membuka Website ReBus:

1. Extract file ReBus ke \XAMPP\htdocs
2. Jangan lupa import database (rentalbus.sql) ke localhost (file sql berada di dalam zip di folder yang bernama "FILE SQL DATABASE")
3. Buka console command, ganti route dari c: ke file ReBus yang disimpan.
4. Jangan lupa membuka XAMPP agar databasenya berjalan
5. Ketik "php artisan serve"
6. Salin dan tempel alamat servernya di browser
7. Anda telah membuka website ReBus

Cara Menggunakan Website (Setelah melakukan 7 langkah di atas):
1. Pada halaman awal, anda dapat memesan tiket dengan 2 cara, yaitu dengan cara menekan tombol klik disini yang berwarna hijau atau mengklik "Pesan Tiket" di navigasi
2. Akan muncul halaman pesan tiket bus, pilih tujuan yang diinginkan, pilih tanggal pemesanan, dan ketik jumlah kursi yang diinginkan. (Note: Hanya dapat memilih tujuan yang ada di dropdown list, selain dari dropdown tidak bisa).
3.Setelah itu, klik tombol cari untuk memesannya.
4. Berhasil memesan / merental bus
5. Anda bisa melihat pesanan dengan cara mengklik "Pesanan Saya" di tab navigasi
6. Bila ingin melihat detail dari pesanan, maka dapat mengklik tombol detail.
7. Akan muncul halaman detail pesanan. Halaman tersebut terdiri dari foto bus, nama bus, nama sopir, harga per kursi, dan jumlah kursi
8. Bila ingin keluar dari halaman detail pesanan, tinggal mengklik tombol yang ada di tab navigasi
9. Bila ingin membatalkan pesanan, maka klik tombol "Batalkan pesanan"
10. Akan muncul pop up refund, ada pilihan refund, pilih salah satu , setelah itu pencet tombol "Batalkan Pesanan"
11. Bila pesanan telah selesai, tekan tombol "Beri penilaian" untuk memberi rating perjalanan anda.
12. Akan muncul pop up rating, pilih rating yang sesuai, setelah itu submit
13. Di tab navigasi juga ada tombol "Tentang Kami", yang berisi foto dan nama pembuat website.
14. Bila menekan logo, akan kembali ke halaman awal

Library yang digunakan:
1. Bootstrap
