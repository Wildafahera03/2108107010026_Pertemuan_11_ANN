# 2108107010026_Pertemuan_11_ANN

Nama: Wilda Fahera

NPM : 2108107010026

Materi bacaan:

https://www.megabagus.id/deep-learning-artificial-neural-networks/ (halaman 1 - 7) ⁠⁠https://www.megabagus.id/deep-learning-artificial-neural-networks-aplikasi (halaman 1 - 4) Pahami isi dari kedua artikel tersebut dan kerjakan:

Contoh pada artikel kedua menggunakan tensorflow pada python environment ⁠Tugas 2 sebelumnya menggunakan SVM, kerjakan dengan menggunakan ANN pada python environment yang sama Kumpulkan kedua tugas tersebut menggunakan repository pada github dengan nama repository: NPM_Pertemuan_11_ANN. Repository tersebut berisi:

Dataset sebelum dipreprocessing (format csv) ⁠Kode python yang memuat process preprocessing, training, testing dan perhitungan akurasi ⁠File requirements.txt yang berisi library yang digunakan ⁠File README.md yang berisi penjelasan tentang kedua tugas yang dikerjakan beserta perbandingan akurasi SVM dan ANN

# Dataset yang dipakai
* Klasifikasi
  Dataset yang digunakan berasal dari web kaggle https://www.kaggle.com/datasets/muratkokludataset/raisin-dataset 

Informasi Dataset:

1. Jumlah baris dan kolom
- Dataset ini memiliki 908 baris.
- Dataset ini memiliki 8 kolom.

2. Nama kolom
Nama kolom dalam dataset ini adalah sebagai berikut:
- Area
- MajorAxisLength
- MinorAxisLength
- Eccentricity
- Extension
- Class

3. Tipe data kolom
Tipe data setiap kolom dalam dataset ini adalah sebagai berikut:
- Area: int64
- MajorAxisLength: float64
- MinorAxisLength: float64
- Eccentricity: float64
- ConvexArea: int64
- Extent: float64
- Perimeter: float64
- Class: object

* Regresi
  Dataset yang digunakan berasal dari web kaggle https://www.kaggle.com/datasets/shivam2503/diamonds 

Rincian Dataset:
- Berisi nilai harga dalam bentuk integer.
- carat: Berisi nilai berat berlian dalam bentuk float64.
- cut: Merupakan kategori untuk kualitas potongan dengan tipe data object.
- color: Merupakan kategori untuk warna berlian dengan tipe data object.
- clarity: Merupakan kategori untuk tingkat kejelasan berlian dengan tipe data object.
- x: Berisi nilai panjang dalam mm dalam bentuk float64.
- y: Berisi nilai lebar dalam mm dalam bentuk float64.
- z: Berisi nilai kedalaman dalam mm dalam bentuk float64.
- depth: Berisi nilai persentase kedalaman dalam bentuk float64.
- table: Berisi nilai lebar bagian atas berlian relatif terhadap titik terlebar dalam bentuk float64.

# Perbandingan hasil SVM dan ANN

# Klasifikasi
1. Model SVM berhasil memprediksi dengan akurasi 88%
2. ANN berhasil memprediksi nilai akurasi 83.33%

# Regresi
1. SVM memperoleh 0.7796460165386356
2. ANN model R2 Score: 0.9740887053850329
  
