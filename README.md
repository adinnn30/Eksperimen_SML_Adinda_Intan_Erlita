# Eksperimen_SML_Adinda_Intan_Erlita

# 📊 Eksperimen SML - Analisis Sentimen Review Marketplace

## 📌 Deskripsi Proyek

Proyek ini merupakan bagian dari tugas *Eksperimen Machine Learning* yang bertujuan untuk melakukan analisis sentimen terhadap ulasan produk marketplace Indonesia.

Dataset yang digunakan berisi teks review dan label sentimen, yang kemudian diproses dan digunakan untuk melatih model machine learning.

---

## 🎯 Tujuan

* Melakukan preprocessing data teks secara otomatis
* Membangun model klasifikasi sentimen
* Melakukan hyperparameter tuning
* Melacak eksperimen menggunakan MLflow
* Menyimpan hasil eksperimen secara online melalui DagsHub

---

## 📂 Struktur Repository

```
Eksperimen_SML_Adinda_Intan_Erlita/
│
├── Indonesian-Marketplace-Product-Reviews_raw/
│   └── reviews.csv
│
├── preprocessing/
│   ├── automate-Adinda-Intan-Erlita.py
│   ├── Eksperimen_Adinda-Intan-Erlita.ipynb
│   └── Indonesian-Marketplace-Product-Reviews_preprocessing/
│       └── reviews_cleaned.csv
│
├── Membangun_model/
│   ├── modelling.py
│   ├── modelling_tuning.py
│   ├── namadataset_preprocessing/
│   │   └── reviews_cleaned.csv
│   ├── requirements.txt
│   └── (artifact & screenshot)
│
└── .github/
    └── workflows/
        └── automate.yml
```

---

## ⚙️ Tahapan Proyek

### 1. Data Preparation

* Load dataset
* Exploratory Data Analysis (EDA)
* Cleaning text (lowercase, remove punctuation, dll)
* Label encoding

### 2. Automation Preprocessing

* Script Python untuk preprocessing otomatis
* Menghasilkan dataset bersih (`reviews_cleaned.csv`)

### 3. Modeling

* TF-IDF Vectorization
* Random Forest Classifier
* Train-test split

### 4. Hyperparameter Tuning

* Menggunakan GridSearchCV
* Parameter tuning:

  * n_estimators
  * max_depth

### 5. Experiment Tracking

* Menggunakan MLflow
* Logging:

  * Parameter
  * Metrics (accuracy, dll)
  * Model
  * Artifact (confusion matrix, dataset)

### 6. Deployment Tracking (Advanced)

* Integrasi dengan DagsHub
* Menyimpan hasil eksperimen secara online

---

## 📈 Hasil Model

* Model: Random Forest
* Accuracy: ~0.89
* Evaluasi menggunakan confusion matrix

---

## 🔗 MLflow Tracking (DagsHub)

👉 Link eksperimen:
https://dagshub.com/adinnn30/Eksperimen_SML_Adinda_Intan_Erlita.mlflow

---

## 🚀 Cara Menjalankan

### 1. Install dependencies

```
pip install -r requirements.txt
```

### 2. Jalankan preprocessing

```
python preprocessing/automate-Adinda-Intan-Erlita.py
```

### 3. Jalankan modeling

```
python Membangun_model/modelling_tuning.py
```

---

## 🛠 Tools & Library

* Python
* Pandas
* Scikit-learn
* MLflow
* DagsHub
* Matplotlib

---

## ✨ Catatan

Proyek ini dibuat untuk memenuhi kriteria:

* ✔ Basic
* ✔ Skilled
* ✔ Advanced (MLflow + DagsHub)

---

## 👩‍💻 Author

Adinda Intan Erlita
