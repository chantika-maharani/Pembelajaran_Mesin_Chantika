# Latihan Pertemuan 2 - Fitur, Label, dan Pembagian Data Latih/Uji
Mata Kuliah: Pembelajaran Mesin (INF62325)
Nama : Chantika Maharani
NIM : 2488010080

## Ringkasan
Latihan ini membahas konsep dasar machine learning, meliputi identifikasi fitur dan label pada dataset, perbedaan klasifikasi dan regresi berdasarkan tipe label, serta pembagian data menjadi data latih dan data uji menggunakan `train_test_split` dari scikit-learn.

## Isi Repositori
- PM_Pertemuan2_Chantika_Maharani_2488010080.ipynb : notebook latihan

## Temuan Utama
- Jenis label pada dataset menentukan apakah suatu kasus termasuk klasifikasi (label kategori) atau regresi (label numerik)
- Pembagian data latih dan uji penting untuk mengukur kemampuan generalisasi model, bukan sekadar mengukur hafalan terhadap data yang sama
- Alur kerja machine learning bersifat iteratif karena proses pelatihan dan evaluasi model dapat diulang untuk memperbaiki performa berdasarkan hasil pengujian


# Latihan Pertemuan 3 - Eksplorasi Data (EDA)
Mata Kuliah: Pembelajaran Mesin (INF62325)
Nama : Chantika Maharani
NIM : 2488010080

## Ringkasan
Praktikum ini membahas eksplorasi data (EDA) pada dataset 'tips', meliputi pemeriksaan struktur data, statistik deskriptif, deteksi missing value dan duplikat, visualisasi (histogram, box plot, scatter plot), serta heatmap korelasi antar fitur numerik.

## Isi Repositori
- PM_P3_Chantika_Maharani_2488010080.ipynb : notebook praktikum

## Temuan Utama
- Terdapat hubungan positif antara total_bill dan tip, di mana pasangan fitur ini juga memiliki korelasi tertinggi (0.68) dibanding pasangan fitur numerik lainnya
- Transaksi pada waktu Dinner jumlahnya lebih banyak dan cenderung memiliki total_bill lebih besar dibanding Lunch
- Fitur petal_length dan petal_width pada dataset Iris menunjukkan korelasi tertinggi (0.96) dan paling berguna untuk klasifikasi karena mampu memisahkan kelompok spesies dengan jelas
