# Data Latih Training SQLite

## About

Data latih ini adalah data dummy penjualan dari sebuah toko online. 

Ada dua data yang disediakan 

1. Data Customer: Data digenerasi menggunakan openAI, digunakan untuk data latihan dasar-dasar SQL.  
2. Data Sales: Data digenerasi dari data generator di [https://github.com/KeithGalli/Pandas-Data-Science-Tasks/tree/master/Misc] yang sudah disesuaikan dengan kebutuhan.

Catatan: Dua data diatas tidak saling berhubungan. Data Customer digunakan untuk belajar dasar SQL dan data sales digunakan untuk belajar analisis penjualan.

Kita akan belajar mengolah data tersebut dengan menggunakan [https://sqlitestudio.pl]

## Data
Data terdiri dari data dummy penjualan bulan januari sampai dengan desember 2021. Dan data kumpulan dari semua data penjualan tersebut.

## Import data ke SQLite Studio
- Buatlah sebuah database dengan nama `sales`
- Buatlah sebuah tabel dengan nama `sales_data` dan import data dari file `All_Sales_2021.csv` ke dalam tabel tersebut.

Catatan: Kamu bisa mencoba data bulanan terlebih dulu, jika sudah menguasai data bulanan, kamu bisa mencoba data kumulatif.

## Data Cleaning/Preprocessing
Data yang ada dalam data latih tersebut  masih mengandung beberapa kesalahan, seperti:
- Data Kosong
- Data yang tidak sesuai dengan data yang seharusnya
- Format tanggal dan jam yang tidak siap untuk diolah.

Lalu lakukan pembersihan dan pemrosesan data tersebut agar data bisa diolah, dengan cara:
- Menghapus data yang kosong
- Menambahkan Kolom Kota
- Menambahkan Kolom Provinsi
- Menambahkan Kolom Bulan
- Menambahkan Kolom Tanggal
- Menambahkan Kolom Jam
- Mengubah format tanggal dan jam menjadi format yang siap untuk diolah.


## Data Analysis

Analisis data menggunakan SQL dan apa informasi yang bisa diambil dari data tersebut.

- Menghitung total penjualan per bulan
- Menghitung total penjualan per kota
- Menghitung total penjualan per provinsi
- Menghitung total penjualan per tanggal
- Menghitung total penjualan per jam    
- Mencari Bulan dengan penjualan tertinggi
- Mencari Kota dengan penjualan tertinggi
- Mencari Provinsi dengan penjualan tertinggi
- Mencari Tanggal dengan penjualan tertinggi
- Mencari Jam dengan penjualan tertinggi
- Mencari Tau Produk-Produk Mana Saja Yang Sering Terjual Secara Bersamaan
- Mencari Produk yang Paling Banyak Terjual
- Mencari Produk yang Paling Banyak Terjual di Kota tertentu
- Mencari Produk yang Paling Banyak Terjual di Provinsi tertentu
- Mencari Produk yang Paling Banyak Terjual di Tanggal tertentu
- Mencari Produk yang Paling Banyak Terjual di Jam tertentu 
- Mencari Produk yang Paling Banyak Terjual di Bulan tertentu

Dan sebangainya ...

### Terimakasih
















