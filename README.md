# 🚚 Supply Chain Delivery Performance Analysis

📊 Data Analyst Portfolio Project
🎯 Fokus: Optimasi performa pengiriman & profitabilitas bisnis

---

## 📌 Project Overview

Project ini menganalisis performa pengiriman pada perusahaan e-commerce global untuk mengidentifikasi penyebab utama keterlambatan dan dampaknya terhadap profit.

---

## 🚨 Business Problem

Lebih dari **50% pengiriman mengalami keterlambatan**, yang menyebabkan:

* Penurunan kepuasan pelanggan
* Risiko kehilangan profit
* Ketidakakuratan estimasi pengiriman

👉 Masalah bersifat **sistemik**, bukan kasus individual

---

## 🎯 Objectives

* Menganalisis performa pengiriman end-to-end
* Mengukur dampak finansial keterlambatan
* Mengidentifikasi bottleneck operasional
* Membangun model prediksi keterlambatan
* Memberikan rekomendasi strategis

---

## 📊 Key Insights

| Metric             | Value      |
| ------------------ | ---------- |
| Total Orders       | 172,765    |
| Late Delivery Rate | **54.71%** |
| On-Time Delivery   | 45.29%     |
| Total Profit       | $7.5M      |
| Profit at Risk     | $2.1M      |
| Model Accuracy     | 74%        |

---

## 📁 Dataset

Dataset yang digunakan adalah **DataCo Supply Chain Dataset**.

### 🔗 Full Dataset

👉 [Download Dataset](https://drive.google.com/file/d/14SeeHaRiTcMYMRYMXSgY9IDHjc_MAE7N/view?usp=sharing)

> ⚠️ Dataset tidak disimpan di GitHub karena ukuran file besar (>100MB)

---

### ▶️ Load Data

```python
import pandas as pd

url = "https://drive.google.com/uc?id=14SeeHaRiTcMYMRYMXSgY9IDHjc_MAE7N"
df = pd.read_csv(url, encoding='latin-1')
```

---

## ⚙️ Data Processing

* Data Cleaning (hapus kolom tidak relevan)
* Feature Engineering:

  * Order Processing Time
  * Delay
  * Is_Delayed
  * Time Features
  * Profitability Flag

---

## 📊 Analysis

### 🔹 Delay Distribution

Sebagian besar keterlambatan terjadi pada 1–4 hari → menunjukkan masalah operasional sistemik.

### 🔹 Profit Analysis

Profit per order stabil, namun volume order terlambat menyebabkan penurunan profit secara signifikan.

### 🔹 Bottleneck Analysis

Faktor utama:

* 🚨 Shipping Mode (paling dominan)
* Region relatif merata
* Customer segment tidak signifikan

---

## 🤖 Machine Learning

Model yang digunakan:

* Random Forest Classifier
* SMOTE untuk handling imbalance

📈 Hasil:

* Accuracy: **74%**
* Precision tinggi untuk late orders
* Recall: 75%

👉 Model dapat digunakan sebagai **early warning system**

---

## 💡 Business Recommendations

### 🔴 Critical

* Audit First & Second Class shipping
* Deploy predictive alert system

### 🟡 High

* Perbaiki proses pembayaran
* Optimasi kapasitas peak season

### 🟢 Medium

* Gunakan Standard Class sebagai default
* Audit department delay tinggi

---

## 📸 Visualization

Tambahkan screenshot dari notebook kamu di sini 👇

```
images/dashboard.png
```

---

## 🛠️ Tools & Technologies

* Python (Pandas, NumPy)
* Data Visualization (Matplotlib, Seaborn)
* Machine Learning (Scikit-learn, SMOTE)
* Google Colab

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
```

Buka notebook:

```bash
jupyter notebook
```

---

## 👨‍💻 Author

Project ini dibuat untuk portfolio Data Analyst & persiapan ujian BNSP.
