<p align="center">
  <img src="Universitas-Diponegoro-Semarang-Logo.png" width="135" alt="Logo Universitas Diponegoro">
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="Screenshot%20from%202026-06-05%2021-42-44.png" width="120" alt="Logo Konsentrasi Biro">
</p>

<h1 align="center">Post Test Praktikum Algoritma dan Pemrograman 2026</h1>
<h3 align="center">Kelas G - Kelompok 3</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Python-Data%20Analysis-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter">
  <img src="https://img.shields.io/badge/Visualization-Matplotlib%20%7C%20Seaborn-2E7D32?style=for-the-badge" alt="Visualization">
  <img src="https://img.shields.io/badge/Theme-Fixed%20Call%20Report-7B1FA2?style=for-the-badge" alt="Theme">
</p>

---

## Tentang Project

Project ini merupakan pengerjaan post test Praktikum Algoritma dan Pemrograman yang berfokus pada analisis dataset **Kelas G - Fixed Call Report**. Dataset ini berisi laporan panggilan bulanan berdasarkan tahun, bulan, dan kategori layanan.

Analisis dilakukan menggunakan Python di Jupyter Notebook untuk membaca data, mengolah data, melakukan agregasi, memfilter data, melihat hubungan antar variabel, serta menampilkan hasilnya dalam bentuk visualisasi yang informatif.

> Tema utama project: **data report, tren layanan, korelasi, dan distribusi panggilan**.

## Dashboard Project

| Komponen | Keterangan |
| --- | --- |
| Mata Praktikum | Algoritma dan Pemrograman |
| Tahun | 2026 |
| Kelas | G |
| Kelompok | 3 |
| Dataset | `Kelas G_Fixed Call Report.csv` |
| Tools | Python, Jupyter Notebook, Pandas, Matplotlib, Seaborn |
| Output | Bar chart, line chart, scatter plot, histogram, dan boxplot |

## Dataset

| File Dataset | Deskripsi |
| --- | --- |
| `Kelas G_Fixed Call Report.csv` | Dataset laporan panggilan bulanan yang memuat total panggilan dan beberapa kategori layanan dari tahun ke tahun. |

### Kolom Dataset

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

## Alur Kodingan

| Tahap | Deskripsi |
| --- | --- |
| 1. Import library | Memanggil library yang diperlukan untuk membaca data dan membuat visualisasi. |
| 2. Load dataset | Membaca file CSV agar dapat diolah dalam bentuk data tabular. |
| 3. Data preparation | Menyesuaikan kolom, memfilter data, mengurutkan bulan, dan menyiapkan data sesuai kategori soal. |
| 4. Analisis | Melakukan perhitungan agregasi, tren, korelasi, dan distribusi. |
| 5. Visualisasi | Menampilkan hasil analisis dalam bentuk grafik agar pola data lebih mudah dipahami. |
| 6. Interpretasi | Menggunakan grafik untuk membaca perubahan, hubungan, dan persebaran data. |

## Jobdesk Anggota Kelompok

Klik nama anggota untuk membuka detail pekerjaan.

<details>
<summary><strong>Reyhan Saputra - Kategori A: Agregasi</strong></summary>

### Deskripsi Pekerjaan

Reyhan bertanggung jawab pada bagian analisis agregasi data. Fokus utama pekerjaannya adalah menghitung nilai ringkasan berdasarkan tahun, seperti total keseluruhan panggilan, rata-rata informasi ambulans bulanan, dan nilai maksimum panggilan informasi layanan.

| Bagian | Detail |
| --- | --- |
| Kategori | Kategori A - Agregasi |
| Notebook | `postest_kel3_kategoriA (2).ipynb` |
| Fokus | Mengelompokkan data berdasarkan tahun dan menghitung nilai statistik utama. |
| Visualisasi | Bar chart |
| Manfaat | Membantu melihat perbandingan data layanan antar tahun secara cepat. |

</details>

<details>
<summary><strong>Bryan Nathanael Saaragih - Kategori B: Tren/Filter</strong></summary>

### Deskripsi Pekerjaan

Bryan bertanggung jawab pada bagian tren dan filter data. Analisis dilakukan dengan memfilter data pada tahun tertentu, kemudian menampilkan perubahan jumlah konsultasi dokter dari bulan ke bulan.

