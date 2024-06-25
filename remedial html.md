# Halaman Web
## kode program
```html
<body>
        <div>
        <table border="0" width="100%" width="100%">
            <tr> 
                <td height="50px" bgcolor="yellow"> Flower Shop </td>  
            </tr>
        </table>
    </div>
```

## Analisis :
`Tag <body>`: Ini adalah bagian dari HTML yang menampung semua konten yang akan ditampilkan di halaman web.    
`Tag <div>`: Digunakan untuk mengelompokkan elemen-elemen HTML. Dalam konteks ini, div digunakan untuk mengelompokkan elemen yang akan dimasukkan ke dalam tabel.    
`Tag <table>`: Digunakan untuk membuat tabel di HTML.
`Attribute border="0"`: Ini menentukan bahwa tabel tidak akan memiliki garis pemisah antara sel-selnya.  
`Attribute width="100%" width="100%"`: Ini mencoba membuat tabel menutupi seluruh lebar halaman dengan memberikan 100% lebar pada tabel serta pada satu-satunya kolom yang ada.
`Tag <tr>`: Mendefinisikan baris dalam tabel.   
`Tag <td>`: Mendefinisikan sel dalam tabel. 
`Attribute height="50px"`: Ini menentukan tinggi sel menjadi 50 piksel.  
`Attribute bgcolor="yellow"`: Ini menentukan bahwa warna latar belakang sel adalah kuning.
`Teks "Flower Shop"`: Ini adalah teks yang akan ditampilkan di dalam sel tabel.

## kode program
```html
    <div align="center">
        <h1> Selamat datang di flower shop </h1>
        <img src="bunga 2.jpg" width="410px" height="410px">
    </div> <br>
```

## Analisis : 
`Tag <div>`: Digunakan untuk mengelompokkan elemen-elemen HTML dan dalam konteks ini, digunakan untuk mengatur penataan atau tata letak (layout) elemen-elemen yang berada di dalamnya.  
`Attribute align="center"`: Ini adalah atribut yang digunakan untuk menentukan bahwa konten di dalam `<div>` akan dipusatkan secara horizontal di dalam halaman. 
`Tag <h1>`: Ini adalah tag yang digunakan untuk menampilkan teks berukuran besar sebagai judul. Di sini, teks yang ditampilkan adalah "Selamat datang di flower shop".
`Tag <img>`: Digunakan untuk menampilkan gambar di halaman web.
`Attribute src="bunga 2.jpg"`: Ini adalah atribut yang menentukan lokasi atau URL dari gambar yang akan ditampilkan. Dalam kasus ini, gambar yang disebut "bunga 2.jpg" akan ditampilkan.
`Attribute width="410px" height="410px"`: Ini adalah atribut yang menentukan lebar dan tinggi gambar dalam piksel. Dalam hal ini, gambar tersebut akan ditampilkan dengan lebar dan tinggi masing-masing 410 piksel.
`Tag <br>`: Ini adalah tag untuk membuat jeda baris (line break). Dalam konteks ini, digunakan setelah elemen `<div>` untuk memberikan jarak vertikal antara elemen `<div>` tersebut dengan elemen-elemen berikutnya.

## kode program
```html
<div align="center">
            <a href="order bunga.html"> <input type="submit" value="Order Now!"> </a>
    </div> <br>
```

## Analisis : 
`Attribute align="center"`: Ini adalah atribut yang digunakan untuk menentukan bahwa konten di dalam `<div>` akan dipusatkan secara horizontal di dalam halaman.  
`Tag <a>`: Ini adalah tag untuk membuat hyperlink atau tautan.  
`Attribute href="order bunga.html"`: Ini adalah atribut yang menentukan URL atau alamat tujuan ketika tautan tersebut diklik. Dalam hal ini, tautan akan mengarah ke halaman "order bunga.html". 
`Tag <input>`: Ini adalah tag untuk membuat elemen input.
`Attribute type="submit"`: Ini menentukan bahwa elemen input adalah tombol submit. 
`Attribute value="Order Now!"`: Ini adalah atribut yang menentukan teks yang akan ditampilkan pada tombol submit. Dalam hal ini, teks yang ditampilkan adalah "Order Now!".
`Tag <br>`: Ini adalah tag untuk membuat jeda baris (line break). Dalam konteks ini, digunakan setelah elemen `<div>` untuk memberikan jarak vertikal antara elemen `<div>` tersebut dengan elemen-elemen berikutnya

