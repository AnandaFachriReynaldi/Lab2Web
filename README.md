# Lab2Web
## Ananda Fachri Reynaldi
## 312110248
## TI.21.B1

1. Membuat dokumen HTML baru di VS Code
![Step1](SS/SS1.png)
2. Menambahkan deklarasi CSS Internal pada bagian head dokumen
![Step2](SS/SS2.png)
3. Menambahkan deklarasi Inline CSS pada tag `<p>`
```
<p style="text-align: center; color: #ccd8e4;">
```
![Step3](SS/SS3.png)
4. Membuat file baru dengan nama style_eksternal.css dengan isi :
```
nav {
background: #20A759;
color:#fff;
padding: 10px;
}
nav a {
color: #fff;
text-decoration: none;
padding:10px 20px;
}
nav .active,
nav a:hover {
background: #0B6B3A;
}
```
![Step4](SS/SS4.png)
Lalu tambahkan tag `<link>` untuk merujuk file css yang sudah dibuat pada bagian `<head>`
```
<head>
 <!-- menyisipkan css eksternal -->
 <link rel="stylesheet" href="style_eksternal.css" type="text/css">
</head>
```
![Step5](SS/SS5.png)


