Nama: Marshely Ayu Iswanto 

NIM: 2311102073

Kelas: IF-11-03

“MODUL 5”


Deskripsi Program 


No.1

Program tersebut merupakan program go yaitu merupakan implementasi deret Fibonacci menggunakan fungsi rekursif dalam bahasa Go. Fungsi ``fibonacci(n)'' menghitung suku ke-n deret Fibonacci dengan memanggil dua suku sebelumnya ``fibonacci(n-1)'' dan ``fibonacci(n-2)'' hingga titik terendah tercapai . Kondisi nilai jika 'n' adalah 0 atau 1. Fungsi ``main()'' menetapkan nilai ``n = 10'' dan menggunakan loop ``for'' untuk mencetak deret Fibonacci hingga suku ke-10. Meskipun pendekatan ini sederhana, rekursi bisa sangat tidak efisien ketika menghitung Fibonacci untuk nilai 'n' yang besar karena penghitungannya dilakukan berkali-kali. Output dari program tersebut adalah deret Fibonacci hingga suku ke-10


No.2 

Program Go ini mencetak pola bintang berbentuk segitiga dengan jumlah baris yang ditentukan oleh input pengguna. Fungsi utama 'starPattern' menggunakan rekursi untuk mencetak pola bintang, dimulai dari 1 bintang pada baris pertama hingga 'n' bintang pada baris terakhir. Fungsi 'printStars' digunakan untuk mencetak bintang pada setiap baris, dengan mencetak bintang sebanyak nilai yang diberikan secara rekursif. Program akan meminta pengguna untuk memasukkan jumlah baris ('n'), lalu mencetak pola bintang sesuai dengan nilai tersebut, di mana setiap baris bertambah satu bintang dibandingkan dengan baris sebelumnya. Input program ini adalah sebuah bilangan bulat n yang dimasukkan oleh pengguna, yang menentukan jumlah baris pada pola bintang yang akan dicetak. Pengguna diminta untuk memasukkan nilai tersebut melalui prompt "Masukkan jumlah baris:". Nilai n ini akan digunakan untuk menentukan berapa banyak baris yang akan dicetak, dengan jumlah bintang pada setiap baris bertambah satu setiap barisnya, dimulai dari 1 hingga n.


No 3

Program Go ini meminta pengguna untuk memasukkan sebuah bilangan n, kemudian mencetak semua faktor dari bilangan tersebut. Faktor adalah angka-angka yang dapat membagi n tanpa sisa. Fungsi printFactors menggunakan rekursi untuk memeriksa setiap angka mulai dari 1 hingga n, dan jika angka tersebut membagi n tanpa sisa (dengan kondisi n % i == 0), maka angka tersebut dicetak sebagai faktor. Fungsi rekursif ini terus dipanggil dengan menambah nilai i hingga mencapai nilai n, di mana pemeriksaan faktor berhenti. Hasil dari seluruh faktor yang ditemukan akan dicetak di layar. Program ini memungkinkan pengguna untuk dengan mudah menemukan dan menampilkan semua faktor dari bilangan yang dimasukkan, dimulai dari angka 1 hingga bilangan itu sendiri. 


No.4 

Program Go ini mencetak pola angka dengan cara menurun dari angka n hingga 1, lalu meningkat kembali ke angka n. Fungsi printPattern menggunakan rekursi untuk mencetak angka tersebut. Dimulai dengan mencetak angka current, kemudian fungsi akan memanggil dirinya sendiri dengan nilai current-1 hingga mencapai 1. Setelah mencapai 1, fungsi kembali mencetak angka-angka saat langkah rekursi berbalik. Fungsi utama meminta pengguna untuk memasukkan nilai n, yang menentukan batas angka pola yang akan dicetak. Setelah itu, fungsi printPattern dipanggil untuk mencetak pola angka mulai dari n hingga 1, lalu kembali ke angka n, menghasilkan pola simetris yang menurun dan meningkat.


No.5

Program Go ini mencetak bilangan ganjil mulai dari 1 hingga nilai n yang dimasukkan pengguna, dengan menggunakan rekursi. Fungsi printbilanganganjil dimulai dengan mencetak angka 1, kemudian memanggil dirinya sendiri dengan menambahkan 2 pada setiap langkah rekursi, yang menghasilkan angka ganjil berturut-turut. Proses rekursi berhenti ketika nilai current melebihi n. Fungsi utama meminta input n dari pengguna, yang menentukan batas atas untuk bilangan ganjil yang dicetak. Kemudian, fungsi printbilanganganjil dipanggil dengan parameter 1 untuk memulai pencetakan bilangan ganjil hingga mencapai batas yang ditentukan, mencetak hanya angka ganjil yang kurang dari atau sama dengan n.


No.6

Program Go ini menghitung hasil perpangkatan x^y menggunakan rekursi. Fungsi pangkat menerima dua parameter, yaitu x (bilangan dasar) dan y (eksponen), dan menghitung hasil perpangkatan dengan cara mengalikan x dengan hasil dari pemanggilan rekursif pangkat(x, y-1) hingga eksponen y mencapai 0. Ketika y bernilai 0, fungsi akan mengembalikan nilai 1, yang merupakan dasar dari hukum eksponen. Fungsi utama meminta input dari pengguna untuk nilai x (bilangan dasar) dan y (eksponen), kemudian memanggil fungsi pangkat untuk menghitung hasil perpangkatan tersebut. Setelah hasilnya dihitung, program akan mencetak hasil perpangkatan yang sesuai dengan nilai input yang diberikan oleh pengguna. Program ini menggunakan rekursi untuk mengurangi eksponen y satu per satu hingga mencapai 0.
