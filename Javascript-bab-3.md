## Objek Javascript

### 1. Objek untuk memasukan data
Terdapat beberapa objek yang dapat digunakan untuk memeasukkan data. Objekobjek tersebut biasanya terdapat dalam suatu form. Adapun objek-objek tersebut
meliputi Objek Text, Objek Radio, Objek Checkbox, Objek Textarea, dan Objek
Select.

### 2. Objek Text
Untuk menginputkan data kita dapat menggunakan komponen/objek text.
Contoh penggunaannya dapat kita lihat pada contoh berikut:


```javascript
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Objek Javascript</title>
</head>
<body>

<script type="text/javascript">
	function tekan()
	{
	 var namastr = (document.fform.nama.value);
	 var alamatstr = (document.fform.alamat.value);
	 document.fform.onama.value = namastr;
	 document.fform.oalamat.value = alamatstr;
	}
</script>

<form name ="fform">
<h1> Memasukkan Data Dengan Objek Teks</h1><hr>
<pre>
Nama Anda : <input type="text" size="11" name="nama">
Alamat : <input type="text" size="25" name="alamat">
</pre>
<br>
<input type="button" value="kirim" onclick="tekan()">
<input type="reset" value="ulang">
<h3>Output</h3>
<pre>
Jadi Nama Anda adalah :<input type="text" size="11" name="onama">
Alamat Anda di :<input type="text" size="25" name="oalamat">
</form>
</pre>
</body>
</html>
```

### 3. Objek Radio
Objek radio adalah komponen yang digunakan untuk melakukan suatu pemilihan data.
Karena selalu berupa Array, untuk mengakses satu tombol radio digunakan radio[indeks].
disamping itu objek radio juga mempunyai nilai true jika dipilih dan false jika tidak dipilih. 
Untuk memilih suatu objek radio menggunakan properti Checked.

```javascript
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Objek Radio Javascript</title>
</head>
<body>
<script type="text/javascript">
	function radio_box(form)
	{
	 var ket = "";
	 if (form.wanita.checked == true)
	 {
	 ket = "Wanita";
	 }
	 else
	 {
	 ket = "Pria";
	 }
	 alert('Anda adalah seorang ' +ket);
	}
</script>

<form>
	<H1> Memasukkan Data Dengan Objek Radio</H1><hr>
	<p>
		<input type="radio" value="wanita" name="wanita">Wanita
	</p>
	<hr>
	<p>
		<input type="button" value="confirm" onclick="radio_box(this.form)">
		<input type="reset" value="RESET">
	</p>
</form>

</body>
</html>
```

### 4. Objek Checkbox
Objek checkbox menyimpan informasi tentang elemen form yang berupa kotak cek.
Penggunaannya hampir sama seperti objek radio.

```javascript
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Objek Checkbox</title>
</head>
<body>

<script type="text/javascript">
	function radio_box(form)
	{
	 var ket = "";
	 var ket1 = "";
	 if (form.bola.checked == true)
	 {
	 ket = "Nonton Bola";
	 }

	 if (form.tv.checked == true)
	 {
	 ket1 = " Nonton Tv";
	 }
	 alert('Hobby anda ' + ket + '' + ket1);
	}
</script>

<form>
	<h1> Memasukkan Data Dengan Objek Checkbox</h1><hr>
	<p>Hobby anda :
	<input type="checkbox" value="ON" name="bola">Nonton Sepak Bola
	<input type="checkbox" value="ON" name="tv">Nonton televisi</p>
<hr>
<p>
	<input type="button" value="confirm" onclick="radio_box(this.form)">
	<input type="reset" value="RESET">
</p>
</form>

</body>
</html>

```

### 5. Objek TextArea
Objek textarea menyimpan informasi tentang elemen form yang berupa kotak teks
dengan banyak baris.

```javascript
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Objek TextArea Javascript</title>
</head>
<body>

<script type="text/javascript">
	function tekan()
	{
	 var ketstr = (document.fform.Ket.value);
	 document.fform.Oket.value = ketstr;
	}
</script>

<form name ="fform">
	<h1> Memasukkan Data Dengan Objek TextArea</h1><hr>
	<h3>Keterangan :<h3><br>
	<textarea name="Ket" rows="3" cols="30"></textarea>
	<br><br>
	<input type="button" value="kirim" onclick="tekan()">
	<input type="reset" value="ulang">
	<H3>Output Keterangan :</H3>
	<textarea name="Oket" rows="3" cols="30"></textarea>
</form>

</body>
</html>

```

### 6. Objek Select
Objek select menyimpan informasi tentang elemen form yang berupa kotak daftar.
objek select berguna apabila di dalam form terdapat banyak pilihan yang jelas mempunyai nilai tertentu.


```javascript
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Objek Select</title>
</head>
<body>

<script type="text/javascript">
	function tekan()
	{
	 var jurusanstr = (document.fform.Jurusan.value);
	 document.fform.Ojurusan.value = jurusanstr;
	}
</script>

<form name ="fform">
	<h1> Penggunaan Objek Select</h1><hr>
	<h3> Masukan :<h3>
	Jurusan Di UNIKOM :
	<select name="Jurusan" Size="1">
	 <option value ="Teknik Informatika"> Teknik Informatika </option>
	 <option value ="Manajemen Informatika"> Manajemen Informatika </option>
	 <option value ="Teknik Komputer"> Teknik Komputer </option>
	 <option value ="Teknik Industri"> Teknik Industri </option>
	 <option value ="Teknik Elektro"> Teknik Elektro </option>
	 <option value ="Teknik Sipil"> Teknik Sipil </option>
	 <option value ="Teknik Arsitektur"> Teknik Arsitektur </option>
	 <option value ="Teknik Perencanaan Wil. Kota "> Perencanaan Wil. Kota </option>
	</select>
	
		<input type="button" value="kirim" onclick="tekan()">
		<input type="reset" value="ulang">
		<H3>Output jurusan :</H3>
		<input type="text" name="Ojurusan" size="30">
</form>

</body>
</html>
```

## LATIHAN : 
- Buatlah halaman seperti berikut, yang mencakup semua materi yang terdapat pada bab 3  ini.
	1. Input berupa : NIS (text), NAMA (text), JENIS KELAMIN (checkbox), AGAMA (checkbox), STATUS (radio), JURUSAN (checkbox), KOMENTAR (textarea).
	(Sesuaikan objek yang dipakai)
	2. Proses terjadi di tombol KIRIM
	3. Output : Menampilkan data seperti pada no.1
	4. Isi dengan NIS, dan NAMA ANDA
	5. Tugas individu, laporan di buat dengan menggunakan Ms.Word (softfile)
	yang berisi source codenya dan tampilan hasilnya.
