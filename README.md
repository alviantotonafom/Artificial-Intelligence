## Alvian Totonafo Mendrofa - 20220801045

# Prediksi Kelulusan Siswa Berdasarkan Jam Belajar dan Tidur

## Deskripsi Proyek
Proyek ini bertujuan untuk memprediksi apakah seorang siswa akan lulus atau tidak berdasarkan dua fitur utama:
- Jumlah jam belajar per hari.
- Jumlah jam tidur per hari.

Kami menggunakan dua model machine learning, yaitu **K-Nearest Neighbors (KNN)** dan **Logistic Regression**, untuk memprediksi kelulusan siswa. Visualisasi scatter plot juga digunakan untuk membantu memahami pola data dan hasil prediksi.

## Dataset
Dataset yang digunakan adalah data buatan dengan tiga kolom utama:
- **jam_belajar**: Jumlah jam belajar siswa per hari.
- **jam_tidur**: Jumlah jam tidur siswa per hari.
- **lulus**: Status kelulusan siswa (0 = Tidak Lulus, 1 = Lulus).

Data ini telah dimasukkan langsung ke dalam kode untuk keperluan sederhana.

## Model Machine Learning
Kami menerapkan dua model untuk memprediksi kelulusan siswa:
1. **K-Nearest Neighbors (KNN)**: Menggunakan tetangga terdekat untuk memprediksi kelulusan berdasarkan jarak fitur `jam_belajar` dan `jam_tidur`.
2. **Logistic Regression**: Model regresi logistik digunakan untuk memodelkan probabilitas biner dari kelulusan siswa.

## Alur Kerja
1. **Persiapan Data**: Data dibagi menjadi fitur (`jam_belajar` dan `jam_tidur`) dan label (`lulus`), kemudian dibagi lagi menjadi data latih dan data uji.
2. **Standardisasi**: Fitur distandarisasi untuk memastikan distribusi data seragam sebelum digunakan dalam model.
3. **Pelatihan Model**: Kedua model dilatih dengan data latih.
4. **Prediksi**: Model digunakan untuk memprediksi hasil kelulusan pada data uji.
5. **Evaluasi**: Kinerja model dievaluasi berdasarkan akurasi dan laporan klasifikasi.
6. **Visualisasi**: Scatter plot digunakan untuk memvisualisasikan data asli dan hasil prediksi dari model KNN.

## Hasil dan Analisis
- **KNN** memberikan akurasi yang baik dalam memprediksi kelulusan siswa berdasarkan `jam_belajar` dan `jam_tidur`.
- **Logistic Regression** juga menunjukkan performa yang cukup baik.
- **Visualisasi** membantu melihat bagaimana model memprediksi kelulusan berdasarkan pola data asli.
