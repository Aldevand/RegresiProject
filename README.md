# Project Analisis dan Regresi

## 1. Setup Environment
- Membuat environment baru dengan conda
- Menginstal library yang dibutuhkan
- Mengaktifkan environment sebelum menjalankan kode

## 2. Struktur Direktori
<img width="584" height="1030" alt="STRUKTUR FOLDER - visual selection" src="https://github.com/user-attachments/assets/4fc79969-271d-4f38-aba4-d1dc6e12a9e8" />


## 3. Pipeline Project

Collection → Ambil dataset mentah ke folder data/raw/.

EDA (Exploratory Data Analysis) → Eksplorasi data, cek distribusi, missing value, dll.

Preprocessing → Pembersihan data, encoding, scaling, dll.

Modeling → Membangun model regresi (contoh: Linear Regression).

Evaluation → Evaluasi performa model dengan metrik regresi (MSE, R²).

Hasil Evaluasi
R-squared Score: Nilai R-squared (R²) Anda menunjukkan seberapa baik model dapat menjelaskan variabilitas dalam data. Nilai R² yang tinggi, mendekati 1, mengindikasikan bahwa model Anda mampu menjelaskan sebagian besar varian dalam variabel target. Ini adalah metrik yang sangat baik untuk model regresi.

Mean Squared Error (MSE) dan Root Mean Squared Error (RMSE): Metrik ini mengukur rata-rata kuadrat kesalahan antara nilai yang diprediksi dan nilai sebenarnya. Semakin rendah nilai MSE dan RMSE, semakin kecil kesalahan prediksi rata-rata model Anda, yang menunjukkan performa yang lebih baik.

Interpretasi Visual
Scatter Plot (Nilai Sebenarnya vs. Prediksi): Plot ini menunjukkan korelasi kuat antara nilai yang diprediksi oleh model dan nilai sebenarnya. Titik-titik data cenderung berada di dekat garis diagonal, yang menunjukkan bahwa model memiliki kemampuan prediksi yang konsisten di seluruh rentang nilai data.


