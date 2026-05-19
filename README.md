# Heart Disease Prediction with Ensemble SVM

## Deskripsi
Penelitian ini merupakan implementasi machine learning untuk prediksi penyakit jantung menggunakan metode Ensemble Support Vector Machine (Ensemble SVM).

Model dibangun menggunakan kombinasi kernel:
- Sigmoid (Base Learner)
- RBF (Base Learner)
- Polynomial (Meta Learner)

## Dataset
Dataset yang digunakan:
- Cardiovascular Disease Dataset

## Library
Beberapa library yang digunakan:
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Tahapan Penelitian
1. Load Dataset
2. Exploratory Data Analysis (EDA)
3. Preprocessing
4. Training Model SVM
5. Ensemble SVM dengan Stacking
6. Evaluasi Model
7. Prediksi Penyakit Jantung

## Hasil
Model mampu memprediksi pasien yang terindikasi penyakit jantung maupun tidak berdasarkan data kesehatan pasien.

Contoh output:
```python
Prediksi untuk pasien 1:
Pasien positif menderita penyakit jantung.

Prediksi untuk pasien 2:
Pasien tidak menderita penyakit jantung.
```

## Cara Menjalankan
Install library:
```bash
pip install -r requirements.txt
```

Jalankan notebook:
```bash
jupyter notebook
```

## Author
Ammara Desma Marzooqa
