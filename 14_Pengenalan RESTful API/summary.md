# 14 Pengenalan RESTful API
Application Programming Interface (API)
API memungkinkan komunikasi dan perturakaran data
antara 2 atau lebih software/sistem yang terpisah.
Tujuan API adalah mempercepat proses development
dengan menyediakan function secara terpisah,
sehingga developer tidak membuat fitur yang serupa. 
API berperan sebagai pembawa pesan yang menerima
permintaan dari pengguna dan memberitahukan sistem
apa yang harus dilakukan, lalu memberi respon
sesuai permintaan. 

REST API
Representational State Transfer meruapakan standart
arsitektur komunikasi berbasis web. Umumnya menggunakan HTTP
methode sebagai protokol untuk komunikasi data. REST juga merupakan salah
satu implementasi web service sebagai standar digunakan
sebagai pertukaran data antara aplikasi maupun sistem. 
REST API berisi aturan yang dapat membatasi programmer
untuk  melakukan tindakan-tindakan tertentu pada sebuah database. 
API merupakan penghubunganya, sedangkan REST sebagai membuat aturan
sesuai programmer dalam merancang web service. Terdapat request
dan response pada data yang dikirimkan ataupun diterima.

HTTP methode
dirancang untuk memungkinkan komunikasi antar client dan server.
4 method: get, put, post, delete.
get digunakan untuk mengambil informasi tentang resource yang
sudah ditentukan oleh URL. get digunakan untuk membaca data.
post digunakan untuk mengirimkan data baru ker server. 
put digunakan untuk mengirim data ke server untuk membuat maupun
memperbaiki ke resource.
delete digunakan untuk menghapus resource yang telah ditentukan. 

REST API Component
1. Method
2. URL (Base URL + Path)
adalah cara untuk mendapat request. Terdiri dari kata kunci server.
3. Header
adalah kumpulan feed dan value yang terkait tentang pemberian informasi 
yang memberi tahu bahwa pesan tersebut sah. 
4. Body
Request body mendefinisikan parameter apa yang dikirimkan ke server.
Menginfromasikan data yang diupdate, diubah, maupun dihapus.

JSON
Java Script Obejct Notation (JSON) adalah sebuah
format data yang digunakan untuk pertukaran dan penyimpanan data.
JSON adalah bagin dari JavaScript. JSON juga dapat berbagai bahasa,
seperti C, C++, dan lain-lain. Sehingga, JSON merupakan ideal antar
aplikasi. 

HTTP Response Code
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
