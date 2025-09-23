# Penjelasan kode Python dan screenshot setiap langkah dan perubahan

# Penjelasan kode Python

```html<img width="1915" height="1000" alt="Screenshot 2025-09-22 134909" src="https://github.com/user-attachments/assets/9575b07e-6bee-4a76-8c14-07363edd1e8a" />

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

**Output :**

<img width="935" height="48" alt="Screenshot 2025-09-23 122233" src="https://github.com/user-attachments/assets/629bba84-8d39-443d-b247-4b6c0141b309" />


```html
    <p> Nama        : Alipiani Dwi Putri </p>
    <p> NIM         : 312410691 </p>
    <p> Kelas       : TI 24 A2 </p>
    <p> Mata Kuliah : Pemrograman Web 1</p>
```

`<p>`: menampilkan teks sebagai paragraf.
Di sini dipakai untuk menampilkan identitas mahasiswa (nama, NIM, kelas, mata kuliah).

**Output :**

<img width="936" height="162" alt="Screenshot 2025-09-23 122401" src="https://github.com/user-attachments/assets/99b0e884-8e73-4e9d-bd2a-e9bc4ee913ac" />


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
- Atribut `align="center"` dipakai untuk meratakan teks ke tengah, meskipun catatan: dalam HTML5 atribut ini sudah usang (deprecated), sebaiknya pakai CSS (`text-align: center;`).

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

  **Output :**

  <img width="944" height="374" alt="Screenshot 2025-09-23 122553" src="https://github.com/user-attachments/assets/689cbd95-0da0-4ff6-a804-229a57d5a6b7" />


```html
    <h3>Menambahkan Gambar</h3>
```

- Heading level 3, subjudul untuk bagian tentang menambahkan gambar.
```
<img src="Logo-Universitas-Pelita-Bangsa-removebg-preview.png" alt="Logo Universitas Pelita Bangsa">
```

img: digunakan untuk menampilkan gambar.

src="..."→ menunjukkan lokasi file gambar.

alt="..."itu wajib secara akademis, sebagai teks alternatif jika gambar gagal ditampilkan atau untuk aksesibilitas.

Dalam hal ini, file gambar adalah Logo-Universitas-Pelita-Bangsa-removebg-preview.png
```
</body>
</html>
```
Menutup elemen body dan html. Ini menandakan dokumen HTML telah selesai.

**Output :**

<img width="950" height="776" alt="Screenshot 2025-09-23 122751" src="https://github.com/user-attachments/assets/ce098624-79c5-49d9-9b71-f0283cbd3623" />

**Kesimpulan:**

- Struktur kode sudah sesuai standar HTML dasar (ada head, body, nav, heading, paragraf, dan gambar).
- Ada beberapa atribut ( align, imgtanpa alt) yang sudah tidak sesuai rekomendasi HTML5 modern, sebaiknya diganti dengan CSS untuk styling.
- Navigasi <nav>bagus untuk struktur semantik.
- Identitas siswa jelas ditampilkan melalui paragraf.



  # Tangkapan Layar seluruh code Python

<img width="1919" height="1005" alt="Screenshot 2025-09-23 123217" src="https://github.com/user-attachments/assets/3f5436b0-4d27-4620-9eaa-6f11e17b7a34" />

# Tangkapan Layar Hasil (Output)

<img width="950" height="776" alt="Screenshot 2025-09-23 122751" src="https://github.com/user-attachments/assets/4c611f1b-f25b-4134-94d5-902558aa3354" />



