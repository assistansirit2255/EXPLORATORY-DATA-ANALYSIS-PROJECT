# 🚗📞 Exploratory Data Analysis of Automobile and Phone Data

This project presents a comprehensive **Exploratory Data Analysis (EDA)** on two distinct datasets: an **Automobile dataset** and a **Phone Call dataset**. The analysis focuses on **data cleaning, manipulation, visualization**, and **insight extraction** to answer specific business questions.

The primary tools used include Python's popular data science libraries: **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**.

---

## 📊 Project Overview

This EDA explores the following:

- Cleaning and transforming messy data
- Uncovering insights through visualizations
- Answering key business questions
- Applying feature engineering
- Treating outliers for statistical accuracy

---

## ❓ Key Questions Answered

### 🚗 Automobile Dataset Analysis

- 🔧 **Data Cleaning**: Replaced all `'?'` with `NaN` and converted data types for accurate analysis.
- 💸 **Most Expensive Car**: Identified the manufacturer and price of the highest-priced car.
- 🐎 **Maximum Horsepower**: Found max horsepower by car manufacturer.
- 🏭 **Production Count**: Counted the number of cars manufactured by each company.
- 💰 **Price Adjustments**: Created a new column with price updates (e.g., doubled for rear-engine cars).
- 📊 **Data Sorting**: Sorted the dataset based on car make and price.
- 🛠️ **Feature Engineering**: Converted number of doors from text to integer.
- 📈 **Price Impact Analysis**: Identified features with the strongest correlation to car price.
- ➕ **Data Concatenation**: Merged German and Japanese car data both row-wise and column-wise.
- 💾 **Data Exporting**: Exported the first and last 15 records to an Excel file.

---

### 📞 Phone Dataset Analysis

- ❌ **Outlier Removal**: Removed outliers from the `duration` column using the IQR method.
- 📊 **Data Visualization**: Used boxplots and distribution plots to analyze `duration` after outlier treatment.
- 🧮 **Statistical Summary**: Provided five-number summaries (min, 25%, 50%, 75%, max) for all columns.

---

## ⚠️ Outlier Analysis & Treatment

Outliers in the phone dataset were treated to improve the accuracy and reliability of the analysis. This included:

- 🧠 **Domain Understanding**: Differentiating between valid extremes and erroneous data.
- 🎯 **Impact Analysis**: Recognizing how outliers distort mean, std deviation, and visualizations.
- 🔍 **Root Cause**: Investigating whether the outliers were input errors or legitimate cases.
- 🛠️ **Treatment Method**: Removed outliers using the Interquartile Range (IQR) method.

This resulted in a cleaner, more robust dataset for visual and statistical interpretation.

---

EDA-Project/
├── data/
│   ├── automobile_data.csv
│   └── phone_data.csv
│
├── EDA_PROJECT1.ipynb        # Jupyter Notebook with all analysis
├── charts/                   # Exported plots and visualizations
│   └── *.png
├── README.md                 # Project documentation


## 🛠️ How to Use

To run this analysis:

1. Clone the repository or download the `.ipynb` notebook
2. Ensure the datasets (`automobile_data.csv` and `phone_data.csv`) are in the same directory
3. Open and run `EDA_PROJECT1.ipynb` using Jupyter Notebook or VS Code

---

## 📦 Dependencies

Install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn

