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
![Customer Distribution by Segments][notebooks/customer_distribution_in_segments.png]
![Profit by Brands][notebooks/brandwise_profit.png]
![Customer Segment Distribution by States][notebooks/customer_segments_by_states.png]
![Customers Distribution by Age][notebooks/customers_by_age.png]
![Age-wise Profit Distribution][notebooks/profits_by_age.png]
![Industry-wise Profit Distribution][notebooks/profits_by_industry.png]
![Customer Segments-wise Profit Distribution][notebooks/profits_by_segments.png]
![Customer Segments-wise State Distribution][notebooks/states_with_segmentation.png]
![Monetary vs Frequency][notebooks/monetary_vs_frequency.png]
![Monetary vs Recency][notebooks/monetary_vs_recency.png]

## Observations and Suggestions

1. Customer Distribution by Segment

**Observation**: Highest number of customers are in "Lost Customers" and "Average Customers."
**Suggestive steps**:
- Implement retention strategies for "Lost Customers."
- Engage "Average Customers" to convert them into "Loyal Customers."

2. Segment-wise Profit
**Observation**: "Average Customers" and "Lost Customers" contribute significantly to profit.
**Suggestive steps**:
- Focus marketing efforts on "New Customers" and "Potential Loyalists."
- Introduce loyalty programs to enhance profitability.

3. Brandwise Profit
**Observation**: WeareA2B and Solex are the most profitable brands.
**Suggestive steps**: 
- Prioritize marketing campaigns for top-performing brands.
- Offer cross-brand promotions to maximize revenue.

4. Customer Segments Distribution by State

**Observation**: NSW and VIC have the highest "Lost Customers."
**Suggestive steps**:
- Develop region-specific strategies to convert "Average Customers" to "Loyal Customers."
- Enhance retention initiatives in QLD.

5. Agewise Customer Distribution and Profit
**Observation**: "Established Career Age" group is the most profitable.
**Suggestions**:
- Target marketing campaigns at "Established Career Age" and "Early Career Age" groups.
- Offer promotions and financing options to these segments.

6. Profit by Industry
**Observation**: Manufacturing and Financial Services are top industries by profit.
**Suggestions**:
- Explore partnerships with top industries.
- Leverage industry networks to increase sales.


## Files and Structure

- **Data Files**:
  - Raw Data: `Raw_data.xlsx`
  - Cleaned data: 
  1. `transaction_data_cleaned.csv`
  2. `new_customer_cleaned.csv`
  3. `customer_demography_cleaned.csv`
  4. `customer_address_cleaned.csv`
  5. `rfm_data.csv`

- **Analysis Notebooks**:
Data cleaning for each sheet:
  1. `transaction_data_cleaning.ipynb`
  2. `new_customer_cleaning.ipynb`
  3. `customer_demography_cleaning.ipynb`
  4. `customer_address_cleaning.ipynb`

For RFM analysis and customer segmentation: `RFM_Analysis.ipynb`
For complete data analysis and Visualization: `combined_data_analysis.ipynb`analysis.

## Tools and Libraries

- **Python Libraries**: Pandas, Plotly, Ipython
- **Jupyter Notebooks**: Used for data cleaning, analysis, and visualization.

## How to Run

1. **Install Required Libraries**:
   ```bash
   pip install pandas plotly ipython