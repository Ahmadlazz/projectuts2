# projectuts2
Nama_NIM_Github:

Ahmad Paesoel_2501010143_Ahmadlazz

Ida Bagus Nyoman Adi Tresna Wijaya_2501010111_gusmanwijaya

Kadek Ega Dwi Putra_2501010100_Inazura



Studi kasus yang di ambil:
Sistem History Browser

A.Rumusan masalah dan Solusi 

1.Bagaimana peran struktur data queue dalam menyimpan dan menampilkan riwayat kunjungan website pada sistem browser history?

2.Bagaimana penggunaan struktur data array dalam menyimpan dan mengelola data history pada sistem browser?

3.Bagaimana sistem browser history yang dirancang dapat membantu pengguna dalam mengelola aktivitas penelusuran internet?

Solusi yang ditawarkan oleh sistem

1.Pada konsep struktur data, queve bekerja dengan prinsip FIFO (First in First out), yaitu data pertama yang diakses maka data tersebut yang diproses terlebih dahulu.
Pada studi kasus jurnal yang saya gunakan ini adalah, sistem yang pernah dikunjungi akan disimpan oleh sistem dan jika pengguna ingin mencari pencariannya yang sebelumnya maka ia dapat melihatnya melalui fitur history pada browser, dan pada fitur tersebut pencariannya sudah teratur dan disimpan secara berurutan sesuai yang pernah dicari pengguna.
Dalam sistem browser history, setiap website yang dikunjungi oleh pengguna akan ditambahkan ke dalam daftar history. Website tersebut disimpan secara berurutan sesuai dengan waktu kunjungan. Dengan menggunakan queue, sistem dapat menampilkan riwayat website secara terstruktur mulai dari halaman yang pertama hingga halaman yang terakhir dikunjungi.

Dengan ini pengguna lebih mudah untuk mengakses situs yang sebelumnya ia kunjungi tanpa khawatir tidak disimpan.

2.Struktur data array digunakan dalam sistem browser history untuk menyimpan dan mengelola data halaman website yang dikunjungi oleh pengguna. Dalam bahasa pemrograman Python, array direpresentasikan menggunakan list, yang memungkinkan penyimpanan data secara berurutan.
Penggunaan array memungkinkan sistem untuk menyimpan data website secara berurutan sesuai dengan urutan kunjungan. Selain itu, array juga mempermudah proses pengolahan data seperti penambahan dan penghapusan data dalam sistem.

Dalam implementasi program browser history, array digunakan sebagai dasar untuk membangun struktur data stack dan queue yang berfungsi dalam pengelolaan navigasi halaman serta penyimpanan riwayat browsing pengguna.

Dengan menggunakan array, sistem dapat mengelola data website secara lebih sederhana dan terstruktur.

3.Sistem browser history yang dirancang bertujuan untuk membantu pengguna dalam mengelola aktivitas penelusuran internet dengan mencatat setiap halaman website yang pernah dikunjungi.

Dalam sistem ini digunakan struktur data stack dan queue untuk mengatur navigasi serta penyimpanan riwayat browsing. Stack digunakan untuk mengelola fitur back dan forward pada browser dengan menggunakan konsep LIFO (Last In First Out), sedangkan queue digunakan untuk menyimpan daftar website yang pernah dikunjungi dengan konsep FIFO (First In First Out).

Dengan adanya sistem ini, pengguna dapat kembali ke halaman sebelumnya, berpindah ke halaman berikutnya, serta melihat daftar website yang pernah diakses. Hal ini memudahkan pengguna dalam menemukan kembali informasi yang pernah dicari sebelumnya.

Dengan demikian, sistem browser history dapat membantu meningkatkan efisiensi dan kenyamanan pengguna dalam melakukan aktivitas penelusuran di internet.

B.Landasan Teori

1. Pengertian Struktur Data

Struktur data adalah cara atau metode yang digunakan untuk mengorganisasi, menyimpan, dan mengelola data dalam komputer sehingga data tersebut dapat diakses dan diproses dengan lebih efisien.

