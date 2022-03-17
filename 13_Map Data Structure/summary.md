# 13 Map Data Structure

## Resume
### Map
Map merupakan struktur data yang ada di java 
yang digunakan untuk menyimpan banyak data di dalamnya.
Data-data yang tersimpan dalam map diindetifikasi 
menggunakan key. Setiap key akan memiliki datanya sendiri, disebut value.
Map daapt disebut juga dengan penyimpanan data berbasis key value.
Bentuk map yaitu HashMap, WeakHashMap, IdentityHashMap,
LinkedHashMap, dan EnumHashMap.

### Macam-macam Map
1. HashMap merupakan implementasi dari map 
yang menggunakan algoritma struktur data HashTable.
2. WeakHashMap juga menggunakan HashMap. 
Perbedaan dari HashMap adalah 
key dapat dihilangkan apabila sudah tidak digunakan.
3. IdentityHashMap masih menerapkan Hash,
tapi apabila menerapkan referensi key yang berbeda 
maka akan dianggap data yang berbeda. 
4. LinkedHashMap tidak ada perbedaan yang signifikan 
terhadap HashMap biasa, akan tetapi secara internal 
LinkedHashMap menerapkan DoubleLinkListed dan HashTable
sebagai struktur data didalam mapnya.
5. ImmutableMap artinya map dalam bentuk ini tidak dapat diubah isinya. 
6. SortedMap artinya map yang dapat diurutkan, 
baik secara ascending maupun descending.
7. NavigableMap masih termasuk SortedMask tetapi dengan 
metode-metode menavigasi yang lebih lengkap. 
Untuk mengubah agar menjadi NavigableMap, 
type data SortedMap diganti dengan NavigableMap. 
Tetapi isi datanya tetap menggunakan TreeMap. 

### Tools
#### JDK 
Java Development Kit (JDK) merupakan tools 
yang digunakan seorang developer
dalam proses developing, debugging, dan monitoring dalam Java.
1. Developing: proses penyusunan baris per baris 
kode program hingga menjadi satu aplikasi atau yang utuh 
dan memiliki suatu fungsi tertentu.
Dalam proses developing, memungkinkan adanya 
bug atau error yang akan terjadi.
2. Debugging: dalam proses ini berguna untuk menghilangkan 
bug tersebutyang kemudian diperbaiki sehingga 
program dapat berjalan sesuai yang diinginkan.
3. Monitoring: proses mengamati jalannya program
yang sudah dikerjakan sesuai dengan keiinginan. 

#### IDE
Integrated Development Environment (IDE):
1. BlueJ
2. NetBeans
3. Eclipse
4. InteliJ IDEA

### Basic Programming
Basic Programming terdiri dari Type Data, Branching, Looping,
Input dan Output, Operator.

#### Type Data
Type data terdiri dari Integer, Decimal, String, Char, Boolean
Tipe data primitif adalah tipe data yang hanya mempunyai value tapi
tidak mempunyai properti atau method. 
Contoh: number, boolean, null, string, double, integer, long.
Tipe data non primitif adalah tidak didefinisikan secara default harus
diisi sendiri seperti arrat dan class dan didalamnya terdapat string, int, dan lain-lain.

#### Operator
Operator terdiri dari:
Assignment, Arithmetic, Conditional, Equality dan Relational, Unary.
Branching merupakan percabangan. Didalamnya terdapat:
if-then-else, switch, tenary, if-then
Looping merupakan perulangan. Didalamnya terdapat:
for, while, do-while, for each, break continue

## Task
