# 15_REST API Testing

## Application Programming Interface (API)
API memungkinkan komunikasi dan perturakaran data
antara 2 atau lebih software/sistem yang terpisah.
Tujuan API adalah mempercepat proses development
dengan menyediakan function secara terpisah,
sehingga developer tidak membuat fitur yang serupa. 
API berperan sebagai pembawa pesan yang menerima
permintaan dari pengguna dan memberitahukan sistem
apa yang harus dilakukan, lalu memberi respon
sesuai permintaan. 

## Representational State Transfer (REST)
REST API merupakan standart arsitektur komunikasi berbasis web. 
Umumnya menggunakan HTTP method sebagai protokol untuk komunikasi data. 
REST juga merupakan salah satu implementasi web service sebagai 
standar digunakan sebagai pertukaran data antara aplikasi maupun sistem. 
REST API berisi aturan yang dapat membatasi programmer
untuk  melakukan tindakan-tindakan tertentu pada sebuah database. 
API merupakan penghubunganya, sedangkan REST sebagai membuat aturan
sesuai programmer dalam merancang web service. Terdapat request
dan response pada data yang dikirimkan ataupun diterima.

## HTTP method
Dirancang untuk memungkinkan komunikasi antar client dan server.
4 method: get, put, post, dan delete.
- Get digunakan untuk mengambil informasi tentang resource yang
sudah ditentukan oleh URL. Get digunakan untuk membaca data.
- Post digunakan untuk mengirimkan data baru ke server. 
- Put digunakan untuk mengirim data ke server untuk membuat maupun
memperbaiki ke resource.
- Delete digunakan untuk menghapus resource yang telah ditentukan. 

## REST API Component
1. Method
2. URL (Base URL + Path)
adalah cara untuk mendapat request. Terdiri dari kata kunci server.
3. Header
adalah kumpulan feed dan value yang terkait tentang pemberian informasi 
yang memberi tahu bahwa pesan tersebut sah. 
4. Body
Request body mendefinisikan parameter apa yang dikirimkan ke server.
Menginfromasikan data yang diupdate, diubah, maupun dihapus.

## Java Script Obejct Notation (JSON)
JSON adalah sebuah format data yang digunakan untuk 
pertukaran dan penyimpanan data. JSON adalah bagin dari JavaScript. 
JSON juga dapat berbagai bahasa, seperti C, C++, dan lain-lain. 
Sehingga, JSON merupakan ideal antar aplikasi. 

## HTTP Response Code
1. 200 : request yang dikirim berarti sukses.
2. 201 : request yang dikririm berarti sukses, dan resourcenya 
berhasil dibuat. Biasanya response code ini menggunakan
method post dan put.
3. 400 : terjadi jika melakukan request post dan put, kemudian
datanya tidak sesuai dengan yang diharapkan ataupun 
ada salah dalam formatnya. 
4. 404 : resource yang diperlukan tidak ditemukan.
5. 401 : tidak melakukan auntentifikasi terlebih dahulu
sebelum melakukan request. 
6. 405 : HTTP method yang digunakan salah.
7. 500 : error karena ada kesalahan di server (internal).

## API Testing
Tes yang dilakukan dimana API yang digunakan berfungsi. API
Testing diharapkan bisa merespon aplikasi web sebelum GUI siap. 
Bertujuan untuk melakukan testing sedini mungkin. 

## Macam-macam API Testing
1. Functionality : memvalidasikan suatu fitur sudah berjalan
sebagaimana semestinya.
2. Load Test : menguji kekuatan suatu sistem dari data
yang diberikan.
3. Security : memiliki tujuan untuk menguji keamanan dari suatu sistem.

## API Testing Tools
1. frisby.jd
2. Apache JMeter
3. Postman
4. REST-assured

## Perbedaan antara API Test dan Unit Test
- Unit Test:
1. Dilakukan oleh Developer
2. fungsi-fungsi terpisah
3. Developer dapat mengakses source code
4. Hanya dasar functionality yang di test
5. Scopenya terbatas
6. Dilakukan sebelum build.

- API Test:
1. Dilakukan oleh Software Tester.
2. Fungsi-fungsi tidak terpisah.
3. Tidak bisa mengakses source code.
4. End to End.
5. Semua functional issue.
6. Scopenya lebih luas.
7. Dilakukan setelah build.

## Proses API Testing
1. Specification Review : bertujuan untuk mereview spesifikasi API.
2. Spesification Review : memastikan tentang detail document 
mengenai test scenario dan ekspektasi hasilnya pada setiap Test Case. 
3. Framework Development : Memilih untuk memakai tools dalam API Testing nantinya.
4. Test Case Development : membuat Test Scenario.
5. Execution & Report : mengeksekusi Test Scenario yang sudah dibuat dan kemudian
membuat laporannya (report) untuk hasil dari testing yang sudah dilakukan.

## Test Cases for API Testing
1. Mendapatkan response yang sesuai dengan inputan.
2. Apakah memberikan feedback atau tidak.
3. Apakah mengganggu fitur yang lain atau tidak.
4. Update struktur data.
5. Memodifikasi data yang ada.

## Best Practice of API Testing
1. Kelompokkan test case kedalam beberapa kategori.
2. Beri judul yang sesuai pada setiap test.
3. Harus berhati-hati ketika melakukan test yang berhubungan
dengan menghapus sesuatu.
4. Ketika membuat test case, harus dipikirkan
segala kombinasi input pada API.

## Types of Output of an API
1. Dapat berbentuk apa saja, pada umumnya JSON atau XML.
2. Status response apakah Passed atau Fail.
3. Memanggil fungsi API lain.

## Common Types of Test in API Testing
1. Memverifikasi apakah kita mendapat respon dari API.
2. Memverifikasi apakah hasil input/request sudah sesuai
atau belum.
3. Memverifikasi apakah data yang kita input/update sudah 
benar-benar berubah atau bertambah.
4. Memverifikasi waktu response yang diberikan.

## Type of Bugs that API Testing Detects
1. Gagal melakukan error handling pada keadaan tertentu.
2. Kesulitan untuk tersembung dan mendapat respon API.
3. Isu keamanan.
4. Performance Issues.
5. Error atau warning yang tidak tepat.
6. Struktur dari data respon tidak benar (JSON & XML).

## Manfaat API Testing
1. Efisiensi waktu
2. Bahasa yang independen
3. Mengurangi biaya testing
4. Mengurangi resiko

## Tantangan dalam API Testing
1. Kombinasi parameter, pemilihan parameter
2. Tidak ada GUI
3. Kita harus mengetahui terlebih dahulu parameter
4. Perlu mengetest error handling dari setiap API

## Kesimpulan
API terdiri dari kumpulan class/function/prosedur
yang mereprsentasikan bisnis logic. Jika API tidak di test
dengan baik, itu dapat mengakibatkan masalah yang tidak hanya 
pada aplikasi API saja, tetapi juga pada aplikasinya.
API Testing sangat diperlukan dalam software engineering.
