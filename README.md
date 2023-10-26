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
![Screenshot 2023-10-24 101428](https://github.com/aasnovita114/Lab5_web/assets/116045324/5392a76e-f2e2-48f6-82d4-eb6313574b45)

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
![Screenshot 2023-10-24 104409](https://github.com/aasnovita114/Lab5_web/assets/116045324/68d59172-ef4c-4c0b-9ded-890a7308e996)

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
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/4ba5eda1-aab1-40c1-a966-339a66fdc170)

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
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/5539d205-de3a-4099-ada0-41b9cfe40af0)

#### lalu masukan nama
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/7797d363-8a9b-4f13-ab95-03f7b097e89b)

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
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/907f50bc-e361-412a-b982-841ed164a719)

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
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/363922b6-0cac-432b-b7ee-a3d9b225e225)

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
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/be4f40bd-44cd-46a9-907c-755e4a487bc8)

``` Kemudian klik "OK" untuk melihat hasil ```

![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/d6515e1d-9a5a-400c-80e0-4fe6a40f626a)



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

![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/2cb11a64-9585-4a13-a0a8-80df9c52689d)


``` kemudian klik "OK" untuk melihat hasilnya ```

![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/b85567df-2da3-486c-9260-770c90b292ba)

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
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/97d9b7c9-1789-4018-a7c1-2c99e22f15e3)

``` Kemudian klik "Tebak" maka akan muncul hasilnnya ```
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/ac79e240-a6f9-4efb-9df4-9fa7d971ff64)


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
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/8560b239-aa87-4161-b414-c382b9e33e06)

``` Jika ingin mengubah latar belakang Klik "Latar Belakang Hijau" maka akan berubah,lihat hasilnnya ```
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/947b2760-27ba-47dc-b6a3-fba388b0b5ad)

``` Sebaliknya jika ingin menugubahnya kembali seperti di atas Klik "Latar Belakang Putih" hasilnnya ```

![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/a95a6ed4-d663-4b9f-9e2a-b20928ae0083)

``` Jika ingin mengubah warna text ```

![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/13f76519-0662-4b19-a047-c395fc7e7e3b)

``` jika ingin mengubah warna lain text ```

![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/a50e0a94-ff3f-4071-abcd-969e111947ab)

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
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/431923e6-d28f-4829-bbd8-935ae7f12707)

``` Kemudian pilih menu dan hasilnya akan muncul seperti berikut; ```
![Screenshot 2023-10-27 004018](https://github.com/aasnovita114/Lab5_web/assets/116045324/e9cc54b6-ec4c-4b77-8929-090d5624dd5c)

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
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/20209c7b-a9e4-4a0f-b23d-02040edb1e91)

``` Kemudian masukan email anda ```
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/361e1419-491f-4a50-b16b-a4629a1bd103)

``` Maka hasilnya akan seperti di bawah ini; ```
![image](https://github.com/aasnovita114/Lab5_web/assets/116045324/a7d44a43-356f-4b7d-a391-fcf7a1288d8f)

# Selesai,TerimaKasih:)
