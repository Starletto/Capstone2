# Capstone2
Machine Learning project to estimate house values in California districts. Developed with Python &amp; Scikit-Learn. Algorithm: Random Forest Regressor. Accuracy: 77.41%.

# California Housing Price Prediction 🏠
**Capstone Project Module 2 - Machine Learning Regression**

## 📌 Project Overview
Proyek ini bertujuan untuk membangun model machine learning yang dapat memprediksi nilai rata-rata rumah (`median_house_value`) di berbagai distrik di California berdasarkan data sensus tahun 1990. Model ini dirancang untuk membantu investor real estate dan pengembang properti dalam mengestimasi nilai pasar suatu distrik secara cepat dan akurat.

## 📊 Dataset Information
Dataset ini mencakup 10 fitur utama:
- **Geografis:** `longitude`, `latitude`, `ocean_proximity`
- **Karakteristik Rumah:** `housing_median_age`, `total_rooms`, `total_bedrooms`
- **Demografis:** `population`, `households`, `median_income`
- **Target:** `median_house_value`

## 🛠 Workflow & Methodology
Proyek ini dikerjakan dengan alur kerja sebagai berikut:
1. **Identifikasi Goal:** Menetapkan tujuan bisnis dan metrik evaluasi.
2. **Mengecek Dataset:** Inspeksi struktur data, tipe data, dan missing values.
3. **EDA (Exploratory Data Analysis):** Visualisasi korelasi, distribusi harga, dan peta persebaran geografis.
4. **Menentukan Target:** Memisahkan fitur (X) dan target (y).
5. **Membagi Data:** Melakukan *train-test split* (80% training, 20% testing).
6. **Data Preprocessing:** 
   - Menghapus data outlier
   - Encoding fitur kategorikal `ocean_proximity`
7. **Training Model:** Melatih algoritma **Random Forest Regressor**.
8. **Evaluasi Model:** Mengukur performa menggunakan berbagai metrik regresi.
9. **Hasil:** Menarik kesimpulan bisnis dan rekomendasi.

## 📈 Model Performance
Model akhir menggunakan **Random Forest Regressor** memberikan hasil sebagai berikut:

| Metric | Value |
| :--- | :--- |
| **R-squared (R2)** | **0.7741** (77.41% Akurasi) |
| **MAE** | $31139.91 |
| **RMSE** | $46601.68 |
| **MAPE** | **18.61%** (Good Forecasting) |
| **MSLE** | 0.0591 |

*Kesimpulan: Model memiliki performa yang kuat dengan akurasi 77.41% dan tingkat kesalahan persentase di bawah 20%.*
