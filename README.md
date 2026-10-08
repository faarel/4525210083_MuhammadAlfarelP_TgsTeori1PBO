# Praktikum Pemrograman Berorientasi Objek (PBO) - PHP

**Nama:** Muhammad Alfarel Prihadi  
**NPM:** 4525210083  
**Program Studi:** Teknik Informatika  
**Universitas:** Universitas Pancasila  

---

## Deskripsi

Repository ini berisi hasil praktikum mata kuliah **Pemrograman Berorientasi Objek (PBO)** menggunakan bahasa pemrograman **PHP**.

Praktikum ini membahas beberapa konsep dasar dan lanjutan dalam pemrograman berorientasi objek, yaitu Class, Constructor, Inheritance, Polymorphism, Association & Composition, serta Abstract Class dan Interface.

Setiap pertemuan memiliki contoh program yang dibuat untuk memahami penerapan konsep OOP dalam bahasa PHP. Repository ini juga dilengkapi dengan screenshot hasil program sebagai dokumentasi dari setiap praktikum.

---

# Materi Praktikum

## 01. Class

Pada materi pertama, dipelajari konsep dasar **Class dan Object** dalam PHP.

Class digunakan sebagai rancangan atau cetakan untuk membuat sebuah object. Sedangkan object merupakan hasil dari class yang dapat memiliki atribut dan method.

Pada praktikum ini dibuat class `iPhone` yang memiliki informasi seperti warna dan kapasitas penyimpanan. Object kemudian dibuat dari class tersebut untuk menampilkan data masing-masing iPhone.

<img width="1022" height="742" alt="image" src="https://github.com/user-attachments/assets/05390cbb-1c56-4db9-aa84-1cc83e22bc54" />


### Yang dipelajari:
- Membuat Class
- Membuat Object
- Atribut dan Method
- Menggunakan Object untuk menjalankan method

### Hasil Praktikum:
Program menampilkan spesifikasi beberapa object iPhone berdasarkan warna dan kapasitas penyimpanannya.

---

## 02. Constructor

Pada materi kedua, dipelajari konsep **Constructor** pada PHP.

Constructor merupakan method khusus yang akan otomatis dijalankan ketika sebuah object dibuat. Constructor biasanya digunakan untuk memberikan nilai awal pada atribut yang dimiliki oleh sebuah object.

Pada praktikum ini digunakan class `Mahasiswa` yang memiliki data seperti nama, NIM, dan umur. Data tersebut dapat diberikan melalui constructor ketika object dibuat.

<img width="1582" height="957" alt="image" src="https://github.com/user-attachments/assets/12d9568d-ea3e-4b5f-8636-59fbad680379" />


### Yang dipelajari:
- Pengertian Constructor
- Membuat Constructor
- Memberikan nilai awal pada object
- Menggunakan Setter dan Getter
- Menampilkan informasi object

### Hasil Praktikum:
Program dapat membuat object mahasiswa dan menampilkan informasi mahasiswa seperti nama, NIM, dan umur.

---

## 03. Inheritance

Pada materi ketiga, dipelajari konsep **Inheritance atau pewarisan**.

Inheritance memungkinkan sebuah class untuk mewarisi atribut dan method dari class lain. Class yang diwarisi disebut parent class, sedangkan class yang menerima pewarisan disebut child class.

Pada praktikum ini inheritance digunakan pada class `Mahasiswa` dan `MahasiswaInternational`. Class `MahasiswaInternational` dapat menggunakan atribut dan method yang berasal dari class `Mahasiswa` serta memiliki atribut tambahan berupa negara asal.

Selain itu, inheritance juga diterapkan pada konsep bangun datar seperti `Lingkaran`, `Persegi`, dan `Segitiga`.

<img width="1545" height="932" alt="image" src="https://github.com/user-attachments/assets/d6a00b17-c0b7-41dd-81be-4c8e14b33207" />
<img width="1572" height="981" alt="image" src="https://github.com/user-attachments/assets/2600bc1c-6ba1-40c3-a38d-b81e2d741b3f" />



### Yang dipelajari:
- Konsep Parent Class
- Konsep Child Class
- Pewarisan atribut dan method
- Penggunaan `extends`
- Penggunaan method dari Parent Class

