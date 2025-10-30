# Fraud Detection Using Machine Learning

[![Python](https://img.shields.io/badge/python-3.10-blue)](https://www.python.org/)  
[![Scikit-Learn](https://img.shields.io/badge/scikit--learn-1.2.2-orange)](https://scikit-learn.org/)

Detect fraudulent transactions using machine learning models on real-world transactional data.

---

## 📂 Dataset

The dataset contains **transaction records** with features such as merchant, category, job, location, and transaction details.  

Files:

- `fraudTrain.csv` – Training data
- `fraudTest.csv` – Test data

**Key Columns:**

| Column | Description |
|--------|-------------|
| trans_num | Transaction ID |
| trans_date_trans_time | Transaction timestamp |
| category | Transaction category |
| merchant | Merchant name |
| street, city, state | Location details |
| job | Cardholder’s job |
| dob, first, last, gender | Cardholder demographics |
| is_fraud | Target variable (0 = Not Fraud, 1 = Fraud) |

---

## ⚡ Features

- Random Forest Classifier  
- Decision Tree Classifier
- Xg Boost Classifier 
- Data preprocessing with Label Encoding  
- Evaluation using Accuracy, Confusion Matrix, F1-score  

---

## 🔧 Installation

```bash
git clone <repo_url>
cd fraud-detection
pip install -r requirements.txt
