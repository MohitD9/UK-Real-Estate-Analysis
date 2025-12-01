# UK Real Estate Analysis

## Project Overview

This project focuses on analyzing the UK real estate market from 2001 to 2017, using SQL for data extraction and cleaning, followed by visualizations created in Tableau. The goal of this analysis is to uncover key insights into property price trends, regional disparities, and how various factors such as property type and location impact pricing. 

### Key Insights:
- **Price Trends**: The dataset reveals how the UK property market evolved over the years, with median prices for different property types and cities.
- **Regional Insights**: Comparing prices across various UK cities, highlighting trends in London, Leeds, Birmingham, and other major cities.
- **Price by Property Type**: Exploring the average price across various property types (e.g., Detached House, Semi-Detached, Flats).

## Technologies Used
- **SQL**: Used for data extraction, transformation, and cleaning, including removing duplicates, handling missing values, and normalizing data.
- **Tableau**: Utilized for creating interactive dashboards and visualizations, showcasing price trends, property type distributions, and regional price variations.
- **Python**: For handling specific data processing tasks.
  
## Dataset Information

The dataset used for this project consists of real estate listings in the UK from 2001 to 2017, including data on:
- **Price**: The price at which the property was sold.
- **Date of Sale**: The date when the property was sold.
- **Property Type**: The type of property (e.g., Detached House, Semi-Detached, Flat).
- **Square Meters**: The size of the property in square meters.
- **City**: The city where the property is located.

**Note**: The dataset was cleaned to remove missing values, handle duplicates, and correct inconsistencies in property types and other fields.

## Analysis Overview

### 1. **Data Cleaning and Preparation (SQL)**
   - **Handling Missing Values**: Replaced missing values in critical columns like price and square meters with appropriate defaults or removed rows with missing data.
   - **Duplicate Removal**: Identified and removed duplicate records to ensure the dataset reflects unique property sales.
   - **Outlier Detection**: Filtered out extreme price values (e.g., properties with prices over £10 million or under £50,000).
   - **Standardizing Property Types**: Ensured consistency in categorical variables like property types (e.g., 'Detached House' instead of 'Det House').

### 2. **Key Visualizations in Power BI**
   - **Price Trends Over Time**: A line chart showcasing median property prices across the years, highlighting market shifts.
   - **Price Distribution by Property Type**: A bar chart comparing average prices for different property types to identify trends and anomalies.
   - **Median Price by City**: A bar chart showing regional variations in property prices, emphasizing cities like London, Leeds, and Manchester.
   - **Price vs. Price per Square Meter**: A scatter plot displaying the relationship between price and property size to explore market patterns.

## Future Improvements
- **Additional Data Sources**: Integrating external data sources such as inflation rates, unemployment rates, or mortgage rates to enhance the analysis.
- **Advanced Modeling**: Implementing predictive modeling techniques to forecast future property prices.
- **Real-Time Analysis**: Connecting the dashboard to a live data source to track real-time trends in the property market.

## Contact
Feel free to reach out with questions or feedback:

- **LinkedIn**: https://www.linkedin.com/in/mohiit-dhamankar/
- **Email**: mohiit99999@gmail.com

---

Thank you for exploring my project! Please feel free to fork the repository and contribute any improvements or new ideas.

