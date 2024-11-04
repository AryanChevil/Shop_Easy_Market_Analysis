# Shop_Easy_Market_Analysis
ShopEasy Market Analysis Project
Project Overview
This project focuses on performing a comprehensive market analysis for ShopEasy, an online retail business facing reduced customer engagement and conversion rates. Despite launching several new online marketing campaigns, ShopEasy observed a decline in customer interactions and conversions. This project aims to analyze customer feedback, sentiment, social media engagement, and conversion metrics to provide actionable insights for enhancing marketing strategies and customer engagement.

Business Problem
ShopEasy is dealing with:

Reduced Customer Engagement: Fewer customer interactions with the site and marketing content.
Decreased Conversion Rates: Lower conversion of site visitors into paying customers.
High Marketing Expenses: Significant marketing investments with underwhelming returns.
Need for Customer Feedback Analysis: A requirement to understand customer opinions to improve engagement and conversions.
Project Objectives
Analyze Customer Feedback: Conduct sentiment analysis on customer reviews to categorize feedback into positive, neutral, or negative sentiment.
Identify Engagement Trends: Examine social media engagement metrics (views, clicks, likes) and identify monthly patterns to enhance content strategies.
Conversion Rate Analysis: Track and analyze conversion rates across different products and months to identify high-performing items and seasonal trends.
Visualize Key Insights: Develop an interactive Power BI dashboard to provide dynamic insights and support data-driven decision-making for marketing optimization.
Tools and Technologies Used
Python: For data extraction, sentiment analysis, and data processing.
SQL: For querying, cleaning, and transforming data from the database.
Power BI: For creating interactive dashboards and data visualizations.
VADER (Valence Aware Dictionary for Sentiment Reasoning): Used for sentiment analysis on customer reviews.
pandas: For data manipulation and analysis.
pyodbc: For database connectivity between Python and SQL Server.
SQL Server: Database to store and manage customer review, product, and engagement data.
AdventureWorksDW2022: Used as a sample database structure.
Microsoft SQL Server Management Studio (SSMS): For SQL development and database management.
Jupyter Notebook: For running Python code and conducting exploratory data analysis (EDA).
Key Components
Data Extraction and Processing
SQL Queries: Extracted data from the PortfolioProject_MarketingAnalytics database, including customer reviews, engagement data, and product details.
Data Cleaning: Cleaned and standardized text data using SQL and Python for consistent analysis.
Sentiment Analysis: Used VADER sentiment analysis in Python to calculate sentiment scores for each review, categorizing them into positive, neutral, and negative sentiments.
Sentiment Categorization: Combined VADER sentiment scores with ratings to create mixed sentiment categories, such as "Mixed Positive" and "Mixed Negative," for a nuanced analysis.
Dashboard Development
Created a Power BI dashboard with the following features:

Customer Review Analysis:

Sentiment breakdown by product and rating, allowing exploration of customer opinions.
Monthly sentiment trends, helping visualize shifts in customer sentiment over time.
Average rating displayed prominently for quick insight into overall customer satisfaction.
Social Media Engagement Metrics:

Monthly views, clicks, and likes segmented by content type (Blog, Social Media, Video).
Product-specific engagement metrics, providing clarity on high-performing products.
Conversion Rate Analysis:

Conversion rates by product and month to identify high-performing items and seasonal trends.
Breakdown of customer journey actions (View, Click, Drop-off, Purchase), pinpointing bottlenecks in the conversion funnel.
Overall Summary and Insights:

Consolidated view showing total customer engagement, average ratings, and conversion rates.
Insights on the relationship between customer sentiment and conversion rates to inform marketing strategies.
SQL Queries Used
The SQL queries used in this project are structured for specific tasks, including data extraction, data cleaning, and categorization. Key SQL operations include:

Data Cleaning: Removed extra spaces from review text and standardized content types in engagement data.
Data Categorization: Used CASE statements to categorize products by price range (Low, Medium, High).
Data Joining: Performed joins on customer and geographic data to enrich the dataset with location information.
Refer to the SQL code screenshots in the repository for specific query structures.

Python Code Snippets
The Python code includes:

Sentiment Analysis Pipeline: Applied VADER sentiment analysis to calculate sentiment scores and categorize them based on score and rating.
Sentiment Bucketing: Grouped sentiment scores into ranges for more detailed analysis.
Data Transformation: Converted raw SQL data into a format suitable for Power BI visualization and saved the processed data as a CSV file.
Key Insights
Sentiment Trends: Positive sentiment dominated customer reviews, with key months showing higher engagement and satisfaction.
High-Performing Products: Certain products, like the Climbing Rope and Hockey Stick, had higher conversion rates, indicating a strong product-market fit.
Conversion Patterns: Conversion rates peaked during certain months, guiding ShopEasy to focus marketing efforts during high-conversion periods.
Engagement Channels: Social media saw the highest engagement in terms of views, clicks, and likes, suggesting that increasing social media investment could yield better customer engagement.
Conclusion
This project provided actionable insights into customer behavior and engagement for ShopEasy, supporting strategic marketing decisions. By combining customer feedback sentiment analysis with social media and conversion metrics, the project helped identify opportunities for improving engagement and optimizing marketing spend.

Future Recommendations
Enhanced Sentiment Analysis: Incorporate machine learning models to further refine sentiment categorization.
A/B Testing on High-Performing Products: Conduct targeted campaigns and measure performance to identify the most effective marketing strategies.
Seasonal Campaign Optimization: Leverage identified monthly trends to optimize marketing campaigns for high-conversion seasons.
