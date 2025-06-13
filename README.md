# 🩺 Prediksi Diabetes dengan Algoritma Naive Bayes

Proyek ini bertujuan untuk memprediksi kemungkinan seseorang menderita diabetes berdasarkan data yang tersedia menggunakan algoritma **Naive Bayes**. Analisis ini dilakukan dalam sebuah notebook interaktif berbasis Python dan dijalankan melalui **Google Colab**.

## 📌 Deskripsi Masalah

Penyakit diabetes merupakan salah satu penyakit kronis yang jumlah penderitanya semakin meningkat. Dengan memanfaatkan data medis seperti kadar glukosa, tekanan darah, dan indeks massa tubuh (BMI), kita dapat memanfaatkan algoritma pembelajaran mesin untuk memprediksi kemungkinan terjadinya diabetes.

## 📁 Struktur Proyek
.
├── Prediksi_Diabetes.ipynb # Notebook utama (berisi semua analisis dan visualisasi)
├── README.md # Dokumentasi proyek ini

## 🔧 Teknologi & Library

Notebook ini menggunakan pustaka Python populer untuk data science, yaitu:

- `pandas` — manipulasi dan analisis data
- `numpy` — operasi numerik
- `matplotlib` & `seaborn` — visualisasi data
- `sklearn` (scikit-learn) — pemodelan machine learning

## 🚀 Langkah Menjalankan Proyek

1. **Clone repositori ini:**

   ```bash
   git clone https://github.com/username/Prediksi-Diabetes-NaiveBayes.git
   cd Prediksi-Diabetes-NaiveBayes

2. **Buka Notebook:**
- Gunakan Google Colab
- Upload file Prediksi_Diabetes.ipynb
- Jalankan seluruh sel secara berurutan

3. **Pastikan semua library berikut sudah tersedia:**

    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn

## 🔄 Alur Analisis

1. **Import dan Eksplorasi Dataset**  
   Membaca dataset dan memahami struktur serta distribusi data.

2. **Pra-pemrosesan Data**
   - Mengganti nilai **0** sebagai _missing values_ pada kolom medis tertentu (misalnya: Glucose, Blood Pressure, BMI).
   - Menangani missing values dengan teknik imputasi (mean/median).
   - Melakukan normalisasi data jika diperlukan untuk meningkatkan performa model.

3. **Pembagian Data**
   - Dataset dibagi menjadi data **training (80%)** dan **testing (20%)**.

4. **Pelatihan Model**
   - Menggunakan algoritma **Gaussian Naive Bayes** dari library `scikit-learn`.

5. **Evaluasi Model**
   - **Akurasi** model
   - **Confusion Matrix**
   - **Precision, Recall, F1-Score**

---

## 📊 Contoh Hasil Evaluasi

- **Akurasi model**: ± 76% (tergantung dari pembagian data dan preprocessing)
- **Confusion Matrix**: Menunjukkan seberapa banyak prediksi benar/salah dalam kategori positif dan negatif
- **Precision & Recall**: Menilai kemampuan model mendeteksi kasus diabetes secara spesifik
