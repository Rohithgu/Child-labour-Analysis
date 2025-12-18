📊 Child Labour Data Analysis (Excel + Python)
📌 Project Overview

This project focuses on analyzing child labour statistics using data extracted from an Excel file.
The analysis aims to identify year-wise trends, distribution patterns, and key insights using Python data analysis libraries.

The project demonstrates skills in:

Data cleaning

Exploratory Data Analysis (EDA)

Aggregation and grouping

Data visualization

Converting Excel data into meaningful insights

🗂 Dataset Description

Source: Excel file (.xlsx)

Domain: Social / Economic Data

Granularity: Year-wise child labour statistics

Key Columns:
Column Name	Description
Year	Year of observation
Age_Group	Age category of children
Child_Labor_Rate_Percent	Percentage of child labour
Region / Country (if applicable)	Geographic classification
🛠 Tools & Technologies Used

Excel – Data source

Python

Pandas (data manipulation)

NumPy (numerical operations)

Matplotlib (visualization)

Seaborn (advanced plots)

Jupyter Notebook

GitHub (version control)

🔄 Data Processing Steps

Loaded Excel data into Pandas DataFrame

Checked and handled missing values

Renamed columns for consistency

Converted data types (Year, numeric columns)

Grouped data by year

Calculated average child labour rate

Prepared clean data for visualization

📈 Exploratory Data Analysis (EDA)
✔ Analysis Performed:

Year-wise average child labour rate

Trend analysis over time

Distribution analysis using violin plots

Comparative analysis using bar charts

✔ Visualizations:

Line plot – trend over years

Bar plot – year-wise comparison

Violin plot – distribution of labour rates

📊 Sample Python Code
labour = (
    child.groupby('Year', as_index=False)
         .agg(labour_rate=('Child_Labor_Rate_Percent', 'mean'))
)

🔍 Key Insights

Child labour rates show year-wise variation

Certain years exhibit higher concentration

Distribution analysis reveals data spread and outliers

Aggregated trends help understand long-term patterns

📁 Project Structure
├── data/
│   └── child_labour_data.xlsx
├── notebooks/
│   └── child_labour_analysis.ipynb
├── visuals/
│   └── plots.png
├── README.md

🚀 How to Run the Project

Clone the repository

Install required libraries

pip install pandas numpy matplotlib seaborn


Open Jupyter Notebook and run the analysis

🎯 Use Cases

Academic research

Social impact analysis

Data analyst portfolio project

Power BI / Tableau dashboard foundation

📌 Future Enhancements

Add region-wise comparison

Integrate Power BI dashboard

Forecast future trends

Automate Excel ingestion
