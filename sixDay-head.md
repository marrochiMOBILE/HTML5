# dibagian head html
## `<meta>...</meta>`
Elemen <meta> digunakan untuk menentukan set karakter mana yang digunakan, deskripsi halaman, kata kunci, penulis, dan metadata lainnya.

Metadata digunakan oleh browser (cara menampilkan konten), oleh mesin pencari (kata kunci), dan layanan web lainnya.

Tentukan set karakter yang digunakan:

```html
<meta charset="UTF-8">
```
Tentukan deskripsi halaman web Anda:
```html
<meta name="description" content="Free Web tutorials">
```
Tentukan kata kunci untuk mesin pencari:
```html
<meta name="keywords" content="HTML, CSS, XML, JavaScript">
```
Tentukan pembuat halaman:
```html
<meta name="author" content="Marrochi">
```

Refresh dokumen setiap 30 detik:
```html
<meta http-equiv="refresh" content="30">
```


Contoh tag <meta>:
```html
<meta charset="UTF-8">
<meta name="description" content="Free Web tutorials">
<meta name="keywords" content="HTML,CSS,XML,JavaScript">
<meta name="author" content="John Doe">
```


Di HTML, ada metode untuk memungkinkan desainer web mengambil kendali atas viewport, melalui tag <meta>.
Area pandang adalah area yang terlihat pengguna dari halaman web. Ini bervariasi dengan perangkat, dan akan lebih kecil di ponsel daripada di layar komputer.
Anda harus memasukkan elemen viewport <meta> berikut di semua halaman web Anda
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

Elemen viewport <meta> memberikan instruksi browser tentang cara mengontrol dimensi dan penskalaan halaman.
Lebar = bagian lebar perangkat mengatur lebar halaman untuk mengikuti lebar layar perangkat (yang akan bervariasi tergantung pada perangkat).
Skala awal = 1,0 bagian menetapkan tingkat pembesaran awal saat halaman pertama kali dimuat oleh browser.
Berikut adalah contoh halaman web tanpa tag meta viewport, dan halaman web yang sama dengan tag viewport <meta>:


> Tip: Jika Anda menjelajahi halaman ini dengan ponsel atau tablet, Anda dapat  melihat perbedaannya.
