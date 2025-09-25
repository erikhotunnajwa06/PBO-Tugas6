# Deskripsi
Tugas ini memberikan pemahaman menyeluruh tentang bagaimana membangun aplikasi CRUD yang terintegrasi dengan database, merancang antarmuka GUI berbasis Java Swing, serta memanfaatkan Dialog Modal untuk memastikan alur kerja yang lebih aman, terkontrol, dan sesuai kaidah OOP.
# Koneksi NetBeans dengan PostgreSQL
Koneksi antara NetBeans dan PostgreSQL merupakan langkah penting dalam pengembangan program berbasis database. PostgreSQL adalah sistem manajemen basis data relasional open-source yang handal dan banyak digunakan. NetBeans sebagai Integrated Development Environment (IDE) menyediakan kemudahan dalam mengelola proyek Java yang terintegrasi dengan database PostgreSQL melalui JDBC (Java Database Connectivity). Dengan koneksi ini, pengembang dapat melakukan operasi CRUD (Create, Read, Update, Delete) secara langsung dari aplikasi Java yang dibuat di NetBeans.
# JFrame Form
JFrame adalah salah satu class utama di Java Swing yang dipakai untuk membuat window (jendela GUI).
Bisa diibaratkan sebagai kanvas utama tempat kamu menempelkan komponen lain seperti:
JLabel → menampilkan teks
1. JTextField → input teks
2. JButton → tombol
3. JTable → tabel data
4. JPanel → panel sebagai wadah tata letak
Jadi kalau di dunia nyata, JFrame itu kerangka jendela, sedangkan komponen Swing lain itu isinya.
# Dialog Modal
Dialog Modal adalah sebuah jendela dialog dalam pemrograman Java Swing yang muncul di atas jendela utama (JFrame) dan bersifat memblokir interaksi pengguna dengan jendela utama sampai dialog tersebut ditutup. Dengan sifat modal ini, pengguna hanya dapat berinteraksi dengan dialog tersebut, misalnya untuk mengisi form atau memberikan konfirmasi, sebelum kembali ke aplikasi utama. 
# Dialog Insert, Update, dan Delete
Dalam source code di JFrame Form Data Sembako ada beberapa code untuk diimplementasikan dengan designnya.
1. Dialog Insert: Menambahkan data baru ke dalam tabel.
2. Dialog Update: Memperbarui data yang sudah ada di tabel.
3. Dialog Delete: Menghapus data dari tabel.
4. Select Table: Mengambil dan menampilkan data dari tabel.