## kode program
```html
<div>
        <table border="1">
            <tr>
                <td colspan="2" bgcolor="aqua" width="1000" align="center"> <a href="list bungaa.html"> List daftar bunga </a></td>
                <td colspan="2" bgcolor="aqua" width="1000" align="center"> <a href="order bunga.html"> Pesan Bunga </a></td>
            </tr>
```

## Analisis : 
`Tag <table>`: Digunakan untuk membuat tabel di HTML. 
`Attribute border="1"`: Ini menentukan bahwa tabel akan memiliki garis pembatas di antara setiap selnya.
`Tag <tr>`: Ini adalah tag untuk mendefinisikan baris dalam tabel.
`Tag <td>`: Ini adalah tag untuk mendefinisikan sel dalam tabel. 
`Attribute colspan="2"`: Ini menentukan bahwa sel tersebut akan menggabungkan dua kolom dalam satu baris. Dalam hal ini, setiap hyperlink akan memenuhi dua kolom.  
`Attribute bgcolor="aqua"`: Ini adalah atribut yang menentukan warna latar belakang sel menjadi warna aqua.
`Attribute width="1000"`: Ini menentukan lebar sel menjadi 1000 piksel.
`Attribute align="center"`: Ini menentukan bahwa konten di dalam sel akan dipusatkan secara horizontal di dalam sel.
`Tag <a>`: Ini adalah tag untuk membuat hyperlink atau tautan.  
`Attribute href="list bungaa.html"` dan `href="order bunga.html"`: Ini adalah atribut yang menentukan URL atau alamat tujuan ketika tautan tersebut diklik. Dalam kasus ini, tautan pertama akan mengarah ke halaman "list bungaa.html", sementara tautan kedua akan mengarah ke halaman "order bunga.html"

## Hasil
![](asetremed/html1.png)

# List bunga
## Kode program
```html
<body>
        <h1> List Bunga </h1>
        <table border="1"> 
            <tr> 
                <td> Bunga 1 <br> <img src="bunga 1.jpg" width="100"></td>
                <td> 
                <ul>
                    <li> Asal : <b> gunung latimojong </b></li>
                    <li> Keharuman : <b> Tahan lama </b> </li>
                    <li> harga : <b> 75.000 </b> </li>
                </ul>
```

