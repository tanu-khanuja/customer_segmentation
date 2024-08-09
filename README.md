# Customer Segmentation Analysis for Australian Bike Company

## Overview

This project involves a comprehensive Customer Segmentation Analysis for an Australian bike company. By using the given dataset and applying advanced analytical techniques, the goal of the project is to uncover valuable insights about customer behavior and segment performance. The analysis uses RFM (Recency, Frequency, Monetary) model to categorize customers and visualize key metrics, aiming to enhance sales strategies and customer engagement. Along with RFM analysis, a detailed analysis is performed on state wise customer distribution, profits made from different age groups, industrial sectors, customer segments, and brands. The recency and frequency of customers is analyzed against monetary benefits to the company.

## Data

The raw data comprises four distinct sheets from an Excel file:

1. **Transactions**: Contains detailed transaction records for customers across Australian.
2. **NewCustomerList**: Lists newly acquired customers who have recently interacted with the company.
3. **CustomerDemographic**: Provides demographic information including age, gender, and occupation.
4. **CustomerAddress**: Includes address details of the customers.

## Data Cleaning and Preparation

1. **Data Cleaning**: Each dataset is cleaned and processed in separate notebooks. The cleaned data is then exported as CSV files for analysis.

2. **RFM Analysis**:
   - **Segmentation**: Customers are segmented based on their Recency, Frequency, and Monetary scores calculate from transaction data.
   - **Analysis**: Conducted Recency vs. Monetary and Frequency vs. Monetary analyses to understand customer purchasing behavior.

3. **Visualization and Analysis**:
   - **Customer Segments by State**: Analysed how different customer segments are distributed across various states.
   - **Agewise Customer Distribution**: Visualized the distribution of customers across different age groups.
   - **Profit Analysis**: Analysed profit distribution by industry, customer segment, and age groups.

## Visualizations

### Customer Distribution by Segments
![Customer Distribution by Segments](customer_distribution_in_segments.png)

### Monetary vs Recency

![Monetary Values wrt Recency days ](images/customer_segments_by_state.png)

*Figure 1: Distribution of customer segments across different states.*

### Agewise Customer Distribution

![Agewise Customer Distribution](images/agewise_customer_distribution.png)

*Figure 2: Distribution of customers across various age groups.*

### Profit by Industry

![Profit by Industry](images/profit_by_industry.png)

*Figure 3: Profit distribution across different industry sectors.*

### Profit by Segments

![Profit by Segments](images/profit_by_segments.png)

*Figure 4: Contribution of different customer segments to overall profit.*
