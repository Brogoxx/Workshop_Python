Dokumen yang terkait adalah dokumentasi resmi Python untuk penanganan kesalahan 
(error handling). Materi tersebut menjelaskan tentang konsep penanganan kesalahan 
dalam Python dan cara menggunakannya dengan menggunakan pernyataan try, except, 
else, finally, serta penggunaan kelas pengecualian (exception classes).

1.Pendahuluan:
Penanganan kesalahan adalah teknik yang digunakan untuk mengatasi kesalahan atau 
situasi yang tidak terduga saat program dieksekusi.
Python menggunakan objek pengecualian (exception objects) untuk mewakili kesalahan
dan kondisi tidak normal lainnya.

2.Membangkitkan Pengecualian (Raising Exceptions):
Pengecualian dapat dibangkitkan dengan menggunakan pernyataan raise.
Pengecualian yang dibangkitkan dapat diberikan pesan atau argumen tambahan yang 
menjelaskan alasan pemanggilan pengecualian.

3.Menangkap Pengecualian (Catching Exceptions):
Pernyataan try digunakan untuk memasukkan blok kode yang mungkin membangkitkan 
pengecualian.
Pernyataan except digunakan untuk menangkap pengecualian yang dibangkitkan oleh 
blok try.
Dalam pernyataan except, kita dapat menentukan tipe pengecualian yang akan 
ditangkap, atau menangkap semua pengecualian menggunakan pernyataan except 
Exception.

4.Else dan Finally:
Pernyataan else dapat digunakan setelah blok try-except untuk mengeksekusi kode 
jika tidak ada pengecualian yang dibangkitkan.
Pernyataan finally dapat digunakan setelah blok try-except untuk mengeksekusi 
kode yang harus dijalankan baik terjadi pengecualian maupun tidak.

5.Pengecualian Terdefinisi dengan Baik (Defining Clean-up Actions):
Pernyataan try-except dapat digunakan bersama dengan pernyataan with untuk 
menangani sumber daya yang perlu dibersihkan secara otomatis setelah digunakan, 
seperti membuka file atau mengakses database.

6.Pengecualian Bersarang (Nested Exceptions):
Pengecualian dapat bersarang, artinya pengecualian dalam blok except dapat 
membangkitkan pengecualian baru yang kemudian dapat ditangkap oleh blok except 
lainnya.

7.Menentukan Pengecualian Kustom (Defining Custom Exceptions):
Python memungkinkan kita untuk membuat kelas pengecualian kustom dengan mewarisi 
dari kelas Exception.
Dengan kelas pengecualian kustom, kita dapat membangun hierarki pengecualian yang 
sesuai dengan kebutuhan aplikasi.