## Analisis : 
`Tag <body>`: Ini adalah bagian dari HTML yang menampung semua konten yang akan ditampilkan di halaman web.    
`Tag <h1>`: Ini adalah tag untuk menampilkan teks berukuran besar sebagai judul. Dalam hal ini, judul "List Bunga" akan ditampilkan di halaman web.  
`Tag <table>`: Digunakan untuk membuat tabel di HTML.  
`Attribute border="1"`: Ini menentukan bahwa tabel akan memiliki garis pembatas di antara setiap selnya. 
`Tag <tr>`: Ini adalah tag untuk mendefinisikan baris dalam tabel.  
`Tag <td>`: Ini adalah tag untuk mendefinisikan sel dalam tabel.  
`Teks "Bunga 1"`: Ini adalah teks yang akan ditampilkan di dalam sel tabel.  
`Tag <br>`: Ini adalah tag untuk membuat jeda baris (line break). Dalam konteks ini, digunakan untuk membuat jeda antara teks "Bunga 1" dengan gambar yang akan ditampilkan.  
`Tag <img>`: Digunakan untuk menampilkan gambar di halaman web.
` Attribute src="bunga 1.jpg"`: Ini adalah atribut yang menentukan lokasi atau URL dari gambar yang akan ditampilkan. Dalam kasus ini, gambar yang disebut "bunga 1.jpg" akan ditampilkan. 
`Attribute width="100"`: Ini menentukan lebar gambar dalam piksel. Dalam hal ini, lebar gambar akan disetel menjadi 100 piksel.
`Tag <ul>`: Ini adalah tag untuk membuat daftar yang tidak berurutan (unordered list).  
`Tag <li>`: Ini adalah tag untuk mendefinisikan item dalam daftar.  
`Teks "Asal : gunung latimojong"`: Ini adalah teks yang akan ditampilkan sebagai item pertama dalam daftar.  
`Teks "Keharuman : Tahan lama"`: Ini adalah teks yang akan ditampilkan sebagai item kedua dalam daftar.
`Teks "harga : 75.000"`: Ini adalah teks yang akan ditampilkan sebagai item ketiga dalam daftar.
`Tag <b>`: Ini adalah tag untuk memberi teks cetak tebal.

## Kode program
```html
<td colspan="3" align="center" bgcolor="grey"> kosong </td>
            </tr> 
```

## Analisis : 
`Tag <td>`: Ini adalah tag untuk mendefinisikan sel dalam tabel.  
`Attribute colspan="3"`: Ini menentukan bahwa sel tersebut akan menggabungkan tiga kolom dalam satu baris. Dalam konteks ini, sel tersebut akan memenuhi tiga kolom.  
`Attribute align="center"`: Ini menentukan bahwa konten di dalam sel akan dipusatkan secara horizontal di dalam sel.  
`Attribute bgcolor="grey"`: Ini menentukan bahwa warna latar belakang sel tersebut adalah abu-abu (grey).  
`Teks "kosong"`: Ini adalah teks yang akan ditampilkan di dalam sel tabel.

## Kode program
```html
 <tr>
    <td bgcolor="red" align="center" colspan="4"> <a href="order bunga.html"> Pesan Sekarang </a></td>
            </tr>
        </table> <br>
```

## Analisis : 
`Tag <tr>`: Ini adalah tag untuk mendefinisikan baris dalam sebuah tabel.
`Tag <td>`: Ini adalah tag untuk mendefinisikan sel dalam tabel.  
`Attribute bgcolor="red"`: Ini menentukan bahwa warna latar belakang dari sel tersebut adalah merah.    
`Attribute align="center"`: Ini menentukan bahwa konten di dalam sel tersebut akan dipusatkan secara horizontal di dalam sel.
`Attribute colspan="4"`: Ini menentukan bahwa sel tersebut akan menggabungkan empat kolom dalam satu baris. Dalam konteks ini, sel tersebut akan memenuhi seluruh lebar tabel karena `colspan` diatur menjadi 4, yang sesuai dengan jumlah total kolom tabel.
`Tag <a>`: Ini adalah tag untuk membuat hyperlink atau tautan.
`Attribute href="order bunga.html"`: Ini adalah atribut yang menentukan URL atau alamat tujuan ketika tautan tersebut diklik. Dalam hal ini, tautan akan mengarah ke halaman "order bunga.html".  
`Teks "Pesan Sekarang"`: Ini adalah teks yang akan ditampilkan sebagai tautan di dalam sel tabel.  
`Tag <br>`: Ini adalah tag untuk membuat jeda baris (line break). Dalam konteks ini, tag `<br>` digunakan setelah penutup tag `</table>` untuk memberikan jarak vertikal antara tabel tersebut dengan elemen-elemen berikutnya.

## Kode program
```html
        <a href="index.html"> kembali ke home </a>
```

