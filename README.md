# Judul Project
Analisis Perilaku Pembelian Pelanggan untuk Strategi Promosi Berbasis Data di Cherry on Top

## Repository Outline

1. description.md - Penjelasan gambaran umum project
2. Sesilia_Virdha.ipynb - Notebook yang berisi pengolahan data dengan python
3. Sesilia_Virdha_dataset.csv - dataset bersih yang akan digunakan untuk analisis
4. dataset.csv - dataset yang kotor yang belum dilakukan data cleaning

## Problem Background
Perusahaan Cherry on Top merupakan perusahaan bakery yang berupaya meningkatkan penjualan dan efisiensi operasional. Namun ketidakpastian pola waktu pembelian pelanggan menyebabkan ketidakefisienan dalam penjadwalan staf dan pengelolaan bahan baku. Di sisi lain strategi promosi yang ada belum disesuaikan dengan karakteristik perilaku pelanggan. Dengan kondisi ini maka diperlukan analisis terhadap data histori transaksi pelanggan, seperti usia, gender, dan waktu pembelian. analisis ini bertujuan untuk merancang promosi supaya tepat sasaran.

## Project Output
Output dari project ini adalah strategi promosi berbasis data yang dirancang untuk meningkatkan penjualan sebesar 15% dalam 3 bulan. Berdasarkan analisis data histori transaksi pelanggan, termasuk usia, gender, waktu pembelian, dan status membership

## Data
Saya mengambil data bersumber dari kaggle dimana terdapat 10 kolom dengan 500 baris tidak terdapat missing value. Tetapi disini saya hanya mengambil 8 kolom dengan menghapus kolom bakery_id karena ingin fokus analisis untuk keseluruhan bukan membandingkan performa antar cabang. kolom customer id karena berhubungan dengan bakery jika tidak dihapus maka akan menjadi ambigu karena id customer 1 di bakery_1 dan bakery_2 kemungkinan tidak sama

## Method
method yang digunakan untuk project ini adalah sebagai berikut:
1. analisis deskriptif : mean, median, modus, dan standar deviasi untuk melihat distribusi umur yang merupakan member
2. analisis inferensial : chi squared test untuk menguji hubungan antara variabel kategori (seperti gender dan waktu pembelian)
3. visualisasi


## Stacks
1. bahasa pemrograman : python
2. tools : vscode, tableau
3. library python : pandas, numpy, plotly, scipy


## Reference
https://public.tableau.com/views/Milestone1_Sesil/Chart?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
