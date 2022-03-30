# 21 Fundamental Performance Test
Teknik non functional testing untuk
menentukan parameter sistem dalam
hal responsif dan stabilitas dibawah 
berbagai beban (load) kerja.
Performance testing mengukur kualitas
atribut dari sistem seperti stabilitas,
ketahanan (reliability) dan penggunaan
sumber daya.

Yang diukur dari performance test:
1. Performa suatu aplikasi sampai suatu 
batas tertentu.
2. Bukan merupakan functional-test.
3. Dapat dalam berbagai macam bentuk untuk
memahami reliability, stability, dan availability
pada environment-nya. Contoh:
- Mengamati response time ketika menjalankan
request dalam jumlah yang sangat banyak.
- Melihat suatu sistem berinteraksi dengan
jumlah data yang cukup besar.

Metode Performance Test
- Membuat Test Plan: Kenali yang dibutuhkan, 
Endpoint yang akan ditest, Kebutuhan 
masing-masing endpoint.
- Menentukan Metode Test: Pilih berdasarkan
kondisi sistem, apakah belum pernah dites
atau sudah, Pilih berdasarkan situasi
yang akan dihadapi.
- Some Types of Performance Test:
Load test, Endurance test, Stress test,
Peak test.

Smoke Testing
Dilakukan untuk verify script yang sudah dibuat,
apakah sistem tersebut dapat handle minimal load,
tanpa masalalh sama sekali. Biasanya hanya 1-2 VUs.

Load Testing
Pengujian yang paling sederhana yang dilakukan
untuk memahami perilaku sistem dalam keadaan 
beban tertentu. Hasil dari load test digunakan 
untuk mengukur kepentingan bisnis saat transaksi
yang kritis dengan memonitor dampak terhadap
database, application server atau pendukung lainnya.

Stress Testing
Metode dilakukan untuk mengamati kemampuan
dan kestabilan sistem pada saat kondisi ekstrem.
Dilakukan bertahap menuju load normal, puncak, dan
melebihinya, lalu turun untuk melihat proses recovery.

Spike Testing
Sama seperti stress testing, namun kenaikan langsung
menuju melebihi puncak dilakukan dalam waktu singkat. 
Jika stress test memberikan waktu untuk scale-out, 
disini tidak. 

Soak Testing
Untuk mengetahui reliability ketika dalam tekanan 
di bawah puncak dalam jangka panjang (>=1 jam). 
Dapat mengetahui apakah terdapat bug pada race condition,
memory leaks, db connection dan sebagainya.