## Analisis : 
`Tag <a>`: Ini adalah tag untuk membuat hyperlink atau tautan.
`Attribute href="index.html"`: Ini adalah atribut yang menentukan URL atau alamat tujuan ketika tautan tersebut diklik. Dalam kasus ini, tautan akan mengarahkan pengguna ke halaman "index.html".
`Teks "kembali ke home"`: Ini adalah teks yang akan ditampilkan sebagai tautan di dalam halaman web.

## Hasil
![](asetremed/html2.png)

# Order bunga
## Kode program
```html
<label for="nama"> <b> nama </b></label> <br>
        <input type="text" id="nama" required> <br> <br>
```

## Analisis : 
`Tag <label>`: Ini adalah tag untuk menautkan teks deskripsi (label) dengan elemen input pada formulir HTML.    
`Attribute for="nama"`: Ini menentukan bahwa label tersebut terkait dengan elemen input yang memiliki atribut `id` bernilai "nama". Ketika label ini diklik, fokus akan dipindahkan ke elemen input yang terkait.  
`Tag <b>`: Ini adalah tag untuk memberi teks cetak tebal.
`Teks "nama"`: Ini adalah teks yang akan ditampilkan di dalam label. Dalam hal ini, teks tersebut ditampilkan dalam cetak tebal karena dikelilingi oleh tag `<b>`.
`Tag <input>`: Ini adalah tag untuk membuat elemen input dalam formulir HTML.  
`Attribute type="text"`: Ini menentukan bahwa elemen input tersebut adalah input teks.  
`Attribute id="nama"`: Ini adalah atribut yang memberikan identifikasi unik untuk elemen input. Label menggunakan atribut `for` untuk mengaitkan dirinya dengan elemen input yang memiliki id yang sama.  
`Attribute required`: Ini menentukan bahwa pengguna harus memasukkan nilai ke dalam elemen input ini sebelum mengirimkan formulir. Jika tidak, formulir tidak akan dapat disubmit.  
`Tag <br>`: Ini adalah tag untuk membuat jeda baris (line break). Dalam konteks ini, digunakan untuk membuat jeda antara elemen label, elemen input, dan elemen-elemen berikutnya dalam halaman HTML.

## Kode program
```html
<label for="Jenis Bunga"> Jenis Bunga : </label> <br>
        <select id="jenis bunga" name="bunga">
            <option disabled> --- Pilih Bunga --- </option>
            <option value="Bunga 1">  Bunga 1 </option>
            <option value="Bunga 2"> Bunga  2</option>
            <option value="Bunga 3">  Bunga 3</option>
            <option value="Bunga 4">  Bunga 4</option>
            <option value="Bunga 5">  Bunga 5 </option>
        </select> <br> <br>
```

## Analisis : 
`Tag <label>`: Ini adalah tag untuk menautkan teks deskripsi (label) dengan elemen input pada formulir HTML.    
`Attribute for="Jenis Bunga"`: Ini menentukan bahwa label tersebut terkait dengan elemen input yang memiliki atribut `id` bernilai "Jenis Bunga". Ketika label ini diklik, fokus akan dipindahkan ke elemen input yang terkait.
`Teks "Jenis Bunga :" `: Ini adalah teks yang akan ditampilkan di dalam label, memberi petunjuk kepada pengguna tentang informasi yang diharapkan untuk diinput atau dipilih.      
`Tag <select>`: Ini adalah tag untuk membuat sebuah dropdown list atau daftar pilihan.  
`Attribute id="jenis bunga"`: Ini adalah atribut yang memberikan identifikasi unik untuk elemen dropdown list ini.      
`Attribute name="bunga"`: Ini adalah atribut yang memberikan nama untuk elemen dropdown list ini, yang akan digunakan ketika formulir dikirimkan.      
`Tag <option>`: Ini adalah tag untuk menentukan pilihan dalam dropdown list.  
`Attribute disabled`: Ini menandakan bahwa opsi tersebut tidak dapat dipilih oleh pengguna. Ini digunakan untuk opsi pertama yang berfungsi sebagai label atau instruksi untuk pengguna.      
`Teks "--- Pilih Bunga ---" `: Ini adalah teks yang ditampilkan sebagai opsi pertama dalam dropdown list, memberikan instruksi kepada pengguna untuk memilih salah satu opsi yang tersedia.
`Attribute value="Bunga 1"`: Ini menentukan nilai yang akan dikirimkan ke server ketika opsi tersebut dipilih. Dalam hal ini, nilai yang akan dikirim adalah "Bunga 1".
`Teks "Bunga 1" `: Ini adalah teks yang akan ditampilkan sebagai pilihan pertama dalam dropdown list.      
Selanjutnya, langkah-langkah 3 (untuk membuat opsi dalam dropdown list) diulang untuk setiap pilihan yang tersedia dalam dropdown list.
`Tag <br>`: Ini adalah tag untuk membuat jeda baris (line break). Dalam konteks ini, digunakan untuk membuat jeda antara elemen label, dropdown list, dan elemen-elemen berikutnya dalam halaman HTML.

