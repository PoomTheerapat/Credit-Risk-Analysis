# Credit Risk Analysis Project

โปรเจกต์นี้เป็นการวิเคราะห์ความเสี่ยงด้านสินเชื่อ (Credit Risk Analysis) และการพัฒนาแบบจำลองคะแนนเครดิต (Credit Scoring / Scorecard Model) โดยใช้ข้อมูลลูกค้าและเทคนิคทางสถิติและ Machine Learning เพื่อช่วยในการตัดสินใจอนุมัติสินเชื่อ

โดยใช้ข้อมูลจาก simulating credit bureau data

ที่มาของข้อมูล https://www.kaggle.com/datasets/laotse/credit-risk-dataset

---

## 📌 Project Objectives
- วิเคราะห์พฤติกรรมและความเสี่ยงของลูกหนี้
- สร้าง Credit Scoring Model เพื่อทำนายโอกาสผิดนัดชำระหนี้
- แปลงโมเดลเป็น Scorecard ที่สามารถใช้งานเชิงธุรกิจได้
- ประเมินประสิทธิภาพของโมเดลด้วยตัวชี้วัดมาตรฐาน

---

## 📂 Project Structure
```text
.
├── data/
│   ├── raw/                # ข้อมูลดิบ
│   └── processed/          # ข้อมูลหลังทำความสะอาด
├── notebooks/
│   ├── 01_eda.ipynb        # Exploratory Data Analysis
│   ├── 02_feature.ipynb    # Feature Engineering & Binning
│   ├── 03_model.ipynb      # Model Training
│   └── 04_scorecard.ipynb  # Scorecard Development
├── models/
│   └── credit_model.pkl
├── reports/
│   └── project_summary.pdf
├── requirements.txt
└── README.md
```
## 🔍 Methodology

- Data Preparation

- Data Cleaning

- Missing Value Handling

- Outlier Detection

- Exploratory Data Analysis (EDA)

- Distribution Analysis

- Default Rate Analysis

- Correlation Analysis

- Feature Engineering

- Binning (Manual / Quantile / WOE)

- Weight of Evidence (WOE)

- Information Value (IV)

- Modeling

- Logistic Regression

- Model Selection & Tuning

- Model Evaluation

- KS Statistic

- Scorecard Development



## 📊 Tools & Technologies

- Python

- Pandas / NumPy

- Scikit-learn

- Matplotlib / Seaborn

- Jupyter Notebook