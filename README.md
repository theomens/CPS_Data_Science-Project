# Data Science Project — BCS 404

Exploratory data analysis, statistical analysis, and machine learning on the
Kaggle Titanic dataset, submitted for **BCS 404: Introduction to Data Science
with Python**, Department of Computer Science, Accra Technical University
(2025/2026, Second Semester, Lecturer: Dr. Joseph Dadzie).

## Project Overview

This project applies the full data science workflow to the Titanic passenger
dataset:

1. **Data Acquisition** — loading and inspecting the dataset.
2. **Data Cleaning** — handling missing values and duplicates.
3. **Data Visualisation** — histogram, bar chart, boxplot, scatter plot,
   correlation heatmap, and pairplot.
4. **Statistical Analysis** — descriptive statistics, frequency distributions,
   and correlation analysis.
5. **Machine Learning** — a Logistic Regression classifier predicting
   passenger survival (≈81.6% test accuracy).
6. **Discussion & Conclusion** — findings, limitations, and recommendations.

## Repository Structure

```
titanic-data-science-project/
├── README.md                      <- this file
├── notebook/
│   └── titanic_analysis.ipynb     <- full Jupyter notebook (all tasks)
├── data/
│   └── titanic.csv                <- Titanic dataset (Kaggle train.csv)
├── report/
│   └── Titanic_Project_Report.pdf <- formal written report (PDF)
└── requirements.txt                <- Python package dependencies
```

## Dataset

The dataset is the Titanic training set (`train.csv`) from Kaggle:
https://www.kaggle.com/competitions/titanic/data

It contains 891 passenger records with demographic and travel details, and a
`Survived` column used as the prediction target.

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/titanic-data-science-project.git
cd titanic-data-science-project
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the notebook
```bash
jupyter notebook notebook/titanic_analysis.ipynb
```

## Key Results

| Metric | Value |
|---|---|
| Model | Logistic Regression |
| Accuracy | 81.6% |
| Strongest positive correlation | SibSp & Parch (r ≈ 0.41) |
| Strongest negative correlation | Pclass & Fare (r ≈ -0.55) |
| Female survival rate | 74.2% |
| Male survival rate | 18.9% |

## Author

- **Name:** _Ramseyer Asuah_
- **Index Number:** _01258065B_
- **Course:** BCS 404 — Introduction to Data Science with Python

## License

This project is submitted for academic purposes as part of the BCS 404
course at Accra Technical University.
