## Variable Javascript
### 1. Variable dalam javascript
  - Variable adalah sebuah penanda identitas untuk menympan suatu nilai atau informasi. Variable yang di deklarasikan dapat di isi dengan nilai apa saja. Jika variable tersebut di beri nilai, maka dalam javascript dianggap variable tersebut telah dideklarasikan. 
  _Aturan penamaan variable_:
####
    - Harus diawali dengan karakter (huruf atau baris bawah)
    - Tidak boleh menggunakan spasi
    - Huruf KAPITAL dan kecil memiliki arti yang berbeda
    - Tidak boleh menggunakan kata-kata yang merupakan perintah dalam JavaScript.

  _Deklarasi Variable_
####
    Var nama_variable = nilai atau Nama_variable = nilai

_Contoh_ : 
```javascript
var nama;
var nama = "Muhammad Irfa Nufaiyal Kharish, S.Kom"
var X = 1992;
var Y =;
var Nama = "Zanky";
```
### 2. Tipe Data
- Tidak seperti bahasa pemrograman lainnya, JavaScript tidak memiliki tipe data secara
explisit. Hal ini dapat dilihat dari beberapa contoh variabel diatas. Anda
mendeklarasikan variabel tapi tidak menentukan tipenya.
Meskipun JavaScript tidak memiliki tipe data secara explisit. JavaScript mempunyai
tipe data implisit. Terdapat empat macam tipe data implisit yang dimiliki oleh
JavaScript yaitu :
  - Numerik, seperti : 0222532531, 1000, 45, 3.146789 dsb
  - String, seperti : “Hallo”, “April”, “Jl. Setiabudi No 17A”, “Cece Kirani” dsb
  - Boolean, bernilai true atau false
  - Null, variabel yang tidak diinisilisasi
    
### 3. Tipe Numerik
- Pada dasarnya JavaScript hanya mengenal dua macam tipe numerik, yaitu bilangan
bulat (integer) dan bilangan pecahan(real/float).
Untuk bilangan bulat, kita dapat merepresentasikan dengan basis desimal, oktal atau
heksadesimal. _Contoh_:
  ```javascript
  var A = 100;
  var B = 0x2f;
  ```
Untuk pendeklarasian tipe bilangan real, dapat menggunakan tanda titik atau notasi ilmiah (notasi E). _Contoh_:
  ```javascript
  var a = 3.14533567;
  var b = 1.23456E+3;
  ```

