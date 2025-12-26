# Credit Risk Analysis Project

โปรเจกต์นี้เป็น workshop การวิเคราะห์ความเสี่ยงด้านสินเชื่อ (Credit Risk Analysis) และการพัฒนาแบบจำลองคะแนนเครดิต (Credit Scoring / Scorecard Model) โดยใช้ข้อมูลลูกค้าและเทคนิคทางสถิติเพื่อศึกษาวิเคราะห์ถึงปัจจัยต่อการผิดนัดชำระหนี้ จากตัวแปร Demographic Data ในด้านต่างๆ อาทิเช่น อายุ, รายได้, การถือครองที่อยู่อาศัย, อายุงาน, ดอกเบี้ย, ยิดสินเชื่อ, และอื่นๆ ผ่านเครื่องมือ python Jupyterlab ในการวิเคราะห์

โดยใช้ข้อมูลจาก simulating credit bureau data

ที่มาของข้อมูล https://www.kaggle.com/datasets/laotse/credit-risk-dataset

---

## 📌 Project Objectives
- วิเคราะห์พฤติกรรมและความเสี่ยงของลูกหนี้จากปัจจัยแวดล้อมที่มี
- สร้าง Credit Scoring Model เพื่อทำนายโอกาสผิดนัดชำระหนี้
- แปลงโมเดลเป็น Scorecard ที่สามารถใช้งานได้คร่าวๆ
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
