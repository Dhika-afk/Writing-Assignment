# **Javascript Intermediate**
 ![alt text](1.png)

## **Array**
Merupakan sebuah tipe data berupa list order yang mampu menyimpan beragam tipe data. Array dapat menyimpan tipe data berupa String, Number, Boolean dll.<br>
 ![alt text](2.png)

Cara membuat dan memanggil Array:<br>
![alt text](3.png)<br>
![alt text](4.png)<br>
![alt text](5.png)<br>
![alt text](6.png)

## **Array Method**
-	.push()
untuk menambahkan elemen dari array<br>
![alt text](7.png)
 
-	.pop()
untuk mengurangi elemen dari array<br>
![alt text](8.png)
 
-	.unshift()
Digunakan menghapus elemen array di awal array<br>
![alt text](9.png)
 
-	.shift()
Digunakan untuk menambahkan elemen array di awal array<br>
![alt text](10.png)
 
-	.sort
Digunakan untuk mengurutkan elemen dari array.<br>
![alt text](11.png)
 

Looping Array
-	map()
map() melakukan perulangan/looping dengan membuat array baru.<br>
 ![alt text](12.png)

-	foreach
forEach() adalah method untuk melakukan looping pada setiap elemen array<br>
 ![alt text](13.png)


## **Multidimensional Array**
Multidimensional array merupakan sebuah array di dalam array<br>
 ![alt text](14.png)
 

## **Method Multidimensional Array**
Pada multidimensional array juga memiliki method built in yang sama juga seperti array sebelumnya yaitu push(), pop(), shift(), unshift(), sort().
Contoh:<br>
 ![alt text](15.png)

## **Looping Multidimensional Array**
Multidimensional array juga dapat melakukan perulangan seperti array pada umunya dengan method map dan foreach.<br>
-	Map()<br>
 ![alt text](16.png)<br>
 ![alt text](18.png)

-	Foreach()<br>
 ![alt text](19.png)

-	For loop<br>
![alt text](20.png)
 

## **Object**
Object adalah sebuah variable yang menyimpan nilai(properti) dan fungsi(method)

Contoh object<br>
 ![alt text](21.png)

## **Cara membuat sebuah object:**
-	Membuat dan memanggil object<br>
    ![alt text](22.png)
    
-	Memanggil property dalam object<br>
    ![alt text](24.png)

 
 

## **Update and delete Object**
-	Object dapat mengupdate value dari key yang sudah tersedia<br>
 ![alt text](25.png)

-	Object dapat menambahkan key dan value baru<br>
 ![alt text](26.png)

-	Delete Object<br>
 ![alt text](27.png)


## **Method**
Value pada property berupa function dapat disebut juga sebagai method.

```
Contoh:
Consol.log
Console adalah global javascript object
Log() adalah property yang berupa function dari object console.
```
## **Nested Object**
Object yang berasal dari turunan object lainnya atau objek di dalam objek.<br>
![alt text](28.png)

## **Pass by Reference**
Mengubah data pada sebuah object melalui function dengan cara memasukkan object sebagai parameter function.<br>
 ![alt text](29.png)

## **Looping Object**
 ![alt text](30.png)

## **Looping array of object**
Arrayof object merupakan object berbentuk array yaitu dapat menyimpan lebih dari satu data.<br>
 ![alt text](31.png)<br>
 ![alt text](32.png)
 


## **Recursive**
Merupakan function yang memanggil dirinya sendiri hingga mencapai suatu kondisi tertentu. Biasanya digunakan pada case matematika, fisika, kimia dan yang berhubungan dengan calculation


## **Ciri-ciri rekursive**
-	Memiliki kondisi yang menyatakan kapan fungsi tersebut akan berhenti.
-	Fungsi rekursif selalu memanggil dirinya sendiri sambil mengurangi atau memecahkan data masukan setiap panggilannya.<br>
Contoh kasus rekurisive
 ![alt text](33.png)

## **REGEX**
Regex adalah singkatan dari Regular Expresion.
Regex merupakan sebuah teks (string) yang mendefinisikan sebuah pattern/pola untuk pencarian sehingga dapat membantu kita untuk melakukan matching (pencocokan), locate (pencarian), dan manipulasi teks.<br>
 ![alt text](34.png)


## **Berikut ini beberapa contoh pemanfaatan regex dalam pemrograman:**
1.	Regex untuk Validasi Data
Digunakan untuk matching atau pencocokan teks.
2.	Regex untuk Pencarian
penerapan regex untuk pencarian sebenarnya hampir sama dengan validasi data. Pola regex dimasukan dalam kata kunci, lalu dicocokan dengan database atau teks.
3.	Regex untuk Find and Replace
untuk mengelola teks dan konten lebih efisien.

