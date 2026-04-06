# 🏥 Analisis Perbandingan Algoritma Klasifikasi dengan Teknik SMOTE pada Gagal Jantung

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis performa berbagai algoritma Machine Learning dalam memprediksi kematian akibat gagal jantung. Tantangan utama dalam dataset ini adalah ketidakseimbangan kelas (*imbalanced data*), yang diatasi dengan teknik **SMOTE (Synthetic Minority Over-sampling Technique)**.

## 📊 Dataset
Dataset yang digunakan adalah **Heart Failure Prediction Dataset**.
- **Fitur Utama:** Usia, Anemia, Tekanan Darah Tinggi, Diabetes, Fraksi Ejeksi, dll.
- **Target:** `DEATH_EVENT` (0: Tidak Meninggal, 1: Meninggal).

## 🛠️ Metodologi
1. **Exploratory Data Analysis (EDA):** Visualisasi distribusi data dan korelasi antar fitur.
2. **Preprocessing:** Penanganan nilai hilang, normalisasi, dan pembagian data train/test.
3. **Handling Imbalance:** Menerapkan SMOTE untuk menyeimbangkan kelas target.
4. **Modeling:** Membandingkan beberapa algoritma (seperti Random Forest, SVM, KNN, dll).
5. **Evaluasi:** Menggunakan Accuracy, Precision, Recall, dan F1-Score.

## 📈 Hasil Analisis
*(Isi bagian ini dengan ringkasan hasil terbaik kamu, contoh:)*
- Tanpa SMOTE: Akurasi tinggi tetapi Recall untuk kelas minoritas rendah.
- Dengan SMOTE: Peningkatan signifikan pada Recall, memberikan prediksi yang lebih baik untuk pasien berisiko tinggi.

## 🚀 Cara Menjalankan
1. Clone repositori ini:
   ```bash
   git clone [https://github.com/nabilakhyarotunnisa/analisis-perbandingan-algoritma-dengan-teknik-SMOTE.git](https://github.com/nabilakhyarotunnisa/analisis-perbandingan-algoritma-dengan-teknik-SMOTE.git)
