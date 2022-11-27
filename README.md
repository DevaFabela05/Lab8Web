# Lab8Web# Lab7Web

## PHP Dan Database MySQL

### Langkah - langkah Pratikum 8

#### membuat folder lab8_php_database

Dengan mengaktifkan xampp terlebih dahulu untuk menyalakan aphace dan mysql, lalu kemudian membuat folder baru dengan nama lab8_php_database pada root directory web server (c:\xampp\htdocs). dan bisa di cek melalui http://localhost/lab8_php_database/ pada google chrome maupun mozila. Beginilah tampilannya:
![gambar1](screenshot/s1.png)

#### Membuat Database, Tabel dan Menambahan Data

membuat Database pada Mysql dengan nama latihan1 dan membuat tabel data_barang. kemudian menambahkan data pada tabel data_barang Inilah tampilannya:
![gambar2](screenshot/s2.png)

#### Membuat Program CRUD

Sebelumnya pastikan xampp sudah aktif dan sudah membuat folder lab8_php_database pada (c:xampp/htdocs). Inilah tampilannya:
![gambar3](screenshot/s3.png)

#### Membuat file koneksi database

Untuk mengconnectkan file di database Pastikan Database sudah terbuat dan buat syntax yang hubungkan user dan db. Buka melalui browser untuk menguji koneksi database (untuk menyampilkan pesan koneksi berhasil, uncomment pada perintah echo “koneksi berhasil”. berikut tampilannya :
![gambar4](screenshot/s4.png)

#### Membuat file index untuk menampilkan data (Read)

Membuat file dengan nama index.php pastikan databse sudah terconnect dengan program kemudian tambahkan query untuk menampilkan data dengan SELECT \* FROM data_barang. dan pastikan nama yang di masukan sama dengan nama tabel pada database. Berikut tampilannya:
![gambar5](screenshot/s5.png)

#### Menambah Data (Create)

Membuat form untuk menambahkan data dan connectkan dengan koneksi.php dan index.php agar otomatis data yang sudah ditambahkan langsung terinput. Berikut tampilannya:
![gambar6](screenshot/s6.png)

#### Mengubah Data (Update)

Berikut ini adalah tampilannya:
![gambar7](screenshot/s7.png)

#### Menghapus Data (Delete)

Berikut ini adalah tampilannya
![gambar8](screenshot/s8.png)
