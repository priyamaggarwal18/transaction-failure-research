# 💳 Proactive Prediction of UPI Transaction Failure using Machine Learning 🚀

<div>
  <img src="https://img.shields.io/badge/Name-Priyam%20Aggarwal-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Roll%20Number-2210992098-orange?style=for-the-badge">
  <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/priyamaggarwal18/transaction-failure-research?style=for-the-badge&color=green">
  <img alt="Last commit" src="https://img.shields.io/github/last-commit/priyamaggarwal18/transaction-failure-research?style=for-the-badge&color=green">
</div>

<br>

## 📝 Research Overview
This repository contains the implementation and findings of the academic research paper:  
**"PROACTIVE PREDICTION OF UPI TRANSACTION FAILURE USING MACHINE LEARNING ON SYNTHETIC DATA"** *Authored by: Priyam Aggarwal and Dr. Ajay Kumar (Chitkara University)*.

While existing systems detect failures after they occur, this research introduces a **proactive mechanism** to predict the likelihood of a Unified Payments Interface (UPI) transaction failure **before execution**. By analyzing transaction metadata, the system estimates failure probability to improve user experience and reduce system load during peak hours.

---

## 🏗️ Project Architecture
The proposed solution acts as a predictive layer that works alongside existing digital payment systems to analyze details before execution.

* **Data Ingestion Layer:** Processes synthesized transaction datasets (CSV format).
* **Processing Layer:** Handles feature engineering and data cleaning to identify hidden patterns.
* **Model Training Layer:** Utilizes **Random Forest** and **XGBoost** algorithms for high-performance classification.
* **Evaluation Layer:** Measures success through Accuracy, Precision, Recall, and ROC-AUC scores.

---

# 📂 Repository Structure

```
upi-failure-prediction
│
├── data
│   └── transactions.csv
│
├── plots
│   ├── amount_distribution.png
│   ├── amount_vs_status.png
│   ├── correlation_heatmap.png
│   ├── failure_rate_hour.png
│   ├── receiver_bank_distribution.png
│   ├── sender_bank_distribution.png
│   ├── status_distribution.png
│   └── transactions_by_hour.png
│
├── src
│   ├── eda_plots.ipynb
│   └── model_training.ipynb
│
├── README.md
└── requirements.txt
```

---

## 📊 Notebooks & Analysis

### 📈 Exploratory Data Analysis (EDA)
➡️ **[Open EDA Notebook](src/eda_plots.ipynb)** Performs pattern analysis, peak load identification (Hour of Day), and visualizes the impact of sender/receiver banks on transaction success rates.

### 🤖 Machine Learning Model
➡️ **[Open Model Training Notebook](src/model_training.ipynb)** Includes feature engineering (extracting Transaction Hour, Day of Week, and Bank IDs), data preprocessing, and model training using an 80/20 train-test split.

---

## 📂 Dataset
The study utilized a synthetic dataset of **500,000+ transactions** to simulate realistic behavior while ensuring data privacy and ethical compliance.
* **Source:** [Kaggle UPI Payment Dataset](https://www.kaggle.com/datasets/devildyno/upi-payment-transactions-dataset)
* **Repository Link:** [Open Dataset](data/transactions.csv)

---

## 📈 Key Research Findings
* **Peak Load Impact:** Transaction failure rates are significantly higher during peak hours due to server overload.
* **Amount Influence:** Higher transaction amounts correlate with an increased probability of failure.
* **Bank Patterns:** Specific inter-bank routing issues and sender/receiver bank combinations play a critical role in reliability.

---

## ⚙️ Setup & Installation
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/priyamaggarwal18/transaction-failure-research.git](https://github.com/priyamaggarwal18/transaction-failure-research.git)
    ```
2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Run the analysis:** Open the notebooks in `src/` using VS Code or Jupyter.

---

## 🛠️ Technologies Used
* **Python:** Pandas, NumPy, Scikit-learn, XGBoost
* **Visualization:** Matplotlib, Seaborn
* **Tools:** Jupyter Notebook, Git

---

## ⚖️ Ethics & Data Disclaimer
✔ No real financial or user data is used; the project utilizes **synthetic data**.  
✔ Strictly for **academic research purposes**.  

---

# 
<div>
  <img src="https://contrib.rocks/image?repo=priyamaggarwal18/Game_Hub1" alt="Contributions" align="left">
  <h3 align="left">Maintained By - Priyam Aggarwal</h3>
    <a href="https://itspriyam.vercel.app" target="_blank" style="text-decoration: none;">
    <img src="https://img.shields.io/badge/Portfolio-%23000000.svg?style=for-the-badge&logo=web&logoColor=white" alt="Portfolio">
  </a>&nbsp;&nbsp;
  <a href="https://www.linkedin.com/in/priyamaggarwal" target="_blank" style="text-decoration: none;">
  <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>&nbsp;&nbsp;
</div>
