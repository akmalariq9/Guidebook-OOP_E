# **OOP-E 2023 _Guidebook_**
<div align=justify>

Berikut adalah _guidebook_ atau panduan dasar untuk pengerjaan tugas mata kuliah _Object Oriented Programming_ (OOP) kelas E tahun 2023. 

## **Prerequisite**
Sebelum masuk ke tutorial, terdapat beberapa prasyarat yang harus dipenuhi, yaitu sebagai berikut: <br>

- Eclipse IDE (https://eclipseide.org/)
- Akun Github (https://github.com/)

## **Git Download and Installation**
Git merupakan salah satu _tools_ yang diperlukan untuk melakukan maintenance pada sebuah _project_. Berikut adalah tutorial instalasi untuk git:
- Download git melalui link berikut: https://git-scm.com/download/win

![Download GIT](https://media.discordapp.net/attachments/1150687865420906517/1150688166148313098/Untitled.png?width=1246&height=701)

- Buka file .exe yang sudah didownload, lalu lakukan instalasi dengan click _next_ hingga proses selesai.

![Install Git](https://media.discordapp.net/attachments/1150687865420906517/1150688557913088041/Screenshot_852.png?width=1246&height=701)

- Lakukan _right-click_ di salah satu folder pada _file explorer_. Apabila git sudah terinstall dengan benar, maka seharusnya terdapat opsi untuk melakukan git bash. 

![Git Check](https://media.discordapp.net/attachments/1150687865420906517/1150688803850309642/oop2.png?width=1246&height=701)

## **Connect Credential Github to Git**
Setelah melakukan instalasi git, langkah selanjutnya adalah menyambungkan _credential_ dengan github. Untuk melakukannya, dapat mengikuti langkah berikut:
- Buka Git bash atau terminal pada windows, kemudian masukkan code berikut:
```c
git config --global user.name "Your Username"
```
- Setelah itu, dapat dilanjutkan dengan memasukkan code berikut:
```c
git config --global user.email "youremail@gmail.com"
```

## **Start Github Repository**
Setelah git terkoneksi dengan github, maka langkah selanjutnya adalah membuat repository. Untuk pembuatan repository dapat mengikuti langkah berikut:
- _Login_ ke github dan klik tombol berikut:

![New Repository Button](https://media.discordapp.net/attachments/1150687865420906517/1150689167886524508/oop13.png?width=1246&height=701)

- Lakukan _setup_ sesuai dengan kebutuhan masing-masing.

![Setup Repository](https://media.discordapp.net/attachments/1150687865420906517/1150689166896668736/oop4.png?width=1246&height=701)

- Tampilan awal saat repository berhasil dibuat adalah sebagai berikut:

![oop6](https://media.discordapp.net/attachments/1150687865420906517/1150689167559364618/oop6.png?width=1246&height=701)


## **Clone Github Repository**
_Clone_ github repository bertujuan untuk menduplikasi dan mengedit repository tersebut di direktori lokal. Untuk melakukan _clone_ dapat mengikuti langkah-langkah berikut:

- Masuk kedalam repository yang akan di _clone_

![Link button](https://media.discordapp.net/attachments/1150687865420906517/1150689471046635560/oop7.png?width=1246&height=701)

- Lakukan _copy_ pada url yang ada sesuai pada gambar berikut:

![Copy Link](https://media.discordapp.net/attachments/1150687865420906517/1150689471273107526/oop8.png?width=1246&height=701)

- Masuk ke direktori yang akan kalian gunakan untuk meletakkan folder repository, kemudian gunakan perintah ```git clone <link>``` pada terminal shell atau git bash untuk melakukan _clone_.

![Terminal Clone](https://media.discordapp.net/attachments/1150687865420906517/1150689471545745438/oop9.png?width=1245&height=701)

- Tunggu proses selesai dan buka folder repository yang sudah di clone menggunakan IDE.

![Folder After Clone](https://media.discordapp.net/attachments/1150687865420906517/1150690005925249034/oop10.png?width=1246&height=701)

## **Git Commit - Push**
Git Commit / Push merupakan salah satu kegiatan untuk menyimpan atau memperbarui file dari sebuah repository. File yang awalnya diedit pada direktori lokal akan diupload kedalam repository. Untuk melakukan git push, dapat mengikuti langkah-langkah berikut:

- Masuk kedalam file yang akan diedit atau di-push kedalam repository menggunakan IDE. Berikut adalah tampilan repository awal pada github dan direktori lokal yang belum mengalami perubahan:

Github Repository:

![Github Repo View](https://media.discordapp.net/attachments/1150687865420906517/1150690289170784276/oop6.png?width=1246&height=701)

Direktori Lokal:

![Local Repo View](https://media.discordapp.net/attachments/1150687865420906517/1150690418632167537/Screenshot_874.png?width=1246&height=701)

- Lakukan perubahan pada file yang diinginkan. Misalnya merubah readme, menambah code di sebuah file, menambahkan gambar di folder, dan sebagainya. Berikut adalah tampilan pada direktori lokal setelah melakukan beberapa perubahan seperti menambahkan folder img, menambahkan file gambar, merubah isi dari _markdown file_, dan menambahkan file .c

![Edit Local Repo](https://media.discordapp.net/attachments/1150687865420906517/1150690627558834297/oop11.png?width=1246&height=701)

- Setelah selesai melakukan perubahan, maka push dapat dilakukan dengan menjalankan perintah berikut pada terminal atau git bash:
```
git add .
```
```
git commit -m "enter your commit messages"
```
```
git push origin
```

Berikut adalah contoh saat melakukan commit atau push melalui git bash:

![Commit Terminal](https://media.discordapp.net/attachments/1150687865420906517/1150690816197673041/oop12.png?width=975&height=601)


- Setelah menjalankan perintah berikut, maka repository pada github akan berubah seperti pada gambar berikut:

![Repository After Commit](https://media.discordapp.net/attachments/1150687865420906517/1150690937949929523/Screenshot_876.png?width=1246&height=701)

## **The End**
Makasi teman-teman, kalo ada yang ditanyakan bisa langsung WA aja yaa, gausaa sungkan!


