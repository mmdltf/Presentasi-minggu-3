
# **Presentasi-minggu-2**

## **JS Intermediate-Array dan JS Multidimensional-Array** 

 ###  Array
 Array adalah sebuah struktur data yang dapat menyimpan berbagai jenis tipe data mulai dari string, number, boolean dan lainnya. Array ditandai dengan lambang ( [ ] ) dan ketika kita ingin memanggil value di dalam array kita bisa menggunakan nomor index pada array tersebut, contoh: 
 let pakan = ["makan", "sapi", 3, "ekor"]
	 - index [0] = makan   
	 - index [1] = sapi   
	 - index [2] = 3   
	 - index [3] = ekor
	 

    
  
Array memiliki properties dan methods seperti: 

 -   .push() yaitu untuk menambahkan array pada index terakhir
    -   .pop() yaitu untuk menghapus array pada index terakhir
 -   .shift() yaitu untuk menghapus array pada index pertama
 -   .unshift() yaitu untuk menambahkan array pada index pertama
 -   .sort() yaitu untuk melihat jumlah value yang terdapat pada blok array 

array.prototype.length untuk melihat jumlah value yang terdapat pada blok array  tersebut, contoh:
	 
	 `let  mobil  =['avanza','xenia','innova'];
	  console.log(mobil.length); output 3 `
	 
array.prototype.push yaitu untuk menambahkan value dengan penempatan index ke- terakhir pada array, contoh: 

	`let hp =['xiaomi','s20','iphone 11 promax'];` 
     hp.push('sony'); 
	 console.log(hp); output [ "xiaomi", "s20", "iphone 11 promax", "sony" ]`
 ###  Looping Array
Looping pada array dapat dilakukan dengan .forEach dan .map(). Kedua jenis looping pada array ini memiliki perbedaan yaitu output nya dimana .forEach() tidak menghasilkan array sementara .map() akan menghasilkan output dalam array.
Dibawah ini merupakan contoh .forEach() dan .map()
![enter image description here](https://i.postimg.cc/9FgYV62D/lap-1.png)
 ### Multi-dimensional Array
 Array multidimension adalah array yang terletak didalam array. Multi-dimensional sebenarnya sama seperti single-dimensional yaitu sama-sama dapat menggunakan Property dan Method built-in Array.
Contoh :
![enter image description here](https://i.postimg.cc/6pPmYHpv/lap-2.png)
maka output yang akan dikeluarkan 
`[ [ 'kucing', 'anggora' ], 
[ 'umur', '2 tahun' ], 
[ 'harga', 'Rp 2.000.000' ] ]`
## **JS Intermediate-Object** 
Object adalah sebuah tipe data pada sebuah variabel yang menyimpan method dan property. untuk mengakses property bisa menggunakan 2 cara: Dot notation ( . ) dan Bracket notation [' ']. kemudian untuk menambahkan property kita awali dengan memanggil object lalu diikuti dengan (.) atau[' '] lalu = '....valuenya'.	

 - dot Notation
 let merkGitar = { merk1: 'Ibanez', merk2:'ESP', merk3:'jackson',}
 kemudian merkGitar.merk2
 - bracket Notation
  let merkGitar = { merk1: 'Ibanez', merk2:'ESP', merk3:'jackson',}
  kemudian merkGitar['merk2']



## **Js Intermediate-Recursive** 
rekursive adalah fungsi yang didefinisikan dalam bentuk versi yang lebih sederhana dari dirinya sendiri, dalam algoritma rekursif ini akan selalu memecahkan masalah dengan menguranginya hingga menjadi masalah-masalah kecil atau bisa dibilang sebuah function yang mengeksekusi diri sendiri, nah jika tidak ada kondisi khusus, maka bisa membuat eksekusi kode terus berulang dan tak pernah stop.. Rekursif akan selalu memiliki kondisi dimana sebuah fungsi akan berhenti. Implementasi recursive seperti contoh dibawah ini
![enter image description here](https://i.postimg.cc/QCTchvYZ/lap-3.png)

**Sifat recursive** 

-   Fungsi recursive memiliki kondisi yang menyatakan kapan fungsi tersebut berhenti.
-   fungsi recursive selalu memaanggil dirinya sendiri sambil mengurangi atau memecahkan data masukan setiap panggilannya.

## **JavaScript Intermediate - Asynchronous - Introduction dan Promises** 	
Berbeda dengan synchronous dimana proses eksekusi dijalankan secara berurutan asynchronous memiliki proses pengeksekusian yang bersifat kondisional dimana ketika dihadapkan pada sebuah event yang memiliki waktu eksekusi yang beragam. Event tersebut akan tereksekusi mulai dari waktu yang paling singkat sampai paling lama, contoh implementasinya pada web-aplication seperti tokopedia ketika proses load produk masih berjalan kita masih tetap menjalankan event lainnya atau bisa dibilang proses eksekusi tidak tergantung pada urutan nya. Contoh: 

		let m1....function{....}...Console.log(m1) dengan waktu 1200ms 
		let m2....function{....}...Console.log(m2) dengan waktu 0ms 
		let m3....function{....}...Console.log(m3) dengan waktu 800ms 

Maka event yang akan dieksekusi terlebih dahulu adalah m2, m3 baru m1. Asynchronous memiliki 3 jenis yaitu: 

 - Callback 
 - Promise 
 - Async/Await
### Callback
Callback memiliki perbedaan pada function pada umumnya dimana callback hanya melakukan proses eksekusi hanya pada point tertentu. 

![enter image description here](https://i.postimg.cc/wTfBnZvW/image.png)

### Promise

promise merupakan sebuah object yang dapat atau lebih tepat nya untuk mengembalikan object yang digunakan dalam sebuah event. Dalam promise terdapat `.then` dan `.catch` yang dimana digunakan untuk kondisi yang diinginkan serta tidak.
![enter image description here](https://i.postimg.cc/8PBJKBSs/image.png)
![enter image description here](https://i.postimg.cc/SNqjM2M4/image.png)
## **Js Intermediate-Web Storage** 

Web storage merupakan media penyimpanan yang dapat menyimpan data secara lokal yang dimana data pada web storage tidak bersifat sementara namun akan tetap tersimpan. Terdapat dua jenis web storage pada umumnya yaitu local storage dan session storage. 
-   ### Local Storage
    Local storage memiliki ciri-ciri yaitu data tidak akan hilang walaupun tab di reload maupun browser kita tutup, data tersebut akan terus tersimpan pada storage.

-   ### Session Storage
    Lain hal nya pada session storage, tipe storage ini berbeda dengan local storage karena data yang tersimpan pada storage akan menghilang ketika session telah habis seperti ketika kita menutup browser maupun mereload.







