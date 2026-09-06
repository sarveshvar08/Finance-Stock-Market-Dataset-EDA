# 📊 Finance Stock Market Dataset — Exploratory Data Analysis

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a real-world financial securities metadata dataset.

The main objective is to understand the structure, composition, and data quality of financial securities using Python, Pandas, NumPy, Matplotlib, and Seaborn.

> **Note:** This dataset contains security-symbol metadata rather than historical stock prices. It does not contain Date, Open, High, Low, Close, or Volume data. Therefore, this project focuses on securities metadata rather than stock-price or time-series analysis.

---

## 🎯 Central Analytical Question

**What is the composition of the financial securities in this dataset in terms of listing exchange, market category, ETF status, and other security attributes, and what data-quality patterns can we identify?**

---

## 📂 Dataset

The dataset contains:

- **8,049 records**
- **12 columns**

### Important Columns

| Column | Description |
|---|---|
| `Symbol` | Security ticker/symbol |
| `Security Name` | Name or description of the security |
| `Listing Exchange` | Exchange associated with the security |
| `Market Category` | Market-category code |
| `ETF` | Indicates whether the security is an ETF |
| `Round Lot Size` | Standard round-lot quantity |
| `Test Issue` | Test-issue status |
| `Financial Status` | Financial-status information |
| `CQS Symbol` | CQS symbol |
| `NASDAQ Symbol` | NASDAQ symbol |
| `NextShares` | NextShares indicator |
| `Nasdaq Traded` | Indicates whether the security is Nasdaq traded |

---

## 🔍 What This Project Covers

### 1. Dataset Understanding
- Loading the dataset
- Displaying the first few records
- Checking dataset dimensions
- Understanding column names and data types
- Classifying variables as numerical, categorical, binary, or identifier/text

### 2. Data Quality Analysis
- Missing-value analysis
- Missing-value percentages
- Duplicate-row detection
- Duplicate-symbol detection
- Unique-value analysis
- Numerical statistical summaries

### 3. NumPy Demonstrations

The project demonstrates:

- Array creation
- `np.array()`
- `np.zeros()`
- `np.ones()`
- `np.arange()`
- `np.linspace()`
- Array properties
- Indexing and slicing
- Reshaping
- Flattening
- Ravel
- Transpose
- Vectorization
- Broadcasting
- Aggregation
- Boolean indexing
- Fancy indexing
- Reproducible random-number generation

A fixed random seed (`42`) is used where random values are demonstrated.

---

## 📈 Visualizations

The project includes visualizations for:

### Listing Exchange Distribution

Shows how securities are distributed across different listing-exchange codes.

### ETF vs Non-ETF

Compares the number of securities marked as ETFs with those that are not.

### Market Category Distribution

Shows the frequency of different market-category codes.

### Round Lot Size Distribution

Examines the numerical `Round Lot Size` variable.

---

## 💡 Key Findings

The analysis found that:

1. The dataset contains **8,049 securities and 12 columns**.
2. Most variables are categorical or identifier/text fields.
3. `Round Lot Size` is the main numerical variable.
4. Listing exchanges have different numbers of securities.
5. ETF and non-ETF securities are distributed differently.
6. Market-category frequencies are not uniform.
7. Missing values occur in selected metadata fields, particularly `Financial Status` and `CQS Symbol`.
8. `Round Lot Size` is constant at **100**, giving it very little variation.
9. The dataset does not contain historical stock prices, dates, or trading volume.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas** — Data loading, cleaning, filtering, and analysis
- **NumPy** — Numerical operations and array manipulation
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical and categorical visualizations
- **Jupyter Notebook** — Project development and presentation

---

## 📁 Project Structure

```text
Finance-Stock-Market-Dataset-EDA/
│
├── Finance_EDA_Minor_Project.ipynb
├── symbols_valid_meta.csv
└── README.md