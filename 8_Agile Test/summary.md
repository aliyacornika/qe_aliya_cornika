# 8 Agile Testing

## Resume
Dalam materi ini, mempelajari tentang:
1. Definition of SDLC
2. Phases of SDLC
3. Agile Testing Manifesto
4. Testing Pyramid

### SDLC
Software Development Life Cycle (SDLC) bertujuan untuk
suatu sistem informasi berjalan sesuai dengan yang diharapkan.
Selain itu, dalam industri sebagai software untuk
mendesain, mengembangkan, dan menguji kualitas software.

### Phases of SDLC
Berikut merupakan tahapan SDLC:
1. Requirements Gathering
Mengumpulkan kebutuhan secara lengkap untuk dianalisis
kemudian membuat diagram prosesnya. 
Analisis yang merinci dapat mempermudah. 
Oleh karena itu, dibutuhkan informasi yang aktual.
Informasi dapat diperoleh melalui wawancara, survey, maupun diskusi.
2. Design
Membuat perancangan desain sebagai gambaran awal (mockup),
mendesain infrastruktur IT dan model sistem.
3. Development (Code)
Desain yang sebelumnya sudah dibuat dapat 
diubah menjadi kode-kode program.
Tahap ini merupakan tahap
mengembangkan infrastruktur IT, database, dan code.
4. Testing
Melakukan pengujian apakah sudah sesuai dengan
desain dan fungsinya atau belum.
Tahapan pengujian dapat dilakukan diawali dengan
membuat Test Case serta dilanjut untuk
mengeksekusi Test Case tersebut.
5. Deployment
Sistem disebarkan untuk klien (dalam artian dapat untuk
umum) ketika user mulai mengoperasikan sistem.
6. Maintenance
Support user sistem, maintenance, penyesuaian sistem.
Maintenance digunakan untuk mengistirahatkan sistem.

### Agile Testing Manifesto
Agile testing pada dasarnya berbeda dengan pengujian yang lama (tradisional).
Salah satu pengaruh dari testing manifesto adalah
dengan kondisi adanya kebutuhan untuk mengukur dan
meningkatkan upaya pengujian, QE/QA dapat mengevaluasi
dan meningkatkan seberapa baik dalam melakukan software testing.
Ada 5 kunci testing manifesto:
1. Testing is an activity not a phase.
2. Prevent bugs rather than finding bugs.
3. Don't be a checker, be a tester.
4. Don't try to break the system, instead help build the best 
possible system.
5. The whole team is responsible for quality,
not just the tester.

### Testing Pyramid
Merupakan suatu konsep perkembangan yang
mempunyai tujuan mempersingkat siklus, sehingga tim baru 
dapat memulai automated testing dengan
cakupan pengujian yang luas.
Setiap pengujian memiliki banyak test case
dalam kondisi waktu yang singkat,
testing pyramid dapat mempermudah pengecekan.
Pada testing pyramid, terdapat 3 bagian.
Bagian paling bawah adalah Unit Test.
Dimana harus dihitung pengujian sekecil mungkin pada
code yang sudah dibuat (per unit).
Bagian tengah adalah Integration.
Mempunyai arti tes yang dirancang untuk
memverifikasi integrasi bagian berbeda
dari komponen terpisah dari
sistem perangkat lunak secara besamaan.
Integrasi berarti dapat berupa dengan Database, 
sistem eksternal, Framework, dan lain sebagainya.
Pada bagian paling atas adalah User Interface (UI)
Merupakan tahapan paling akhir. Setelah diuji codenya,
maka tampilan harus sesuai dengan apa yang diperintah.
Tampilan atau UI sangat penting untuk user.
UI memudahkan user untuk menggunakannya dan dipastikan 
tahap-tahap sebelumnya sudah diuji dengan baik.

## Task
https://drive.google.com/drive/folders/101oITnmSTqvXS72OGFtiuP-4Y1sr1mYN?usp=sharing

1. Quality Engineer (QE) merupakan seseorang yang melakukan 
pengecekan atau kualitas pada sebuah software atau aplikasi yang sudah dibuat, 
pengecekan dapat berupa testing atau pengujian. 
Tujuannya yaitu untuk mencegah terjadinya bugs, 
supaya aplikasi dapat berjalan sebagaimana semestinya. 
Dalam tahap SDLC, peran QE adalah pada tahap Testing/Pengujian. 
Pengujian dilakukan karena untuk mengetahui apakah sudah sesuai dengan desain dan fungsinya. Pengujian dapat dilakukan dengan diawali
membuat Test Case serta dilanjut untuk mengeksekusi Test Case tersebut.

2. a.	Testing is an activity not a phase
Poin pertama, hendaknya menerapkan mindset jika sebuah pengujian 
merupakan aktivitas dan bukan fase. Jika fase saja tidak cukup, 
aktivitas yang berjalan dengan baik menghasilkan hasil yang baik. 
Hendaknya melakukan pengujian secara berkala. 
Dalam pengujian beriringan dengan proses development, 
sehingga tidak terpisah atau membentuk fase sendiri. 
Akan tetapi jadi satu dengan proses development.
b.	Prevent bugs rather than finding bugs
Dalam poin ini, ada beberapa factor yang dapat memunculkan bug. 
Salah satunya adalah requirement yang belum lengkap atau detail. 
Untuk menguranginya, hendaknya menulis dahulu dari fitur 
yang akan dikerjakan sebelum memulai menulis code. 
Biasanya terdapat masalah pada kurangnya komunikasi 
antar team untuk membangun perangkat lunak yang maksimal.
c.	Don’t be a checker, be a tester
Tidak hanya mengecek, seorang tester harus melakukan 
pengecekan fungsional serta memahami betul kebutuhan user. 
Karena tidak cukup melakukan pengujian 
tanpa adanya masukan terhadap yang diuji. 
d.	Don’t try to break the system, instead help build the best possible system
Dalam poin ini, ada kalanya seorang penguji hendak melakukan improvement. 
Namun jika dilakukan berlebihan, 
hal itu dapat merusak sebuah sistemnya, 
bukan malah membangun menjadi lebih baik. Hal ini dapat 
terjadi jika mengerjakan masing-masing tidak dengan team.
e.	The whole team is responsible for quality, not just the tester.
Untuk melakukan testing, selutuh team hendaknya 
mengetahui pasti dan bertanggung jawab apa yang sedang diuji. 
Tidak hanya pengujinya saja, team juga yang 
berkualitas akan menghasilkan hasil yang berkualitas pula. 
