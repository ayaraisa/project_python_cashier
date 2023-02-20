**Super Cashier**

**Latar Belakang**

Kasir merupakan salah satu kegiatan transaksi jual beli yang lumrah di pertokoan. Sistem kasir ini mememiliki beberapa fitur diantaranya adalah menjumlah barang belanja, membuat laporan rutin pembelian dan lain sebagainya. Pada project ini dibuat super cashier dengan menggunakan Bahasa Python yang diharapkan dapat berguna untuk mempermudah profesi kasir ke depannya

Objectives yang dibutuhkan

Dalam sistem kasir ini, terdapat feature-feature sebagai berikut:

a. Membuat proses untuk memasukkan ID Transaksi

b. Membuat proses untuk menambahkan barang yang ini dibeli dan detail jumlah dan harganya

c. Membuat proses untuk mengupdate detail barang yang sudah diinputkan sebelumnya jika ada kesalahan input

d. Membuat proses untuk menghapus salah satu pesanan yang telah diinputkan

e. Membuat proses untuk menghapus seluruh transaksi yang telah diinputkan

f. Membuat proses untuk memeriksa apakah seluruh data yang diinput sudah benar dan lengkap

g. Membuat proses untuk menghitung total belanja yang harus dibayarkan dan diskon yang didapatkan (jika dapat).

**Alur code atau Flowchart**

**Fungsi dan Atribut yang digunakan**

1. Init()

Metode instalasi untuk class Transaction

cart (dict) = dictionary untuk menyimpan data transaksi

![](Aspose.Words.96cdfee5-74c2-4ade-bae2-2f0f3ab1affb.001.png)

1. Add\_item

Metode untuk menambahkan item pada dict

Item\_name : str

Item\_qty : int

Item\_price : int

![Graphical user interface, text, application

Description automatically generated](Aspose.Words.96cdfee5-74c2-4ade-bae2-2f0f3ab1affb.002.png)

1. Update\_item\_name

Metode untuk mengganti nama pada item

.pop : untuk menghilangkan item\_name yang lama

.update : untuk mengganti item\_name dengan yang baru

![](Aspose.Words.96cdfee5-74c2-4ade-bae2-2f0f3ab1affb.003.png)

1. Update\_item\_qty

Metode untuk mengganti jumlah pada item

![Graphical user interface, text, application

Description automatically generated](Aspose.Words.96cdfee5-74c2-4ade-bae2-2f0f3ab1affb.004.png)

1. Update\_item\_price

Metode untuk mengganti harga pada item

![Graphical user interface, text, application

Description automatically generated](Aspose.Words.96cdfee5-74c2-4ade-bae2-2f0f3ab1affb.005.png)

1. Delete\_item

Metode untuk menghapus pesanan

![Text

Description automatically generated with medium confidence](Aspose.Words.96cdfee5-74c2-4ade-bae2-2f0f3ab1affb.006.png)

1. Reset\_item

Metode untuk menghapus seluruh pesanan

![A picture containing text

Description automatically generated](Aspose.Words.96cdfee5-74c2-4ade-bae2-2f0f3ab1affb.007.png)

1. Show\_order

Metode untuk menampilkan pesanan yang sudah terinput di dict

![Text

Description automatically generated](Aspose.Words.96cdfee5-74c2-4ade-bae2-2f0f3ab1affb.008.png)

1. Total\_price

Metode untuk menjumlahkan total belanja

![Table

Description automatically generated](Aspose.Words.96cdfee5-74c2-4ade-bae2-2f0f3ab1affb.009.png)

**Demonstrasi**

1. Menambahkan item

Customer ingin menambahkan dua item dalam daftar pesanan. Item tersebut adalah:

1. Ayam Goreng sebanyak 2 buah seharga 20.000
1. Pasta Gigi sebanyak 3 buah seharga 15.000

Method yang digunakan adalah add\_item

![Table

Description automatically generated with medium confidence](Aspose.Words.96cdfee5-74c2-4ade-bae2-2f0f3ab1affb.010.png)

1. Mengapus item

Customer ingin membatalkan pesanan Pasta Giginya

Method yang digunakan adalah delete\_item

![A picture containing box and whisker chart

Description automatically generated](Aspose.Words.96cdfee5-74c2-4ade-bae2-2f0f3ab1affb.011.png)

1. Menghapus  semua pesanan

Customer ingin membatalkan semua pesanan

Method yang digunakan adalah reset\_item

![](Aspose.Words.96cdfee5-74c2-4ade-bae2-2f0f3ab1affb.012.png)

1. Menghitung Total belanja

Customer ingin membayar belanjanya, sehingga diperlukan total  yang harus dibayar

Method yang digunakan adalah total\_price

![A picture containing table

Description automatically generated](Aspose.Words.96cdfee5-74c2-4ade-bae2-2f0f3ab1affb.013.png)

**Conclusion**



