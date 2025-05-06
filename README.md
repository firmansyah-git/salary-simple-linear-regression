# 🧠 Simple Linear Regression - Salary Prediction
Ini adalah proyek beginner-friendly yang saya buat untuk mempelajari konsep dasar **Regresi Linier** menggunakan dataset yang sangat minimal — hanya terdiri dari **2 kolom** (Tahun Pengalaman & Gaji) dan **39 baris data**. Tujuannya adalah untuk benar-benar memahami cara kerja regresi sebelum lanjut ke model yang lebih kompleks.

# 📂 Dataset
[Salary Dataset - Kaggle](https://www.kaggle.com/datasets/abhishek14398/salary-dataset-simple-linear-regression)  

**Dataset Overview**

| Column | Description|
|--------|------------|
| YearsExperience | Experience in years
| Salary | Salary of the person (USD)

# 🎯 Tujuan Proyek
Mempelajari regresi linier sederhana dengan 1 fitur (YearsExperience) untuk memprediksi Salary, sekaligus:
- Menguji seberapa kuat hubungan linier antar dua variabel
- Melatih model regresi menggunakan scikit-learn
- Mengevaluasi model dengan metrik MSE, RMSE, dan R² Score
- Memperkuat pemahaman dasar tentang machine learning.

# 🛠️ Tools & Library
- Python
- Pandas
- Matplotlib, Seaborn
- scikit-learn

# 📊 Hasil Evaluasi
**Persamaan model:**  
Salary = 9,449.46 x YearsExperience + 24,848.20

- MSE: 31,270,951.72
- RMSE: ±5.59 juta USD
- R² Score: 0.957
- Relative Error: ~8%

Model mampu memprediksi gaji dengan kesalahan rata-rata ±5.6 juta USD, dan menjelaskan ~95.7% variasi data gaji berdasarkan pengalaman kerja.


# 📎 Notebook
Lihat implementasi lengkap di [Notebook](/Salary%20_LinearRegression.ipynb).

## 🔭 Langkah Selanjutnya

Proyek ini adalah tahap awal dari perjalanan belajar saya. Rencana selanjutnya:
- Coba regresi linier multivariat (lebih dari 1 variabel prediktor)
- Gunakan dataset yang lebih besar dan realistis dari Kaggle
- Belajar analisis residual dan validasi model yang lebih mendalam

# 🙋‍♂️ Connect With Me
Hi, I'm Firmansyah — aspiring data analyst with a background in IT and a passion for turning data into business insights. This project is part of my continuous learning journey.

🌐 LinkedIn: https://www.linkedin.com/in/firmansyah-241482344  
📁 Email: firmansyah3034@gmail.com