## Kode program
```html
 <label for="pembayaran"> Pembayaran </label><br>
        <input type="radio" name="pembayaran"> 
        <label> Tunai </label>
        <input type="radio" name="pembayaran"> 
        <label> Transfer </label> <br> <br>
```

## Analisis : 
`<label for="pembayaran"> Pembayaran </label>`: Ini adalah label yang mengidentifikasi grup opsi pembayaran. Atribut `for` memberikan referensi ke elemen input dengan id "pembayaran", yang pada kasus ini tidak ada. Secara umum, atribut `for` biasanya digunakan dengan elemen input yang memiliki id unik, yang memungkinkan pengguna untuk mengklik label untuk memilih elemen input yang sesuai.  
`<input type="radio" name="pembayaran">`: Ini adalah elemen input tipe radio button untuk opsi pembayaran. Atribut `type` menentukan tipe input sebagai radio button. Atribut `name` adalah nama grup radio button yang sama, dalam hal ini "pembayaran". Ini memastikan bahwa hanya satu opsi pembayaran yang dapat dipilih oleh pengguna.
`<label> Tunai </label>`: Ini adalah label yang menunjukkan opsi pembayaran "Tunai" untuk elemen radio button sebelumnya. Label ini tidak terhubung ke elemen input secara eksplisit dengan atribut `for`, sehingga klik pada label tidak memilih opsi pembayaran.    
`<input type="radio" name="pembayaran">`: Ini adalah elemen input tipe radio button untuk opsi pembayaran kedua. Mirip dengan elemen sebelumnya, tetapi memiliki teks label yang berbeda.    
`<label> Transfer </label>`: Ini adalah label yang menunjukkan opsi pembayaran "Transfer" untuk elemen radio button kedua. Seperti sebelumnya, label ini juga tidak terhubung ke elemen input secara eksplisit.    
`<br> <br>`: Ini adalah elemen line break untuk memberi jarak antara elemen-elemen dalam formulir.

## Kode program
```html
Alamat Pengiriman: <br>
        <textarea cols="25" rows="5"> </textarea> <br> <br>
```

## Analisis : 
`<p>Alamat Pengiriman:</p>`: Ini adalah elemen paragraf yang memberikan label atau instruksi kepada pengguna bahwa field berikutnya adalah untuk memasukkan alamat pengiriman. Penggunaan tag `<p>` disini untuk menunjukkan paragraf atau bagian dari teks, yang biasanya digunakan untuk menampilkan teks yang terstruktur dalam dokumen HTML.    
`<textarea cols="25" rows="5"> </textarea>`: Ini adalah elemen textarea yang digunakan untuk memasukkan teks dengan lebih dari satu baris. Atribut `cols` menentukan jumlah kolom teks yang akan ditampilkan, sedangkan atribut `rows` menentukan jumlah baris teks yang akan ditampilkan. Dalam hal ini, textarea memiliki 25 kolom dan 5 baris. Isi awal dari textarea adalah spasi kosong, yang nantinya akan diisi oleh pengguna dengan alamat pengiriman.
`<br> <br>`: Ini adalah elemen line break yang digunakan untuk memberi jarak antara elemen-elemen dalam formulir.

