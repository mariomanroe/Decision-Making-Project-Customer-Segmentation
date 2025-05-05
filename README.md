# Decision Making Project | Customer Segmentation

## Deskripsi Dataset
Dataset [Online Retail II] (https://archive.ics.uci.edu/dataset/502/online+retail+ii ) berisi semua transaksi yang terjadi untuk perusahaan ritel online yang berbasis di Inggris dan terdaftar, tanpa toko fisik, antara tanggal 01/12/2009 dan 09/12/2011. Perusahaan ini utamanya menjual barang-barang hadiah serba guna yang unik. Banyak pelanggan perusahaan ini adalah pedagang grosir.
Dataset terdiri dari 525461 baris 8 fitur yaitu:
1. Invoice: Nomor Faktur. Nominal. Nomor integral 6 digit yang diberikan secara unik untuk setiap transaksi. Jika kode ini dimulai dengan huruf 'C', itu menandakan pembatalan.
2. StockCode: Kode Produk (barang). Nominal. Nomor integral 5 digit yang diberikan secara unik untuk setiap produk yang berbeda.
3. Description: Nama Produk (barang). Nominal.
4. Quantity: Jumlah dari setiap produk (barang) per transaksi. Numerik.
5. InvoiceDate: Tanggal dan waktu Faktur. Numerik. Hari dan waktu ketika transaksi dihasilkan.
6. UnitPrice: Harga per unit. Numerik. Harga produk per unit dalam mata uang pound sterling (£).
7. Customer ID: Nomor Pelanggan. Nominal. Nomor integral 5 digit yang diberikan secara unik untuk setiap pelanggan.
8. Country: Nama Negara. Nominal. Nama negara tempat pelanggan tinggal.


## KESIMPULAN
Setelah mengevaluasi beberapa algoritma clustering seperti K-Means, K-Means++, dan K-Medoids with BanditPAM++, ditemukan bahwa K-Means, K-Means++, dan K-Medoids memberikan hasil klaster yang dapat diandalkan. Namun, setelah pertimbangan lebih lanjut, hasil cluster dari K-Medoids dipilih untuk diimplementasikan dalam strategi bisnis dan pemasaran perusahaan.
Keputusan ini diambil setelah mempertimbangkan kejelasan interpretasi dan potensi implementasi strategi bisnis yang sesuai dengan karakteristik masing-masing klaster. Dengan menggunakan hasil klaster dari K-Medoids, langkah-langkah spesifik dalam pemasaran dan strategi bisnis dapat disesuaikan dengan karakteristik unik dari setiap kelompok pelanggan. Ini memungkinkan penggunaan strategi yang lebih terarah dan sesuai dengan kebutuhan tiap klaster untuk meningkatkan keuntungan perusahaan.
