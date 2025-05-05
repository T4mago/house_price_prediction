# house_price_prediction
house price prediction using linear regressionn

# Prediksi Harga Rumah di Bandung

Proyek ini merupakan implementasi model Machine Learning sederhana menggunakan **Linear Regression** untuk memprediksi harga rumah di wilayah Bandung. Dataset disusun secara lokal berdasarkan fitur-fitur utama rumah seperti luas bangunan, luas tanah, dan jumlah kamar tidur.

## 📁 Dataset
File `harga_rumah_bandung_lengkap.csv` berisi data rumah di Bandung dengan kolom sebagai berikut:
- `luas_bangunan` (m²)
- `luas_tanah` (m²)
- `kamar_tidur` (jumlah kamar tidur)
- `harga` (dalam juta rupiah)

## 📊 Model yang Digunakan
- **Linear Regression** dari `sklearn.linear_model`
- Dataset dibagi menjadi data latih dan data uji menggunakan `train_test_split`
- Evaluasi model dilakukan dengan:
  - Mean Squared Error (MSE)
  - R² Score

## 🔧 Library yang Digunakan
- `pandas`
- `scikit-learn`
- `matplotlib`

## 🚀 Cara Menjalankan
1. Buka file `.ipynb` ini di [Google Colab](https://colab.research.google.com/)
2. Jalankan setiap cell dari atas ke bawah
3. Pastikan file CSV tersedia di folder kerja atau dibuat di awal script

## 📈 Visualisasi
Model akan menampilkan plot perbandingan antara harga sebenarnya dan harga hasil prediksi.

## 📝 Catatan
Proyek ini ditujukan untuk keperluan edukatif dan tugas metodologi penelitian. Model ini bersifat sederhana dan belum menggunakan teknik optimalisasi lebih lanjut seperti feature engineering atau tuning hyperparameter.

## 📚 Referensi
- [scikit-learn Linear Regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html)
- [Google Colab](https://colab.research.google.com/)
