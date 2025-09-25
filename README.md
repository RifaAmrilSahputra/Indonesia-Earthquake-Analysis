# Indonesia-Earthquake-Analysis

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk melakukan **analisis gempa bumi di Indonesia** menggunakan dataset BMKG dan USGS. Analisis meliputi:

- Analisis temporal (tren gempa per tahun/bulan)
- Analisis spasial (peta sebaran gempa)
- Analisis magnitudo dan kedalaman
- Clustering wilayah rawan gempa
- Visualisasi interaktif dengan Plotly

Data ini dapat digunakan untuk studi risiko gempa, mitigasi bencana, dan latihan predictive modeling probabilistik.

---

## 📂 Dataset
Dataset yang digunakan:

1. **BMKG Lama**: `katalog_gempa.csv` (1 Nov 2008 – 26 Jan 2023)  
   - Kolom: `tgl`, `ot`, `lat`, `lon`, `depth`, `mag`, `remark`, focal mechanism (jika ada)  

2. **BMKG Baru**: `katalog_gempa_v2.tsv` (1 Nov 2008 – 20 Sep 2025)  
   - Lebih lengkap, 37 variabel termasuk data focal mechanism  

3. **USGS**: SQLite, 1900–2025, disimpan dalam format GeoJSON

Dataset dapat diakses di [Kaggle](https://www.kaggle.com/datasets/kekavigi/earthquakes-in-indonesia) dan source code raw data di [GitHub kekavigi](https://github.com/kekavigi/repo-gempa)

---

## 🛠 Teknologi
- Python 3.x
- Pandas & NumPy → manipulasi data
- Matplotlib & Seaborn → visualisasi dasar
- Plotly → peta interaktif dan visualisasi interaktif
- Scikit-learn → clustering (KMeans)
- Jupyter Notebook / VSCode

---

## 📊 Analisis yang Dilakukan
1. **Exploratory Data Analysis (EDA)**  
   - Tren gempa per tahun/bulan  
   - Distribusi magnitudo dan kedalaman  

2. **Visualisasi Spasial**  
   - Scatter map gempa di Indonesia  
   - Heatmap intensitas gempa  

3. **Clustering Wilayah**  
   - Identifikasi wilayah rawan gempa menggunakan KMeans  

---
