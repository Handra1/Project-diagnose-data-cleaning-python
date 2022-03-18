# Project-diagnose-data-cleaning-python
This project about learning diagnose data for cleaning in python (In Indonesia)

Cleaning data adalah sebuah proses mempersiapkan dataset untuk kita analisis. Hal tersebut menjadi bagian penting, karena data tidak pernah ada dalam hasil yang “clean”. 
Berikut ini contoh umum permasalahan data yang perlu kita bersihkan:
- Inconsistent column name: Nama kolom memiliki inkonsistensi kapitalisasi atau bad character.
- Missing Data : Data yang hilang perlu kita identifikasi.
- Outliers : Dapat menimbulkan masalah potensial dan perlu diselidiki.
- Duplicate rows : Dapat dilakukan analisis lalu kita temukan.
- Untidy :  Dapat mengandung banyak masalah dan mencegah kita mengubah dataset yang cocok untuk dilaporkan ke dataset yang sesuai untuk analisis.
- Need to process columns: Sebelum kolom bisa kita gunakan untuk analisis.
- Column types can signal unexpected data values: Tipe kolom dapat menandakan keberadaan nilai data yang tidak terduga.

Gunakan package Pandas dengan perintah read_csv untuk membaca file tersebut berdasarkan lokasi penyimpanan file.
Visually Inspect: Untuk menampilkan 5 baris pertama gunakan atribute perintah head(), Untuk menampilkan 5 baris terakhir gunakan atribute perintah tail(),
Untuk menampilkan nama kolom gunakan atribute  perintah columns, Untuk melihat jumlah baris dan kolom data gunakan atribute perintah shape.
Untuk mengetahui informasi tambahan gunakan atribute perintah info().
Hasilnya objek dataframe di pandas dengan 162 baris dan 5 kolom. Kolom populasi hanya memiliki 156 values, sehingga kita mengetahui jika data yang hilang (missing data) sebanyak 162 - 156 = 6 data yang hilang.