## Kode program
```html
<label for="waktu"> <B> Waktu Pengiriman </B></label> <BR>
        <input type="checkbox" name="pagi"> pagi
        <input type="checkbox" name="siang"> siang 
        <input type="checkbox" name="sore"> sore
        <input type="checkbox" name="malam"> malam 
        <BR> <BR>
        <input type="submit" value="Pesan">
        <input type="reset" value="ulang"> <br>
```

## Analisis : 
`<label for="waktu"> <B> Waktu Pengiriman </B></label>`: Ini adalah label yang mengidentifikasi grup opsi waktu pengiriman. Tag `<B>` menghasilkan teks dalam format tebal. Atribut `for` memberikan referensi ke elemen input dengan id "waktu", namun dalam kode tersebut tidak terdapat elemen input dengan id tersebut.    
`<BR>`: Ini adalah elemen line break yang digunakan untuk memberi jarak antara elemen-elemen dalam formulir.    
`<input type="checkbox" name="pagi"> pagi`: Ini adalah elemen input tipe checkbox untuk memilih waktu pengiriman "pagi". Atribut `type` menunjukkan tipe input sebagai checkbox. Atribut `name` memberikan nama untuk grup checkbox, yang dalam hal ini adalah "pagi".    
`<input type="checkbox" name="siang"> siang`: Ini adalah elemen input tipe checkbox untuk memilih waktu pengiriman "siang". Sama seperti elemen sebelumnya, tetapi dengan label yang berbeda.    
`<input type="checkbox" name="sore"> sore`: Ini adalah elemen input tipe checkbox untuk memilih waktu pengiriman "sore".    
`<input type="checkbox" name="malam"> malam`: Ini adalah elemen input tipe checkbox untuk memilih waktu pengiriman "malam".    
`<input type="submit" value="Pesan">`: Ini adalah elemen input tipe submit yang menampilkan tombol "Pesan". Ketika tombol ini diklik, data pada formulir akan dikirimkan.    
`<input type="reset" value="ulang">`: Ini adalah elemen input tipe reset yang menampilkan tombol "Ulang". Ketika tombol ini diklik, semua input pada formulir akan direset menjadi nilai awalnya.    
`<br>`: Ini adalah elemen line break yang digunakan untuk memberi jarak antara elemen-elemen dalam formulir.

## Kode program
```html
<a href="list bungaa.html"> Liat daftar Bunga </a> <BR>
        <a href="index.html"> Kembali ke home </a>
```

## Analisis : 
`<a href="list bungaa.html"> Liat daftar Bunga </a>`: Ini adalah sebuah hyperlink yang mengarahkan pengguna ke halaman dengan daftar bunga. Atribut `href` menentukan alamat URL dari halaman tujuan, dalam hal ini "list bungaa.html". Teks di antara tag `<a>` adalah teks yang akan ditampilkan kepada pengguna sebagai tautan. Dalam hal ini, teks yang ditampilkan adalah "Liat daftar Bunga".    
`<a href="index.html"> Kembali ke home </a>`: Ini adalah sebuah hyperlink yang mengarahkan pengguna kembali ke halaman utama (home) dari situs web. Atribut `href` menentukan alamat URL dari halaman tujuan, dalam hal ini "index.html". Teks di antara tag `<a>` adalah teks yang akan ditampilkan kepada pengguna sebagai tautan. Dalam hal ini, teks yang ditampilkan adalah "Kembali ke home".    
`<BR>`: Ini adalah elemen line break yang digunakan untuk memberi jarak antara dua tautan (anchor) dalam dokumen HTML.

## Hasil
![](asetremed/html3.png)