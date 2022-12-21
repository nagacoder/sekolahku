---
sidebar_position: 1
---

# Tugas Kelompok 1

# 1.Introduction

## 1.1 Purpose of this document

Sekolah ku adalah system management sekolah yang mencakup sebagian besar
operasional yang berkaitan dengan sekolah, antara lain: guru, siswa, orang tua,
karyawan, jadwal, kelas, mata pelajaran, bus dan biaya kuliah, Untuk
mengurangi penanganan kertas dan penggunaan metode modern dalam merekam data
yang akan memastikan bahwa pekerjaan akan dilakukan dalam waktu yang lebih singkat, lebih efisien
dan menyimpan data agar tidak hilang.

## 1.2 Scope of this document

Konsentrasi sistem ini dibagi menjadi tiga faktor sebagai berikut:

### Teacher

Guru dapat menambahkan Tugas Rumah (PR) dan ujian untuk
siswa, guru juga dapat menambahkan nilai siswa.

### Parent

Orang tua dapat memeriksa aktifitas anak mereka (nilai,
ujian, kursus), dan juga bisa melakukan pembayaran biaya sekolah secara online

### Admin/Employee

Admin dapat mengelola siswa seperti mengubah informasi siswa, orang tua siswa dan mengelola permintaan siswa (komplain dan lain lain)

### Student

Siswa dapat melihat jadwal mereka,mengirim PR, ujian dan dapat untuk melihat kehadiran mereka

## 1.3 Overview

![image](./system-overview.png)

## 1.4 System Architecture

![image]("http://www.plantuml.com/plantuml/png/TPDDw-8m4CRl-HI3T_7UWrYtqLsGzQNjOH4FsMRKOfkKP8h2udVVj0qcxFBleSmyyvkXp3nTMHA6-hPXeY9j89LjhLYIKozHKSAIWp130C2I0aLrHvC0SqydgeUu8SmsHYj29MVmXm6SJmwY2tj7nDe50U2lpg2r0o85YT_2EYJpqSHSTIFHmEoWBTqCviVTfB-7iKfBrx3lq0YgjHegvsy61I6K5is5mJd31btQ-xJif8ZIt5KhMkGeJ7N_g3-K2mX-uXFMTTC44FYhjlIlw1SKTMwDa6W34WJ_0P7WMxxh5f_QF49Nq6AElqGRc2ZtzPI60w2gC42H69FAFkCj_2_axiIoRqBJLvBM3MpGYP_LQQglTJLUnQb-NgoEjc2ZGs2-1Ey4I63BYyLXdxjNMImolkC5PxuwWC47ZitI8bsdEOTZoK-_c3VbVBwSvZ9_cI2CbWxfPEYGisYwK-7ZBBP29TsVyHS0")

## 1.5 Business Context

Tujuan utamanya adalah memberikan kepada pengguna sistem waktu yang lebih sedikit dan efisiensi yang lebih tinggi. Untuk lebih jelas, mudah mengakses data atau membuatnya di mana saja dengan lebih sedikit usaha. Demi mencapai semua ini, ide yang muncul adalah membuat sistem di mana setiap informasi tentang siswa tercatat, seperti: nilai-nilainya, pekerjaan rumahnya, mata pelajarannya, ujiannya, dan data pendaftarannya. Sistem ini juga memungkinkan guru untuk dengan mudah membuat pekerjaan rumah dan mengikuti tingkat siswa dengan memeriksa nilai, tingkat, dan tugas-tugasnya, dan poin terpenting yang memungkinkan sistem bagi orang tua untuk memeriksa statistik siswanya dan membayar biaya sekolahnya tanpa perlu ke sekolah. Akhirnya, sistem ini memungkinkan karyawan untuk membuat jadwal siswa tanpa perlu melakukannya secara manual, memeriksa data dan permintaan pendaftarannya secara online. Semua itu akan menjamin waktu yang lebih sedikit, usaha yang lebih sedikit, dan efisiensi yang lebih tinggi.

# 2.General Description

## 2.1 Product Functions

Sistem ini dapat diklasifikasikan menjadi:

### Teacher Main Functions:

1. Add Exam or homeworks:
   Guru bisa membuat ujian
   atau pekerjaan rumah kapan saja tanpa perlu pergi ke sekolah
2. Add Attendance:
   Guru dapat mengabsen siswa yang hadir di
   kelasnya.
3. Add students’ grades:
   Guru dapat menandai kertas siswa secara
   online dengan mudah.

### Student Main Functions

1.  Display schedule: Dapat melihat schedules mereka
2.  Submit exam or homework:Dapat melakukan submit PR mereka
3.  Display grades: Dapat melihat PR dan nilai keseluruhan
4.  Add Attendance: Siswa juga dapat hadir sendiri tetapi atas perintah
    gurunya karena dia memiliki kemampuan untuk membagikan kode kehadiran kepada siswa- bisa hadir dengan cara ini

### Parents Main Functions:

1. View student page: Orang tua dapat melakukan check kepada anak mereka seperti (nilai,absensi dan biaya sekolah) secara online
2. Pay student fees: Orang tua dapat melakukan pembayaran biaya sekolah

### Admin/Employee Main Functions:

1. Do schedule: Melakukan insert/edit Schedule kepada siswa
1. Edit Students Info: Dapat mengubah informasi siswa

## 2.2 Similar System Information

TODO : need to create survey for this

## 2.3 User Problem Statement

Permasalah akan dibagi sesuai dengan klasifikasi pengguna di
poin berikut:

### Parents

Masalah terbesar adalah jika mereka harus melakukan sesuatu yang berhubungan dengan anak, Mereka harus pergi ke sekolah.

### Student

Masalah siswa adalah disorganisasi dan yang dia tangani
dengan jumlah kertas yang banyak.

### Teacher

Masalah guru adalah bagaimana menangani dan mencari di kertas jika
jumlahnya sangat banyak.

### Admin/Employee

Masalah karyawan adalah dia mengerjakan tugas siswa
menjadwalkan secara manual sehingga membutuhkan banyak waktu untuk melakukannya untuk semua siswa.

# 3.Use Case Diagram

![image](./Use-case.png)
