
# 📊 Customer Shopping Behaviour Analysis

## 📌 Overview

This project presents an end-to-end analysis of customer shopping behaviour using transactional data. It covers data loading, cleaning, exploratory data analysis, and SQL-based querying to extract meaningful business insights. The findings are visualised through a Power BI dashboard and communicated using a structured report and presentation, demonstrating a complete data analyst workflow.

---

## 📁 Dataset

The dataset consists of **3,900 records and 18 features**, covering customer demographics, purchase details, and shopping behaviour.

Key features include:

* Customer demographics (Age, Gender, Location, Subscription Status)
* Purchase details (Item, Category, Amount, Season, Size, Colour)
* Behavioural data (Discount usage, Purchase frequency, Review ratings, Shipping type)

The dataset contained **37 missing values in the review rating column**, which were handled during data cleaning.

---

## 🛠️ Tools & Technologies

* **Python (Pandas, NumPy)** – Data loading, cleaning, and EDA
* **SQL (MS SQL Server)** – Data analysis and querying
* **Power BI** – Dashboard creation and data visualization
* **Gamma** – Presentation creation
* **Excel** – Data handling (if applicable)

---

## 🔄 Project Steps

### 1. Data Loading

The dataset was imported into Python using Pandas for further analysis and processing.

### 2. Exploratory Data Analysis (EDA)

Initial exploration was performed to understand the dataset structure, data types, summary statistics, and identify missing values using functions like `info()` and `describe()`.

### 3. Data Cleaning

* Handled missing values in the review rating column using median imputation
* Standardized column names into snake_case
* Removed redundant columns after validation
* Ensured overall data consistency

### 4. Feature Engineering

* Created **age groups** for better segmentation
* Derived **purchase frequency metrics** for behavioural analysis

### 5. SQL Analysis (MS SQL Server)

The cleaned dataset was loaded into MS SQL Server to perform business-focused analysis, including:

* Revenue analysis by gender
* Identification of high-spending discount users
* Top-rated products analysis
* Shipping type comparison
* Subscriber vs non-subscriber behaviour
* Customer segmentation (New, Returning, Loyal)
* Revenue contribution by age group

### 6. Dashboard (Power BI)

An interactive dashboard was built in Power BI to visualize key insights, trends, and comparisons, enabling better understanding of customer behaviour.

### 7. Reporting & Presentation

Insights were summarized into a structured report and presented using Gamma for clear communication of findings.

---

## 📊 Dashboard

The Power BI dashboard provides visual insights into:

* Customer segmentation
* Revenue distribution
* Product performance
* Shipping behaviour
* Subscription impact

---

## 📈 Results & Insights

* Customers using subscriptions tend to spend more and show higher loyalty
* Express shipping users have higher average purchase value
* A small group of customers contributes significantly to overall revenue
* Discount usage influences purchasing behaviour among high-value customers

---

## ▶️ How to Run

1. Clone the repository
2. Open the Python notebook/script and run data preprocessing steps
3. Load the cleaned dataset into **MS SQL Server**
4. Execute SQL queries for analysis
5. Open the Power BI file to explore the dashboard
6. View the report and presentation for final insights

---

## 📎 Project Deliverables

* Python scripts / Jupyter Notebook
* SQL query files
* Power BI dashboard (.pbix)
* Project report
* Gamma presentation (PDF)



