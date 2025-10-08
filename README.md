# 🧩 Praktikum 3: Membuat List, Table, dan Form

## 📘 Tujuan
Pada praktikum ini, mahasiswa belajar untuk:
1. Memahami struktur dasar pembuatan **List (Daftar)**.
2. Memahami struktur dasar pembuatan **Table (Tabel)**.
3. Memahami tag dasar untuk membuat **Form (Formulir)**.
4. Membuat dokumen HTML yang lebih kompleks.
5. Mengimplementasikan **CSS** pada List, Table, dan Form.

---

## ⚙️ Persiapan
1. Buka **VS Code** atau text editor lainnya.  
2. Buat folder baru dengan nama **Lab3Web**.  
3. Lakukan setiap langkah secara berurutan sesuai panduan modul.  
4. Validasi dokumen HTML menggunakan [validator.w3.org](https://validator.w3.org).

---

## 📝 Langkah-Langkah Praktikum

### 1. Membuat List
Buat file **lab3_list.html**, lalu isi struktur HTML dasar:
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HTML Lanjutan</title>
</head>
<body>
  <header>
    <h1>Membuat List</h1>
  </header>
</body>
</html>
```
## Screenshot
![Membuat list](gambar1.png)

### 2. Ordered List
Ordered List menampilkan daftar yang berurutan (1, 2, 3 atau A, B, C).
```html
<section id="order-list">
  <h2>Ordered List</h2>
  <ol type="A" start="D">
    <li>Pemrograman Web</li>
    <li>Sistem Informasi</li>
    <li>Basis Data 2</li>
  </ol>
</section>
```
## Screenshot
![Ordered list](gambar2.png)

### 3. Unordered List
Unordered List menampilkan daftar tidak berurutan, dengan simbol seperti lingkaran atau kotak.
```html
<section id="unorder-list">
  <h2>Unordered List</h2>
  <ul type="square">
    <li>Jaringan Komputer</li>
    <li>Struktur Data</li>
    <li>Algoritma & Pemrograman</li>
  </ul>
</section>
```
## Screenshot
![Unordered List](gambar3.png)

### 4. Description List
Description List digunakan untuk menampilkan istilah dan deskripsi.
```html
<section id="desc-list">
  <h2>Description List</h2>
  <dl>
    <dt>Fakultas Teknik</dt>
    <dd>Teknik Informatika</dd>
    <dd>Teknik Industri</dd>
    <dd>Teknik Lingkungan</dd>
    <dt>Fakultas Ekonomi dan Bisnis</dt>
    <dd>Akuntansi</dd>
    <dd>Manajemen</dd>
    <dd>Bisnis Digital</dd>
  </dl>
</section>
```
## Screenshot
![Description List](gambar4.png)

### 5. Membuat Table
Buat file lab3_tabel.html dan isi struktur HTML-nya seperti berikut:
```html
<table border="1" cellpadding="4" cellspacing="0">
  <thead>
    <tr>
      <th>No.</th>
      <th>Fakultas</th>
      <th>Program Studi</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1.</td>
      <td>Teknik</td>
      <td>Teknik Informatika</td>
    </tr>
    <tr>
      <td>2.</td>
      <td>Teknik</td>
      <td>Teknik Industri</td>
    </tr>
    <tr>
      <td>3.</td>
      <td>Teknik</td>
      <td>Teknik Lingkungan</td>
    </tr>
  </tbody>
</table>
```
## Screenshot
![Membuat Tabel](gambar5.png)