### Hasil Praktikum:
Program dapat membuat object dari class turunan dan menggunakan fitur yang diwariskan dari class induknya.

---

## 04. Polymorphism

Pada materi keempat, dipelajari konsep **Polymorphism**.

Polymorphism merupakan kemampuan beberapa object yang berbeda untuk menggunakan method dengan nama yang sama tetapi memiliki perilaku yang berbeda.

Pada praktikum ini terdapat class `Smartphone` dan `FeaturePhone` yang memiliki fungsi seperti menyalakan, melakukan panggilan, dan mematikan perangkat. Meskipun memiliki method yang sama, masing-masing object dapat memberikan hasil yang berbeda.

<img width="1403" height="933" alt="image" src="https://github.com/user-attachments/assets/54136144-c65b-4e10-b6b1-91c998626110" />


### Yang dipelajari:
- Pengertian Polymorphism
- Method yang memiliki perilaku berbeda
- Penggunaan Parent Class
- Penggunaan Child Class
- Perbedaan perilaku object

### Hasil Praktikum:
Program dapat menjalankan method yang sama pada object berbeda dan menghasilkan perilaku sesuai dengan jenis handphone yang digunakan.

---

## 05. Association & Composition

Pada materi kelima, dipelajari hubungan antar object menggunakan konsep **Association dan Composition**.

Association merupakan hubungan antara dua object yang saling berhubungan tetapi masing-masing object masih dapat berdiri sendiri.

Sedangkan Composition merupakan hubungan yang lebih kuat antara object, dimana suatu object menjadi bagian dari object lainnya.

Pada praktikum ini terdapat beberapa contoh hubungan object seperti dokter dengan pasien, tim dengan pemain, serta buku dengan bab.

<img width="1611" height="957" alt="image" src="https://github.com/user-attachments/assets/b2bbe552-6ade-45b2-88b5-10c9886df381" />


### Yang dipelajari:
- Hubungan antar object
- Konsep Association
- Konsep Composition
- Object sebagai bagian dari object lainnya
- Membuat object yang saling berhubungan

### Hasil Praktikum:
Program dapat menunjukkan hubungan antara beberapa object, seperti dokter dengan pasien, tim dengan pemain, dan buku dengan bab.

---

## 06. Abstract Class & Interface

Pada materi keenam, dipelajari konsep **Abstract Class dan Interface**.

Abstract Class merupakan class yang digunakan sebagai dasar atau rancangan untuk class turunannya. Abstract Class dapat memiliki method biasa maupun abstract method yang harus diimplementasikan oleh class turunannya.

Sedangkan Interface digunakan sebagai aturan atau kontrak yang menentukan method yang harus dimiliki oleh class yang mengimplementasikannya.

Pada praktikum ini digunakan beberapa class seperti `Car`, `Boat`, `Motor`, dan `Building`. Setiap class memiliki perilaku yang disesuaikan dengan jenis object tersebut.

<img width="1597" height="961" alt="image" src="https://github.com/user-attachments/assets/a6df2939-3f24-424f-87e1-ec94af2385ad" />

### Yang dipelajari:
- Pengertian Abstract Class
- Pengertian Interface
- Abstract Method
- Implementasi Interface
- Pewarisan pada Abstract Class
- Penggunaan method sesuai aturan Interface

### Hasil Praktikum:
Program dapat membuat beberapa jenis object dan menjalankan method sesuai dengan aturan yang telah ditentukan melalui Abstract Class dan Interface.

---

# Kesimpulan

Dari praktikum yang telah dilakukan, dapat dipahami bahwa **Pemrograman Berorientasi Objek (OOP)** memiliki beberapa konsep penting yang digunakan untuk membuat program lebih terstruktur.

Materi yang dipelajari dimulai dari konsep dasar **Class dan Object**, kemudian dilanjutkan dengan **Constructor, Inheritance, Polymorphism, Association & Composition, serta Abstract Class dan Interface**.

Dengan menggunakan PHP, konsep-konsep tersebut dapat diterapkan melalui pembuatan beberapa contoh program sehingga lebih mudah memahami cara kerja pemrograman berorientasi objek.

Repository ini digunakan sebagai dokumentasi hasil praktikum PBO selama proses pembelajaran.
