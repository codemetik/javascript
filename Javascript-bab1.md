## Sejarah Javascript
Javascript diperkenalkan pertama kali oleh Netscape pada tahun 1995. Pada awalnya
bahasa ini dinamakan “LiveScript” yang berfungsi sebagai bahasa sederhana untuk
browser Netscape Navigator 2. Pada masa itu bahasa ini banyak di kritik karena
kurang aman, pengembangannya yang terkesan buru buru dan tidak ada pesan
kesalahan yang di tampilkan setiap kali kita membuat kesalahan pada saat menyusun
suatu program. Kemudian sejalan dengan sedang giatnya kerjasama antara Netscape
dan Sun (pengembang bahasa pemrograman “Java” ) pada masa itu, maka Netscape
memberikan nama “JavaScript” kepada bahasa tersebut pada tanggal 4 desember
1995. Pada saat yang bersamaan Microsoft sendiri mencoba untuk mengadaptasikan
teknologi ini yang mereka sebut sebagai “Jscript” di browser Internet Explorer 3.

Javascript adalah bahasa yang berbentuk kumpulan skrip yang pada fungsinya
berjalan pada suatu dokumen HTML, sepanjang sejarah internet bahasa ini adalah
bahasa skrip pertama untuk web. Bahasa ini adalah bahasa pemrograman untuk
memberikan kemampuan tambahan terhadap bahasa HTML dengan mengijinkan
pengeksekusian perintah perintah di sisi user, yang artinya di sisi browser bukan di
sisi server web.

Javascript bergantung kepada browser(navigator) yang memanggil halaman web yang
berisi skrip skrip dari Javascript dan tentu saja terselip di dalam dokumen HTML.
Javascript juga tidak memerlukan kompilator atau penterjemah khusus untuk
menjalankannya (pada kenyataannya kompilator Javascript sendiri sudah termasuk di
dalam browser tersebut). Lain halnya dengan bahasa “Java” (dengan mana JavaScript
selalu di banding bandingkan) yang memerlukan kompilator khusus untuk
menterjemahkannya di sisi user/klien.

## Keperluan Javascript
1. Teks Editor
   - Sublime Text
   - Visual Code
   - dll
2. Web Browser
   - Google Chrome
   - Microsoft Edge
   - Mozilla Firefox
   - Safari
   - Opera
   - UC Browser
   - Vivaldi
   - Samsung Internet

## Penulisan Javascript
Kode Javascript dituliskan pada file HTML. Terdapat dua cara yaitu :
1. Javascript ditulis pada file yang sama :
   ```HTML
   <!DOCTYPE html>
   <html>
   <head>
   	<meta charset="utf-8">
   	<meta name="viewport" content="width=device-width, initial-scale=1">
   	<title>Judul Halaman</title>
   </head>
   <body>
   	
   <script type="text/javascript">
   	//kode javascript disini
   </script>
   </body>
   </html>
   ```
3. Javascript ditulis pada file terpisah
   ```javascript
   <script language="javascript" src="namefile.js"></script>
   ```

## Program Pertama Javascript
```html
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Judul Halaman</title>
</head>
<body>
<b>Bagian Pertama ini ditulis dengan HTML</b>

<p id="p"></p>

<script type="text/javascript">
	document.write("Bagian ini ditulis dengan Javascript");
	document.write("<br>");
	document.write("Bagian ini juga ditulis dengan Javascript");
	
	//menampilkan paragraph dengan memanggil atribut yang memiliki id dengan nama p
	var p = document.getElementById("p");
	p.innerHTML = "Bagian ini menampilkan paragraph dengan javascript";

</script>
</body>
</html>
```

## Ada 4 Cara menampilkan Output pada Javascript
1. Menggunakan fungsi `console.log();`   
- fungsi ini untuk menampilkan ke console Javascript.
- fungsi `console.log()` biasanya digunakan untuk _debugging_. Karena setiap pesan error di javascript selalu ditampilkan di dalam Console.
  
2. Menggunakan fungsi `alert();`
- Fungsi ini untuk menampilkan jendela dialog. fungsi sebenarnya ada pada objek window.
secara lengkap bisa ditulis seperti ini:
```javascript
window.aler("Hellow World!");
```
bisa juga ditulis alert() saja seperti ini:
```javascript
alert("Hellow World!");
```
- fungsi alert(), hanya bisa digunakan di dalam browser saja. sedangkan pada Nodejs fungsi ini tidak ada.
  
3. Menggunakan fungsi `document.write();`
- Objek `document` adalah objek yang mewakili dokumenm HTML di dalam javascript.
```javascript
document.write("<h1>Hello World!</h1>");
document.write("<hr>");
document.write("<p>Saya sedang belajar Javascript</p>");
document.write("di <b>github.com/codemetik</b>");
```
4. Menggunakan `innerHTML`.
- `innerHTML` adalah sebuah atribut di dalam (objek) elemen HTML yang berisi string HTML.
```html
<body>

    <h1>Belajar Javascript</h1>
    <div id="hasil-output"></div>

    <script>
        // membuat objek elemen
        var hasil = document.getElementById("hasil-output");

        // menampilkan output ke elemen hasil
        hasil.innerHTML = "<p>Aku suka Javascript</p>";
    </script>

</body>
```
