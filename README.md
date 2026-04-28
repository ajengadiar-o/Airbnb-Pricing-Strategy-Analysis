# Airbnb-Pricing-Strategy-Analysis
Project Overview
This project aims to analyze Airbnb listing data to understand the key factors influencing pricing, demand, and revenue performance. The analysis focuses on identifying pricing inefficiencies and deriving data-driven strategies to optimize booking performance and maximize revenue.

Objectives :
1. Identify factors influencing Airbnb listing prices
2. Analyze the relationship between price and demand (reviews as proxy)
3. Detect pricing inefficiencies (overpriced vs underpriced listings)
4. Evaluate the impact of listing quality (rating) on performance
5. Develop pricing strategies to optimize revenue
   
Dataset link : https://www.kaggle.com/datasets/ashishjangra27/airbnb-dataset
The dataset contains Airbnb listing information, including:
1. Price
2. Rating
3. Number of reviews
4. Property characteristics (bedrooms, beds, bathrooms)
5. Location (country)
   
Tools & Technologies :
1. Python
2. Pandas
3. NumPy
4. Matplotlib
5. Seaborn
6. Google Colab
   
Project Workflow :
1. Data Understanding
a. Initial data inspection
b. Summary statistics (mean, median, skewness)

Distribution analysis :
3. Data Cleaning
a. Handling missing values
b. Data type correction
c. Outlier detection using IQR method
Data validation :
4. Exploratory Data Analysis (EDA)
a. Price distribution analysis
b. Price vs demand (reviews)
c. Pricing efficiency analysis
d. Rating vs performance
e. Correlation analysis
f. Revenue proxy analysis

Key Insights :
1. Pricing is influenced by multiple factors, not just property size
2. Demand is highly price-sensitive, concentrated in lower price ranges
3. Pricing inefficiencies exist across listings
4. Rating does not strongly drive demand
5. Revenue is maximized by balancing price and demand, not by maximizing price alone
   
Business Recommendations :
1. Implement demand-based pricing strategies
2. Optimize mid-tier pricing for stable performance
3. Adjust overpriced and underpriced listings
4. Support premium pricing with strong value propositions
5. Combine pricing strategy with visibility and competitiveness
   
Key Metric :
1. Revenue Proxy
2. revenue_proxy = price * reviews
3. Used to estimate potential revenue in the absence of actual booking data.

Conclusion :
Pricing strategy in the Airbnb market requires a multi-dimensional approach. The optimal strategy balances price and demand to maximize both booking performance and revenue, rather than focusing on a single factor.

How to Run :
1. Open the notebook in Google Colab
2. Upload the dataset
3. Run all cells sequentially
