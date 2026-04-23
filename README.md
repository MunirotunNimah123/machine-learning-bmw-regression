# 📊 Machine Learning Project – BMW Sales Prediction
### Perbandingan Algoritma Linear Regression, Decision Tree, dan Random Forest dalam Prediksi Penjualan Mobil BMW

---

## 📌 Deskripsi Project
Project ini bertujuan untuk membangun model Machine Learning berbasis regresi untuk memprediksi jumlah penjualan mobil BMW (*units_sold*) berdasarkan data historis. Selain itu, dilakukan perbandingan performa beberapa algoritma untuk menentukan model terbaik.

---

## 📂 Dataset
- **Nama Dataset**: BMW Global Sales Dataset  
- **Jumlah Data**: ±1000 data  

### Fitur Utama:
- `price_usd` → harga mobil  
- `marketing_spend_usd` → biaya pemasaran  
- `dealership_count` → jumlah dealer  
- `competition_index` → tingkat persaingan  
- `gdp_growth_percent` → pertumbuhan ekonomi  
- `interest_rate_percent` → suku bunga  

### Target:
- `units_sold` → jumlah unit terjual  

---

## 🎯 Tujuan Project
- Memprediksi jumlah penjualan mobil BMW  
- Menganalisis pengaruh faktor pemasaran dan ekonomi  
- Membandingkan performa algoritma regresi untuk mendapatkan model terbaik  

---

## ⚙️ Algoritma yang Digunakan
- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  

---

## 🔧 Tahapan Machine Learning

### 1. Data Understanding
- Melihat bentuk data (shape)  
- Mengecek tipe data (info)  
- Statistik deskriptif  
- Mengecek missing value  

### 2. Data Preprocessing
- Mengatasi missing value  
- Encoding data kategorikal  
- Feature engineering  
- Menghapus kolom yang tidak diperlukan  

### 3. Exploratory Data Analysis (EDA)
- Histogram → melihat distribusi penjualan  
- Heatmap → melihat korelasi antar fitur  
- Scatterplot → melihat pola/trend data  

### 4. Data Splitting
- 70% training : 30% testing  
- 80% training : 20% testing  
- 90% training : 10% testing  

### 5. Model Building
- Membangun model menggunakan 3 algoritma  

### 6. Hyperparameter Tuning
- Menggunakan GridSearchCV untuk optimasi model  

### 7. Model Evaluation
Menggunakan metrik:
- MAE (Mean Absolute Error)  
- MSE (Mean Squared Error)  
- RMSE (Root Mean Squared Error)  
- R² Score  

---

## 📈 Hasil dan Evaluasi Model

- **Linear Regression** → R² sekitar 0.80  
- **Decision Tree** → R² sekitar 0.84 – 0.86  
- **Random Forest** → R² terbaik mencapai 0.91  

👉 Model terbaik adalah **Random Forest** karena memiliki nilai R² tertinggi dan error paling kecil.

---

## 🚀 Deployment Sederhana
Model diuji menggunakan data baru dan menghasilkan:

- **Prediksi penjualan: 401 unit**

👉 Hal ini menunjukkan model dapat digunakan untuk prediksi data baru secara otomatis.

---

## 🏆 Kesimpulan
- Random Forest merupakan model terbaik dengan R² = 0.91  
- Faktor pemasaran dan ekonomi berpengaruh terhadap penjualan  
- Model dapat digunakan untuk membantu pengambilan keputusan bisnis  

---

## 👩‍💻 Author
- **Nama**: Munirotun Ni’mah  
- **NIM**: F1G123010  
