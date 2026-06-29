# Customer Shopping Behavior Analysis

## Overview

This project analyzes customer shopping behavior using Python, SQL, and Power BI to uncover purchasing trends, customer segments, and business insights. The workflow covers the complete data analytics process—from data cleaning and exploratory data analysis (EDA) to SQL querying, dashboard creation, and business reporting.

The objective was to transform raw retail transaction data into actionable insights that support data-driven decision making.

---

## Dataset

The dataset contains **3,900 retail transactions** with **18 attributes**, including:

* Customer demographics (Age, Gender, Location)
* Purchase information (Items, Categories, Purchase Amount)
* Shopping behavior
* Subscription status
* Discounts and promotions
* Shipping methods
* Customer review ratings

During data cleaning, missing review ratings were handled, new analytical features were created, and redundant columns were removed to prepare the data for analysis.

---

## Tools & Technologies

* **Python**

  * Pandas
  * NumPy
  * Matplotlib
  * Jupyter Notebook
* **MySQL Server**

  * Data storage
  * Business analysis using SQL
* **Power BI**

  * Interactive dashboard creation
* **Gamma**

  * Presentation design
* **Microsoft Word**

  * Business report documentation

---

## Project Workflow

### 1. Data Loading

* Imported the dataset into Python using Pandas.
* Inspected data structure and summary statistics.

### 2. Exploratory Data Analysis (EDA)

* Explored customer demographics.
* Analyzed purchase behavior.
* Examined spending patterns and product categories.
* Identified missing values and data inconsistencies.

### 3. Data Cleaning

* Filled missing review ratings using median values by category.
* Renamed columns using snake_case.
* Created new features such as:

  * Age Group
  * Purchase Frequency (Days)
* Removed redundant columns.
* Exported the cleaned dataset to MySQL.

### 4. SQL Analysis

Created SQL queries to answer key business questions, including:

* Revenue by gender
* Subscriber vs. non-subscriber spending
* Highest-rated products
* Revenue by age group
* Most discounted products
* Customer loyalty segmentation
* Category performance
* Shipping method analysis

### 5. Power BI Dashboard

Developed an interactive dashboard featuring:

* KPI Cards
* Revenue analysis
* Customer segmentation
* Purchase trends
* Subscription insights
* Product category performance
* Age group analysis
* Interactive slicers and filters

### 6. Reporting & Presentation

* Produced a business analysis report summarizing findings.
* Created a presentation in Gamma highlighting insights and recommendations.

---

## Dashboard Highlights

The Power BI dashboard includes:

* Total Customers
* Average Purchase Amount
* Average Review Rating
* Revenue by Age Group
* Revenue by Product Category
* Subscription Distribution
* Interactive filters for:

  * Gender
  * Category
  * Subscription Status
  * Shipping Type

---

## Results

Key insights from the analysis include:

* Most customers are **non-subscribers**, representing an opportunity for subscription growth.
* **Male customers** generated higher overall revenue.
* **Young Adult** and **Middle-aged** customers contributed the highest revenue.
* **Gloves, Sandals, and Boots** received the highest customer ratings.
* Several products rely heavily on discounts, indicating opportunities to optimize promotional strategies.
* A large portion of customers fall into the **Loyal** customer segment, while returning customers present opportunities for targeted retention campaigns.

---

## Repository Structure

```
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   ├── raw_dataset.csv
│   └── cleaned_dataset.csv
│
├── notebooks/
│   └── customer_analysis.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── powerbi/
│   └── Customer_Shopping_Dashboard.pbix
│
├── report/
│   └── Customer_Shopping_Behavior_Analysis_Report.pdf
│
├── presentation/
│   └── Customer_Shopping_Analysis.pptx
│
└── README.md
```

---

## How to Run

1. Clone this repository.
2. Install the required Python libraries:

```bash
pip install pandas numpy matplotlib jupyter mysql-connector-python
```

3. Open the Jupyter Notebook.
4. Run the notebook to clean and explore the dataset.
5. Load the cleaned dataset into MySQL Server.
6. Execute the SQL queries located in the `sql/` folder.
7. Open the Power BI dashboard (`.pbix`) to explore the visualizations.
8. Review the business report and presentation for a summary of findings.

---

## Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* SQL Query Development
* Database Management
* Power BI Dashboard Design
* Business Intelligence
* Data Storytelling
* Reporting & Presentation

---

## Author

**Hunter Woodruff**

This project was created as part of a data analytics portfolio to demonstrate end-to-end analytical, SQL, visualization, and business reporting skills.
