# E-commerce Data Cleaning & EDA

A step-by-step data cleaning and exploratory analysis of a messy e-commerce orders dataset (~15,000 orders, 16 columns), ending with a cleaned dataset ready for analysis.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

## Dataset

Orders with customer age, gender and city, product category, quantity, unit price, discount, payment method, order date, rating, delivery days, return status and total amount.

## Tasks

| Notebook | What it covers |
|---|---|
| `task1.ipynb` | Numerical summary: mean, median, std, range |
| `task2.ipynb` | Categorical summary: unique values and most frequent categories |
| `task3.ipynb` | Value distributions for city, category, payment method and returns |
| `task4.ipynb` | Standardizing inconsistent text labels |
| `tasks_5_6_7.ipynb` | Missing values: detection and median / mode imputation |
| `task8.ipynb` | Outlier detection with boxplots |
| `task9_10.ipynb` | IQR-based outlier bounds and treatment |
| `task11.ipynb` | Validating order totals against price x quantity x discount |
| `remaining_tasks.ipynb` | Final quality check, date parsing and export of the cleaned dataset |

## Files

| File | Description |
|---|---|
| `messy_data.csv` | Raw dataset |
| `cleaned_ecommerce_dataset.csv` | Cleaned output |

## Run

```bash
pip install pandas matplotlib seaborn jupyter
jupyter notebook
```

## Author

**Paramkusam Saketha Sreevatsa** - [GitHub](https://github.com/Klusaketh) · [LinkedIn](https://www.linkedin.com/in/paramkusamsakethasreevatsa)
