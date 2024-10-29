# Maven Market Data Analysis

## Project Overview

The Maven Market Sales Analysis project aims to provide insights into sales performance, profit margins, and transaction trends across different products, locations, and time periods. This analysis can help Maven Market understand key drivers of profitability and make data-driven decisions.

##Table of Contents

Data Sources
Data Model
Dashboard Overview
Key Metrics
Insights

##Data Sources

-**This project uses various datasets, including**:

-**Customers**: Customer demographic and account information.
-**Products**: Product details, including price and cost.
-**Stores**: Store locations, square footage, and remodeling dates.
-**Regions**: Regional details for segmentation.
-**Transaction Data**: Sales transaction records.
-**Returns Data**: Details on product returns.

##Data Model

-**The data model is designed to integrate all data sources, allowing for seamless analysis. The relationships are defined as follows**:

Customers and Stores are connected to Transaction Data based on customer and store IDs.
Products link to both Transaction Data and Returns Data for sales and return tracking.
Calendar is connected to date-based fields for time-based analysis.
Refer to the data model structure provided in the repository for more details.

##Dashboard Overview

-**The Power BI dashboard includes**:

-**Top Line Performance**: Highlights total transactions, profit, and return rates by product brand.
-**Country and City Insights**: Visualization of transactions by country and city.
-**Revenue Trends**: Weekly revenue trends with a visual comparison to targets.
-**Profit and Return Metrics**: Profit margins and return rates by product.

##Key Metrics

-**Total Transactions**: 16,7616
-**Current Month Profit**: $71,682 (5.61% above target)
-**Current Month Returns**: 496 (2.9% above target)
-**Profit Margin**: 59.93%
-**Return Rate**: 0.99%

##Insights

-**Top-Selling Brands**: Brands like "Hermanos," "Tell Tale," and "Ebony" show the highest transactions.
-**Location Insights**: The majority of transactions occur in the USA, followed by Mexico and Canada.
-**Profit Margins**: Products like "Fast" and "Fort West" have higher-than-average profit margins.
-**Weekly Revenue Trends**: Shows consistent revenue growth with seasonal spikes.




