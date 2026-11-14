# 📊 Retail Sales Analysis Using Python

**Author:** Firas Shabandari  
**Field:** Computer Science – Artificial Intelligence and Big Data  
**University:** University of Wollongong in Dubai (UOWD)

## 📌 Project Overview

This project focuses on analysing historical retail transaction data using Python to understand sales performance, customer purchasing behaviour and product trends.

The goal is to explore the dataset, clean and prepare the data, identify meaningful patterns and generate business insights through data analysis and visualisation.

## 🎯 Project Objectives

- Analyse monthly sales performance.
- Identify the countries generating the highest revenue.
- Examine customer purchasing behaviour.
- Identify top-performing products.
- Calculate important business metrics.
- Create visualisations to communicate findings.

## 📂 Dataset Information

**Dataset:** Online Retail Dataset  
**Source:** UCI Machine Learning Repository

[Download the Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)

Dataset details:
- 541,909 original transaction records.
- 8 columns.
- Historical transaction period: December 2010 – December 2011.
- Data from a UK-based online retailer.

The original dataset is not included in this repository. Please download it from the official source.

## 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- OpenPyXL
- Google Colab
- Jupyter Notebook

## 🔍 Project Workflow

### 1. Data Exploration (EDA)
- Examined dataset dimensions and column names.
- Identified missing values.
- Checked data types.
- Analysed duplicate records.
- Generated statistical summaries.

### 2. Data Cleaning
- Removed duplicate records.
- Converted transaction dates into datetime format.
- Investigated missing CustomerID values.
- Examined cancelled invoices and invalid transactions.
- Prepared a separate dataset for valid sales analysis.

### 3. Feature Engineering
Created a new Revenue column using:

`Revenue = Quantity × UnitPrice`

### 4. Exploratory Data Analysis
- Monthly sales analysis.
- Country-wise revenue analysis.
- Customer purchasing analysis.
- Order statistics.
- Product performance analysis.

### 5. Data Visualisation
- Monthly sales trend line chart.
- Country-wise revenue bar chart.
- Top product revenue chart.
- Customer order activity heatmap.

## 📈 Key Findings

- **Total Revenue:** £10,642,110.80
- **Total Orders:** 19,960
- **Average Order Value:** £533.17
- **Highest Sales Month:** November 2011
- **Lowest Sales Month:** February 2011
- **Highest Revenue Country:** United Kingdom
- **Identified Customers:** 4,338

The United Kingdom contributed approximately 84.59% of the recorded sales revenue.

November recorded the highest monthly sales, while February recorded the lowest. Sales activity also showed fluctuations throughout the year.

*Note: These metrics use the valid-sales filters applied in the analysis. The December 2011 data covers only part of the month.*

## 💡 Business Insights

The analysis highlights the importance of understanding monthly sales trends, identifying high-performing markets and examining customer purchasing behaviour.

The findings could help a retail business:
- Understand its strongest sales periods.
- Identify important geographical markets.
- Monitor product performance.
- Make more informed inventory and sales decisions.

## 📚 What I Learned

Through this project, I gained practical experience in:

- Python-based data analysis.
- Data cleaning and preprocessing.
- Working with Pandas.
- Exploratory Data Analysis.
- Data visualisation using Matplotlib.
- Interpreting business data.
- Communicating analytical findings.

## 👨‍💻 About Me

I am Firas Shabandari, a Bachelor of Computer Science student specialising in Artificial Intelligence and Big Data at the University of Wollongong in Dubai.

I am interested in Data Analytics, Artificial Intelligence, automation and technology-driven problem-solving.

This project is part of my journey towards developing practical technical skills and building my data analytics portfolio.

**GitHub:** https://github.com/firasshabandari-prog
