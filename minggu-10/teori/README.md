Untuk mengakses basis data CockroachDB menggunakan Python, dapat menggunakan pustaka psycopg2 dan SQLAlchemy :

Menggunakan psycopg2:

Instal psycopg2 dengan perintah pip install psycopg2.
Impor modul psycopg2 ke dalam kode Python.
Buat objek koneksi menggunakan psycopg2.connect() dengan parameter host, port, database, user, dan password yang sesuai.
Buat objek kursor menggunakan metode connection.cursor().
Eksekusi perintah SQL menggunakan metode cursor.execute() dan dapatkan hasilnya menggunakan metode cursor.fetchall() atau cursor.fetchone().
Setelah selesai, tutup kursor dan koneksi menggunakan metode cursor.close() dan connection.close().

Menggunakan SQLAlchemy:

Instal SQLAlchemy dengan perintah pip install sqlalchemy.
Impor modul SQLAlchemy ke dalam kode Python.
Buat objek engine menggunakan create_engine() dengan URL koneksi CockroachDB yang sesuai.
Definisikan model menggunakan kelas dengan deklarasi basis menggunakan declarative_base() dan kolom menggunakan Column().
Buat sesi menggunakan sessionmaker(bind=engine) dan inisialisasi sesi dengan Session().
Gunakan sesi untuk menjalankan query menggunakan metode query() dan lakukan manipulasi data jika diperlukan.
Setelah selesai, tutup sesi menggunakan metode session.close().
Kedua pustaka tersebut memungkinkan Anda untuk terhubung ke CockroachDB dan menjalankan perintah SQL sesuai kebutuhan. Gunakan psycopg2 jika Anda ingin kontrol yang lebih langsung dan lebih rendah, sedangkan SQLAlchemy menyediakan lapisan ORM yang lebih tinggi dan memudahkan pengelolaan basis data.