| Bagian | Detail |
| --- | --- |
| Kategori | Kategori B - Tren/Filter |
| Notebook | `posttest_kel3_kategoriB.ipynb` |
| Fokus | Memfilter data tahun 2022 dan mengurutkan bulan dari Januari sampai Desember. |
| Visualisasi | Line chart |
| Manfaat | Membantu melihat fluktuasi konsultasi dokter selama satu tahun penuh. |

</details>

<details>
<summary><strong>Ali Budiman - Kategori C: Korelasi</strong></summary>

### Deskripsi Pekerjaan

Ali bertanggung jawab pada bagian analisis korelasi. Pekerjaan ini melihat hubungan antar variabel layanan, misalnya hubungan antara panggilan informasi kesehatan, informasi ambulans, komplain, dan konsultasi dokter.

| Bagian | Detail |
| --- | --- |
| Kategori | Kategori C - Korelasi |
| Notebook | `posttest_kel3_kategoriC.ipynb` |
| Fokus | Membandingkan dua variabel untuk melihat pola hubungan data. |
| Visualisasi | Scatter plot |
| Manfaat | Membantu memahami apakah kenaikan satu layanan berkaitan dengan kenaikan layanan lain. |

</details>

<details>
<summary><strong>Ircham Putra Buana - Kategori D: Distribusi</strong></summary>

### Deskripsi Pekerjaan

Ircham bertanggung jawab pada bagian distribusi data. Analisis ini digunakan untuk melihat persebaran data, variasi nilai, dan kemungkinan adanya data ekstrem atau outlier.

| Bagian | Detail |
| --- | --- |
| Kategori | Kategori D - Distribusi |
| Notebook | `posttest_kel3_kategoriD.ipynb` |
| Fokus | Menganalisis sebaran data panggilan berdasarkan kategori tertentu. |
| Visualisasi | Histogram dan boxplot |
| Manfaat | Membantu menemukan pola persebaran dan nilai yang berbeda jauh dari data lainnya. |

</details>

## Ringkasan Kategori

| Kategori | Tema Analisis | Visualisasi | Tujuan |
| --- | --- | --- | --- |
| Kategori A | Agregasi | Bar chart | Melihat nilai total, rata-rata, dan maksimum berdasarkan tahun. |
| Kategori B | Tren/Filter | Line chart | Melihat perubahan data bulanan pada tahun tertentu. |
| Kategori C | Korelasi | Scatter plot | Melihat hubungan antar variabel layanan. |
| Kategori D | Distribusi | Histogram dan boxplot | Melihat persebaran data dan kemungkinan outlier. |

## Detail Notebook

| Notebook | Isi Analisis |
| --- | --- |
| `postest_kel3_kategoriA (2).ipynb` | Analisis agregasi data berdasarkan tahun. |
| `posttest_kel3_kategoriB.ipynb` | Analisis tren bulanan konsultasi dokter tahun 2022. |
| `posttest_kel3_kategoriC.ipynb` | Analisis korelasi antar variabel layanan. |
| `posttest_kel3_kategoriD.ipynb` | Analisis distribusi data menggunakan histogram dan boxplot. |
| `PostTest.ipynb` | Notebook utama atau gabungan pengerjaan post test. |

## Struktur File

```text
Post-Test_Prak-Alprog_KelasG_Kel3/
|-- Kelas G_Fixed Call Report.csv
|-- PostTest.ipynb
|-- Universitas-Diponegoro-Semarang-Logo.png
|-- Screenshot from 2026-06-05 21-42-44.png
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

## Instalasi Library

```bash
pip install pandas matplotlib seaborn notebook
```

| Library | Fungsi |
| --- | --- |
| `pandas` | Membaca dan mengolah dataset CSV. |
| `matplotlib` | Membuat grafik dasar seperti bar chart, line chart, histogram, dan scatter plot. |
| `seaborn` | Membuat visualisasi statistik yang lebih rapi dan informatif. |

## Tujuan Akhir

Project ini dibuat untuk memahami pola laporan panggilan berdasarkan data historis. Setiap kategori memberikan sudut pandang analisis yang berbeda, mulai dari ringkasan tahunan, tren bulanan, korelasi antar layanan, hingga distribusi data.

Dengan pembagian tugas yang jelas dan visualisasi yang terstruktur, project ini dapat menjadi dokumentasi analisis data yang rapi, informatif, dan siap ditampilkan di GitHub.
