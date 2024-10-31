Penjelasan Unguided 1

Program diatas menghitung permutasi dan kombinasi berdasarkan input 
yang diberikan oleh pengguna. Program ini juga memeriksa apakah syarat 
input terpenuhi sebelum melakukan perhitungan. Fungsi ini menghitung 
faktorial dari suatu bilangan n. Faktorial adalah hasil perkalian semua 
bilangan bulat positif kurang dari atau sama dengan n. Fungsi ini digunakan 
untuk menghitung permutasi, yaitu banyaknya cara mengatur r elemen dari 
n elemen yang berbeda. Program ini meminta empat angka dari pengguna 
dan menghitung permutasi serta kombinasi untuk dua pasang angka (a, c 
dan b, d), tetapi hanya jika syarat a >= c dan b >= d terpenuhi.

Penjelasan Unguided 2

Program ini adalah program sederhana yang digunakan untuk menentukan 
pemenang dari sebuah kompetisi berdasarkan seberapa banyak soal yang 
dijawab peserta dan waktu yang mereka habiskan untuk menjawabnya. 
Program membaca input baris demi baris hingga pengguna mengetik 
"Selesai". Fungsi hitungSkor digunakan untuk menghitung jumlah soal 
yang dijawab peserta dalam waktu yang lebih kecil atau sama dengan 300 
detik. Hanya soal yang selesai dalam waktu ≤ 300 detik yang dihitung. 
Nama peserta dengan skor terbanyak dan waktu total paling sedikit 
disimpan dalam variabel pemenang. Ketika input "Selesai" diberikan, 
program akan menampilkan nama pemenang, jumlah soal yang dijawab, 
dan total waktu yang dihabiskan untuk soal-soal tersebut.

Penjelasan Unguided 3

Program ini adalah program yang menghasilkan deret angka berdasarkan 
aturan dari Collatz conjecture, yaitu aturan matematika yang mengatakan 
bahwa jika kita mengambil bilangan positif apa pun, mengikuti langkah
langkah tertentu, akhirnya kita akan selalu mencapai angka 1. Jika n adalah 
bilangan genap, maka kita bagi n dengan 2 (n = n / 2). Jika n adalah bilangan 
ganjil, kita kalikan n dengan 3 lalu ditambah 1 (n = 3 * n + 1). Program 
membatasi input n pada rentang 1 hingga 999.999. Hal ini dilakukan untuk 
memastikan bahwa input valid dan menghindari masalah performa jika 
pengguna memasukkan bilangan yang sangat besar.