# Analysing Pharmaceutical Sales Data

## Project Overview

This project analyzes pharmaceutical sales data using Python, Pandas, and Matplotlib. The goal is to explore historical drug sales, identify trends, and visualize patterns in pharmaceutical purchases over time.

The dataset contains daily pharmaceutical sales records, including drug categories, brands, and sales quantities.

This project is based on the roadmap.sh project challenge: [Pharmaceutical Sales Data Project Roadmap](https://roadmap.sh/projects/pharmaceutical-sales-data)

---

## Objectives

The project answers the following business questions:

1. What are the total sales quantities for each drug category (ATC code)?
2. Which individual drug brands have the highest total sales?
3. Which three drugs have the highest sales in:

   * January 2015
   * July 2016
   * September 2017
4. Which drug sold the most often in 2017?
5. Which drug category has the highest average daily sales?
6. Are respiratory drugs (R03) sold more during specific months?

---

## Technologies Used

* Python 3
* Pandas
* Matplotlib
* Jupyter Notebook

---

## Dataset

The dataset used in this project comes from Kaggle and contains historical pharmaceutical sales information.

Main columns include:

* `datum` — Date of sale
* `M01AB`, `M01AE`, etc. — Drug categories based on ATC codes
* Sales quantities for each category

---

## Data Analysis Process

### 1. Data Cleaning

* Loaded the CSV file using Pandas
* Checked for missing values
* Converted date columns into datetime format

### 2. Exploratory Data Analysis

* Calculated total sales by drug category
* Identified top-selling drug brands
* Filtered data by specific months and years
* Compared sales trends across categories

### 3. Data Visualization

Created charts using Matplotlib, including:

* Bar charts
* Histograms
* Monthly trend visualizations

---

## Example Visualizations

* Total sales by ATC category
* Top-selling drugs
* Monthly respiratory drug sales trends
* Daily average sales comparisons

---

## Key Insights

* Certain drug categories consistently outperform others in sales.
* Respiratory drugs (R03) show seasonal sales patterns.
* Sales peaks vary significantly depending on the month and year analyzed.

---

## How to Run the Project

1. Clone or download this repository
2. Install the required libraries:

```bash
pip install pandas matplotlib jupyter
```

3. Open Jupyter Notebook:

```bash
jupyter notebook
```

4. Run the notebook file:

```text
pharmaceutical_sales_analysis.ipynb
```

---

## Skills Demonstrated

* Data cleaning with Pandas
* Data aggregation and filtering
* Time-series analysis
* Data visualization with Matplotlib
* Exploratory data analysis (EDA)

---

## Author

Jy'Mere Williams

---
