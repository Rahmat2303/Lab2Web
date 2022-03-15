# Lab2Web
## CSS Dasar
### 1. Membuat dokumen HTML
Buatlah dokumen HTML seperti berikut:

![Gambar 1](screenshot/ss1a.PNG)

Dan ini tampilannya di browser, tampilannya masih polos karena belum menggunakan CSS.

![Gambar 2](screenshot/ss1b.PNG)

###  2. Mendeklarasikan CSS Internal
Untuk mendeklarasikan CSS internal menggunakan tag  `<style></style>` yang di simpan di bagian tag `<head></head>`.

Untuk tag `<body></body>` menggunakan **selector body** yang diisi dengan **"font-family:'Open Sans', sans-serif;"**.

Untuk tag `<header></header>` menggunakan **selector header** yang diisi dengan **"min-height: 80px; border-bottom:1px solid #77CCEF;"**.

Untuk tag `<h1></h1>` menggunakan **selector h1** yang diisi dengan **"font-size: 24px; color: #0F189F; text-align: center; padding: 20px 10px;"**.

Dan untuk tag `<i></i>`  yang ada di dalam tag `<h1></h1>` menggunakan **selector h1 i** yang diisi dengan **"color:#6d6a6b;"**.

Ini gambarnya :

![Gambar 3](screenshot/ss2a.PNG)

Ini tampilannya di browser :

![Gambar 4](screenshot/ss2b.PNG)

Terlihat jauh perbedaanya jika menggunakan CSS.

### 3. Menambahkan Inline CSS
Agar bisa mendeklarasikan **Inline CSS** yaitu dengan cara menambahkannya di dalam tag HTML. Contoh saat ini menambahkan **Inline CSS** di dalam tag `<p></p>`. Ketika menggunakan **Inline CSS** tidak perlu menggunakan selector, karena posisi CSSnya sudah ada di dalam tag HTML tersebut.

Seperti ini gambarnya :

![Gambar 5](screenshot/ss3a.PNG)

Kemudian ini tampilannya di browser :

![Gambar 6](screenshot/ss3b.PNG)

### 4. Membuat CSS Eksternal
Cara pertama yaitu buat file baru dengan format .css, seperti contohnya style_eksternal.css

Kemudian isi file tadi dengan deklarasi CSS seperti di gambar.

![Gambar 7](screenshot/ss4a.PNG)

Di bagian tag `<nav></nav>` di sisipkan hover agar pada saat di sentuh oleh kursor bagian tersebut akan berubah sesuai dengan deklarasi CSSnya.

Kemudian pada file HTML tambahkan tag `<link>` di bagian tag `<head></head>`.
Untuk href di isi dengan nama file CSS yang tadi sudah dibuat.

![Gambar 8](screenshot/ss4b.PNG)

Ini tampilannya di browser :

![Gambar 9](screenshot/ss4c.PNG)

###  5. Menambahkan CSS Selector
Tambahkan kode berikut pada file stle_eksternal.css, untuk **Selector ID** menggunakan tanda **#** dan untuk **Selector Class** menggunakan tanda titik.

![Gambar 10](screenshot/ss5a.PNG)

Dan ini tampilannya di browser :

![Gambar 11](screenshot/ss5b.PNG)

Nama ID atau nama Classnya harus sama dengan nama ID atau nama Class yang ada di file HTML.


