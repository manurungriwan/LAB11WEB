# LAB11WEB
NAMA : RIWAN IROSUCIPTO MANURUNG

KELAS : TI19C1

NIM : 311910500

Langkah-langkah Praktikum
Buat folder baru dengan nama lab11_php_ci pada docroot webserver (htdocs)


Untuk mengaktifkan ekstentsi tersebut, melalu XAMPP Control Panel, pada bagian Apache klik Config -> PHP.ini

![WhatsApp Image 2021-06-19 at 10 12 51](https://user-images.githubusercontent.com/56192368/122629820-02a19280-d0ea-11eb-820a-99724e10e701.jpeg)

Pada bagian extention, hilangkan tanda ; (titik koma) pada ekstensi yang akan diaktifkan. Kemudian simpan kembali filenya dan restart Apache web server.

![WhatsApp Image 2021-06-19 at 10 12 53](https://user-images.githubusercontent.com/56192368/122629858-38df1200-d0ea-11eb-9ffe-cce940cf91c3.jpeg)


Instalasi Codeigniter 4

Untuk melakukan instalasi Codeigniter 4 dapat dilakukan dengan dua cara, yaitu cara manual dan menggunakan composer. Pada praktikum ini kita menggunakan cara manual.

![WhatsApp Image 2021-06-19 at 10 12 53 (1)](https://user-images.githubusercontent.com/56192368/122629905-5ad89480-d0ea-11eb-99ce-e1f6822bd186.jpeg)


Menjalankan CLI (Command Line Interface)

Perintah yang dapat dijalankan untuk memanggil CLI Codeigniter adalah: ( php spark ) 

![WhatsApp Image 2021-06-19 at 10 12 53 (2)](https://user-images.githubusercontent.com/56192368/122629918-76dc3600-d0ea-11eb-85b1-f4a753028564.jpeg)

Mengaktifkan Mode Debugging

Ketika terjadi error pada aplikasi akan ditampilkan pesan kesalahan seperti berikut.

![WhatsApp Image 2021-06-19 at 10 12 53 (3)](https://user-images.githubusercontent.com/56192368/122629935-94110480-d0ea-11eb-9bd3-721d2350ea28.jpeg)

Ubah nama file env menjadi .env kemudian buka file tersebut dan ubah nilai variable CI_ENVIRINMENT menjadi development

![WhatsApp Image 2021-06-19 at 10 12 54](https://user-images.githubusercontent.com/56192368/122629965-cde20b00-d0ea-11eb-903b-3b725dca411e.jpeg)

Contoh error yang terjadi. Untuk mencoba error tersebut, ubah kode pada file app/Controller/Home.php hilangkan titik koma pada akhir kode.
![WhatsApp Image 2021-06-19 at 10 12 54 (1)](https://user-images.githubusercontent.com/56192368/122629990-efdb8d80-d0ea-11eb-8a1f-094781c9c235.jpeg)

Routing dan Controller

Router terletak pada file app/config/Routes.php

![WhatsApp Image 2021-06-19 at 10 12 54 (2)](https://user-images.githubusercontent.com/56192368/122630015-0f72b600-d0eb-11eb-8563-7f66acbfc9ef.jpeg)

buka CLI dan jalankan perintah berikut.
yaitu php spark

![WhatsApp Image 2021-06-19 at 10 12 54](https://user-images.githubusercontent.com/56192368/122630024-29ac9400-d0eb-11eb-85ae-f4c211981a0f.jpeg)

Selanjutnya coba akses route yang telah dibuat dengan mengakses alamat url http://localhost:8080/about

![WhatsApp Image 2021-06-19 at 10 12 55 (1)](https://user-images.githubusercontent.com/56192368/122630051-506aca80-d0eb-11eb-8dcf-d9d70eee8ddf.jpeg)

Membuat Controller

Selanjutnya adalah membuat Controller Page. Buat file baru dengan nama page.php pada direktori Controller kemudian isi kodenya seperti berikut.

![WhatsApp Image 2021-06-19 at 10 12 55 (2)](https://user-images.githubusercontent.com/56192368/122630075-7bedb500-d0eb-11eb-8762-43f3df10034f.jpeg)

Selanjutnya refresh Kembali browser,![WhatsApp Image 2021-06-19 at 10 12 56 (2)](https://user-images.githubusercontent.com/56192368/122630104-af304400-d0eb-11eb-809b-78e63fd8b61a.jpeg)

Tambahkan method baru pada Controller Page seperti berikut.
![WhatsApp Image 2021-06-19 at 10 12 56 (1)](https://user-images.githubusercontent.com/56192368/122630122-cc651280-d0eb-11eb-8e70-55638ff9179b.jpeg)

Method ini belum ada pada routing, sehingga cara mengaksesnya dengan menggunakan alamat: http://localhost:8080/page/tos

![WhatsApp Image 2021-06-19 at 10 12 56 (2)](https://user-images.githubusercontent.com/56192368/122630136-f1598580-d0eb-11eb-8496-0cda805fcf7e.jpeg)

Buat file css pada direktori public dengan nama style.css
![WhatsApp Image 2021-06-19 at 10 12 56 (3)](https://user-images.githubusercontent.com/56192368/122630157-0c2bfa00-d0ec-11eb-9a65-79fedc7f8831.jpeg)

Kemudian buat folder template pada direktori view kemudian buat file header.php dan footer.php

![WhatsApp Image 2021-06-19 at 10 12 57](https://user-images.githubusercontent.com/56192368/122630197-472e2d80-d0ec-11eb-817c-6a64c4548107.jpeg)

Kemudian ubah file app/view/about.php seperti berikut
![WhatsApp Image 2021-06-19 at 10 12 57 (2)](https://user-images.githubusercontent.com/56192368/122630213-5dd48480-d0ec-11eb-98c6-c29bd801e438.jpeg)

selanjutnya refresh tampilan tersebut:
![WhatsApp Image 2021-06-19 at 10 12 58](https://user-images.githubusercontent.com/56192368/122630226-76449f00-d0ec-11eb-85c8-e8fcddfc2bfc.jpeg)


