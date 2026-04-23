# supply-chain-analyst  
![Banner](images/dashboard.png)
# 🚚 Supply Chain Delivery Performance Analysis

## 📌 Project Overview

Project ini bertujuan untuk menganalisis performa pengiriman pada perusahaan e-commerce global dan mengidentifikasi penyebab utama keterlambatan serta dampaknya terhadap profitabilitas bisnis.

---

## 🚨 Business Problem

Lebih dari **50% pengiriman mengalami keterlambatan**, yang menyebabkan:

* Penurunan kepuasan pelanggan
* Kerugian profit signifikan
* Ketidakakuratan estimasi pengiriman

---

## 🎯 Objectives

* Menganalisis performa pengiriman end-to-end
* Mengukur dampak finansial keterlambatan
* Mengidentifikasi bottleneck operasional
* Membangun model prediksi keterlambatan
* Memberikan rekomendasi strategis berbasis data

---

## 📊 Key Insights

* 📦 Total Orders: 172,765
* ⏱️ Late Delivery Rate: **54.71%**
* 💰 Profit at Risk: **$2.1 Million**
* 🤖 Model Accuracy: **74% (Random Forest)**

---

## 🔍 Key Findings

### 1. Massive Delay Issue

Sebagian besar pesanan mengalami keterlambatan → ini bukan kasus minor, tapi masalah sistemik.

### 2. Shipping Mode = Faktor Utama

* First Class: 100% delay ❌
* Second Class: 79.8% delay ❌
* Standard Class: paling stabil ✅

### 3. Profit Dipengaruhi Volume Delay

Bukan nilai order, tapi jumlah order terlambat yang jadi masalah utama.

---

## 📈 Machine Learning Model

Model yang digunakan:

* Random Forest Classifier
* SMOTE untuk handling imbalance

Hasil:

* Accuracy: 74%
* Precision (Late): 78%
* Recall (Late): 75%

---

## 🧠 Business Recommendations

### 🔴 Critical

* Audit shipping mode (First & Second Class)
* Implement predictive alert system

### 🟡 Medium

* Optimasi kapasitas saat peak season
* Perbaiki proses pembayaran

### 🟢 Low

* Retrain model secara berkala
* Optimasi pricing untuk order rugi

---

## 🛠️ Tools & Technologies

* Python (Pandas, Scikit-learn)
* Machine Learning (Random Forest, SMOTE)
* Data Visualization (Matplotlib, Seaborn)
* Jupyter Notebook / Google Colab

---

## 📸 Project Preview

Tambahkan screenshot dashboard di sini 👇
(Upload ke folder images)

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

## 📁 Dataset

Dataset: DataCo Supply Chain Dataset



---

## 👨‍💻 Author

Project ini dibuat untuk portofolio Data Analyst & persiapan ujian BNSP.

---
