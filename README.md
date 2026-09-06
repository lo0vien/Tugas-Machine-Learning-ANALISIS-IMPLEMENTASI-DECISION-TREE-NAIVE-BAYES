# 🌳 Decision Tree & Naive Bayes

Implementasi **Machine Learning** untuk memprediksi apakah mahasiswa **lulus tepat waktu** menggunakan algoritma Decision Tree dan Gaussian Naive Bayes.

## Dataset

Dataset terdiri dari **500 data mahasiswa** dengan fitur:

1. IPK
2. Kehadiran
3. Jam Belajar
4. Organisasi
5. Penghasilan Orang Tua
6. Jenis Kelamin
7. Status Beasiswa

Target: **Lulus Tepat Waktu (Ya/Tidak)**.

## Model

Tiga model yang dibandingkan:

1. Decision Tree `max_depth=3`
2. Decision Tree `max_depth=None`
3. Gaussian Naive Bayes

## Proses

* Handling missing value menggunakan median
* Encoding data kategorikal
* Train-test split **80:20**
* Training dan prediksi model
* Evaluasi performa
* Analisis error
* Simulasi prediksi

## Evaluasi

Model dievaluasi menggunakan:

**Accuracy · Precision · Recall · F1-Score · Confusion Matrix**

Hasil juga divisualisasikan dalam bentuk **Decision Tree** dan **bar chart perbandingan performa**.

## Analisis

Project mencakup analisis **5 data yang salah diprediksi** serta simulasi mahasiswa dengan **IPK tinggi dan kehadiran rendah** untuk membandingkan hasil Decision Tree dan Naive Bayes.

## Tech Stack

`Python` · `NumPy` · `Pandas` · `Scikit-learn` · `Matplotlib` · `Seaborn`

## Mata Kuliah

**Machine Learning Dasar — Program Studi Informatika**

### Anggota

| Nama           | NPM       |
| -------------- | --------- |
| Nurmelinzah    | G1A024013 |
| Tasya Triani   | G1A024019 |
| Lovien Najla D | G1Q024055 |
