# Lab4Web
## Langkah - langkah Praktikum
Persiapan membuat dokumen HTML dengan nama file lab4_box.html seperti berikut.<p>
![image](/screenshot/ss1.png)
### Membuat Box Element
Kemudian tambahkan kode untuk membuat box element dengan tag div seperti berikut.<p>
`<section>` <p>
    `<div class="div1">Div 1</div>` <p>
    `<div class="div2">Div 2</div>` <p>
    `<div class="div3">Div 3</div>` <p>
`</section>`
### CSS Float Property
Selanjutnya tambahkan deklarasi CSS pada head untuk membuat float element, seperti berikut.<p>
![image](/screenshot/ss2.PNG) <p>
Kemudian buka browser untuk melihat hasilnya.<p>
![image](/screenshot/ss3.png)
### Mengatur Clearfix Element
Clearfix digunakan untuk mengatur element setelah float element. Property clear digunakan untuk mengaturnya.<p>
Tambahkan element div lainnya seteleah div3 seperti berikut.<p>
`<section>` <p>
    `<div class="div1">Div 1</div>` <p>
    `<div class="div2">Div 2</div>` <p>
    `<div class="div3">Div 3</div>` <p>
    `<div class="div4">Div 4</div>` <p>
`</section>` <p>
Kemudian atur property clear pada CSS, seperti berikut.<p>
.div4 { <p>
background-color: blue; <p>
clear: left; <p>
float: none; <p>
} <p>
Selanjutnya buka browser dan refresh kembali. <p>
![image](/screenshot/ss4.png) <p>
Lakukan eksperimen terhadap penggunaan property clear dengan nilai lainnya (left, both, right), dan amati perubahannya.
### Membuat Layout Sederhana
Kita akan membuat layout web sederhana seperti gambar berikut. <p>
![image](/screenshot/ss25.png) <p>
Buat folder baru dengan nama lab4_layout, kemudian buatlah file baru didalamnya dengan nama home.html, dan file css dengan nama style.css.<p>
![image](/screenshot/ss5.png) <p>
Kemudian tulis kode berikut. <p>
![image](/screenshot/ss6.png) <p>
Kemudian buka browser dan lihat hasilnya. <p>
![image](/screenshot/ss7.png) <p>
Kemudian tambahkan kode CSS untuk membuat layoutnya. <p>
![image](/screenshot/ss8.png) <p>
Kemudian lihat hasilnya pada browser. <p>
![image](/screenshot/ss9.png)
### Membuat Navigasi
Kemudian selanjutnya mengatur navigasi. <p>
![image](/screenshot/ss10.png) <p>
Kemudian lihat hasilnya. <p>
![imaga](/screenshot/ss11.png)
### Membuat Hero Panel
Selanjutnya membuat hero panel. Tambahkan kode HTML dan CSS seperti berikut. <p>
![image](/screenshot/ss12.png) <p>
![image](/screenshot/ss13.png) <p>
![image](/screenshot/ss14.png)
### Mengatur Layout Main dan Sidebar
Selanjutnya mengatur main content dan sidebar, tambahkan CSS float.<p>
![image](/screenshot/ss15.png)
### Membuat Sidebar Widget
Kemudian selanjutnya menambahkan element lain dalam sidebar.<p>
![image](/screenshot/ss16.png) <p>
Kemudian tambahkan CSS.<p>
![image](/screenshot/ss17.png) <p>
![image](/screenshot/ss18.png)
### Mengatur Footer
Selanjutnya mengatur tampilan footer. Tambahkan CSS untuk footer.<p>
/* footer */ <p>
footer { <p>
clear:both; <p>
background-color:#1d1d1d; <p>
padding:20px; <p>
color:#eee;<p>
} <p>
![image](/screenshot/ss19.png)
### Menambahkan Elemen lainnya pada Main Content
![image](/screenshot/ss20.png) <p>
Kemudian tambahkan CSS. <p>
![image](/screenshot/ss26.png) <p>
![image](/screenshot/ss21.png)
### Menambahkan Content Artikel
Selanjutnya membuat content artikel. Tambahkan HTML berikut pada main content. <p>
![image](/screenshot/ss22.png) <p>
Kemudian tambahkan CSS. <p>
![image](/screenshot/ss23.png) <p>
![image](/screenshot/ss24.png)