Dalam pemrograman, struktur data sangat penting karena menentukan bagaimana data disimpan serta bagaimana operasi seperti pencarian, penambahan, dan penghapusan data dilakukan.

Beberapa contoh struktur data yang sering digunakan antara lain array, linked list, stack, queue, tree, dan graph. Pemilihan struktur data yang tepat dapat membantu meningkatkan efisiensi dan kinerja suatu program.

2. Konsep Queue dan Stack
Stack

Stack merupakan struktur data yang bekerja dengan prinsip tumpukan, dimana data yang terakhir dimasukkan akan menjadi data pertama yang diambil.

Operasi utama pada stack yaitu:

Push → menambahkan data ke dalam stack

Pop → menghapus data dari stack

Peek → melihat data paling atas tanpa menghapusnya

Contoh penggunaan stack dalam kehidupan sehari-hari adalah tumpukan piring. Piring yang terakhir diletakkan di atas akan menjadi piring pertama yang diambil.

Dalam sistem browser history, stack digunakan untuk mengatur fitur Back dan Forward pada halaman website.

Queue

Queue merupakan struktur data yang bekerja seperti antrian, dimana data yang pertama masuk akan menjadi data pertama yang diproses.

Operasi utama pada queue yaitu:

Enqueue → menambahkan data ke dalam antrian

Dequeue → menghapus data dari antrian

Contoh penggunaan queue dalam kehidupan sehari-hari adalah antrian di bank atau loket tiket, dimana pelanggan yang datang lebih dahulu akan dilayani terlebih dahulu.

Dalam sistem browser history, queue digunakan untuk menyimpan daftar website yang pernah dikunjungi oleh pengguna.

3. Konsep FIFO dan LIFO
FIFO (First In First Out)

FIFO adalah konsep dimana data yang pertama masuk akan menjadi data yang pertama keluar.

Konsep ini biasanya digunakan pada struktur data queue. Contohnya adalah sistem antrian di tempat pelayanan seperti bank atau rumah sakit.

Dalam sistem browser history, FIFO digunakan untuk menyimpan urutan website yang dikunjungi oleh pengguna, sehingga website yang pertama dikunjungi akan berada pada urutan awal dalam daftar history.

LIFO (Last In First Out)

LIFO adalah konsep dimana data yang terakhir masuk akan menjadi data yang pertama keluar.

Konsep ini digunakan pada struktur data stack. Contohnya adalah tumpukan buku atau piring, dimana objek yang terakhir diletakkan akan diambil terlebih dahulu.

Dalam sistem browser history, konsep LIFO digunakan untuk fitur Back, dimana halaman terakhir yang dibuka akan menjadi halaman pertama yang kembali ketika pengguna menekan tombol kembali.

4. Implementasi Menggunakan Array atau Linked List

Struktur data seperti stack dan queue dapat diimplementasikan menggunakan array maupun linked list.

Implementasi menggunakan Array

Array adalah struktur data yang menyimpan elemen secara berurutan dalam satu blok memori. Dalam bahasa pemrograman Python, array dapat direpresentasikan menggunakan list.

Kelebihan penggunaan array antara lain:

• akses data lebih cepat menggunakan indeks

• implementasi lebih sederhana

• mudah digunakan dalam pemrograman

Dalam sistem browser history yang dibuat, array digunakan untuk menyimpan data history serta mengimplementasikan struktur data stack dan queue.

Implementasi menggunakan Linked List

Linked list adalah struktur data yang terdiri dari beberapa node yang saling terhubung. Setiap node memiliki dua bagian, yaitu data dan pointer yang menunjuk ke node berikutnya.

Kelebihan linked list antara lain:

• ukuran penyimpanan lebih fleksibel

• mudah menambahkan atau menghapus data

• tidak memerlukan ukuran tetap seperti array

Linked list sering digunakan dalam implementasi struktur data yang memerlukan penambahan dan penghapusan data secara dinamis.


Selanjutnya ini adalah simulasi sistem history browser

