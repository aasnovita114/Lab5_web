# Lab5Web 
<table>
  <tr>
    <th colspan="2">DATA MAHASISWA</th>
  </tr>
  <tr>
    <td>Nama</td>
    <td>Aas Novitasari</td>
  </tr>
  <tr>
    <td>NIM</td>
    <td>312210167</td>
  </tr>
  <tr>
    <td>Kelas</td>
    <td>TI.22.A1</td>
  </tr>
</table>

# Langkah-langkah Praktikum
Persiapan membuat dokumen HTML dengan nama file l lab5_javascript.html seperti berikut.
```
<!DOCTYPE html>
<html lang="en">
<head>
 <title>Mengenal JavaScript</title>
</head>
<body>
 <h1>Pengenalan JavaScript</h1>
 <h3>Contoh document.write dan console.log</h3>
 <script>
 document.write("Hello World");
 console.log("Hello World");
 </script>
</body>
</html>

```
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/51198952-0677-42b3-ae8f-cf15241265ec)

# Javascript Dasar
## Pemakaian Alert sebagai property window
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Mengenal JavaScript</title>
</head>
<html>
    <head>
        <title>alert box</title>
    </head>
    <body>
        <script language = "javascript">
            <!--
                window.alert("ini merupakan pesan untuk anda");
            //-->
           
        </script>
    </body>
</html>

<body>
```
### Hasil Run
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/475739fd-3e5c-4cbc-b64e-6aaa0822ddc9)

## Pemakaian method dalam objek
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Mengenal JavaScript</title>
</head>
<body>
    percobaan memakai JavaScript:<br>
    <script language ="JavaScript"> 
    <!--
    document.write("selamat mencoba javascript<br>");
    document.write("semoga sukses!")
        //-->
    </script>
    </body>
    </html>
```
### Hasil Run
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/4905f323-feae-48d4-b9b4-c6a38f9f6390)

## Pemakaian Prompt
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>pemasukan data</title>
    </head>
    <body>
        <script language = "javascript">
         <!--
            var nama = prompt("siapa nama anda?","masukan nama anda");
            document.write("hai, " + nama);
         //-->   
        </script>
    </body>
</html>
```
### Hasil Run
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/d763db10-6b4a-4dd4-bfb0-24c11e613b1e)

#### lalu masukan nama
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/32e87ad0-4b4b-417f-a1ef-c951fe45a60f)

## Pembuatan fungsi dan cara pemanggilannya
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>contoh program javascript</title>
        <script language=""javascript>
        function pesan(){
            alert ("memanggil javascript lewat body onload")
            }
        </script>
    </head>
    <body onload=pesan()>
    </body>
</html>
```
### Hasil Run
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/c3bc23c8-a4ca-41db-be20-b33e5d204e37)

# Dasar Pemrograman Di Javascript

## Operasi dasar aritmatika
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>contoh program javascript</title>

        <script language="javascript">
        function test (val1,val2)
        {
            document.write("<br>"+"perkalian : val1*val2 "+"<br>")
            document.write(val1*val2)
            document.write("<br>"+"pembagian : val1/val2 "+"<br>")
            document.write(val1/val2)
            document.write("<br>"+"penjumlahan : valq+val2 "+"<br>")
            document.write(val1+val2)
            document.write("<br>"+"pengurangan : val1-val2 "+"<br>")
            document.write(val1-val2)
            document.write("<br>"+"modulus : val1%val2 "+"<br>")
            document.write(val1%val2)
        }
        </script>
    </head>
    <body>
        <input type="button" name="button1" value="aritmetic" onclick=test(9,4)>
    </body>
</html>
```
### Hasil Run
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/29f9e0f9-0f80-42b2-9193-04c2b533dd6c)


## Seleksi kondisi ``` (if..else) ```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>contoh if-else</title>
</head>
<body>
    <script language = "javascript">
    <!--
    var nilai = prompt("nilai (0-100): ", 0);
    var hasil = "";
    if (nilai >= 60)
    hasil = "lulus";
    else
    hasil = "tidak lulus";
    document.write("hasil: " + hasil);
    //-->    
    </script>
</body>
<html>
```
### Hasil Run
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/7a77221d-1dcf-41c0-9cd7-182c784ce84b)

``` Kemudian klik "OK" untuk melihat hasil ```

![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/873ff5d8-2dc9-4a04-b92b-fda32983e026)



## Penggunaan operator switch untuk seleksi kondisi
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>contoh if-else</title>
</head>
<body>
    <script language = "javascript">
    <!--
    var nilai = prompt("nilai (0-100): ", 0);
    var hasil = "";
    if (nilai >= 60)
    hasil = "lulus";
    else
    hasil = "tidak lulus";
    document.write("hasil: " + hasil);
    //-->    
    </script>
</body>
<html>
```
### Hasil Run
``` Berinilai dari bilangan satu sampai bilangan lainnya ```
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/c71e176a-c713-4f74-aabd-a566f8b78f47)

``` kemudian klik "OK" untuk melihat hasilnya ```

![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/42917e06-f64a-406c-a28e-d2ab9755afda)

# Pembuatan From
## From Input
```
<!DOCTYPE html>
<html lang="en">
<head>
    <script language="javascript">
    function test () {
        var val1=document.kirim.T1.value
        if (val1%2==0)
            document.kirim.T2.value="bilangan genap"
        else
            document.kirim.T2.value="bilangan ganjil"
    }
    </script>
