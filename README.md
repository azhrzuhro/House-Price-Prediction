## House Price Prediction
#### Deskripsi Proyek
Proyek ini adalah analisis prediktif harga rumah menggunakan dataset yang komprehensif. Tujuannya adalah untuk membangun model regresi yang akurat untuk memprediksi harga jual rumah berdasarkan berbagai fitur properti.


#### Tahapan Proyek
1. Analisis Data Eksplorasi (EDA)
Tahap ini berfokus pada pemahaman awal tentang dataset, termasuk:

Pemuatan dan Inspeksi Data: Memuat data dan melihat sekilas 5 baris pertama untuk memahami strukturnya.

Tipe Data dan Ukuran: Memeriksa tipe data dari setiap kolom dan dimensi dataset (1460 baris, 81 kolom).

Penanganan Nilai yang Hilang (Missing Values): Mengidentifikasi kolom dengan nilai yang hilang, seperti LotFrontage, Alley, dan PoolQC, untuk diproses lebih lanjut.

Pemeriksaan Duplikat: Memastikan tidak ada duplikat dalam data.

2. Analisis Statistik Dasar
Analisis statistik dasar dilakukan untuk mendapatkan ringkasan deskriptif dari variabel-variabel numerik, termasuk mean, standar deviasi, dan kuartil.

3. Visualisasi Data
Berbagai plot digunakan untuk memvisualisasikan hubungan antar variabel dan memahami distribusi data. Visualisasi membantu mengidentifikasi korelasi, outlier, dan pola dalam dataset.

4. Pra-pemrosesan Data
Feature Engineering: Membuat fitur baru dari fitur yang sudah ada.

Penanganan Outlier: Mengidentifikasi dan menangani outlier yang dapat mempengaruhi performa model.

Transformasi Data: Menerapkan transformasi logaritmik pada variabel target (SalePrice) untuk menormalkan distribusinya.

5. Pemodelan
Tiga model regresi digunakan dan dievaluasi:

Linear Regression

Ridge Regression

XGBoost Regressor

Model-model ini dilatih pada data pelatihan, dan performanya dievaluasi menggunakan metrik berikut:

R-squared (R2) score: Mengukur seberapa baik model menjelaskan variabilitas dalam variabel target.

Root Mean Squared Error (RMSE): Mengukur standar deviasi residu.

Mean Absolute Error (MAE): Mengukur rata-rata selisih absolut antara nilai yang diprediksi dan nilai aktual.

6. Kesimpulan
Proyek ini berhasil membangun dan membandingkan beberapa model regresi untuk memprediksi harga rumah. Hasil evaluasi model memberikan wawasan tentang model mana yang paling akurat untuk dataset ini.
