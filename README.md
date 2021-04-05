# Praktikum 2
## Nama  : Awong Osakethi 
## NIM   : 311910499
## Kelas : TI.19.A2

## A. Langkah pertama
- Membuat file dokumen HTML, lalu masukan tag dasar HTML
![step 1](https://user-images.githubusercontent.com/56240483/113546828-f93e7900-9616-11eb-87a5-6d55a4d5b570.png)

## B. Langkah kedua
- Kemudian mendeklarasikan internal CSS di bagian `<head>` dan menambahkan inline CSS pada paragraph atau tag `<p>`
![step 2 1](https://user-images.githubusercontent.com/56240483/113546834-f9d70f80-9616-11eb-9cf9-5c5041f287f3.png)
![step 2 2](https://user-images.githubusercontent.com/56240483/113546837-fb083c80-9616-11eb-974e-99f4cbe66407.png)

## C. Langkah ketiga
- Selanjutnya membuat dan memasukan kode ke eksternal CSS, lalu mulai menambahkan tag koneksi link yang dibagian head dalam file HTML, untuk mengkoneksi file CSS eksternal tersebut.
![step 4 1](https://user-images.githubusercontent.com/56240483/113546821-f6438880-9616-11eb-856e-e1d521c80ae5.png)
![step 4 2](https://user-images.githubusercontent.com/56240483/113546824-f80d4c00-9616-11eb-8afc-5f69440b2fa1.png)
  
## D. Langkah empat
- Membuat CSS selector dan masukan kode di ID dan Class Selector di file Eksternal CSS
![step 5](https://user-images.githubusercontent.com/56240483/113546826-f8a5e280-9616-11eb-91af-91d5c35a23b8.png)

## E. langkah lima
- Melakukan percobaan uji Validator pada CSS eksternal
![Screenshot (613)](https://user-images.githubusercontent.com/56240483/113548397-a7e3b900-9619-11eb-95d3-edaaa1ca6726.png)

# Pertanyaan dan Tugas
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
```
Saya melakukan eksperimen, membuat background lingkaran lalu memasukan gambar, dan mengubah warna tampilan
```
![eksperimen 1 1](https://user-images.githubusercontent.com/56240483/113548936-a797ed80-961a-11eb-8b1c-811ba606d972.png)
```
Hasil uji Validator pada CSS Eksternal Eksperimen
```
![Screenshot (614)](https://user-images.githubusercontent.com/56240483/113555046-7ae8d380-9624-11eb-959a-30146e283ac9.png)

2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!
```
CSS elemen h1  yaitu untuk mengubah tampilan seluruh elemen yang memiliki tag h1 yang ada pada internal dan inline penggunaan style,
sedangkan #intro h1 yaitu hanya untuk mengubah tampilan elemen h1 yang memiliki id #intro yang ada pada eksternal css style.
```

3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
```
Saat pengujian, dan melakukan mendeklarasikan elemen yang sama tetapi dengan 
mengisi deklarasi yang berbeda, maka seluruh deklarasi akan di tampilkan bersamaan 
```
![eksperimen 2 0](https://user-images.githubusercontent.com/56240483/113548939-a961b100-961a-11eb-92a4-03e05b854f92.png)
![eksperimen 2](https://user-images.githubusercontent.com/56240483/113549954-7a4c3f00-961c-11eb-816f-c609001ea882.png)

4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser Berikan penjelasan dan contohnya! ( <p id="paragraf-1" class="text-paragraf"> )
```
Dari kedua deklarasi itu akan tampil, tapi yang akan tampil itu hanya 
Selector ID jika deklarasi dari ID dan Class ada kesamaan.
```
![Screenshot (611)](https://user-images.githubusercontent.com/56240483/113549970-7fa98980-961c-11eb-96b7-25797a874535.png)
![Screenshot (612)](https://user-images.githubusercontent.com/56240483/113549890-61dc2480-961c-11eb-9e6c-3c3c648f9891.png)
