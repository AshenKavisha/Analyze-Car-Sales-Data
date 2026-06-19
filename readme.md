# Used Car Market Analysis Using Python and Pandas

## Overview

This project performs Exploratory Data Analysis (EDA) on a dataset of used car listings. The objective is to clean, transform, and analyze the data to discover pricing trends, mileage patterns, and brand popularity within the used car market.

The analysis was conducted using Python, Pandas, and Jupyter Notebook.

---

## Objectives

- Understand the structure and quality of the dataset.
- Clean and preprocess raw data.
- Remove invalid and unrealistic records.
- Analyze vehicle prices across different brands.
- Analyze mileage trends among popular brands.
- Visualize findings using charts and graphs.
- Extract meaningful business insights from the data.

---

## Dataset

The dataset contains used car listings with information such as:

- Vehicle Brand
- Price
- Mileage (Kilometers Driven)
- Registration Year
- Vehicle Type
- Transmission Type
- Fuel Type
- Seller Information

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Data Cleaning Process

Several preprocessing steps were performed to improve data quality:

### 1. Column Renaming
Renamed columns to improve readability and consistency.

### 2. Missing Value Analysis
Identified and analyzed columns with missing values.

### 3. Removing Unnecessary Columns
Removed columns that contained little or no useful information, such as:

- num_pictures
- seller
- offer_type

### 4. Price Cleaning
Filtered out unrealistic vehicle prices to reduce the impact of outliers.

### 5. Registration Year Cleaning
Removed records with invalid registration years.

### 6. Data Type Conversion
Converted columns into appropriate data types for analysis.

---

## Exploratory Data Analysis

### Brand Distribution

Analyzed the most frequently listed vehicle brands in the dataset.

Questions answered:

- Which brands appear most frequently?
- Which manufacturers dominate the used car market?

### Price Analysis

Calculated average vehicle prices for popular brands.

Questions answered:

- Which brands have the highest average prices?
- Which brands offer the most affordable vehicles?

### Mileage Analysis

Calculated average mileage by brand.

Questions answered:

- Which brands have the highest average mileage?
- Which brands typically have lower mileage vehicles?

### Visualization

Created plots and charts to better understand:

- Brand popularity
- Average brand prices
- Average brand mileage

---

## Key Findings

### Brand Popularity

Volkswagen, BMW, Mercedes-Benz, Opel, Audi, and Ford were among the most frequently listed brands.

### Price Trends

Premium brands such as BMW, Mercedes-Benz, and Audi generally exhibited higher average prices compared to economy brands.

### Mileage Trends

Mileage varied significantly between manufacturers, indicating differences in vehicle usage and market positioning.

---

## Project Structure

```text
Used-Car-Market-Analysis/
│
├── cars.ipynb
├── autos.csv
├── README.md
└── images/
```

---

## How to Run the Project

### Clone the Repository

```bash
git clone https://github.com/yourusername/Used-Car-Market-Analysis.git
```

### Navigate to the Project

```bash
cd Used-Car-Market-Analysis
```

### Install Required Libraries

```bash
pip install pandas numpy matplotlib jupyter
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
cars.ipynb
```

and run all cells.

---

## Sample Skills Demonstrated

This project demonstrates practical experience in:

- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Data Visualization
- Python Programming
- Pandas Data Manipulation
- Problem Solving

---

## Future Improvements

Potential enhancements include:

- Interactive dashboards using Plotly or Power BI
- Machine Learning models for price prediction
- Geographical analysis of vehicle listings
- Advanced visualizations and reporting
- Feature engineering for predictive analytics

---

## Author

**Ashen Kavisha**

Software Engineering Undergraduate

Interested in:
- Software Development
- Data Analytics
- Web Development
- Machine Learning


## Dataset Overview

![Dataset Information](images/dataset_info.png)

## Average Price by Brand

![Average Price](images/mean_price.png)

## Average Mileage by Brand

![Average Mileage](images/mean_mileage.png)

GitHub: https://github.com/AshenKavisha

