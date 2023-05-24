---
sidebar_position: 1
---

# Pengenalan

## Apa itu HTML?

<p style={{textAlign: 'center'}}><img
src={require('/img/html5.png').default}
alt="logo"
title="HTML5 (HyperText Markup Language) Essentials"
width="200"
/></p>

HTML (HyperText Markup Language) adalah bahasa markah yang digunakan untuk membuat dan memformat halaman web. HTML digunakan untuk mengatur struktur dan tampilan konten pada halaman web, seperti teks, gambar, video, tautan, tabel, dan elemen-elemen lainnya.

Dalam HTML, elemen-elemen dasar disusun dalam bentuk "tag" yang dikelilingi oleh tanda kurung sudut **(< >)**. Setiap tag HTML memberi tahu browser bagaimana cara menampilkan konten yang terkandung di dalamnya. Sebagian besar elemen HTML memiliki tag pembuka dan penutup, dan konten yang ingin ditampilkan diletakkan di antara kedua tag tersebut.

## Struktur Dokumen HTML
Dokumen HTML biasanya terbagi menjadi 2 bagian, **BODY** dan **HEAD**.
- **HEAD**: Bagian ini biasanya berisi informasi-informasi tentang dokumen HTML terserbut. Seperti judul halaman tersebut, versi HTML yang digunakan, meta data, dll
- **BODY**: Bagian ini berisikan seluruh hal yang ingin kita tampilkan ke halaman web
**Contoh Struktur HTML**:

```html
<html>
	<head>
		<title>Pengantar HTML</title>
	</head>

	<body>
		<h1>Ini Judul pake H1</h1>
		Ini deskripsi
	</body>
</html>
```
## Syntax HTML
<p style={{textAlign: 'center'}}><img
src={require('/img/html-syntax.png').default}
alt="logo"
title="HTML5 (HyperText Markup Language) Essentials"
width="auto"
/></p>

- Syntax HTML sangat mudah untuk dipelajari
- File `.html` atau `.htm` hanyalah sebuah file text yang bisa di buka oleh banyak text editor
- HTML menggunakan `TAGS` untuk menandai suatu konten tertentu
- `<start_tag> Suatu konten </end_tag>` **Contoh**: `<p> p adalah tag paragraf yang digunakan untuk menulis text dalam bentuk paragraf. </p>`
- Kita juga bisa membuat `nested elements` atau `elemen bersarang` seperti `<tag1><tag2>Konten bersarang</tag2></tag1>` **Contoh**: `<p><strong>Teks tebal</strong></p>`

## Kategori Element HTML

Tag HTML dibagi menjadi beberapa kategori berdasarkan:

### Output
**Block Level elements**
   - Block level element akan memenuhi keseluruhan / 100% dari lebar element _parentnya_
   - Block level element dimulai pada baris baru setiap kali didefinisikan
   - Contoh Tags: `<p>, <div>, <form>, <header>, <nav>, <ul>, <li>, <h1> hingga <h6>`

**In-line elements**
- Inline elements hanya akan mengambil ukuran sesuai dengan ukurannya sendiri
- Inline elements dimulai pada baris yang sama dimana ia didefinisikan
 - Contoh Tags: `<a>, <span>, <strong>, <em>, <u>, <b>, <i> <font>, <center>`
     
### Closing
**Paired Tags / Container Tags**
- Paired Tags biasanya didefinisikan berpasangan, ada `<start_tag>` dan `</close_tag>`
- Contoh Tags: `<html>, <head>, <title>, <body>, <p>, <h1> to <h6>, <strong>`
      

**Unpaired Tags / Unclosed Tags / Empty Tags / Non-Container Tags**
- Unpaired tags tidak mewajibkan elementnya untuk diberikan `</close_tag>`
- Unpaired tags di tutup langsung saat mulai didefinisikan
- Contoh Tags: `<br />, <hr />, <link /> <img />`
## Buat file HTML pertamamu
Buka text editor pilihan kalian. Kemudian copy kode di bawah ini:
```html
<html>
	<head>
		<title>Website Pertamaku</title>
	</head>

	<body>
		<h1>Ini website pertamaku</h1>
		lihat yaa
	</body>
</html>
```

Simpan file tersebut dengan ekstensi `.html`. Bukalah file tersebut menggunakan web browser pilihan kalian