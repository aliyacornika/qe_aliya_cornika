# 12 Iterable Data Stucture
Sekumpulan atau struktur data yang dapat dilakukan
iterasi aatu perulangan kepadanya.

General purpose implementation
adalah

Cara menggunakan interface iterable

Iterator
kelas yang memanage iterasi dari sebuah iterable
iterator mengelola pada bagian mana yang sudah iterasi pada data iterable.

List
sebuah interface yang menyediakan cara untuk menyimpan data secara linear
list merupakan turunan dari interface collection
dapat menerima nilai yang sama, shg jika menginputkan 2x data yang sama pada list, dapat dilakakukan
urutan data dalam list bergantung pada kapan data tsb dimasukkan ke dalam list.

ArrayList menyediakan penyimanan data yang dinamis. (tidak terikat kapasitas data yg terismpan oleh arraylist tsb)
LinkdeList merupakan suatu data yg setiap elemennya saling terhubung satu sama lain
cara menghubungkannya adalah dengan menyimpan alamat memori dari amasing2 elemen
alamat memori akan menyimpan dari alamat memori sblmnya

Immutable list merupakan bagian dari list, namun tidak dapat diubah datanya. 

Stack
menyimpan data secara linier,
tetapi proses dan pengambilan datanya menggunakan last-in-first-out (LIFO)
data yang baru dimasukkan akan dikeluarkan terlebih dahulu.

method stack:
pop mengambil data
push menambah
peek mengintip data

Set adalah struktur data yang dapat menyimpan sekumpulan data secara linear,
sama seperti list akan tetapi set tidak bisa menerima jika datanya terdapat duplikat.
Jika ada data yg kembar, maka set hanya menerima data sejumlah 1. 

HashSet dikatakan sbg struktur data yg menyediakan cara tercepat untuk proses pencarian data.
LinkedHasSet menyimpan insertion order, artinya data yang diinputkan terlebih dahulu, maka akan berada pada paling depan.
EnumSet set yg menyimpan nilai enum. 

SortedSet set yg dapat mengelola urutan dari data. 

Queue melakukan implementasi First in First Out list. 
Deque adalah sebuah queue tapi memiliki 2 ujung. 
