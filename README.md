# Lab1Web
# Praktikum1 (Pemrograman Web)

## Ery Shandy
## 312010201
## TI.20.A.2
## Universitas Pelita Bangsa


## Langkah 1
### Buka Visual Studio Code dan buatlah file HTML baru. Setelah itu buatlah struktur dasar HTML

```
<!DOCTYPE html>
<html>
<head>
    <title>Tag HTML Dasar</title>
</head>
<body>

</body>
</html>
```
<img width="960" alt="foto 1 labweb" src="https://user-images.githubusercontent.com/73053784/157254394-a6669926-88bc-480f-a94e-b7f378745796.png">

## Langkah 2
### Membuat 2 buah paragraf dan mengatur atribut paragraf 
Selanjutnya, buatlah beberapa paragraf sederhana sebagai berikut
```
<!-- Ini adalah paragraf pertama -->
<p align="center">Kami sedang belajar \HTML dasar, pada matakuliah Pemrograman
    Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    tag-tag dasar HTML.</p>

<!-- Ini adalah paragraf kedua -->
<p align="right">Ini merupakan sebuah paragraf yang terdiri dari beberapa
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat
    dengan menggunakan tag dasar html.</p>
```
<img width="960" alt="foto 2 labweb" src="https://user-images.githubusercontent.com/73053784/157256289-5a1ca833-f4bf-4ece-9736-ac9dd55f3263.png">

## Langkah 3
### Menambahkan judul menggunakan Tag Heading (h1, h2, h3, h4, h5, h6). Semakin besar angka Tag Heading, Semakin kecil ukuran Headingnya.
```
<!-- judul paragraf pertama -->
<h1>Belajar Dasar HTML</h1>

<!-- judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>
```
<img width="960" alt="foto 3 labweb" src="https://user-images.githubusercontent.com/73053784/157257108-4dafc124-345a-408d-89f7-53f43a37fd22.png">

## Langkah 4
### Memformat Teks menggunakan format-format teks yang tersedia seperti ``` <b>, <strong>, <i>, <em>, <mark>, <small>, <dell>, <ins>, <sub>, <sup>```.
```
<p align="left">Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman
    Web</b> di Prodi <i>Teknik Informatika</i> <ins>Universitas Pelita Bangsa</ins>. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    tag-tag dasar HTML.</p>
```
<img width="960" alt="foto 4 labweb" src="https://user-images.githubusercontent.com/73053784/157258099-8013cfd4-db3a-4d28-a487-ab101d718abe.png">

## Langkah 5
### Menampilkan gambar dengan cara mengambil gambar lalu sisipkan gambar dengan file HTML yang sudah di buat
<img width="960" alt="foto 5 labweb" src="https://user-images.githubusercontent.com/73053784/157259643-2ae822a0-4721-4178-93d3-5b2b903de81f.png">

```
<!-- sub judul paragraf -->
<h3>Menambahkan Gambar</h3>
<!-- menambahkan gambar pada dokumen -->
<img src="logo UPB.png" width="200" title="Logo Univeritas Pelita Bangsa">
</body>
</html>
```

<img width="960" alt="foto 5 tampilan labweb" src="https://user-images.githubusercontent.com/73053784/157261100-d48c6a95-d9f2-4e39-9e56-367d90a2ff0b.png">

## Langkah 6
### Menambahkan Hyperlink. Tambahkan hyperlink pada dokumen sebelum heading 1.
```
 <!-- menambahkan link navigasi -->
<nav>
    <a href="lab1_tag_dasar.html">Dasar HTML</a>
    <a href="lab1_halaman2.html">Halaman 2</a>
    <a href="http://www.google.com">Halaman Web Eksternal Google</a>
    </nav>
    <hr>
```
<img width="960" alt="foto 6 labweb" src="https://user-images.githubusercontent.com/73053784/157262941-3c63a9b3-581e-4a1b-93fd-7a953b92609e.png">

## Langkah 7
### Membuat halaman ke 2 yang akan terhubung dengan halaman 1 dengan cara menggunakan hyperlink
```
<!DOCTYPE html>
<html>
<head>
    <title>Tag HTML Dasar</title>
</head>
<body>
<h1>Halaman Ke 2</h1>
<p align="justify">Ini adalah halaman kedua.</p>
</body>
</html>
```
<img width="960" alt="foto 7 labweb" src="https://user-images.githubusercontent.com/73053784/157263855-eeb79fcb-b627-4228-9ae7-a5f2258d0529.png">

## Jawablah pertanyaan berikut 
1. Lakukan perubahan pada code sesuai dengan keinginan anda, amati perubahannya adakah _error_ ketika terjadi kesalahan penulisan tag?
```
Ketika saya mencoba melakukan perubahan pada tag paragraf menggunakan huruf kapital <P tidak terjadi error ataupun perubahan pada code maupun hasil di browser.
Begitupun ketika saya mencoba mennghilangkan penutup atau garis miring (/) di penghujung paragraf pun tidak terjadi error ataupun perubahan pada code maupun hasil di browser.
```
2. Apa perbedaan dari tag `<p>` dengan tag `<br>` berikan penjelasannya!
```
Dari hasil pengamatan saya, tag <p> digunakan untuk mengganti paragraf, karena jarak garis baru (enternya) lebih jauh dibanding dengan tag <br> yang digunakan untuk pindah ke garis baru
```
3. Apa perbedaan atribut `title` dan `alt` pada tag `<img>`, berikan penjelasannya!
```
Atribut title pada tag <img> digunakan untuk memberikan informasi pada gambar yang di tampilkan.
Sedangkan atribut alt pada tag <img> digunakan untuk memberikan altenatif keterangan pada gambar jika gambar tersebut gagal untuk ditampilkan.
```
4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
```
Menurut saya, bisa disesuaikan. Misalkan untuk mengatur gambar agar tampil proporsional gunakan width dan height sesuai ukuran aslinya, jika ingin mengecilkan ukuran gambar gunakan ukuran yang proposional misal, kita akan ubah width 50px dan height 50px.
```
5. Pada link tambahkan atribut target dengan nilai atribut bervariasi (_blank, _self, _top, _parent), apa yang terjadi pada masing-masing nilai atribut tersebut?
```
Nilai _blank    : Menampilkan halaman website yang di link ke dalam tab yang baru.
Nilai _self     : Menampilkan halaman website yang di link ke dalam tab atau frame yang sama yang digunakan saat ini.
Nilai _top      : Menampilkan halaman website yang di link ke dalam tab yang baru yang ditampilkan dalam fullscreen dan membatalkan semua frame.
Nilai _parent   : Menampilkan halaman website yang di link ke dalam parent frame

