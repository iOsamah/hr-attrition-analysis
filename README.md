# 👥 IBM HR Employee Attrition Analysis

![Python](https://img.shields.io/badge/Python-3.10+-1F3864?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C)
![License](https://img.shields.io/badge/License-MIT-green)

Exploratory analysis of **1,470 employees** to identify what drives attrition — **16.1% overall rate (237 employees)** — with actionable HR recommendations.

![HR Attrition Dashboard](hr_attrition_analysis.png)

## 🎯 Business Question
Which employees are most at risk of leaving, and what can HR change to retain them?

## 🔍 Key Insights
| Driver | Higher attrition | Lower attrition |
|--------|-----------------|-----------------|
| **Overtime** (strongest) | With overtime **30.5%** | Without **10.4%** |
| **Job role** | Sales Representatives **39.8%** | Research Directors **2.5%** |
| **Business travel** | Frequent travelers **24.9%** | Non-travelers **8.0%** |
| **Work-life balance** | Low **31.2%** | High **14.2%** |
| **Monthly income** | Leavers avg **$4,787** | Stayers avg **$6,833** |
| **Age & tenure** | Leavers: **33.6** yrs old, **5.1** yrs tenure | Stayers: **37.6** yrs old, **7.4** yrs tenure |

## 💡 Recommendations
1. **Reduce mandatory overtime**, especially in Sales and Lab roles.
2. **Review compensation** for high-risk roles such as Sales Representatives.
3. **Introduce flexible travel policies** for frequent travelers.
4. **Run work-life balance programs** targeting younger employees.
5. **Build early-career development paths** to retain junior staff.

## 🛠️ Process
1. **Import** — 1,470 records × 35 columns
2. **Cleaning** — removed constant columns, added readable satisfaction labels, saved a clean dataset
3. **Analysis** — attrition rates by department, role, overtime, travel, income, and demographics
4. **Visualization** — nine-panel dashboard of all key drivers
5. **Report** — written summary of findings and recommendations

## 📁 Project Structure
```
├── data/
│   ├── hr_raw.csv              # original dataset (unmodified)
│   └── hr_clean.csv            # cleaned & enriched dataset
├── hr_analysis.ipynb           # full analysis notebook
├── hr_attrition_analysis.png   # nine-panel dashboard
├── hr_attrition_report.txt     # written findings & recommendations
└── requirements.txt
```

## ▶️ How to Run
```bash
git clone https://github.com/iOsamah/hr-attrition-analysis.git
cd hr-attrition-analysis
pip install -r requirements.txt
jupyter notebook hr_analysis.ipynb
```

## 📊 Dataset
[IBM HR Analytics Employee Attrition & Performance](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset) — fictional dataset created by IBM data scientists.

---

**Osama Dhifallah Hamdi** · [LinkedIn](https://linkedin.com/in/osama0hamdi) · [GitHub](https://github.com/iOsamah)
