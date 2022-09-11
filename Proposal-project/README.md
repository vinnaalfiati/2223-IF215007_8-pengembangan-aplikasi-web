# PROPOSAL PROJECT
* __Weight Control__

## Permasalahan
* Padatnya aktivitas sehari-hari terutama mahasiswa memungkinkan mereka kurang memperhatikan gaya hidup yang sehat. Konsumsi makanan yang tidak tepat beresiko menimbulkan berbagai efek negatif bagi tubuh. Mulai dari jenis dan porsi hingga kandungan yang terdapat dalam makanan yang dikonsumsi sehari-hari. Hal ini juga berkaitan dengan pentingnya bagi kita untuk menjaga berat badan tetap pada indeks normal. Berat badan merupakan salah satu faktor risiko untuk sejumlah penyakit metabolik, darah tinggi, kencing manis, kelebihan lemak darah. Namun, menjaga berat badan ideal tidak mudah. Pola makan dan gaya hidup sering memicu orang menjadi lebih gemuk atau lebih kurus dari seharusnya.

## Rencana Solusi
* Aplikasi weight control yang di dalamnya menyediakan kalkulator BMI untuk mengontrol indeks massa tubuh, dan fitur yang menyediakan resep makanan serta rincian nutrisi dari makanan yang dikonsumsi. 

## Use Case
* User dapat melakukan registrasi
* User dapat melakukan login
* User dapat mengelola halaman yang berisi aktivitas yang dilakukan user
* User dapat melakukan perhitungan BMI dengan kalkulator BMI
* User dapat melihat grafik BMI
* User dapat melihat rincian nutrisi dari resep makanan yang tersedia

## Struktur Data
* User

| Atribut  | Tipe Data | Contoh |
| -------- | --------- | ------ |
| id       | 27        | 1111   |
| username | 23        | xxvinn |
| password | 23        | xxxx   |

* BMI

| Atribut      | Tipe Data | Contoh         |
| ------------ | --------- | ------         |
| id           | 27        | 110922233017   |
| usia         | 23        | 20             |
| jeniskelamin | 23        | laki           | 
| height       | 23        | 154            |
| weight       | 23        | 59             |
| bmi          | 23        | 24,9           |
| ket          | 23        | Healthy Weight |

* Grafik

| Atribut      | Tipe Data | Contoh         |
| ------------ | --------- | ------         |
| id           | 27        | 110922233017   |
| bmi          | 23        | 20,50          |
| tanggal      | 23        | 2012           | 

* Resep

| Atribut        | Tipe Data | Contoh                                                                        |
| -------------- | --------- | ----------------------------------------------------------------------------- |
| id             | 27        | 1111                                                                          |
| video          | 27        | 1111                                                                          |
| namamakanan    | 23        | Nasi Goreng                                                                   |
| infoumum       | 23        | Porsi 1 orang, Harga 15.000, Kesulitan rendah                                 |
| rinciannutrisi | 23        | Kalori 558 kkal (26%), Karbo 64gr (18%), Protein 21gr (39%), Lemak 26gr (36%) |

## UX Wireframe