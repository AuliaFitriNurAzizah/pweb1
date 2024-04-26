# pweb1

## HTML

HTML adalah singkatan dari Hypertext Markup Language, HTML merupakan salah satu bahasa pengkodean atau pemograman yang digunakan untuk membuat halaman website yang ditampilkan pada web browser. Sebagian besar halaman yang kamu temukan pada internet kebanyakan menggunakan Bahasa HTML. Cara Kerja bahasa pemrograman HTML adalah:

Pertama-tama kamu harus membuat dokumen HTML pada aplikasi editor HTML seperti Visual Studio, Sublime Text dan lain-lainnya , lalu menyimannya dengan format html atau htm. File HTML dibuat bisa lebih dari satu tergantung kebutuhan file yang akan diperlukan. File-file yang telah dibuat ini berisi Halaman Utama , kontak , isi Website dan lain-lain.
File HTML dapat dibuka oleh web browser seperti Google Chrome , Mozilla Firefox, Internet Explore dan masih banyak lagi. Kemudian, agar dapat diakses oleh banyak orang kamu harus menyewa layanan Hosting website dan mengupload file HTML pada halaman hosting yang dapat kamu akses pada cpanel.
File HTML yang sudah terupload, maka browser akan merender file HTML menjadi halaman website sehingga kamu dan pengunjung web lain dapat mengaksesnya melalui internet.

