# DBS_DataScience

# 🍳 OLAH – Ingredient-Based Recipe Recommendation System

## 📌 Project Overview

OLAH adalah aplikasi berbasis data science yang bertujuan untuk membantu pengguna menemukan resep masakan berdasarkan bahan yang tersedia di rumah. Proyek ini dikembangkan sebagai solusi untuk mengurangi **food waste** dengan memanfaatkan bahan makanan secara optimal.

Sistem ini menggunakan pendekatan **content-based filtering** untuk merekomendasikan resep yang relevan berdasarkan input bahan dari pengguna.

---

## 🎯 Problem Statement

Pemborosan makanan (food waste) masih menjadi permasalahan besar, terutama di tingkat rumah tangga. Banyak bahan makanan yang terbuang karena kurangnya ide dalam mengolahnya menjadi masakan.

Beberapa pertanyaan utama dalam proyek ini:

* Bagaimana merekomendasikan resep berdasarkan bahan yang tersedia?
* Bahan apa yang paling fleksibel digunakan dalam berbagai resep?
* Bagaimana sistem ini dapat membantu mengurangi food waste?

---

## 💡 Proposed Solution

Membangun sistem rekomendasi resep berbasis bahan menggunakan pendekatan:

* Content-Based Filtering
* Similarity Measurement (Cosine Similarity)

Fitur utama:

* Input bahan oleh pengguna
* Rekomendasi resep paling relevan
* Dashboard insight bahan & resep

---

## 📊 Dataset

Dataset yang digunakan berasal dari platform publik (Kaggle) yang berisi:

* Nama resep
* Daftar bahan
* Kategori masakan

Tahapan pengolahan data:

* Data Gathering
* Data Assessing
* Data Cleaning (normalisasi bahan, handling missing value)

---

## 🧪 Exploratory Data Analysis (EDA)

Beberapa analisis yang dilakukan:

* Distribusi jumlah bahan per resep
* Bahan yang paling sering digunakan
* Pola kombinasi bahan

Contoh insight:

* Bahan seperti telur, bawang, dan minyak merupakan bahan paling fleksibel
* Sebagian besar resep hanya membutuhkan < 5 bahan

---

## ⚙️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* TensorFlow (opsional untuk pengembangan lanjutan)
* Streamlit (dashboard)
* Matplotlib / Seaborn (visualisasi)

---

## 🤖 Modeling

Model yang digunakan:

* Content-Based Filtering
* Cosine Similarity untuk mengukur kemiripan antar resep

Output:

* Top-N rekomendasi resep berdasarkan input bahan pengguna

---

## 📈 Results & Evaluation

Model mampu memberikan rekomendasi resep yang relevan berdasarkan bahan yang dimasukkan pengguna.

Evaluasi dilakukan dengan:

* Similarity score
* Relevansi hasil rekomendasi

---

## 🖥️ Dashboard (Streamlit)

Dashboard interaktif dibuat menggunakan Streamlit dengan fitur:

* Input bahan
* Rekomendasi resep
* Visualisasi insight data

Untuk menjalankan:

```bash
streamlit run app/streamlit_app.py
```

---

## 📂 Project Structure

```
olah-recipe-recommendation/
│
├── data/
│   ├── raw/
│   ├── processed/
│
├── notebooks/
│   ├── 1_data_cleaning.ipynb
│   ├── 2_eda.ipynb
│   ├── 3_modeling.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── model.py
│   ├── recommend.py
│
├── outputs/
│
├── app/
│   └── streamlit_app.py
│
└── README.md
```

---

## 🚀 How to Run

1. Clone repository

```bash
git clone https://github.com/username/olah-recipe-recommendation.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Run notebook atau dashboard

```bash
jupyter notebook
```

atau

```bash
streamlit run app/streamlit_app.py
```

---

## 🌱 Impact

Proyek ini diharapkan dapat:

* Membantu pengguna mengurangi pemborosan makanan
* Memberikan rekomendasi masakan yang praktis
* Mendukung gaya hidup sustainable living

---

## 👥 Team

* Data Scientist
* AI Engineer
* Fullstack Developer

---

## 📌 Future Improvements

* Integrasi NLP untuk memahami input bahan lebih fleksibel
* Penambahan fitur substitusi bahan
* Integrasi dengan database real-time
* Mobile app version

---

## ⭐ Acknowledgements

* Kaggle (dataset)
* Open-source community
* Coding Camp 2026 powered by DBS Foundation

---
