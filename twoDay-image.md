# Hari kedua
semangat guys !!

## `<img>`
adalah tag yg untuk menampilkan gambar
```html
 <img src="mantan.jpg" alt="Italian Trulli" title="ini gambar">
```

|atribut|fungsi|
|---|---|
|alt|memberi tahu kepada user ketika gambar tidak tampil|
|title|untuk menampilkan value ketika mouse menyentuh area badan gambar|


### bagaimana untuk mengatur gambar?
yaitu menggunakan heigh dan width
```html
<img src="mantan.gif" height="500" width="300">
```

|atribut|fungsi|
|---|---|
|width|untuk lebar gambar|
|height|untuk tinggi gambar|

### bagaiaman menampatkan gambar di browser lain?
```html
<img src="https://www.abc.net.au/indonesian/image/12321498-4x3-940x705.jpg" height="500" width="300">
```

## menggunakan use `<map>...</map>`
sytax:
```html
<img src ="..." alt="..." usemap="#petaku" />

<map name="petaku">
  <area shape="rect" coords="x1,y1,x2,y2" href="URL" alt="Nama Area" />
  <area shape="circle" coords="x,y,r" href="URL" alt="Nama Area" />
  <area shape="poly" coords="x1,y1,x2,y2,...,xn,yn" href="URL" alt="Nama Area" />
</map>
```
coba 1.1ex dibawah ini:
```html
 <img src="https://s4.bukalapak.com/uploads/content_attachment/40f201de95e30512e4a61ea5/w-744/Alat_Elektronik_Pintar_Samsung_-_2.jpg" alt="Workplace" usemap="#workmap" width="400" height="379">

    <map name="workmap">
      <area shape="rect" coords="80,20,245,245" alt="Computer" href="https://id.wikipedia.org/wiki/Lukisan">
      <area shape="circle" coords="100,290,36" alt="Cup of coffee" href="https://www.tokopedia.com/find/guci-antik">
    </map>
```

