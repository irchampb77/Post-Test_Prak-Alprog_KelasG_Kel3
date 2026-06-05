# Post Test Praktikum Algoritma dan Pemrograman 2026

## Kelas G - Kelompok 3

![Python](https://img.shields.io/badge/Python-Data%20Analysis-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Visualization](https://img.shields.io/badge/Visualization-Matplotlib%20%7C%20Seaborn-green)

Repositori ini berisi pengerjaan post test praktikum Algoritma dan Pemrograman untuk menganalisis dataset **Kelas G - Fixed Call Report**. Analisis dilakukan dengan Python melalui Jupyter Notebook untuk mengolah data laporan panggilan berdasarkan tahun, bulan, dan jenis layanan.

Project ini berfokus pada proses membaca dataset, membersihkan atau menyesuaikan data, melakukan agregasi, memfilter data tertentu, mencari hubungan antar variabel, serta menampilkan hasil analisis dalam bentuk visualisasi yang mudah dipahami.

## Dataset

Dataset utama yang digunakan adalah:

| File Dataset | Deskripsi |
| --- | --- |
| `Kelas G_Fixed Call Report.csv` | Data laporan panggilan bulanan yang berisi jumlah total panggilan dan beberapa kategori layanan dari tahun ke tahun. |

Kolom pada dataset:

| Kolom | Keterangan |
| --- | --- |
| `Year` | Tahun laporan panggilan. |
| `Month` | Bulan laporan panggilan. |
| `Total Number of Calls` | Total seluruh panggilan masuk. |
| `Total Number of Doctors Consultancy` | Jumlah panggilan konsultasi dokter. |
| `Number of Total Health Information` | Jumlah panggilan informasi kesehatan. |
| `Number of Total Ambulance Information` | Jumlah panggilan informasi ambulans. |
| `Number of Total Complaints` | Jumlah panggilan komplain. |
| `Number of Calls To Know About The Service` | Jumlah panggilan untuk mengetahui informasi layanan. |

## Ringkasan Kodingan

| Tahap | Deskripsi |
| --- | --- |
| Import library | Menggunakan library Python seperti `pandas`, `matplotlib`, dan `seaborn` untuk membaca data, mengolah data, dan membuat grafik. |
| Membaca dataset | Dataset CSV dibaca ke dalam program agar dapat dianalisis dalam bentuk tabel. |
| Pengolahan data | Data difilter, dikelompokkan, dihitung nilai agregasinya, dan disiapkan sesuai kebutuhan setiap kategori soal. |
| Visualisasi | Hasil analisis ditampilkan menggunakan bar chart, line chart, scatter plot, histogram, dan boxplot. |
| Interpretasi | Grafik digunakan untuk melihat pola, tren, hubungan antar variabel, dan distribusi data panggilan. |

## Pembagian Pekerjaan Anggota

| No | Anggota Kelompok | Kategori | Fokus Pekerjaan | Output Analisis |
| --- | --- | --- | --- | --- |
| 1 | Reyhan Saputra | Kategori A - Agregasi | Mengolah data berdasarkan kelompok tahun, menghitung total, rata-rata, dan nilai maksimum dari beberapa jenis panggilan. | Bar chart untuk menampilkan hasil agregasi data tahunan. |
| 2 | Bryan Nathanael Saaragih | Kategori B - Tren/Filter | Memfilter data berdasarkan tahun tertentu dan menganalisis tren bulanan konsultasi dokter. | Line chart tren konsultasi dokter sepanjang tahun 2022. |
| 3 | Ali Budiman | Kategori C - Korelasi | Menganalisis hubungan antar variabel layanan panggilan, seperti informasi kesehatan, ambulans, komplain, dan konsultasi dokter. | Scatter plot untuk melihat pola hubungan atau korelasi antar data. |
| 4 | Ircham Putra Buana | Kategori D - Distribusi | Menganalisis persebaran data dan mendeteksi kemungkinan nilai ekstrem atau outlier. | Histogram dan boxplot untuk melihat distribusi data panggilan. |

## Detail Notebook

| Notebook | Kategori | Isi Analisis |
| --- | --- | --- |
| `postest_kel3_kategoriA (2).ipynb` | Kategori A | Analisis agregasi data, seperti total panggilan, rata-rata informasi ambulans, dan nilai maksimum panggilan informasi layanan berdasarkan tahun. |
| `posttest_kel3_kategoriB.ipynb` | Kategori B | Analisis tren/filter data untuk menampilkan fluktuasi bulanan konsultasi dokter pada tahun 2022. |
| `posttest_kel3_kategoriC.ipynb` | Kategori C | Analisis korelasi antar variabel menggunakan scatter plot. |
| `posttest_kel3_kategoriD.ipynb` | Kategori D | Analisis distribusi data menggunakan histogram dan boxplot. |
| `PostTest.ipynb` | Notebook utama | File gabungan atau notebook utama pengerjaan post test. |

## Struktur File

```text
Post-Test_Prak-Alprog_KelasG_Kel3/
|-- Kelas G_Fixed Call Report.csv
|-- PostTest.ipynb
|-- postest_kel3_kategoriA (2).ipynb
|-- posttest_kel3_kategoriB.ipynb
|-- posttest_kel3_kategoriC.ipynb
|-- posttest_kel3_kategoriD.ipynb
`-- README.md
```

## Cara Menjalankan

1. Pastikan Python dan Jupyter Notebook sudah terpasang.
2. Pastikan file `Kelas G_Fixed Call Report.csv` berada dalam folder yang sama dengan notebook.
3. Buka salah satu file notebook menggunakan Jupyter Notebook, JupyterLab, atau Visual Studio Code.
4. Jalankan sel kode dari atas ke bawah.
5. Lihat hasil tabel dan visualisasi grafik pada output notebook.

## Library yang Digunakan

```bash
pip install pandas matplotlib seaborn notebook
```

Library utama:

| Library | Fungsi |
| --- | --- |
| `pandas` | Membaca dan mengolah dataset CSV. |
| `matplotlib` | Membuat visualisasi grafik dasar. |
| `seaborn` | Membuat visualisasi statistik yang lebih rapi dan informatif. |

## Tujuan Analisis

Tujuan dari project ini adalah memahami pola laporan panggilan berdasarkan data historis. Melalui visualisasi dan pengolahan data, setiap kategori membantu melihat informasi yang berbeda, mulai dari total panggilan tahunan, tren konsultasi dokter, hubungan antar variabel, hingga distribusi data panggilan.

Dengan pembagian tugas per kategori, setiap anggota kelompok berkontribusi dalam membangun analisis data yang lengkap dan mudah dipresentasikan.
