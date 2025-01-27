Tugas Pertemuan 9

Nama	: Rizky Muhamad Wicaksana <br>
NPM		4155050210010 <br>
Informatika A1 Machine Learning

K-Means Clustering dengan Data Konsumen <br>
	Perbedaan antara klasifikasi dan clustering <br>
Klasifikasi : data set yang digunakan memiliki label, atau menampilkan class (target attribute) <br>
Clustering : dataset yang digunakan tidak memiliki label, atau class (target attribute) <br>
	Tipe clustering <br>
o	Hierarchical clustering <br>
Data dikelompokan melalui suatu bagan yang berupa hirarki, dimana terdapat penggabungan dua grup yang terdekat disetiap iterasinya ataupun pembagian dari seluruh set data kedalam cluster <br>
o	Non – Hierarchical clustering <br>
Data dikelompokan ke dalam sejumlah cluster tanpa adanya struktur hirarki antara satu dengan yang lainnya. Setiap cluster memiliki titik pusat cluster (centroid) dan secara umum metode ini memiliki fungsi tujuan yaitu meminimumkan jarak (dissimilarity) dari seluruh data ke pusat cluster masing masing <br>
	Contoh metode clustering Algoritma K-MEANS <br>
o	K-MEANS merupakan salah satu metode data clustering non-hierarchical yang bertujuan mengelompokan N data yang ada kedalam K kelompok yang memiliki karakteristik serupa <br>
	Kelebihan dan kekurangan K-MEANS <br>
o	Kelebihan <br>
	Mudah untuk diimplementasikan dan dijalankan <br>
	Waktu yang dibutuhkan untuk menjalankan pembelajaran ini relative cepat <br>
o	Kelemhan <br>
	K buah titik diinisialisasi secara random sehingga pengelompokan data yang dihasilkan dapat berbeda dan jika inisialisasi kurang baik, pengelompokan menjadi kurang optimal <br>
	Dapat terjebak dalam masalah curse of dimensionalitiy jika data pelatihan memiliki dimesni yang sangan tinggi maka akan menjadi sulit <br>
	Studi kasus Algoritma K-MEANS <br>
Sebuah perusahaan melakuan penelitian terhadap data konsumen yang dimiliki, perusahan tersebut akan melakukan pengelompokan data ke dalam beberapa cluster berdasarkan kriteria besaran gaji yang diterima dan pengeluaran perbulannya. Berikut asalah data 20 konsumen dari perusahaan tersebut <br>
Studi kasus kali ini akan melakukan clustering terhadap data konsumen diatas kedalam beberapa kelompok, dimana masing masing kelompok memiliki tingkat kemiripan maksimum. Tujuan penelitian ini adalah agar perusahaan dapat memetakan jenis produk yang sesuai dengan karakteristik konsumen. <br>


1.	Koneksi dengan google drive <br>
![Image](https://github.com/user-attachments/assets/cfa6a1a0-7f7e-47d7-93c5-a28c1dd4fbc2) <br>

2.	Import Library Yang Dibutuhkan <br>
 ![Image](https://github.com/user-attachments/assets/b6b9baf2-75ee-469d-af2c-898932b03544) <br>
 
3.	Menyiapkan Data Set <br>
 ![Image](https://github.com/user-attachments/assets/cf57585d-9401-424d-8912-8246e163e74a) <br>
 
4.	Menggunakan Library K-Means <br>
 ![Image](https://github.com/user-attachments/assets/b60357c4-138e-455a-ad28-8cb4e064ac58) <br>

5.	Menampilkan Output <br>
![Image](https://github.com/user-attachments/assets/fb72f16a-0826-492a-aeb1-1eabc215999e) <br>
