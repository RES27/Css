# CSS
## 1. Pengenalan CSS Dasar
CSS merupakan singkatan dari “Cascading Style Sheets“. sesuai dengan namanya CSS
memiliki sifat ”style sheet language” yang berarti bahasa pemrograman yang di gunakan untuk 
web design. CSS adalah bahasa pemrograman yang di gunakan untuk men-design sebuah 
halaman website. dalam mendesign halaman website, CSS menggunakan penanda yang kita 
kenal dengan id dan class.

## 2. Penempatan CSS
File css di simpan dengan ekstensi .css. kemudian di import atau di hubungkan kedalam
file HTML atau PHP yang ingin kita design dengan CSS menggunakan syntax berikut ini.

* Ekternal 

```
<link rel="stylesheet" type="text/css" href="file css anda">
```
* Inline

```
<selector="color : Blue">
```
*  Internal

```
<style>
selector {padding : 2px;
color : hijau;
}
</style>
```
## 3. Font Dan Text Styling
a) Mengatur Font Dengan CSS
Beberapa syntax css yang digunakan untuk mengatur font:
* font-size digunakan untuk mengatur ukuran font
* font-weight di gunakan untuk mengatur ketebalan font
* font-family untuk mengubah jenis font
* font-style digunakan untuk merubah gaya pada font.
* color digunakan untuk merubah warna font

b) Mengatur Text Dengan CSS

beberata syntax CSS yang bisa di gunakan untuk mengatur format text diantara nya adalah :
* color, Di gunakan untuk mengatur warna text, value yang dapat di isi berupa warna atau 
kode warna.
* text-align, Di gunakan untuk mengatur posisi align pada text atau rata text, value yang bisa 
di isi diantaranya adalah center untuk membuat text rata tengah, left untuk membuat text
menjadi rata kiri, right untuk membuat text menjadi rata kanan dan justify untuk membuat 
text menjadi rata kanan dan rata kiri.
* text-decoration, Di gunakan untuk mengatur dekorasi text, value nya berupa none untuk 
membuat text tidak memiliki dekorasi, overline untuk membuat text memiliki garis pada 
bagian atas text, line-through untuk membuat garis yang mencoreng pada text, dan 
underline untuk membuat garis pada bawah text(garis bawah).
* text-transform, Digunakan untuk mengatur huruf kapital pada text, value yang bisa di 
gunakan diantaranya adalah uppercase untuk membuat text menjadi huruf besar, lowercase 
untuk membuat text menjadi huruf kecil, dan capitalize untuk membuat huruf awal pada 
tiap kata menjadi huruf besar.
* text-indent, Digunakan untuk mengatur jarak alinea pada text, value yang bisa digunakan 
berupa nilai pixel dan lainnya sesuai kebutuhan.
* text-spacing, Digunakan untuk mengatur jarak antar karakter pada text, value yang di isi 
berupa nilai pixel dan lain-lain. 
* word-spacing, Digunakan untuk mengatur jarak antar kata pada text, value yang di isi juga 
berupa nilai pixel.
* line-height, Digunakan untuk mengatur jarak antar baris pada text value yang di isi berupa 
nilai.
* text-shadow, Digunakan untuk mengatur efek bayang pada text, value yang di isikan 
pertama mengisi nilai untuk jarak kiri kanan, dan kedua mengisi jarak atas bawah dan 
yang ketiga mengisi warna, untuk contoh penulisanya 2px 5px blue.
* vertical-align, Digunakan untuk mengatur align dalam bentuk vertikal pada text value 
yang digunakan adalah left untuk membuat text rata kiri, right untuk rata atas dan center 
untuk rata tengah.
## 4. Selector Dan Pseudo Class
a) Selector

Selektor adalah katakunci dan simbol yang digunakan pada CSS untuk menyeleksi atau 
memilih elemen HTML.
Selector Dalam CSS : 

* Id
Hanya dapat di panggil 1 kali
Penulisannya menggunakan simbol pagar (#)
Contoh :
```
#container{
text-aligen =”Center”;
}
```
* Class
Bisa di panggil berkali-kali
Penulisannya menggunakan tanda titik (.)
Contoh :
```
.Container {
text-aligen =”Center”;
}
```
* Tag HTML
Bisa dipanggil berkali-kali
Penulisan langsung memanggil nama tag nya
Contoh :
```
p {
text-align =”center”;
}
```
b) Pseudo Class

Pseudo-class adalah selektor untuk memilih state pada elemen.
Contohnya seperti elemen saat diklik, saat fokus, saat disentuh, dan lain sebagainya
Contoh :
```
a:hover {
color: green;
}
```
Selain :hover ada beberapa selektor pseudo-class lainnya seperti :
* :link untuk memlih link yang belum dikunjungi
* :visited untuk memlih link yang sudah dikunjungi
* :active untuk memilih elemen yang sedang aktif, seperti saat diklik
* :focus untuk memlih elemen yang sedang dalam keadaan fokus, misal teks lagi diinput
* :checked untuk memilih elemen yang dicentang pada checkbox
