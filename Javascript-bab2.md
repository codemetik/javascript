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
maka akan dihasilkan bilangan seperti berikut:
1100b
1010b AND
1000b.
      
_Contoh_ :
```javascript
var A = 12;
var C = A << 2 ;
var D = A >> 1 ;
```

   ### 7.4. Operator Pembanding
   ### 7.5. Operator Logika
   ### 7.6. Operator String
