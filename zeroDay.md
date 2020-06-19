# HTML 5
HTML adalah singkatan dari ***Hypertext Markup Language***. HTML Bahasa Markup Hypertext yg terdiri dari tag dan atribut. yg memungkinkan seorang user untuk membuat dan menyusun bagian paragraf, heading, link atau tautan, dan blockquote untuk halaman web dan aplikasi.

## Apa itu tag?
(dalam hal ini tag HTML adalah) yang ditandai dengan karakter `<` dan `>`.
Tag disini dibagi menjadi dua yaitu tag pembuka <> dan penutup </>.
```
<p>.....</p> = <ini adlah tag pembuka>.... <dan ini adalah tag penutup/>
```

### apakah dalam tag html harus selalu ada tag pembuka dan penutup?
tidak jugha, ada beberpa yg harus menggunakan tag pembuka dan penutup dan jugha yg hanya satu.
contoh tag pembuka dan penutup:
```
<p>.....</p>
<b>.....</b>
```
contoh tag yg hanya salah satu
```
<hr> = </hr> -> sama sajja 
<br> = </br> -> sama sajja
```

## apa itu atribut?
jika sebelumnya kita telah belajar apa itu tag `<>`,`</>` dan elemen seperti `h1`,`p`,`div`. maka kali ini kita akan memahami apa yang dimaksud dengan aribut html.

nah atribut sendiri maksudnya adalah informasi tambahan yang diberikan kepada tag. informasi ini bisa berupa intruksi untuk warna dari text, besar huruf dari text atau yang lainya.

cara penulisan pun cukup menambahkan `name` dan `value`:
```html
<p align="left">Tulisan dengan format rata kiri</p>
<p style="text-align:center">Tulisan dengan format rata tengah</p>
```
jika kita lihat didalam tag elemen <p> itu ada atribut yg bernama align dan style dengan value yg berbeda tergantung atributnya.



## struktur html 5
```html
<!DOCTYPE html>
<html>
  <head>
  .
  .
  </head>
  <body> 
  .
  .
  </body>
</html>
```

1. `<!DOCTYPE html>` untuk memberitahu browser jika yg kita pakai adalah html 5
1. `<head>...<head/>` adalah tag pendukung atau bisa dibilang asset atau informasi yg dibuat oleh user
1. `<body>...</body>` adalah tag yg akan menapilkan output ke layar

# sekarang ayo kita buat aplikasi pertamu..!!
```html
<!DOCTYPE html>
<html>
 <head>
     <title>disini adalah judul</title>
 </head>
 <body>
     Hai Dunia Yang Indah dan banyak diperubutan  
 </body>
</html>
```

cara menjalankanya mudah kalian hanya perlu membuka file dengan browser kalian saya sarankan untuk membuka di google chrome.