## **Contoh kasus REGEX**
-	Validasi input dari sebuah FORM
-	Mencari keyword tertentu pada email atau halaman web
-	Mencari IP address dalam kisaran tertentu
-	Dan masih banyak lagi

## **Regex Method**
-	Test()
test() mengembalikan nilai BOOLEAN (TRUE/FALSE) untuk kecocokan sebuat text yang dicari.<br>
![alt text](35.png) 
 
-	Match()
match() mengembalikan nilai array dari karakter yang match.<br>
 ![alt text](37.png)<br>
 ![alt text](38.png)
 

## **Flags regex**
flags	Keterangan
- g = Global Search
- i	= Case Sensitive
- m	= Multiline
- s	= Allow . character
- u	= Unicode Support
- y	= Sticky Search

## **Javascriot Object Oriented (OOP)**
Merupakan metode pemrograman yang berorientasi kepada objek. Tujuan dari OOP untuk mempermudah dalam pengembangan program dengan cara mengikuti model yang telah ada di kehidupan sehari-hari.

## **4 Pilar pada OOP:**
1.	Encapsulation
Membatasi akses ke property atau method dari sebuah objek.<br>
![alt text](39.png)
 
2.	Inheritance
Mewariskan property dan methodnya ke dalam class lain atau childnya(turunan).<br>
 ![alt text](40.png)

3.	Polymorpishm
Polymorphism adalah kemampuan untuk membuat variabel, fungsi, atau objek yang memiliki banyak bentuk.<br>
 ![alt text](41.png)

4.	Abstraction
Menyumbunyikan detail tertentu dari sebuah objek dan menampilkan fungsionalitas atau fitur penting dari  objek tersebut.<br>
![alt text](42.png)
 


## **Javascript Module**
Merupakan sebuah file-file Javascript yang di dalamnya terdapat value dari objects, functions, dan variables. Kemudian file tersebut dapat diexport dan diimport oleh file lain
-	export : kata kunci variabel label dan fungsi yang bisa diakses diluar modul saat ini.
-	import : memperbolehkan impor fungsi dari modul lain.

## **Manfaat module js:**
-	Mudah menemukan dan mengatasi debug pada program
-	Membuat program menjadi component-component kecil
-	Reusable code

Contoh cara export pada file greetings.js<br>
 ![alt text](43.png)

Contoh import pada file index.js<br>
 ![alt text](44.png)

## **Web Storage**
Web storage adalah salah satu Web API yang dapat menyimpan data secara lokal pada sisi client. data yang disimpan pada Web Storage akan bertahan lebih lama karena data akan disimpan pada storage browser
Tipe Web StorageWeb API menyediakan dua tipe Web Storage untuk kita gunakan, yakni sessionStorage dan localStorage

## **Tipe web Storage yang umum digunakan oleh front end**
-	Local storage, 
Local Storage adalah jenis penyimpanan web yang memungkinkan situs dan aplikasi menyimpan dan mengakses data langsung di browser tanpa tanggalmasa berlaku atau kedaluwarsa.<br>
 ![alt text](45.png)<br>
 ![alt text](46.png)
-	session storage.

Session Storage adalah penyimpanan website pada sisi klien yang digunakan untuk menyimpan data selama web-browser atau tab yang memuat halaman suatu website belum ditutup atau keluar (close).<br>
 ![alt text](47.png)<br>
  ![alt text](48.png)
 
## **Tipe web Storage yang umum digunakan oleh back end**
-	cookies
Cookie adalah sebagin kecil dari data yang dikirim dari sebuah situs web dan disimpan dalam komputer pengguna oleh web browser ketika pengguna tersebut sedang membuka halaman dari suatu webiste tertentu.

## **Asynchronous**
Asynchronous adalah proses jalannya program bisa dilakukan secara bersamaan tanpa harus menunggu proses antrian. Synchronous merupakan bagian dari Asynchronous (1 antrian) dimana proses akan dieksekusi secara bersamaan dan untuk hasil tergantung lama proses suatu fungsi synchronous

## **Promise**
Promise bisa dikatakan sebagai object yang menyimpan hasil dari sebuah operasi asynchronous baik itu hasil yang diinginkan (resolved value) atau alasan kenapa operasi itu gagal (failure reason).<br>
  ![alt text](49.png)

## **Await**
Digunakan untuk menghandle operasi asynchronous dengan syntax yang lebih mirip dengan synchronous. Async/Await sendiri dibuat di atas Promise.<br>
  ![alt text](50.png)

## **Fetch**
Fetch pada Javascript adalah kegiatan untuk meminta/me-request layanan ke endpoint pada website lain atau website sendiri, untuk mengambil response resource / sumber daya berupa data berformat json yang biasa dilakukan programmer untuk membangun website yang membutuhkan data dari website lain<br>
  ![alt text](51.png)
Contoh:<br>
  ![alt text](52.png)<br>
   ![alt text](53.png)
 
