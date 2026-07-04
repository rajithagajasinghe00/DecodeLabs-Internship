[README.md](https://github.com/user-attachments/files/29656110/README.md)
# Data Analytics Projects

Three beginner data analytics projects, each built around the same orders
dataset, done in Python using Google Colab.

**Replace `yourusername` in every link below with your actual GitHub username
once you've uploaded everything.**

| # | Project | Skills | Open in Colab |
|---|---------|--------|----------------|
| 1 | [Data Cleaning](./project-1-data-cleaning) | missing values, duplicates, formatting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/rajithagajasinghe00/DecodeLabs-Internship/blob/main/project-1-data-cleaning/project1_data_cleaning.ipynb) |
| 2 | [Exploratory Data Analysis](./project-2-eda) | statistics, outliers, charts | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rajithagajasinghe00/data-analytics-projects/blob/main/project-2-eda/project2_eda.ipynb](https://colab.research.google.com/drive/1y3XLHfyApjRtMGF6tWlbQS8uDRS41aPg)) |
| 3 | [SQL Data Analysis](./project-3-sql-analysis) | SELECT, WHERE, GROUP BY, HAVING | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rajithagajasinghe00/data-analytics-projects/blob/main/project-3-sql-analysis/project3_sql_analysis.ipynb) |

Click any **"Open in Colab"** badge above to run that project directly in
your browser — no installation needed.

---

## Repository structure

```
data-analytics-projects/
├── project-1-data-cleaning/
│   ├── project1_data_cleaning.ipynb
│   └── README.md
├── project-2-eda/
│   ├── project2_eda.ipynb
│   └── README.md
├── project-3-sql-analysis/
│   ├── project3_sql_analysis.ipynb
│   └── README.md
└── README.md   (this file)
```

## How to run any project

1. Click its **Open in Colab** badge (or the notebook file, then the
   "Open in Colab" button GitHub shows above the preview)
2. Run the first cell — it will ask you to upload a CSV file
3. Run the remaining cells one by one (Shift+Enter)

Each notebook works with any orders-style CSV — column names used in the
examples (`Product`, `TotalPrice`, `OrderID`, etc.) may need to be swapped
for your own dataset's column names, and each notebook says so at the
relevant step.

## About the dataset

An e-commerce orders dataset — one row per order, with columns like
`OrderID`, `Date`, `Product`, `Quantity`, `UnitPrice`, `TotalPrice`,
`PaymentMethod`, `OrderStatus`, and `ReferralSource`.

## Suggested order

Run them in sequence — Project 1's cleaned output is a good input for
Project 2 and 3, though each notebook can also be run on its own.
