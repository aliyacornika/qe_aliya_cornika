# 17 Behaviour Driven Development

BDD merupakan proses software development yg menerapkan
penulisan test case sebelum developer menuliskan
codenya, proses BDD sendiri berfokus pada komponen-
komponen dalam sistem dan test case ditulis dalam bahasa 
pemrograman. Serupa dengan TDD juga menerapkan konsep
test first, namun dengan fokus yang berbeda. Dalam BDD Test
team developer akan menerapkan scenario yang menjelaskan tentang 
behaviour sistem dari perspektif pengguna. Menggunakan format
bahasa yang mudah dipahami oleh seluruh stakeholder dalam
pengembangan sistem. Tujuan BDD adalah untuk 
meningkatkan komunikasi dan kolaborasi antara seluruh
stakeholder maupun teknikal yang terlibat dalam pengembangan sistem.

Komunikasi yang baik dapat menyatukan stakeholder yang
berbeda-beda. Fitur-fitur dapat memenuhi kebutuhan pengguna
dan business value. Prinsip dasar BDD adalah mendeskripsikan 
behaviour dalam sebuah sistem tanpa melibatkan penjelasan implementasinya
secara rinci. 

Dalam menuliskan test script untuk implementasi pengujian dan dasar
bagi developer dalam menuliskan implementation codenya untuk membangun sistem.

BDD Format
(feature dalam BDD dituliskan dalam bahasa gherkin)

1. User Story
- Tahap ini untuk menjelaskan kebutuhan pengguna dalam
functionalitas yang diharapkan.
2. As a [X], I want [Y], So that [Z]
- Menuliskan scenario dalam fitur menggunakan gherkin syntax
berdasarkan user storynya.
3. Scenario
- Mengimplementasikan text script berdasarkan scenario.  
4. Given, When, Then
Given: menjelaskan tentang konteks dari skenario
When: menjelaskan tindakan yang dilakukan oleh user
Then: menjelaskan outcome dari tindakan yang dilakukan oleh user
Contoh: feature (login), scenario (logging in existing user),
given (i go to my application login page),
when (i feel corect in username and password and click login), 
and then (i see my homepage).

Cucumber
Adalah tools untuk melakukan behaviour test (mendukung BDD).
Cucumber membaca semacam ketentuan untuk dieksekusi dimana
ditulis untuk menggunakan text biasa 


