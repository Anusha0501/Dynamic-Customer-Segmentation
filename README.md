# Customer Segmentation and RFM Analysis

This project aims to analyze customer data and perform segmentation using Recency, Frequency, and Monetary (RFM) analysis. It includes data preprocessing, data exploration, and visualization steps to better understand customer behavior and inform decision-making. The final output is a Customer Segmentation Dashboard.

## Steps Involved:

### 1. Data Preparation
- **Exporting Data to CSV:** After performing data quality assessment (DQA) and cleaning, the dataset was exported to a CSV file for further analysis.
- **RFM Analysis:** Recency, Frequency, and Monetary values were calculated to segment customers based on their buying behavior.

```python
cust_trans_rfm.to_csv('Customer_Trans_RFM_Analysis.csv', index=False)
```

### 2. Data Exploration and Analysis

#### 2.1. Age Distribution
- **Age distribution analysis** for new and old customers shows the most common age ranges.
  
#### 2.2. Gender-based Purchases
- **Gender-wise analysis of bike purchases** over the last 3 years reveals that female customers account for more purchases than male customers.

#### 2.3. Job Industry Customer Distribution
- The distribution of customers across different job industries, with a focus on sales, manufacturing, and financial services.

#### 2.4. Wealth Segmentation
- **Wealth segmentation by age group** showed that 'Mass Customers' represent the largest segment across all age groups, followed by 'High Net Worth' customers.

#### 2.5. Car Ownership by State
- **Car ownership distribution** across Australian states (NSW, QLD, VIC), showing customer behavior in relation to car ownership.

### 3. RFM Analysis

#### 3.1. Recency vs Monetary
- A scatter plot showing the relationship between **Recency** and **Monetary** values, indicating that recent customers spend more.

#### 3.2. Frequency vs Monetary
- A scatter plot showing the correlation between **Frequency** of purchases and **Monetary** values, highlighting the customers with frequent visits and high revenue generation.

### 4. Customer Segment Distribution
- **Customer segments** are classified into various categories (e.g., Platinum, Very Loyal, Becoming Loyal) based on their RFM values. A bar plot visualizes the distribution of customers in each segment.

### Output
- A CSV file containing the final RFM analysis and customer segmentation.
- Multiple visualizations to help understand customer behavior and segmentation.

## Key Libraries Used:
- **Pandas**: Data manipulation and analysis.
- **Seaborn** & **Matplotlib**: Data visualization.
- **Numpy**: Numerical operations.

## Files:
- `Customer_Trans_RFM_Analysis.csv`: The exported dataset after RFM analysis.
- `NewCustomerList_Cleaned.csv`: The cleaned dataset for new customers.
- `CustomerAddress_Cleaned.csv`: The cleaned dataset for customer address info.

## Conclusion:
This project provides insights into customer demographics, purchasing behavior, and segmentation based on RFM values. The visualizations and segments can be utilized for targeted marketing, sales strategies, and improving customer relationships.

![Screenshot 2025-01-29 at 15 19 36](https://github.com/user-attachments/assets/923c6f23-2da6-47b6-888f-43d8cf31ce7e)
![Screenshot 2025-01-29 at 15 19 24](https://github.com/user-attachments/assets/31c33dd7-38c7-4793-bdd6-f22195e79b8c)
![Screenshot 2025-01-29 at 15 19 06](https://github.com/user-attachments/assets/e1956f31-3197-4684-b6c6-10ba96e97d2e)
![Screenshot 2025-01-29 at 15 18 49](https://github.com/user-attachments/assets/dad08d23-c5ed-4b20-ac38-45c88a693e54)

