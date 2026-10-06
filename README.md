# Customer Support Ticket Analysis & Dashboard

## 📌 Project Overview

This project analyzes **100,000 customer support tickets** to understand ticket trends, customer issues, support performance, and resolution patterns.

The data was cleaned and analyzed using **Python and Pandas**, and the analysis-ready data was then used to create an interactive **Power BI dashboard**.

## 🎯 Objective

The main objective of this project is to analyze customer support ticket data and identify useful patterns related to:

* Ticket volume and trends
* Customer support channels
* Issue types and priorities
* Ticket status
* Resolution time
* Customer satisfaction
* Regional performance
* Support performance

## 📊 Dataset

* **Rows:** 100,000
* **Columns:** 20
* **Format:** CSV
* **Data:** Synthetic customer support ticket data

The dataset contains information such as:

* Ticket ID
* Created date
* Customer segment
* Channel
* Issue type
* Priority
* SLA
* Sentiment
* CSAT
* Platform
* Region
* Resolution time
* Resolution summary
* Ticket status

## 🧹 Data Cleaning & Analysis

The initial dataset was in CSV format and was analyzed using **Python and Pandas**.

The main steps included:

* Checking the dataset structure
* Checking data types
* Identifying duplicate records
* Checking missing values
* Analyzing duplicate customer IDs
* Investigating missing resolution information
* Filtering and analyzing ticket data
* Preparing the data for visualization

After the Python analysis, the data was converted into **Excel format** and used for the Power BI dashboard.

## 📈 Power BI Dashboard

An interactive dashboard was created using **Microsoft Power BI**.

### Dashboard Features

* Status slicer
* Date slicer
* Channel slicer
* Region slicer
* KPI cards
* Ticket analysis visualizations
* Resolution time analysis
* Customer support performance analysis

The slicers allow users to interact with the dashboard and analyze the data based on different conditions.

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Jupyter Notebook**
* **Microsoft Excel**
* **Power BI**
* **Power Query**
* **DAX**

## 🔄 Project Workflow

```text
CSV Dataset
     ↓
Python & Pandas
     ↓
Data Cleaning & Analysis
     ↓
Excel Dataset
     ↓
Power BI
     ↓
Interactive Dashboard
     ↓
Business Insights
```

## 📷 Dashboard Preview

![Customer Support Dashboard](Screenshots/screenshot.png)

## 📁 Project Structure

```text
customer-support-ticket-analysis/
│
├── README.md
│
├── Data/
│   ├── Synthetic_it_support_tickets.csv
│   └── Synthetic_it_support_tickets.xlsx
│
├── Python/
│   └── customer_support_analysis.ipynb
│
├── PowerBI/
│   └── customer_service_dashboard.pbix
│
└── Screenshots/
    └── screenshot.png
```

## 💡 Key Learning

This project helped me practice an end-to-end data analysis workflow, starting from raw data cleaning and exploration in Python to creating an interactive dashboard in Power BI and presenting data in a business-friendly way.
