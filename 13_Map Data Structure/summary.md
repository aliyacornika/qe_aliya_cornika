# 13 Map Data Structure
## Resume
### 
Map merupakan struktur data yang ada di java yang digunakan untuk menyimpan banyak d ata di dalamnya.

data2 yg tersimpan dalam map diindetifikasi di dmenggunakan key.
setiap key akan memiliki data nya sendiri, disebut value.

map daapt disebut juga dengan penyimpanan data berbasis key value.

bentuk map :
hashmap, weakhashmap, identityHashMap, LinkedHashMap, EnumHashMap

Map
HashMap merupakan implementasi dari map yang menggunakan algoritma struktur data HashTable.
WeakHashMap juga menggunakan hashmap. bedanya, key dapat dihilnagkan apabila sudah tidak digunakan.
IdentityHashMap masih menerapkan hash, tp apabila menerapkan referensi key yang berbeda maka akan dianggap data yang berbeda. 
LinkedHashMap tidak perbedaan yg signifikan terhadap HashMap biasa, akan tetapi secara internal linkhashmap menerapkan doublelinklisted dan hashtable
sbg struktur data didalam mapnya.

immutableMap artinya map dalam bentuk ini tidak dapat diubah isinya. 

SortedMap
artinya map yang dapat diurutkan, baik secara ascending maupun descending.

NavigableMap
masih termasuk SortedMask tetapi dengan method2 menavigasi yang lebih lengkap. 
untuk mengubah agar menjadi navigablemap, type data SortedMap diganti dengan NavigableMap. 
Tetapi isi datanya tetap menggunakan TreeMap. 

JDK:
Java Development Kit (JDK) merupakan tools yang digunakan seorang developer
dalam proses developing, debugging, dan monitoring dalam Java.
Developing: proses penyusunan baris per baris kode program hingga menjadi
satu aplikasi atau yang utuh dan memiliki suatu fungsi tertentu.
Dalam proses developing, memungkinkan adanya bug atau error yang akan terjadi.
Debugging: dalam proses ini berguna untuk menghilangkan bug tersebut
yang kemudian diperbaiki sehingga program dapat berjalan
sesuai yang diinginkan.
Monitoring: proses mengamati jalannya program
yang sudah dikerjakan sesuai dengan keiinginan. 

IDE:
Integrated Development Environment (IDE):
1. BlueJ
2. NetBeans
3. Eclipse
4. InteliJ IDEA

Basic Programming terdiri dari Type Data, Branching, Looping,
Input dan Output, Operator.

Type data terdiri dari Integer, Decimal, String, Char, Boolean
Tipe data primitif adalah tipe data yang hanya mempunyai value tapi
tidak mempunyai properti atau method. 
Contoh: number, boolean, null, string, double, integer, long.
Tipe data non primitif adalah tidak didefinisikan secara default harus
diisi sendiri seperti arrat dan class dan didalamnya terdapat string, int, dan lain-lain.

Operator terdiri dari:
Assignment, Arithmetic, Conditional, Equality dan Relational, Unary.
Branching merupakan percabangan. Didalamnya terdapat:
if-then-else, switch, tenary, if-then
Looping merupakan perulangan. Didalamnya terdapat:
for, while, do-while, for each, break continue
## Task
