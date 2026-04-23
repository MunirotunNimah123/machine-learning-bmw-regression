📊 Machine Learning Project – BMW Sales Prediction

Perbandingan Algoritma Linear Regression, Decision Tree, dan Random Forest dalam Prediksi Penjualan Mobil BMW

📌 Deskripsi Project

Project ini bertujuan untuk membangun model Machine Learning berbasis regresi untuk memprediksi jumlah penjualan mobil BMW (units_sold) berdasarkan data historis.
Selain itu, dilakukan perbandingan performa beberapa algoritma untuk menentukan model terbaik.

📂 Dataset
Nama Dataset: BMW Global Sales Dataset
Jumlah Data: ±1000 data
Fitur Utama:
price_usd → harga mobil
marketing_spend_usd → biaya pemasaran
dealership_count → jumlah dealer
competition_index → tingkat persaingan
gdp_growth_percent, interest_rate_percent → faktor ekonomi
Target:
units_sold → jumlah unit terjual
🎯 Tujuan Project
Memprediksi jumlah penjualan mobil BMW
Menganalisis pengaruh faktor pemasaran dan ekonomi
Membandingkan performa algoritma regresi untuk mendapatkan model terbaik
⚙️ Algoritma yang Digunakan
Linear Regression
Decision Tree Regressor
Random Forest Regressor
🔧 Tahapan Machine Learning

Project ini dilakukan melalui tahapan lengkap, yaitu:

Data Understanding
Analisis struktur data, tipe data, statistik deskriptif, dan missing values
Data Preprocessing
Handling missing values
Encoding data kategorikal
Feature engineering
Penghapusan fitur yang tidak relevan
Exploratory Data Analysis (EDA)
Distribusi data (Histogram)
Korelasi antar fitur (Heatmap)
Analisis pola (Scatterplot)
Data Splitting
Menggunakan 3 skenario:
70:30
80:20
90:10
Model Building
Membangun model menggunakan 3 algoritma berbeda
Hyperparameter Tuning
Menggunakan GridSearchCV untuk optimasi model
Model Evaluation
Menggunakan metrik:
MAE
MSE
RMSE
R² Score
📈 Hasil dan Evaluasi Model

Hasil menunjukkan bahwa:

Random Forest memiliki performa terbaik
Nilai R² Score mencapai 0.91
Error (MAE, RMSE) lebih rendah dibanding model lain

👉 Hal ini menunjukkan bahwa model mampu memprediksi penjualan dengan baik

🚀 Deployment Sederhana

Model diuji menggunakan data baru dan berhasil menghasilkan prediksi:

Prediksi penjualan: 401 unit

Hal ini membuktikan bahwa model dapat digunakan untuk prediksi data baru secara otomatis

🏆 Kesimpulan
Random Forest merupakan model terbaik
Faktor pemasaran dan ekonomi berpengaruh terhadap penjualan
Model dapat digunakan untuk membantu pengambilan keputusan bisnis
👩‍💻 Author

Munirotun Ni’mah
NIM: F1G123010