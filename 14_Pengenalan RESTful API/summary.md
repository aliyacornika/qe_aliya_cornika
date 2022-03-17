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
