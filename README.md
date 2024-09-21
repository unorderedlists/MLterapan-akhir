# Laporan Proyek Machine Learning

## Daftar Isi

- [Project Overview](#project-overview)
- [Business Understanding](#business-understanding)
- [Data Understanding](#data-understanding)
- [Data Preparation](#data-preparation)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Reference](#reference)

## Project Overview

Referensi.<sup>[[1]](https://medium.com/@anicomanesh/evolution-of-recommendation-algorithms-part-i-fundamentals-and-classical-recommendation-bb1c0bce78a9)</sup>

## Business Understanding

### Problem Statements

- Pernyataan Masalah 1
- Pernyataan Masalah 2

### Goals

- Jawaban pernyataan masalah 1
- Jawaban pernyataan masalah 2

### Solution statements

- Solusi 1
- Solusi 2

## Data Understanding

Dataset yang digunakan adalah Book recommendation dataset<sup>[[2]](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset)</sup> dari Kaggle yang memiliki score usability sempurna yaitu 10.00. Usability Score ini merupakan bagian dari sistem penilaian Kaggle yang memberikan gambaran tentang kualitas dan kemudahan penggunaan dataset. Artinya kita dapat mengharapkan bahwa dataset ini telah melalui proses penilaian ketat dan dianggap sangat sesuai untuk keperluan proyek machine learning dalam kemudahan, efisiensi, dan kualitas data.

Dataset ini terdiri dari data pengguna yang telah dianonimkan, data buku dengan informasi seperti ISBN, penulis, dan penerbit dari Amazon, serta data penilaian buku dengan skala eksplisit 1-10 atau implisit dengan nilai 0.

Konten pada dataset adalah sebagai berikut:

- books: buku yang diidentifikasi dengan ISBN masing-masing. ISBN yang tidak valid telah dihapus dari dataset. Informasi berbasis konten juga disertakan (Judul Buku, Penulis, Tahun Terbit, Penerbit) yang diperoleh dari Amazon Web Services. Jika ada lebih dari satu penulis, hanya penulis pertama yang tercantum. Tautan ke gambar sampul juga diberikan dalam tiga ukuran berbeda (URL Gambar-S, URL Gambar-M, URL Gambar-L) yang mengarah ke situs Amazon.
- ratings: berisi informasi penilaian buku secara eksplisit dengan skala 1-10 (nilai lebih tinggi menandakan penghargaan lebih tinggi) atau implisit, dinyatakan dengan 0.
- users: berisi informasi tentang pengguna. ID pengguna (User-ID) telah dianonimkan dan diubah menjadi angka. Data demografi diberikan (Lokasi, Usia) jika tersedia. Jika tidak, kolom ini berisi nilai NULL.

## Data Preparation

## Modeling

## Evaluation

## Reference

[1] Anicomanesh, A. (2021). _Evolution of recommendation algorithms: Part I - Fundamentals and classical recommendation_. Medium. Tersedia: [tautan](https://medium.com/@anicomanesh/evolution-of-recommendation-algorithms-part-i-fundamentals-and-classical-recommendation-bb1c0bce78a9). Diakses pada 21 September 2024.

[2] Arashnic. (2024). _Book recommendation dataset_ [Dataset]. Kaggle. Tersedia: [tautan](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset). Diakses pada 21 September 2024.
