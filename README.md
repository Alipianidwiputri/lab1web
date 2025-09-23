Penejelasan kode Python 

```html
<!DOCTYPE html>
<html lang="en">
```

`<!DOCTYPE html>`: mendefinisikan bahwa dokumen ini menggunakan HTML5
`<html lang="en">`: elemen pembungkus utama dokumen HTML, dengan atribut `lang="en"` menandakan bahasa utama halaman adalah English (meski isi teks-nya pakai bahasa Indonesia).

```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

```

`<head>`: bagian kepala dokumen, berisi informasi meta dan judul, bukan konten utama yang ditampilkan.

`<meta charset="UTF-8">` Untuk mengatur encoding karakter ke UTF-8, supaya teks (termasuk karakter spesial/aksara Indonesia) bisa tampil dengan benar.
`<meta name="viewport" content="width=device-width, initial-scale=1.0">`** Untuk membuat halaman responsif di perangkat mobile. Artinya, tampilan menyesuaikan lebar layar perangkat.
`<title>Document</title>` → Judul halaman yang tampil di tab browser (bukan di dalam body).

```html
<body>
    <nav> 
        <a href="lab1_tag_dasar.html">Dasar HTML</a> 
        <a href="lab1_halaman2.html">Halaman 2</a> 
        <a href="http://www.google.com">Halaman Web Eksternal Google</a> 
    </nav> 
    <hr>
```

`<body>`: bagian utama dokumen, semua konten yang terlihat pengguna ada di sini.
`<nav>`: bagian navigasi, biasanya berisi link ke halaman lain.
`<a href="...">`: hyperlink (anchor).

- `href="lab1_tag_dasar.html"` → Link ke file lokal bernama *lab1\_tag\_dasar.html*.
- `href="lab1_halaman2.html"` → Link ke halaman kedua (juga file lokal).
- `href="http://www.google.com"` → Link eksternal ke situs Google.

`<hr>`: membuat garis horizontal, biasanya dipakai untuk pemisah konten.

```html
    <p> Nama        : Alipiani Dwi Putri </p>
    <p> NIM         : 312410691 </p>
    <p> Kelas       : TI 24 A2 </p>
    <p> Mata Kuliah : Pemrograman Web 1</p>
```

`<p>`: menampilkan teks sebagai paragraf.
Di sini dipakai untuk menampilkan identitas mahasiswa (nama, NIM, kelas, mata kuliah).

```html
    <h1>Belajar Dasar HTML</h1>
```

`<h1>`: heading level 1, biasanya dipakai sebagai judul utama halaman.
Teks "Belajar Dasar HTML" menjadi headline besar di halaman.

```html
    <p align=”center”>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web 
        di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML.</p>
```

- Paragraf yang berisi penjelasan tujuan pembelajaran.
- Atribut `align="center"` dipakai untuk meratakan teks ke tengah, meskipun catatan: dalam HTML5 atribut ini **sudah usang (deprecated)**, sebaiknya pakai CSS (`text-align: center;`).

```html
    <h1>Paragraf Pada HTML</h1>
```

Heading kedua yang memperkenalkan submateri tentang paragraf.

```html
    <p align=”right”>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan tag dasar html.</p> 
```

- Paragraf lagi, dengan atribut `align="right"`, jadi teksnya diratakan ke kanan.
(Sama seperti sebelumnya, di HTML modern sebaiknya pakai CSS.)

```html
    <p> ini adalah tugas praktikum </p>
```

- Paragraf sederhana berisi catatan bahwa ini adalah tugas praktikum.

```html
    <h3>Menambahkan Gambar</h3>
```

- Heading level 3, subjudul untuk bagian tentang menambahkan gambar.

```html
    <img src="Logo-Universitas-Pelita-Bangsa-removebg-preview.png"
```

- `<img>`: digunakan untuk menampilkan gambar.

- `src="..."` → menunjukkan lokasi file gambar.
  Dalam hal ini, file gambar adalah *Logo-Universitas-Pelita-Bangsa-removebg-preview\.png*.

# Tapi ada masalah: tag `<img>` belum ditutup. Harusnya ditulis:

```html
<img src="Logo-Universitas-Pelita-Bangsa-removebg-preview.png" alt="Logo Universitas Pelita Bangsa">
```

`alt="..."` itu wajib secara akademis, sebagai teks alternatif kalau gambar gagal ditampilkan atau untuk aksesibilitas.

```html
</body>
</html>
```

- Menutup elemen body dan html. Ini menandakan dokumen HTML selesai.

Kesimpulan akademis:

- Struktur kode sudah sesuai standar HTML dasar (ada head, body, nav, heading, paragraf, dan gambar).
- Ada beberapa atribut (`align`, `img` tanpa `alt`) yang sudah tidak sesuai rekomendasi HTML5 modern, sebaiknya diganti dengan **CSS** untuk styling.
- Navigasi `<nav>` bagus untuk struktur semantik.
- Identitas mahasiswa jelas ditampilkan dengan paragraf.