### 4. Tipe String
- Untuk mendeklarasikan tipe string dapat dilakukan dengan cara menuliskan string
diantara tanda petik tunggal (') atau tanda petik ganda ("). _Contoh_:
```javascript
var str ='Contoh deklarasi string';
var str1 = "cara ini juga bisa untuk menulis string";
```

### 5. Tipe Boolean
- Tipe boolean hanya mempunyai nilai True atau False. Tipe ini biasanya digunakan
untuk mengecek suatu kondisi atau keadaan. _Contoh_:
```javascript
var X = (Y > 90);
```
contoh diatas menunjukkan bahwa jika Y lebih besar dari 90 maka X akan bernilai
True.

### 6. Tipe Null
- Tipe Null digunakan untuk merepresentasikan variabel yang tidak diberi nilai awal
(inisialisasi).

### 7. Operator
Operator pada JavaScript terbagi menjadi enam, yaitu :
1. Aritmatika
2. Pemberinan nilai (Assign)
3. Pemanipulasian bit (bit)
4. Pembanding
5. Logika
6. String

   ### 7.1. Operator Aritmatika
<table>
  <tr>
    <th>Operator</th>
    <th>Tunggal / Biner </th>
    <th>Keterangan</th>
  </tr>
  <tr>
    <td> + </td>
    <td> Biner </td>
    <td> Penjumlahan </td>
  </tr>
  <tr>
    <td> - </td>
    <td> Biner </td>
    <td> Pengurangan </td>
  </tr>
  <tr>
    <td> * </td>
    <td> Biner </td>
    <td> Perkalian </td>
  </tr>
  <tr>
    <td> / </td>
    <td> Biner </td>
    <td> Pembagian </td>
  </tr>
  <tr>
    <td> % </td>
    <td> Biner </td>
    <td> Modulus </td>
  </tr>
  <tr>
    <td> _ </td>
    <td> Tunggal </td>
    <td> Negasi </td>
  </tr>
  <tr>
    <td> ++ </td>
    <td> Tunggal </td>
    <td> Penambahan dengan satu </td>
  </tr>
  <tr>
    <td> -- </td>
    <td> Tunggal </td>
    <td> Pengurangan dengan satu </td>
  </tr>
</table>

  ### 7.2. Operator Pemberian nilai (Assign)
<table>
  <tr>
    <th>Operator</th>
    <th>Keterangan</th>
    <th>Contoh</th>
    <th>Ekuivalen</th>
  </tr>
  <tr>
    <td> = </td>
    <td> Sama dengan </td>
    <td> X = Y </td>
    <td></td>
  </tr>
  <tr>
    <td> += </td>
    <td> Ditambah dengan </td>
    <td> X += Y </td>
    <td> X = X + Y</td>
  </tr>
  <tr>
    <td> -= </td>
    <td> Dikurangi dengan </td>
    <td> X -= Y </td>
    <td> X = X - Y</td>
  </tr>
  <tr>
    <td> *= </td>
    <td> Dikali dengan </td>
    <td> X *= Y</td>
    <td> X = X * Y</td>
  </tr>
  <tr>
    <td> /= </td>
    <td> Dibagi dengan </td>
    <td> X /= Y</td>
    <td> X = X / Y</td>
  </tr>
  <tr>
    <td> %= </td>
    <td> Modulus dengan </td>
    <td> X %= Y </td>
    <td> X = X % Y</td>
  </tr>
  <tr>
    <td> &= </td>
    <td> Bit AND dengan </td>
    <td> X & Y </td>
    <td> X = X & Y </td>
  </tr>
  <tr>
    <td> |= </td>
    <td> Bit OR </td>
    <td> X |= Y </td>
    <td> X = X | Y </td>
  </tr>
  
</table>

   ### 7.3. Operator Pemanipulasian bi (bit)
<table>
  <tr>
    <th>Operator</th>
    <th>Keterangan</th>
  </tr>
  <tr>
    <td> & </td>
    <td> Bit AND </td>
  </tr>
  <tr>
    <td> | </td>
    <td> Bit OR </td>
  </tr>
  <tr>
    <td> ^ </td>
    <td> Bit XOR </td>
  </tr>
  <tr>
    <td> ~ </td>
    <td> Bit NOT </td>
  </tr>
  <tr>
    <td> << </td>
    <td> Geser ke kiri </td>
  </tr>
  <tr>
    <td> >> </td>
    <td> Geser ke kanan </td>
  </tr>
  <tr>
    <td> >>> </td>
    <td> Geser ke kanan dengan diisi nol</td>
  </tr>
</table>

_Contoh_ :
```javascript
var A = 12; // A = 1100b
var B = 10; // B = 1010b
var C = A & B
```
maka akan dihasilkan bilangan seperti berikut: <br>
<br>1100b
<br><u>1010b AND</u>
<br>1000b.
      
_Contoh_ :
```javascript
var A = 12;
var C = A << 2 ;
var D = A >> 1 ;
```
maka variable C akan bernilai 48(0011 0000b)
variable D akan bernilai 6 (0110b)

   ### 7.4. Operator Pembanding
   <table>
     <tr>
       <th>Operator</th>
       <th>Keterangan</th>
     </tr>
     <tr>
       <td> == </td>
       <td> Sama dengan </td>
     </tr>
     <tr>
       <td> != </td>
       <td> Tidak Sama dengan </td>
     </tr>
     <tr>
       <td> > </td>
       <td> Lebih besar </td>
     </tr>
     <tr>
       <td> < </td>
       <td> Lebih kecil </td>
     </tr>
      <tr>
       <td> >= </td>
       <td> Lebih besar atau sama dengan </td>
     </tr>
      <tr>
       <td> <= </td>
       <td> Lebih kecil atau sama dengan </td>
     </tr>
   </table>
         
   ### 7.5. Operator Logika
  <table>
    <tr>
      <th>Operator</th>
      <th>Keterangan</th>
    </tr>
    <tr>
      <th> && </th>
      <th> Operator Logika AND </th>
    </tr>
    <tr>
      <th> || </th>
      <th> Operator Logika OR </th>
    </tr>
    <tr>
      <th> ! </th>
      <th> Operator Logika NOT </th>
    </tr>
  </table>
  
  _Contoh_ :
  ```javascript
  var A = true;
  var B = false;
  var C = A && B; //menghasilkan false
  var D = A || B; //false
  var E = !A; //false 
  ```
   ### 7.6. Operator String
- Selain operator pembanding, operator string pada JavaScript juga mengenal satu
operator lagi yang bernama PENGGABUNGAN. Operator ini digunakan untuk menggabungkan beberapa string menjadi sebuah string yang lebih panjang.
_Contoh_ :
`nama = "Java" + "Script";`
akan menghasilkan "JavaScript" pada variable nama.

```html
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Operasi Aritmatika</title>
</head>
<body>
<p>
	<script type="text/javascript">
		document.writeln("<pre>");
		document.writeln("<h1>Operasi Aritmatika</h1>");
		var A = "100";
		var B = "200";
		var C = 300;
		var D = 400;
		var E = A + B;
		document.writeln('"100" + "200" = ' + E);
		E = B + C;
		document.writeln('"200" + "300" = ' + E);
		E = C + D;
		document.writeln('"300" + "400" = ' + E);
		document.writeln("</pre>");
	</script>
</p>
</body>
</html>
```

Hasil Tampilan Web Browser

![opt aritmatika](https://github.com/user-attachments/assets/ab41d25d-e44b-4159-9b96-2cef2ce42ca9)

### 8. Memasukkan Data
Untuk memasukan data dari keyboard dapat dilakukan dengan menggunakan perintah <b>input</b>
_Contoh_:
```html
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Masukan Bilangan</title>
</head>
<body>
<p>
	<script type="text/javascript">
	/*
	function jumlah()
	{
	 var bil1 = parseFloat(document.fform.bilangan1.value);
	 if (isNaN (bil1))
	 bil1=0.0;
	 var bil2 = parseFloat(document.fform.bilangan2.value);
	 if (isNaN (bil2))
	 bil2=0.0;
	 var hasil = bil1 + bil2;
	 alert ("Hasil Penjumlahan = " + hasil);
	}
	*/
	</script>
</p>
<form name="fform">
	<h1><br>Masukan Data Lewat Keyboard</h1>
	<pre>
	Bilangan Pertama : <input type="text" size="11" name="bilangan1">
	Bilangan Kedua : <input type="text" size="11" name="bilangan2">
	</pre>
<input type="button" value="Jumlahkan" onclick="jumlah()">
<input type="reset" value="Ulang">
</form>
</body>
</html>
```

Hasil Tampilan pada Web Browser

![masukan](https://github.com/user-attachments/assets/a19e0b60-b0ed-4938-a38e-6c8231161602)
