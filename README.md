# Customer Segmentation using RFM Analysis

## Project Overview

This project was completed as part of my Data Analysis internship at Syntecxhub.

The main goal of this project was to understand customer purchasing behavior using RFM Analysis. RFM stands for Recency, Frequency, and Monetary Value, which helps group customers based on their recent purchases, purchase frequency, and spending.

I worked with an e-commerce sales dataset and used Python for data preparation and analysis. I then created an interactive Power BI dashboard to explore the customer segments and their behavior.

## Dataset

The dataset contains e-commerce transaction data with information such as:

- Customer ID
- Order ID
- Order Date
- Total Amount
- Quantity
- Category
- Region
- Payment Method
- Discount
- Return information

Dataset size:

- 34,500 transaction records
- 7,903 unique customers

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Power BI
- Git & GitHub

## Project Steps

### 1. Data Preparation

I first loaded the e-commerce dataset into Python and checked:

- Missing values
- Duplicate rows
- Customer IDs
- Data types
- Important columns required for RFM analysis

The order date column was converted into datetime format before performing the analysis.

### 2. RFM Calculation

I calculated three main customer metrics:

**Recency**  
Number of days since the customer's most recent purchase.

**Frequency**  
Number of unique orders made by the customer.

**Monetary**  
Total amount spent by the customer.

This resulted in an RFM dataset containing 7,903 customers.

### 3. RFM Scoring

Customers were given separate scores for Recency, Frequency and Monetary Value using quintile-based scoring.

These scores were combined to create an overall `RFM_Score`.

### 4. Customer Segmentation

Based on the RFM scores, customers were grouped into five segments:

- Champions
- Loyal Customers
- New Customers
- At Risk
- Hibernating Customers

### 5. Segment Analysis

I compared the segments based on:

- Number of customers
- Customer percentage
- Average Recency
- Average Frequency
- Average Monetary Value
- Total Monetary Value

I also created visualizations to understand the differences between customer groups.

## Customer Segment Insights

### Champions

These customers have recent purchases, high purchase frequency and higher spending.

Possible strategies:
- Loyalty rewards
- Exclusive offers
- Premium products

### Loyal Customers

These customers purchase regularly and show consistent engagement.

Possible strategies:
- Loyalty programs
- Cross-selling
- Personalized offers

### New Customers

These customers have purchased recently but have lower purchase frequency.

Possible strategies:
- Welcome offers
- Second-purchase incentives
- Product recommendations

### At Risk

These customers had previous purchase activity but have not purchased recently.

Possible strategies:
- Win-back campaigns
- Reminders
- Targeted discounts

### Hibernating Customers

This is the largest customer segment and has lower recent engagement, purchase frequency and spending.

Possible strategies:
- Re-engagement campaigns
- Limited-time offers
- Personalized reminders

## Power BI Dashboard

The Power BI dashboard contains two pages.

### Home

The Home page provides an overall view of the customer segments and sales data.

It includes:

- Total Sales
- Total Customers
- Total Orders
- Average Order Value
- Average Customer Spend
- Customer Distribution by Segment
- Total Customer Value by Segment
- Average Recency
- Average Purchase Frequency
- Customer Frequency vs Monetary Value
- Sales Trend Over Time
- Sales by Category

Interactive filters were also added for:

- Segment
- Region
- Category
- Payment Method

### RFM Customer Analysis

The second page focuses specifically on RFM analysis.

It includes:

- Average Recency
- Average Frequency
- Average Monetary Value
- RFM Customer Count
- Customers by RFM Segment
- Average Customer Value by Segment
- Average Recency by Segment
- Average Purchase Frequency by Segment
- Customer Distribution by RFM Score
- Customer RFM Details

## Key Learning

Through this project, I got practical experience in:

- Data cleaning and preparation
- Customer-level aggregation
- RFM analysis
- Customer segmentation
- Data visualization
- Power BI dashboard creation
- Turning analysis into business-oriented insights

This project helped me understand how customer transaction data can be converted into useful segments for further analysis and marketing decisions.

## Files Included

- `01_EcommerceSales.ipynb` – Python analysis and RFM calculations
- `02_Ecommerce Salescsv` – Original transaction dataset
- `03_RFM Customer Segmentation.csv` – Customer-level RFM dataset
- `04_Customer Segmentation RFM Dashboard.pbix` – Power BI dashboard
- `README.md` – Project documentation

## Internship

This project was completed as part of my Data Analysis internship at **Syntecxhub**.
