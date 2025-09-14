# Proyek Analisis Data

## 1. Setup Environment
- Membuat environment baru dengan conda
- Menginstal library yang dibutuhkan
- Mengaktifkan environment sebelum menjalankan kode

## 2. Struktur Direktori
project/
│
├── data/
│ ├── raw/ # Menyimpan file asli hasil upload
│ ├── processed/ # Menyimpan data yang sudah dibersihkan
│
├── notebooks/ # Jupyter Notebook (.ipynb)
├── src/ # Script Python utama
└── README.md # Dokumentasi project

## 3. Pipeline Project

Collection → Ambil dataset mentah ke folder data/raw/.

EDA (Exploratory Data Analysis) → Eksplorasi data, cek distribusi, missing value, dll.

Preprocessing → Pembersihan data, encoding, scaling, dll.

Modeling → Membangun model regresi (contoh: Linear Regression).

Evaluation → Evaluasi performa model dengan metrik regresi (MSE, RMSE, R²).

Interpretation → Menarik insight dan membuat laporan.