</head>
<body>
    <form method="post" name="kirim">
        <p>BIL <input type="text" name="T1" size="20">
        MERUPAKAN BIL <input type="text" name="T2" size="20">
        <p><input type="button" value="TEBAK" name="B1" onclick=test()></p>
    </form>
</body>
</html>

```
### Hasil Run
``` Ketik sebuah bilangan Contoh: ```
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/e7532ad5-7bd9-4d77-b82f-79d6c07c2534)

``` Kemudian klik "Tebak" maka akan muncul hasilnnya ```
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/07bbe657-c785-440b-ab95-961757b0ab97)


## Form Button
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>objek document</title>
</head>
<body>
    <script language = "javascript">
    <!--
     function ubahWarnaLB(warna) {
        document.bgColor = warna;
     }
     function ubahWarnaLD(warna) {
        document.fgColor = warna;
     }  
    //-->
    </script>

    <h1>tes</h1>
    <form>
        <input type="button" value="Latar Belakang Hijau" onclick="ubahWarnaLB('GREEN')">
        <input type="button" value="Latar Belakang Putih" onclick="ubahWarnaLB('WHITE')">
        <input type="button" value="Teks Kuning" onclick="ubahWarnaLD('YELLOW')">
        <input type="button" value="Teks Biru" onclick="ubahWarnaLD('BLUE')">
    </form>
    <script language = "javascript">
    <!--
     document.write("Dimodifikasi terakhir pada " +
     document.lastModified); 
    //-->
    </script>

</body>
</html>
```
### Hasil Run
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/bf471ba1-5441-48d3-900c-d839c1eee79e)

``` Jika ingin mengubah latar belakang Klik "Latar Belakang Hijau" maka akan berubah,lihat hasilnnya ```
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/2f9ebe5d-278c-46ad-b075-e83d100f35a7)

``` Sebaliknya jika ingin menugubahnya kembali seperti di atas Klik "Latar Belakang Putih" hasilnnya ```

![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/adb0b2fa-17a5-49e6-a8a4-93453e536fc1)

``` Jika ingin mengubah warna text ```

![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/0e921d3b-21ed-4128-a6f3-d25d33fe481b)

``` jika ingin mengubah warna lain text ```

![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/5d1314fb-7dc2-41a6-9eae-f29a5cd45631)

# HTML DOM
## Pilihan menggunakan checkBox dengan perhitungan otomatis
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Daftar Menu</title>
    <script>
        function hitung(ele) {
            var total = document.getElementById('total').value;
                total = (total ? parseInt(total) : 0);
            var harga = 0;

            if (ele.checked) {
                harga = ele.value;
                total += parseInt(harga);
            }else{
                harga = ele.value;
                if (total > 0)
                    total -=parseInt(harga);
            }

            document.getElementById('total').value = total;
        }
    </script>
</head>
<body>
    <h1>Daftar Menu Makanan</h1>
    <label><input type="checkbox" value="5000" id="menu1" onclick="hitung(this);" /> Ayam Goreng Rp. 5,000</label><br />
    <label><input type="checkbox" value="500" id="menu2" onclick="hitung(this);" /> Tempe Goreng Rp. 500</label><br />
    <label><input type="checkbox" value="2500" id="menu3" onclick="hitung(this);" /> Telur Dadar Rp. 2.500</label><br />
    <strong>Total Bayar: Rp. <input id="total" type="text" /></strong>
</body>
</html>
```
### Hasil Run
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/ac4dec1f-733a-4b32-8f4d-95c8b12ec49f)

``` Kemudian pilih menu dan hasilnya akan muncul seperti berikut; ```
![Screenshot 2023-10-27 004018](https://github.com/aasnovita114/Lab5_web/assets/116045324/6410a1dc-5b02-4021-b164-bc405f1cb332)

# Pertanyaan dan Tugas
## 1. Buat script untuk melakukan validasi pada isian form.
```
<!DOCTYPE html>
<html>
<head>
    <title>Contoh Validasi Form</title>
</head>
<body>
    <form id="myForm" onsubmit="return validateForm()">
        <label for="name">Nama:</label>
        <input type="text" id="name" name="name"><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email"><br>

        <input type="submit" value="Submit">
    </form>

    <script>
        function validateForm() {
            var name = document.getElementById("name").value;
            var email = document.getElementById("email").value;

            if (name === "") {
                alert("Nama harus diisi");
                return false;
            }

            if (email === "" || !email.includes("@")) {
                alert("Email tidak valid");
                return false;
            }

            // Validasi berhasil, form bisa disubmit
            return true;
        }
    </script>
</body>
</html>
```
### Hasil Run
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/8ff84e00-561f-41cd-8dd5-dd6f51c5a613)

``` Kemudian masukan email anda ```
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/2c34f347-e5b9-484b-8463-1c9287db05f9)

``` Maka hasilnya akan seperti di bawah ini; ```
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/585f0b47-d88d-4cba-b797-bfca918b9140)

# Selesai,TerimaKasih:)
