# 12 Iterable Data Stucture
Iterable Data Structure merupakan
Sekumpulan atau struktur data yang dapat dilakukan
iterasi atau perulangan kepadanya.

## General purpose implementation
General purpose implementation
merupakan implementasi yang biasanya digunakan
untuk setiap harinya.

## Iterator
kelas yang memanage iterasi dari sebuah iterable
iterator mengelola pada bagian mana yang sudah iterasi pada data iterable.

## List
List merupakan sebuah interface yang menyediakan
cara untuk menyimpan data secara linear.
List merupakan turunan dari interface collection
dapat menerima nilai yang sama, 
sehingga jika menginputkan dua data yang sama pada list, 
dapat dilakakukan urutan data dalam list bergantung 
pada kapan data tersebut dimasukkan ke dalam list.

### ArrayList 
Menyediakan penyimpanan data yang dinamis. 
ArrayList tidak terikat kapasitas data yg tersimpan oleh 
ArrayList tersebut.

### LinkedList 
Merupakan suatu data yang setiap elemennya 
saling terhubung satu sama lain.
Cara menghubungkannya adalah dengan menyimpan alamat 
memori dari masing-masing elemen alamat memori akan menyimpan 
dari alamat memori sebelumnya.

### Immutable List 
merupakan bagian dari list, namun tidak dapat diubah datanya. 

## Stack
menyimpan data secara linier,
tetapi proses dan pengambilan datanya menggunakan last-in-first-out (LIFO)
data yang baru dimasukkan akan dikeluarkan terlebih dahulu.

### Method Stack
Pop yaitu mengambil data,
push menambah data, dan
peek mengintip data.

## Set 
Adalah struktur data yang dapat menyimpan sekumpulan data secara linear,
sama seperti list akan tetapi set tidak bisa menerima jika datanya terdapat duplikat.
Jika ada data yang kembar, maka set hanya menerima data sejumlah 1. 

### HashSet 
1. HashSet dikatakan sebagai struktur data yang menyediakan 
cara tercepat untuk proses pencarian data.
2. HashSet hanya berisi elemen yang unik.
3. HashSet mengijinkan nilai yang bernilai nol.
4. HashSet adalah alat terbaik untuk mencari data.

### LinkedHasSet 
1. LinkedHasSet menyimpan insertion order, artinya data yang diinputkan terlebih dahulu, maka akan berada pada paling depan.
2. LinkedHasSet hanya berisi elemen yang unik,
sama seperti HashSet.

### EnumSet 
1. Set yang menyimpan nilai enum. 
2. Tidak mengizinkan untuk menambah
null value.

## SortedSet 
merupakan set yang dapat mengelola urutan dari data. 
Dibagi menjadi 2, Treeset dan NavigableSet.

## Queue 
melakukan implementasi First in First Out list. 
## Deque 
adalah sebuah queue tapi memiliki 2 ujung. 
