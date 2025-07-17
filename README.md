Exploratory Data Analysis of Automobile and Phone Data
Project Overview
This project presents a comprehensive exploratory data analysis (EDA) on two distinct datasets: an automobile dataset and a phone call dataset. The analysis focuses on data cleaning, manipulation, and visualization to extract meaningful insights and answer specific business questions. The primary tools used for this analysis are Python's data science libraries, including Pandas, NumPy, Matplotlib, and Seaborn.

Key Questions Answered
This analysis addresses a variety of questions to uncover patterns and relationships within the data:

Automobile Dataset Analysis
Data Cleaning: Converted all '?' values to NaN and performed necessary data type conversions for accurate analysis.

Most Expensive Car: Identified the manufacturer and price of the most expensive car in the dataset.

Maximum Horsepower: Calculated the maximum horsepower for each car company.

Production Count: Determined the total number of cars manufactured by each company.

Price Adjustments: Created a new column with updated prices based on engine location (doubling the price for rear-engine cars).

Data Sorting: Sorted the dataset based on car make and price to facilitate comparisons.

Feature Engineering: Added a new column to represent the number of doors as an integer.

Price Impact Analysis: Identified the features that have the most significant impact on car prices through correlation analysis.

Data Concatenation: Demonstrated both row-wise and column-wise concatenation using sample datasets of German and Japanese cars.

Data Exporting: Saved the first and last 15 records of the dataframe to an Excel file.

Phone Data Analysis
Outlier Removal: Performed outlier removal on the 'duration' column using the Interquartile Range (IQR) method to ensure a more accurate representation of the data.

Data Visualization: Generated box plots and distribution plots to visualize the 'duration' data after outlier treatment.

Statistical Summary: Provided a five-number summary (min, 25%, 50%, 75%, max) for every column in the dataset.

Outlier Analysis and Treatment
A critical step in this EDA was the identification and removal of outliers in the phone dataset's 'duration' column. Outliers can significantly skew statistical analysis and model performance. The following factors were considered during outlier treatment:

Domain Knowledge: Understanding the context of the data to differentiate between erroneous entries and genuinely extreme values.

Impact on Analysis: Recognizing how outliers can affect statistical measures like mean and standard deviation.

Cause of Outliers: Investigating whether outliers are due to data entry errors, measurement errors, or are legitimate but rare occurrences.

Method of Treatment: Choosing an appropriate method for handling outliers, such as removal, transformation, or capping.

The outlier removal process resulted in a more robust dataset, enabling more reliable conclusions.

How to Use
To explore this analysis, you can run the EDA PROJECT1 .ipynb file in a Jupyter Notebook environment. Make sure you have the required datasets (automobile_data.csv and phone_data.csv) in the same directory.

Dependencies
The following Python libraries are required to run the notebook:

pandas

numpy

matplotlib

seaborn

You can install these dependencies using pip:

pip install pandas numpy matplotlib seaborn

This README was generated based on the analysis performed in the provided Jupyter Notebook.
