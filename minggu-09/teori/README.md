Lingkungan Virtual (Virtual Environment):

Lingkungan virtual adalah direktori yang berisi instalasi Python terisolasi dari instalasi global.
Membuat lingkungan virtual memungkinkan Anda mengelola dependensi proyek secara terpisah.
Lingkungan virtual dapat mencegah konflik dependensi antarproyek.
Membuat Lingkungan Virtual:

Anda dapat membuat lingkungan virtual dengan menjalankan perintah python3 -m venv nama_folder di terminal.
Nama folder adalah direktori tempat lingkungan virtual akan dibuat.
Mengaktifkan Lingkungan Virtual:

Setelah lingkungan virtual dibuat, Anda perlu mengaktifkannya sebelum menggunakannya.
Di Linux/Mac, Anda dapat menjalankan source nama_folder/bin/activate.
Di Windows, gunakan nama_folder\Scripts\activate.
Menonaktifkan Lingkungan Virtual:

Untuk menonaktifkan lingkungan virtual, Anda dapat menjalankan perintah deactivate di terminal.
Menggunakan Lingkungan Virtual:

Setelah lingkungan virtual aktif, perintah python akan merujuk ke interpreter Python lingkungan virtual.
Anda dapat menginstal paket-paket dan dependensi proyek menggunakan pip seperti biasa.
Menghapus Lingkungan Virtual:

Untuk menghapus lingkungan virtual, cukup hapus direktori lingkungan virtual dari sistem file.
