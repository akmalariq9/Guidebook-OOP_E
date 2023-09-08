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

![image](https://github.com/akmalariq9/Guidebook-OOP_E/assets/109916703/de88c61c-ed04-4527-b09b-ae17794d5d5f)

- Buka file .exe yang sudah didownload, lalu lakukan instalasi dengan click _next_ hingga proses selesai.

![image](https://github.com/akmalariq9/Guidebook-OOP_E/assets/109916703/4476448a-7ca8-4910-9113-f5378c7265be)

- Lakukan _right-click_ di salah satu folder pada _file explorer_. Apabila git sudah terinstall dengan benar, maka seharusnya terdapat opsi untuk melakukan git bash. 

![image](https://github.com/akmalariq9/Guidebook-OOP_E/assets/109916703/11dd78c6-a3ff-49c9-a50a-4f480e1b064d)

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

![oop3](https://github.com/akmalariq9/Guidebook-OOP_E/assets/109916703/edb3ca88-ad78-4cdb-9efc-4004504f0b7c)

- Lakukan _setup_ sesuai dengan kebutuhan masing-masing.

![oop4](https://github.com/akmalariq9/Guidebook-OOP_E/assets/109916703/e343fa4e-182e-43aa-a7fc-3a3b64782dbc)

- Tampilan awal saat repository berhasil dibuat adalah sebagai berikut:

![oop5](https://github.com/akmalariq9/Guidebook-OOP_E/assets/109916703/73361200-e149-4bfe-9a5e-87942441fb8b)


## **Clone Github Repository**
_Clone_ github repository bertujuan untuk menduplikasi dan mengedit repository tersebut di direktori lokal. Untuk melakukan _clone_ dapat mengikuti langkah-langkah berikut:

- Masuk kedalam repository yang akan di _clone_

![oop7](https://github.com/akmalariq9/Guidebook-OOP_E/assets/109916703/c7b52891-454d-4bbe-9619-69b92a0de5f9)

- Lakukan _copy_ pada url yang ada sesuai pada gambar berikut:

![oop8](https://github.com/akmalariq9/Guidebook-OOP_E/assets/109916703/a216b35f-9aca-4b97-a8b4-4cec5dca5472)

- Masuk ke direktori yang akan kalian gunakan untuk meletakkan folder repository, kemudian gunakan perintah ```git clone <link>``` pada terminal shell atau git bash untuk melakukan _clone_.

![oop9](https://github.com/akmalariq9/Guidebook-OOP_E/assets/109916703/2aa8bdb8-558e-4fae-8ce1-5e4a06bbff3b)

- Tunggu proses selesai dan buka folder repository yang sudah di clone menggunakan IDE.

![oop10](https://github.com/akmalariq9/Guidebook-OOP_E/assets/109916703/65817984-f6d2-4f56-a06a-4c37294f5f57)

## **Git Commit - Push**
Git Commit / Push merupakan salah satu kegiatan untuk menyimpan atau memperbarui file dari sebuah repository. File yang awalnya diedit pada direktori lokal akan diupload kedalam repository. Untuk melakukan git push, dapat mengikuti langkah-langkah berikut:

- Masuk kedalam file yang akan diedit atau di-push kedalam repository menggunakan IDE. Berikut adalah tampilan repository awal pada github dan direktori lokal yang belum mengalami perubahan:

![oop10](https://github.com/akmalariq9/Guidebook-OOP_E/assets/109916703/65817984-f6d2-4f56-a06a-4c37294f5f57)

![Screenshot (874)](https://github.com/akmalariq9/Guidebook-OOP_E/assets/109916703/1dbb5eaf-a4cc-4888-b1d5-ce2cb5077354)

- Lakukan perubahan pada file yang diinginkan. Misalnya merubah readme, menambah code di sebuah file, menambahkan gambar di folder, dan sebagainya. Berikut adalah tampilan pada direktori lokal setelah melakukan beberapa perubahan seperti menambahkan folder img, menambahkan file gambar, merubah isi dari _markdown file_, dan menambahkan file .c

![oop11](https://github.com/akmalariq9/Guidebook-OOP_E/assets/109916703/1e1f87e5-e1fa-4680-95ff-f0178bc7a32c)

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

- Setelah menjalankan perintah berikut, maka repository pada github akan berubah seperti pada gambar berikut:

![Screenshot (876)](https://github.com/akmalariq9/Guidebook-OOP_E/assets/109916703/d2a1896c-56b2-4ffc-bbe3-dbd407639f89)


