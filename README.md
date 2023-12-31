# Web1 praktikum
Instruksi Praktikum
1. Persiapkan text editor misalnya VSCode.
2. Buat file baru dengan nama lab1_tag_dasar.html
3. Buat struktur dasar dari dokumen HTML.
4. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.
5. Lakukan validasi dokumen html dengan mengakses http://validator.w3.org

## Langkah-langkah Praktikum
Persiapan membuka VSCode dan Browser.
![s1](https://github.com/Agussetiaa/Praktikumweb1/assets/115542822/0750032c-40c7-44ca-89a4-70b3ed11802f)
Kemudian buat file baru dengan nama lab1_tag_dasar.html dan tambahkan tag dasar dokumen
HTML.

## Modul Praktikum Pemrograman Web
![s22](https://github.com/Agussetiaa/Praktikumweb1/assets/115542822/6edb53b8-715e-477a-84f9-3c8373fe7f83)
Kemudian selanjutnya, buka file tersebut pada web browser misalnya Mozilla Firefox.


![s2](https://github.com/Agussetiaa/Praktikumweb1/assets/115542822/e53dae58-2099-4793-81ed-dc3e03649a83)




## 1.Membuat Paragraf
```
<!-- Ini adalah paragraf pertama -->
<p>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi
Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat
adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar
HTML.</p>
<!-- Ini adalah paragraf kedua -->
<p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling
mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan
tag dasar html.</p>
```

![ss1](https://github.com/Agussetiaa/Latihanweb1/assets/115542822/2f8bd369-d0c2-4732-84a4-b6ec0f777b5f)

## 2.Menambahkan Judul
```
<!-- judul paragraf pertama -->
<h1>Belajar Dasar HTML</h1>
<!-- judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>
```

![ss2](https://github.com/Agussetiaa/Latihanweb1/assets/115542822/4a3266e5-f029-40c3-b6ac-9b5739ac88f6)

## 3.Memformat teks
```
 <p align=”center”>Kami sedang belajar <mark>HTML dasar,</mark> pada matakuliah <b>Pemrograman Web</b>
        di Prodi <I>Teknik Informatika </I> <u>Universitas Pelita Bangsa</u>. Pelajaran pertama
        yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
        tag-tag dasar HTML.</p>
```

![ss3](https://github.com/Agussetiaa/Latihanweb1/assets/115542822/0daca610-1810-4c24-b24b-bb95a04fd511)

## 4.Menyisipkan Gambar
```
<h3>Menambahkan Gambar</h3>
    <img src="logo upb.png" width="200" title="Logo Univeritas Pelita Bangsa">
```

![ss4](https://github.com/Agussetiaa/Latihanweb1/assets/115542822/9018e4c5-9f9c-4354-b1a3-9284b0ca940f)


![ss4a](https://github.com/Agussetiaa/Latihanweb1/assets/115542822/56de970b-841b-42f5-a88f-e78b09506fe3)

## 5. Menambahkan Hyperlink
```
 <nav>
        <a href="lab1_tag_dasar.html">Dasar HTML</a>
        <a href="lab1_halaman2.html">Halaman 2</a>
        <a href="http://www.google.com">Halaman Web Eksternal Google</a>
        </nav>
    <hr>
```

![ss5](https://github.com/Agussetiaa/Latihanweb1/assets/115542822/7827826b-2851-44e2-8f46-c322888b7961)

## Halaman 2

![ss5a](https://github.com/Agussetiaa/Latihanweb1/assets/115542822/c012fd87-63be-4a7f-85ec-9c7ebd807f80)


## Jawab Pertanyaan Berikut
1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?
```
Ketika saya salah dalam penulisan tag img yang seharusnya <img> menjadi </img>, gambar yang saya ingin tampilkan menjadi tidak tampil dalam web/browser.
```

2. Apa perbedaan dari tag `<p>` dengan tag `<br>`, berikan penjelasannya!
```
tag <br> melompati satu line cocok untuk memulai paragraf baru sedangkan tag <p> seperti menekan enter di software document editor 
```

3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!
```
Perbedaan atribut title dan alt yaitu pada gambar yang dihasilkan. Ketika gambar berhasil ditampilkan maka akan terlihat sebuah title, sedangkan jika gambar gagal ditampilkan maka akan menampilkan teks dalam atribut alt tersebut
```

4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
```
Untuk menampilkan gambar yang proporsional sebaiknya kedua attribut tersebut diisi sesuai dengan ukuran yang kita inginkan. Dengan mengatur kedua ukuran tersebut kita dapat menyesuaikan gambar dengan lokasi penempatan gambar tersebut.
```

5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, _parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?
```
Nilai _blank akan membuka link/halaman di tab baru.
Nilai _self akan membuka link/halaman di tab saat ini.
Nilai _top membuka link/halaman dan membatalkan semua frame.
Nilai _parent membuka link/halaman pada parent frame.
``