Code:
<img width="1281" height="665" alt="image" src="https://github.com/user-attachments/assets/d4e4be21-defd-4bf8-b0a3-235ef6cae352" />
<img width="1288" height="222" alt="image" src="https://github.com/user-attachments/assets/fc1768c9-e633-45de-bcad-b3fe95220067" />
<img width="1288" height="222" alt="image" src="https://github.com/user-attachments/assets/6e224b54-8a96-4765-a9c8-b4cbf6e36e99" />

Uji coba sistem browser:

ini adalah menu navigasi yang pertama ini digunakan oleh user ketika ingin mengunjungi sebuah website seperti ada digambar web yang di cari adalah Youtube, Instagram, Spotify, Google
<img width="1171" height="596" alt="image" src="https://github.com/user-attachments/assets/1ac878a1-59d0-4715-8089-40de376c03ab" />

Menu yang kedua adalah back ini adalah perintah yang digunakan untuk kembali ke website yang sebelumnya dikunjungi misalnya Youtube → Instagram → Spotify → Google, maka ketika menu back tersebut dipilih akan terjadi perpindahan dari web google → Spotify dikarenakan web google tersebut adalah halaman yang terakhir dikunjungi dikarenakan menggunakan sistem LIFO(last in first out).

<img width="1307" height="324" alt="image" src="https://github.com/user-attachments/assets/41fbed0a-25d2-4b54-9f31-4d7e12ad5f69" />

Menu ketiga adalah Forward ini berkebalikan dengan menu back, menu back digunakan untuk mengunjungi halaman yang sebelumnya sedangkan forward ini digunakan untuk perintah ke halaman selanjutnya.
<img width="1307" height="475" alt="image" src="https://github.com/user-attachments/assets/5b5da020-3756-48eb-8582-9bcdaa17a20c" />

Menu keempat adalah inti dari project ini yaitu history browser, menu ini ketika dipilih akan menampilkan hasil browser yang sebelumnya kita kunjungi dan akan tetap disimpan oleh sistem jadi pengguna tidak lelah untuk mencari halaman yang ingin dikunjungi lagi.
<img width="1309" height="237" alt="image" src="https://github.com/user-attachments/assets/f5863d88-ac36-4f2d-93c8-4d95ca974b52" />

Menu kelima ini adalah keluar, menu ini ditunjukan sebagai perintah untuk sistemnya berhenti untuk bekerja, karena jika kita tidak memerintahkan sistemnya untuk keluar maka sistem tersebut akan terus berjalan.
<img width="1306" height="159" alt="image" src="https://github.com/user-attachments/assets/d9dbd8ae-7395-4cba-aef8-1475a65360fa" />

Diagram_Flowchart yang kami gunakan
<img width="990" height="589" alt="image" src="https://github.com/user-attachments/assets/5faa8f1a-2452-431c-8895-b53d4eea0045" />
<img width="1001" height="253" alt="image" src="https://github.com/user-attachments/assets/de3085e1-eb4c-4d8d-b76d-1f3d15ace94b" />
<img width="999" height="226" alt="image" src="https://github.com/user-attachments/assets/d44404ca-bd5c-4218-9daa-c842bd9c0952" />






Untuk yang terakhir Judul dari refrensi yang kami gunakan dari project

Pada studi kasus ini kami menggunakan 3 jurnal sebagai refrensi

1.Arlina, K. A. A., & Astuti, Y. Pemanfaatan History pada Browser Komputer untuk Menentukan Pemilihan Website atau Blog pada SEO Indonesia.

2.Fitra, M. R. A., Pratama, E., Al-Kautsar, M. Z., Harahap, F. A., & Ramadhani, F. (2025). Implementasi Struktur Data Stack untuk Pengelolaan Riwayat Penelusuran dalam Bentuk Ekstensi Web Browser Chrome. Indonesian Journal of Education and Development Research (IJEDR).

3.Syahputra, A. K. Internet dan Website: Search Engine dan Web Browser. STMIK Royal Kisaran.