### Dotted Table Border
Dotted table border merupaka jenis tabel di html dengan menggunakan garis tabel berbentuk titik putus-putus. Bentuk tersebut merupkan salah satu bentuk variasi tabel di dalam HTML. Contoh penggunaannya adalah sebagai berikut.
```
<!DOCTYPE html>
<html>
<head>
<style>
th, td {
  border-style: dotted;
}
</style>
</head>
<body>

<h2>Table Dengan Dotted Borders</h2>

<p>Contoh Penggunaan tabel dengan dotted boerder</p>

<table style="width:100%">
  <tr>
    <th>Nama</th>
    <th>Kelas</th> 
    <th>No.Absen</th>
  </tr>
  <tr>
    <td>Aul</td>
    <td>TI C</td>
    <td>7</td>
  </tr>
  <tr>
    <td>Abun</td>
    <td>TI D</td>
    <td>2</td>
  </tr>
  <tr>
    <td>Ahmad</td>
    <td>TI A</td>
    <td>8</td>
  </tr>
</table>

</body>
</html>
```
![dotted](https://github.com/AuliaFitriNurAzizah/pweb1/assets/167959436/b16ee04d-66ed-44fb-a8fc-22696c0908bf)

### Font
Font dalam html digunakan untuk mengatur huruf sesuai dengan kebutuhan penggunaknya. Contohnya font untuk paragraph atau font untuk heading. Berikut adalah contoh penerapannya.
```
<h1 style="font-family:verdana;">Ini heading</h1>
<p style="font-family:courier;">Ini paragraf</p>
```
![font](https://github.com/AuliaFitriNurAzizah/pweb1/assets/167959436/faa6ec54-d394-455d-9908-4a057933defc)

### Tag abbr HTML
Elemen HTML <abbr> mewakili singkatan atau akronim. Saat menyertakan singkatan atau akronim, berikan perluasan penuh istilah tersebut dalam teks biasa saat pertama kali digunakan, bersama dengan <abbr> untuk menandai singkatan tersebut. Ini memberi tahu pengguna apa arti singkatan atau akronim tersebut.
Berikut ini merupakan contoh dari hasil penggunaan elemen HTML <abbr>
```
<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>
```
![abbr](https://github.com/AuliaFitriNurAzizah/pweb1/assets/167959436/e0b4ebd5-9b08-4588-8d65-12b258790bd6)

### Background Color
Properti background-colormenetapkan warna latar belakang suatu elemen.
Latar belakang suatu elemen adalah ukuran total elemen, termasuk padding dan batas (tetapi bukan margin).
Tip: Gunakan warna latar belakang dan warna teks yang membuat teks mudah dibaca.
Dibawah ini adalah contoh dari penggunaan background color dalam html
```
<body style="background-color:powderblue;">

    <h1>This is a heading</h1>
    <p>This is a paragraph.</p>
    
    </body>
```
![bg-color](https://github.com/AuliaFitriNurAzizah/pweb1/assets/167959436/901aa2f6-2a65-421a-88c5-1a465fffe836)

### Image as link
Untuk mendapatkan link di halaman beranda, Anda perlu membuat hyperlink. Untuk melakukan ini dalam HTML Anda perlu menggunakan <a>tag. Setiap <a>tag memiliki dua bagian yaitu tag pembuka dan penutup.
Untuk menambahkan gambar ke halaman web Anda gunakan imgtag.
Tag ini sedikit berbeda dengan atag karena tidak memiliki tag pembuka dan penutup.
Untuk membuat imgtag, Anda perlu memberikan tag file sumber.
```
<!DOCTYPE html>
<html>
<body>

<h2>Image as a Link</h2>

<p>The image is a link. You can click on it.</p>

<a href="https://www.w3schools.com/">
<img src="https://www.w3schools.com/html/smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a>

</body>
</html>
```
![image as link](https://github.com/AuliaFitriNurAzizah/pweb1/assets/167959436/9435f161-02bd-4f77-b252-8f14492a2d0d)

### Mark HTML
<mark>: Elemen Tandai Teks. Elemen HTML <mark> mewakili teks yang ditandai atau disorot untuk tujuan referensi atau notasi karena relevansi bagian yang ditandai dalam konteks yang melingkupinya. Elemen <mark> digunakan untuk menentukan bagian konten yang harus disorot. Secara default, sebagian besar browser merender teks dalam tag <mark> sebagai teks hitam dengan latar belakang kuning. Secara resmi, <mark> harus digunakan untuk menekankan teks yang tidak ditekankan dalam konten aslinya. Contoh dari penggunaan mark html adalah sebagai berikut
```
<p>Do not forget to buy <mark>milk</mark> today.</p>
```
![mark](https://github.com/AuliaFitriNurAzizah/pweb1/assets/167959436/10dcee1b-ec4e-4084-878b-120ed8f6a73a)


### Paragraf
Paragraf adalah kumpulan dari beberapa kalimat. Pada web, Paragraf biasanya digunakan untuk menampilkan teks atau artikel. Paragraf pada HTML dibuat dengan tag p . Selain tag ini, ada juga tag pendukung lain seperti div , hr , div , dan pre 
```
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```
![paragraph](https://github.com/AuliaFitriNurAzizah/pweb1/assets/167959436/63b0dcc9-9b9f-45c6-86fa-c295593c2250)

### Cell Spacing
Atribut HTML table Cellspacing digunakan untuk menentukan jarak antar sel. Atribut spasi sel diatur dalam piksel. Jika atribut cellspacing tidak disetel secara eksplisit, sebagian besar browser akan menerapkan spasi default 1 piksel.
Berikut ini adalah contoh dari penggunaan cell spacing
```
<!DOCTYPE html>
<html>
<head>
<style>
table, th, td {
  border: 1px solid black;
}
table {
  border-spacing: 30px;
}
</style>
</head>
<body>

<h2>Cellspacing</h2>
<p>Change the space between the cells with the border-spacing property.</p>

<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th> 
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
  <tr>
    <td>John</td>
    <td>Doe</td>
    <td>80</td>
  </tr>
</table>

</body>
</html>
```
![cell spacing](https://github.com/AuliaFitriNurAzizah/pweb1/assets/167959436/7645c01b-b312-4b81-8cb0-933f237de717)

### Cell Padding
Cell padding adalah jarak antara tepi sel dan isi sel.
Secara default padding diatur ke 0. Cell padding adalah jarak antara batas sel tabel dan konten di dalam sel tabel. Atribut style digunakan di dalam tag HTML <table> , dengan properti CSS disebut padding dengan nilai tertentu dalam piksel.
Contoh penggunaan cell pading adalah sebagai berikut.
```
<!DOCTYPE html>
<html>
<head>
<style>
table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
}
th, td {
  padding: 15px;
}
</style>
</head>
<body>

<h2>Cellpadding</h2>
<p>Cell padding specifies the space between the cell content and its borders.</p>

<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th> 
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
  <tr>
    <td>John</td>
    <td>Doe</td>
    <td>80</td>
  </tr>
</table>

<p><strong>Tip:</strong> Try to change the padding to 5px.</p>

</body>
</html>
```
![cell padding](https://github.com/AuliaFitriNurAzizah/pweb1/assets/167959436/7f62b30f-6a5f-4533-8b07-1e1b1ac7ead9)

### Border Color
Properti ini border-colormenetapkan warna empat batas elemen. Properti ini dapat memiliki satu hingga empat nilai. Properti border -color memungkinkan Anda mengubah warna batas yang mengelilingi suatu elemen. Anda dapat mengubah warna sisi bawah, kiri, atas, dan kanan batas elemen satu per satu menggunakan properti −border-bottom-color mengubah warna batas bawah.

-border-top-color mengubah warna batas atas.

-border-left-color mengubah warna batas kiri.

-border-right-color mengubah warna batas kanan.
```
<!DOCTYPE html>
<html>
<body>

<h1 style="border: 2px solid Tomato;">Hello World</h1>

<h1 style="border: 2px solid DodgerBlue;">Hello World</h1>

<h1 style="border: 2px solid Violet;">Hello World</h1>

</body>
</html>
```
![border](https://github.com/AuliaFitriNurAzizah/pweb1/assets/167959436/92829d0b-3394-4760-90f0-c3c5f95a025c)

### Grid HTML
HTML grid memberikan kebebasan dan fleksibilitas dalam merancang layout website. Teknik ini juga menawarkan berbagai fitur untuk membuat tampilan yang inovatif dan adaptif, mulai dari pembuatan grid container, penyesuaian grid gap, penggunaan grid template, sampai penyusunan grid yang responsif.
Contoh penggunaan grid adalah seperti i bawah ini
```
<!DOCTYPE html>
<html>
<head>
<style>
.grid-container {
  display: grid;
  grid-template-columns: 33% 33% 33%;
}
</style>
</head>
<body>

<h1>Grid Example</h1>

<p>Align three DIV elements side by side.</p>

<div class="grid-container">

<div style="background-color:#FFF4A3;">
  <h2>London</h2>
  <p>London is the capital city of England.</p>
  <p>London has over 13 million inhabitants.</p>
</div>

<div style="background-color:#FFC0C7;">
  <h2>Oslo</h2>
  <p>Oslo is the capital city of Norway.</p>
  <p>Oslo has over 600.000 inhabitants.</p>
</div>

<div style="background-color:#D9EEE1;">
  <h2>Rome</h2>
  <p>Rome is the capital city of Italy.</p>
  <p>Rome has almost 3 million inhabitants.</p>
</div>

</div>

</body>
</html>
```
![grid](https://github.com/AuliaFitriNurAzizah/pweb1/assets/167959436/a48ed783-61df-43bb-8875-7e3504b1f8dd)

## CSS
CSS adalah bahasa Cascading Style Sheet dan biasanya digunakan untuk mengatur tampilan elemen yang tertulis dalam bahasa markup, seperti HTML. CSS berfungsi untuk memisahkan konten dari tampilan visualnya di situs. Perbedaan antara html dan CSS adalah HTML digunakan untuk menambahkan struktur dan terutama konten pada halaman web atau aplikasi web. CSS digunakan untuk menambahkan gaya atau pemformatan pada konten halaman web.
CSS dapat membuat tampilan website enak untuk dipandang dan lebih menarik karena CSS dapat memberikan banyak pewarnaan dan juga variasi tampilan.

### Margin CSS
Properti margin CSS digunakan untuk membuat ruang di sekitar elemen, di luar batas yang ditentukan. Terdapat properti untuk mengatur margin untuk setiap sisi elemen (atas, kanan, bawah, dan kiri). Berikut ini adalah contoh dari penerapan margin CSS.
```
<!DOCTYPE html>
<html>
<head>
<style>
p {
  border: 2px solid powderblue;
  margin: 50px;
}
</style>
</head>
<body>

<h1>Ini adalah heading</h1>

<p>Ini adalah paragraf.</p>
<p>Ini adalah paragraf.</p>
<p>Ini adalah paragraf.</p>

</body>
</html>
```
![image](https://github.com/AuliaFitriNurAzizah/pweb1/assets/167959436/079c249f-9049-4616-8f12-9d54b8a2d18e)

### Opacity
Properti ini opacitymenetapkan tingkat opacity untuk suatu elemen. Tingkat opacity menggambarkan tingkat transparansi, dimana 1 tidak transparan sama sekali, 0,5 adalah 50% tembus pandang, dan 0 benar-benar transparan.  Saat menggunakan opacityproperti untuk menambahkan transparansi pada latar belakang suatu elemen, semua elemen turunannya juga menjadi transparan. Hal ini dapat membuat teks di dalam elemen transparan sepenuhnya sulit dibaca. Jika Anda tidak ingin menerapkan opacity ke elemen turunan, gunakan nilai warna RGBA
Contoh dari penggunaan opacity terdapat pada gambar di bawah ini.
```
<!DOCTYPE html>
<html>
<head>
<style>
div.background {
  background: url(klematis.jpg) repeat;
  border: 2px solid black;
}

div.transbox {
  margin: 30px;
  background-color: #ffffff;
  border: 1px solid black;
  opacity: 0.6;
}

div.transbox p {
  margin: 5%;
  font-weight: bold;
  color: #000000;
}
</style>
</head>
<body>

<div class="background">
  <div class="transbox">
    <p>Ini adalah opacity</p>
  </div>
</div>

</body>
</html>
```
![opacity](https://github.com/AuliaFitriNurAzizah/pweb1/assets/167959436/c78f00db-3856-4959-aa44-240e61677ffa)

### Warna outline css
Properti outline-colorCSS berfungsi mengatur warna garis luar elemen.
```
<!DOCTYPE html>
<html>
<head>
<style>
p.ex1 {
  border: 2px solid black;
  outline-style: solid;
  outline-color: red;
}

p.ex2 {
  border: 2px solid black;
  outline-style: dotted;
  outline-color: blue;
}

p.ex3 {
  border: 2px solid black;
  outline-style: outset;
  outline-color: grey;
}
</style>
</head>
<body>

<h2>Properti outline color</h2>
<p>Ini adalah contoh pengguunaan properti outline color</p>

<p class="ex1">Ini adalah outline warna merah.</p>
<p class="ex2">Ini adalah outline garis denga model titik-titik.</p>
<p class="ex3">Ini adalah outline dengan garis berwarna abu-abu.</p>

</body>
</html>
```
![outline color](https://github.com/AuliaFitriNurAzizah/pweb1/assets/167959436/888d6b50-175b-4419-8309-1e1d8001a6d3)

### Color Font Size
Dengan menggunakan CSS kita dapat mengatur warna font dan juga ukuran dari tulusan atau teks. contohnya adalah umtuk mengatur ukuran huruf dan warna pada paragraf ataupun heading. Contoh penggunaan color font size adalah sebagai berikut.
```
<!DOCTYPE html>
<html>
<head>
<style>
h1 {
  color: blue;
  font-family: verdana;
  font-size: 300%;

}
p  {
  color: red;
  font-family: courier;
  font-size: 160%;
}
</style>
</head>
<body>

<h1>warna heading</h1>
<p>warna paragraf.</p>

</body>
</html>
```
![warna, ukuran](https://github.com/AuliaFitriNurAzizah/pweb1/assets/167959436/f1a916b2-7b19-4246-afe9-303938802e0e)

### Tabel CSS
Tabel dalam CSS digunakan untuk menerapkan berbagai properti gaya pada elemen Tabel HTML untuk menyusun data dalam baris dan kolom, atau mungkin dalam struktur yang lebih kompleks dengan cara yang terorganisir dengan baik . Tabel banyak digunakan dalam komunikasi, penelitian, dan analisis data.
```
<!DOCTYPE html>
<html>
<head>
<style>
#customers {
  font-family: Arial, Helvetica, sans-serif;
  border-collapse: collapse;
  width: 100%;
}

#customers td, #customers th {
  border: 1px solid #ddd;
  padding: 8px;
}

#customers tr:nth-child(even){background-color: #f2f2f2;}

#customers tr:hover {background-color: #ddd;}

#customers th {
  padding-top: 12px;
  padding-bottom: 12px;
  text-align: left;
  background-color: #04AA6D;
  color: white;
}
</style>
</head>
<body>

<h1>A Fancy Table</h1>

<table id="customers">
  <tr>
    <th>Nama</th>
    <th>Kelas</th>
    <th>No absen</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Berglunds snabbköp</td>
    <td>Christina Berglund</td>
    <td>Sweden</td>
  </tr>
  <tr>
    <td>Centro comercial Moctezuma</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
  <tr>
    <td>Ernst Handel</td>
    <td>Roland Mendel</td>
    <td>Austria</td>
  </tr>
  <tr>
    <td>Island Trading</td>
    <td>Helen Bennett</td>
    <td>UK</td>
  </tr>
  <tr>
    <td>Königlich Essen</td>
    <td>Philip Cramer</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Laughing Bacchus Winecellars</td>
    <td>Yoshi Tannamuri</td>
    <td>Canada</td>
  </tr>
  <tr>
    <td>Magazzini Alimentari Riuniti</td>
    <td>Giovanni Rovelli</td>
    <td>Italy</td>
  </tr>
  <tr>
    <td>North/South</td>
    <td>Simon Crowther</td>
    <td>UK</td>
  </tr>
  <tr>
    <td>Paris spécialités</td>
    <td>Marie Bertrand</td>
    <td>France</td>
  </tr>
</table>

</body>
</html>
```
![tabel css](https://github.com/AuliaFitriNurAzizah/pweb1/assets/167959436/f1f3d9c6-e44c-48f7-be19-c2bfdceef00a)

## Java Script
JavaScript merupakan bahasa pemrograman populer yang digunakan untuk membuat website interaktif dan dinamis. Adapun dinamis yang dimaksud di sini berarti konten di dalamnya dapat bergerak dan tampil secara otomatis tanpa harus dimuat ulang manual oleh pengguna.

### Pengenalan Java Script
```
<!DOCTYPE html>
<html>
<body>

<h2>What Can JavaScript Do?</h2>

<p id="demo">JavaScript can change HTML content. Let's try it by clicking the button below.</p>

<button type="button" onclick='document.getElementById("demo").innerHTML = "Hello JavaScript!"'>Click Here!</button>


<h2>What Can JavaScript Do?</h2>

<p id="demo2">JavaScript can change the style of an HTML element. JavaScript accept both double and single quotes</p>

<button type="button" onclick="document.getElementById('demo2').style.fontSize='35px'">Click Me!</button>



<h2>What Can JavaScript Do?</h2>

<p>JavaScript can change HTML attribute values.</p>

<p>In this case JavaScript changes the value of the src (source) attribute of an image.</p>

<button onclick="document.getElementById('myImage').src='https://www.w3schools.com/js/pic_bulbon.gif'">Turn on the light</button>

<img id="myImage" src="https://www.w3schools.com/js/pic_bulboff.gif" style="width:100px">

<button onclick="document.getElementById('myImage').src='https://www.w3schools.com/js/pic_bulboff.gif'">Turn off the light</button>


<h2>What Can JavaScript Do?</h2>

<p id="demo">JavaScript can hide HTML elements.</p>

<button type="button" onclick="document.getElementById('demo').style.display='none'">Click Me!</button>


<h2>What Can JavaScript Do?</h2>

<p>JavaScript can show hidden HTML elements.</p>

<p id="demo" style="display:none">Hello JavaScript!</p>

<button type="button" onclick="document.getElementById('demo').style.display='block'">Click Me!</button>

</body>
</html>
```
![js](https://github.com/AuliaFitriNurAzizah/pweb1/assets/167959436/ce67e212-f47a-475a-8f8d-3083634b2b0c)
Salah satu dari banyak metode JavaScript HTML adalah getElementById().

Penerapan tersebut dapat "menemukan" elemen HTML (dengan id="demo"), dan mengubah konten elemen (innerHTML) menjadi "Halo JavaScript":
dapat jugaMengubah gaya elemen HTML, merupakan varian dari mengubah atribut HTML. Dalam contoh tersebut, JavaScript mengubah nilai srcatribut (sumber) dari sebuah < img >tag dan juga dapat menyembunyikan elemen HTML dapat dilakukan dengan mengubah displaygaya














