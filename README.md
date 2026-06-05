# 📊 Task 5: Survival Analysis: Titanic EDA using Python

## 📌 Objective
Perform Exploratory Data Analysis on the Titanic dataset to extract
insights using visual and statistical exploration with Python.

---

## 📂 Dataset
- **Name:** Titanic Dataset
- **Source:** [Kaggle](https://www.kaggle.com/competitions/titanic)
- **Size:** 891 rows × 12 columns

---

## 🛠️ Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📋 Dataset Columns
| Column | Description |
|--------|-------------|
| PassengerId | Unique passenger ID |
| Survived | 0 = Died, 1 = Survived |
| Pclass | Ticket class (1st, 2nd, 3rd) |
| Name | Passenger name |
| Sex | Gender of passenger |
| Age | Age of passenger |
| SibSp | No. of siblings/spouses aboard |
| Parch | No. of parents/children aboard |
| Ticket | Ticket number |
| Fare | Ticket fare paid |
| Cabin | Cabin number |
| Embarked | Port of embarkation (S/C/Q) |

---

## 📊 Analysis Performed
| Type | Details |
|------|---------|
| Univariate | Survival Count, Age Distribution, Passenger Class Distribution |
| Bivariate | Survival by Gender, Survival by Class, Age vs Survival, Fare vs Survival |
| Multivariate | Correlation Heatmap, Pairplot |

---

## 📈 Key Stats
| Metric | Value |
|--------|-------|
| Total Passengers | 891 |
| Survived | 342 (38%) |
| Died | 549 (62%) |
| Missing Age Values | 177 (filled with median) |
| Missing Cabin Values | 687 (dropped) |

---

## 🔍 Key Findings
1. Only **38% of passengers survived** — majority died
2. **Gender** was the strongest survival factor — females survived at a much higher rate
3. **1st class passengers** had the best survival rate, 3rd class the worst
4. **Higher fare** strongly correlated with better survival chances
5. **Age** was not a major differentiator — both groups had similar median ages
6. Most passengers were aged between **20-35 years**
7. **3rd class** had the most passengers but the worst survival outcome

---

## 📁 Repository Structure
```
elevate-labs-task5/
├── CODE/
│   └── task5.ipynb
├── DATASET/
│   └── train.csv
├── PDF/
│   └── report.pdf
└── README.md
```

---

## ✅ Result
A complete EDA on the Titanic dataset with 9 visualizations covering
univariate, bivariate and multivariate analysis with detailed observations
and summary of findings.

---
