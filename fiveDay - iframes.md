# iframes
digunakan untuk menampilkan website yg lain di website kita ma brou..!

contoh 1.1ex:
```html
<iframe src="https://www.pexels.com/id-id/pencarian/foto%20gadis%20cantik/"></iframe>
```

contoh 1.2ex:
```html
<iframe src="nama_HTML_Kalian" height="200" width="300"></iframe>
```

Atau Anda dapat menggunakan CSS untuk mengatur tinggi dan lebar iframe:
contoh 1.3ex:
```html
<iframe src="nama_HTML_Kalian" style="height:200px;width:300px;"></iframe>
```
menghilangkan border
contoh 1.4ex:
```html
<iframe src="nama_HTML_kalian" style="border:none;"></iframe>
```
memberi warna border
contoh 1.5ex:
```html
<iframe src="demo_iframe.htm" style="border:2px solid red;"></iframe>
```

## Target for a Link
```html
<h2>Iframe - Target for a Link</h2>

<iframe height="300px" width="100%" src="nama_html_kalian" name="iframe_a"></iframe>

<p><a href="https://www.pexels.com/id-id/pencarian/foto%20gadis%20cantik/" target="iframe_a">W3Schools.com</a></p>

<p>When the target of a link matches the name of an iframe, the link will open in the iframe.</p>
```
