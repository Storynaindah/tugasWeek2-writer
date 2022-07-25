<h1>Komentar Javascript</h1>

<p>Komentar JavaScript dapat digunakan untuk menjelaskan kode JavaScript, dan membuatnya lebih mudah dibaca.

Komentar JavaScript juga dapat digunakan untuk mencegah eksekusi, saat menguji kode alternatif.</p>

<p>untuk komentar yang hanya satu baris, di mulai dengan:</p>

```
//this comment
```

<p>untuk komentar yang multi baris, di mulai dengan:</p>

```
/*
this is comment
this is comment
this is comment
/*
```

<hr>

<h1> Tiga cara untuk mendeklasi JavaScript Variable </h1>

<p>Variabel digunakan untuk menyimpan data (menyimpan nilai data)</p>

<p>Untuk mendeklarasikannya dapat menggunakan:</p>
<p><li> Var</li>jika masih menggunakan browser lama, bisa menggunakan var.</p>
<p><li> let</li> gunakan let untuk setiap variable yang bisa berubah.</p>
<p><li> Const</li>const digunakan untuk setiap variabel yang memiliki nilai yang tidak dapat berubah.</p>

<hr>

<h1>Operator Aritmatika pada JavaScript</h1>

```
 x + y   //untuk penjumlahan
 x - y   //untuk pengurangan
 x * y  //untuk perkalian
 x / y   //untuk pembagian
 x ** y   //untuk pangkat
 x % y   //untuk mencari nilai sisa
```

<h3 style="color: lightblue">Array</h3>
<p>Array JavaScript ditulis dengan tanda kurung siku. Item array dipisahkan dengan koma. Indeks array berbasis nol, yang berarti item pertama adalah [0], kedua adalah [1], dan seterusnya.</p>

<h3 style="color: lightblue">Object</h3>
<p>Objek JavaScript ditulis dengan kurung kurawal { }. Properti objek ditulis sebagai pasangan nama:nilai, dipisahkan dengan koma.</p>

<hr>
<h1>Fungsi pada JavaScript</h1>
<p>Fungsi JavaScript didefinisikan dengan <b style="color : yellow">function</b> sebagai kata kunci, diikuti dengan <b>nama</b> , diikuti dengan tanda kurung <b>( )</b> . Kode yang akan dieksekusi, oleh fungsi, ditempatkan di dalam tanda kurung kurawal: <b>{ }</b></p>

<p>Contoh penulisan: </p>

```
function nama_fungsi(parameter1, parameter2, parameter3){
  //code untuk di eksekusi
}
```

<p><b style="color:lightblue">Parameter</b> fungsi tercantum di dalam tanda kurung () dalam definisi fungsi. <b style="color:lightblue">Argumen</b> fungsi adalah nilai yang diterima oleh fungsi saat dipanggil.</p>

Di dalam fungsi, argumen (parameter) berperilaku sebagai variabel lokal.</p>

<hr>

<h1>Conditional Statements In JavaScript</h1>
<li>Gunakan <b style="color: lightblue">if</b> untuk menentukan blok kode yang akan dieksekusi, jika kondisi yang ditentukan benar</li>
<li>Gunakan <b style="color: lightblue"> else </b>untuk menentukan blok kode yang akan dieksekusi, jika kondisi yang sama salah</li>
<li>Gunakan <b style="color: lightblue">if else</b> untuk menentukan kondisi baru yang akan diuji, jika kondisi pertama salah</li>

```
let nilai = 98;

if (nilai < 60) {
  console.log("try again");
} else if (nilai <= 90) {
  console.log("good job");
} else {
  console.log("Perpect")
}
```

<hr>
<h1>Berbagai Jenis Loop</h1>
<p>Loop formemiliki sintaks berikut:</p>

<h2>For Loop</h2>

```
for (statement 1; statement 2; statement 3) {
  // kode yang akan dieksekusi
}
```

<h2>While Loop</h2>

```
while (condition) {
  // code block to be executed
}
```

<p>Jika Anda lupa menambah variabel yang digunakan dalam kondisi, loop tidak akan pernah berakhir. Ini akan membuat browser Anda crash.</p>

<h2>Do While</h2>

```
do {
  text += "The number is " + i;
  i++;
}
while (i < 10);
```

<hr>
<h1>JavaScript - HTML DOM</h2>

<p>Metode getElementById
Cara paling umum untuk mengakses elemen HTML adalah dengan menggunakan <span style = "color: yellow">id </span>elemen.

```
<body>
  <p id="user">


  <script>
  document.getElementById("user").innerHTML = "Hello World!";
  </script>
</body>
```

Dalam contoh di atas, <span style = "color:yellow">getElementById </span> adalah metode , sementara <span style = "color:yellow"> innerHTML </span> adalah properti .

Pada contoh di atas <span style = "color: yellow">getElementById </span>metode yang digunakan <span style = "color: yellow">id="demo"</span> untuk mencari elemen.

<h2 style ="color: lightgreen">Menemukan Elemen HTML</h2>
<img src ="img/DOM2.png" width="50%">

<h2 style ="color: lightgreen">Finding HTML Element by Id</h2>

```
const element = document.getElementById("intro");
```

<h2 style ="color: lightgreen">Menemukan HTML Elements by Class Name</h2>

```
const x = document.getElementsByClassName("intro");
```

<b>Jika Anda ingin menemukan semua elemen HTML dengan nama kelas yang sama, gunakan `getElementsByClassName()`.</b>

<h2 style ="color: lightgreen">Menemukan Elemen HTML dengan Nama Tag</h2>

```
const element = document.getElementsByTagName("p");
```

<h2 style ="color: lightgreen">Menemukan HTML Elements by CSS Selectors</h2>

```
const x = document.querySelectorAll("p.intro");
```

Contoh ini mengembalikan daftar semua elemen <b>P</b> dengan class="intro".

<hr>

<h1>JavaScript HTML DOM Events</h1>
<p>Contoh event HTML:</p>

<li>Ketika pengguna mengklik mouse</li>
<li>Ketika halaman web telah dimuat</li>
<li>Saat gambar telah dimuat</li>
<li>Saat mouse bergerak di atas elemen</li>
<li>Ketika bidang input diubah</li>
<li>Saat formulir HTML dikirimkan</li>
<li>Saat pengguna menekan tombol</li>

```
<h2 onclick="this.innerHTML='Ooops!'">Click on this text!</h2>
```

<hr>

```
<button id="myBtn">Try it</button>

<p id="demo"></p>

<script>
document.getElementById("myBtn").onclick = displayDate;

function displayDate() {
  document.getElementById("demo").innerHTML = Date();
}
</script>
```

<hr>
