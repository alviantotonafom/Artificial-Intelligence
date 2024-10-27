
# Prediksi Total Penjualan Pizza Menggunakan Machine Learning

## Deskripsi
Proyek ini bertujuan untuk memprediksi harga total penjualan pizza menggunakan model **Linear Regression**. Data penjualan pizza dianalisis untuk mengidentifikasi pola utama, dan fitur-fitur seperti jumlah pesanan, harga satuan, ukuran, dan kategori pizza digunakan untuk memprediksi total harga.

## Struktur Proyek
- **pizza_sales.csv**: Dataset penjualan pizza yang mencakup detail pesanan.
- **pizza_sales_analysis.ipynb**: Notebook Jupyter yang berisi seluruh proses analisis, mulai dari pemrosesan data hingga pembuatan model dan visualisasi hasil.

## Langkah Analisis
1. **Data Preprocessing**: Membersihkan data, menghapus nilai kosong, dan mengonversi variabel kategori (ukuran dan kategori pizza) menjadi nilai numerik.
2. **Pembuatan Model**: Menggunakan model Linear Regression untuk memprediksi `total_price`.
3. **Evaluasi Model**: Menilai performa model dengan Mean Squared Error (MSE).
4. **Visualisasi Data**: Melihat distribusi fitur utama dan memetakan korelasi antar fitur, serta membandingkan nilai prediksi dengan nilai aktual.

## Hasil Utama
- **Mean Squared Error (MSE)**: 0.31, yang menunjukkan akurasi model yang baik.
- **Korelasi Fitur**: `quantity` dan `unit_price` adalah faktor utama yang mempengaruhi `total_price`.
- **Visualisasi**: Menunjukkan kesesuaian yang baik antara prediksi dan data aktual.

## Kesimpulan
Analisis ini memberikan pemahaman yang lebih baik tentang faktor-faktor yang memengaruhi total harga penjualan. Model ini dapat digunakan oleh bisnis untuk strategi penetapan harga dan memahami pola penjualan yang umum.
