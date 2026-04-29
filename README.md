# Supply Chain Delivery Performance Analysis

<p align="center">
  <b>Data Analyst Portfolio Project</b><br>
   Analyzing Delivery Delays & Profit Impact in Supply Chain Operations
</p>

---

##  Project Highlights

*  **172K+ Orders Analyzed**
*  **54%+ Late Deliveries Identified**
*  **$7M+ Total Profit Evaluated**
*  **$2M+ Profit at Risk Detected**
*  **Machine Learning Model (74% Accuracy)**

---

##  Business Problem

Lebih dari **50% pengiriman mengalami keterlambatan**, yang menyebabkan:

* ❌ Penurunan kepuasan pelanggan
* ❌ Risiko kehilangan profit
* ❌ Ketidakakuratan estimasi pengiriman

> 🔎 Masalah ini bersifat **operasional dan sistemik**, bukan kejadian individual.

---

##  Objectives

✔ Menganalisis performa pengiriman
✔ Mengukur dampak finansial keterlambatan
✔ Mengidentifikasi bottleneck utama
✔ Membangun model prediksi keterlambatan
✔ Memberikan rekomendasi bisnis

---

##  Key Metrics

| Metric                   | Value |
| ------------------------ | ----- |
|  Total Orders          | 172K+ |
|  Late Delivery Rate    | 54%+  |
|  Total Profit          | $7M+  |
|  Profit at Risk        | $2M+  |
|  Loss (Delayed Orders) | $2M+  |
|  Model Accuracy        | 74%   |

---

## 📁 Dataset

Dataset yang digunakan adalah **DataCo Supply Chain Dataset**

🔗 Download:
https://drive.google.com/file/d/14SeeHaRiTcMYMRYMXSgY9IDHjc_MAE7N/view?usp=sharing

> ⚠️ Dataset tidak di-upload ke GitHub karena ukuran file besar (>100MB)

---

## ⚙️ Data Processing

✔ Data Cleaning (remove irrelevant columns)
✔ Remove cancelled shipments
✔ Datetime transformation
✔ Feature Engineering:

* Delay Calculation
* Delivery Classification
* Time-based Features
* Profit Categorization

---

## 📊 Analysis & Insights

### 🔹 Delay Distribution

Mayoritas keterlambatan terjadi pada **1–4 hari** → menunjukkan bottleneck operasional.

### 🔹 Profit Impact

Meskipun profit per order stabil, volume keterlambatan tinggi menyebabkan penurunan total profit.

### 🔹 Bottleneck Analysis

Faktor utama:

*  Shipping Mode (critical factor)
*  Region relatif merata
*  Customer segment tidak signifikan

---

##  Machine Learning

Model:

* Random Forest Classifier
* SMOTE (Handling Imbalanced Data)

Result:
* Accuracy: **74%**
* Effective for identifying high-risk delayed orders

---

##  Dashboard Preview

<p align="center">
  <img src="images/dashboard.png" width="800">
</p>

---

## Business Recommendations

### 🔴 Critical

* Audit shipping methods (First & Second Class)
* Implement predictive alert system

### 🟡 High

* Optimize peak season capacity
* Improve operational workflows

### 🟢 Medium

* Standardize shipping strategy
* Continuous monitoring using dashboard

---

## 🛠️ Tech Stack

<p>
Python • Pandas • NumPy • Scikit-learn • SMOTE • Tableau • Matplotlib • Seaborn
</p>

---

## 📂 Project Structure

```bash
Supply-Chain-Delivery-Performance/
│
├── notebooks/
│   └── SupplyChain.ipynb
│
├── dashboard/
│   └── supply-chain-dashboard.twbx
│
├── images/
│   └── dashboard.png
│
└── README.md
```

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
```

```bash
jupyter notebook
```

---

## 👨‍💻 Author

Portfolio Project — Data Analyst (BNSP Preparation)

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
