# Advertisement_Analytics_Revenue_Prediction

1. Project Overview
 
This project analyzes the relationship between advertising spend, marketing channels, promotions, and revenue to identify key drivers of business performance and support data-driven advertising decisions.
The analysis combines advertising data from Google Ads, Meta, YouTube, and Email with sales and promotional information. It includes data preprocessing, exploratory data analysis, feature engineering, channel-level ROAS analysis, promotional analysis, and machine learning-based revenue prediction.

2. Objectives
 
- Analyze the impact of advertising channels on revenue.
- Compare the performance of Google Ads, Meta, YouTube, and Email.
- Calculate and analyze ROAS (Return on Ad Spend).
- Identify the relationship between advertising spend and revenue.
- Analyze the impact of promotions and discount depth.
- Identify seasonal and time-based revenue patterns.
- Build machine learning models for daily revenue prediction.
- Generate actionable recommendations for advertising budget allocation.

3. Dataset

The project uses multiple datasets containing:

- Daily revenue
- Total orders
- Advertising spend
  - Google Ads
  - Meta
  - YouTube
  - Email
- Promotional campaigns
- Discount depth
- Promotion type
- Date-based information

The datasets were integrated using the Date field to create a unified analytical dataset.

The final dataset contains 1,099 days of data and includes 114 promotional days across 30 unique promotions.

4. Technologies & Libraries

- Python
- Pandas – Data manipulation and preprocessing
- NumPy – Numerical computation
- Matplotlib – Data visualization
- Seaborn – Statistical visualization
- Scikit-learn – Machine learning and model evaluation
- Jupyter Notebook

5. Project Workflow

text
Raw Data
   ↓
Data Loading
   ↓
Data Cleaning & Preprocessing
   ↓
Dataset Integration
   ↓
Exploratory Data Analysis
   ↓
Feature Engineering
   ↓
Advertising & ROAS Analysis
   ↓
Promotion & Seasonality Analysis
   ↓
Machine Learning
   ↓
Model Evaluation
   ↓
Business Recommendations


6. Data Preprocessing

The following preprocessing steps were performed:

Loaded and inspected individual datasets.
Checked data types and dataset structure.
Converted date columns into appropriate datetime format.
Identified missing values.
Merged advertising, revenue, and promotion datasets.
Handled missing promotional values by categorizing them as No Promo.
Created derived marketing performance metrics.

Example engineered metrics include:

Total Media Spend
Blended ROAS
Channel-specific ROAS
Promotional indicators
Discount-related features
Time-based features

7. Exploratory Data Analysis

The project analyzes:

Revenue Analysis
Daily revenue trends
Revenue distribution
Revenue variation over time
Relationship between orders and revenue
Advertising Analysis

Advertising performance was analyzed across:

Google Ads
Meta
YouTube
Email

The analysis compares spending levels and revenue contribution across channels.

ROAS Analysis

ROAS was calculated to evaluate advertising efficiency:

ROAS = Revenue Generated / Advertising Spend

Channel-specific ROAS was analyzed to compare the relative efficiency of different marketing channels.

8. Advertising Channel Analysis

The project evaluates advertising channels using:

Average ROAS
Advertising spend
Revenue relationship
Correlation analysis
Channel-level performance comparison

This helps identify channels with stronger return potential and provides a basis for optimizing advertising budgets.

9. Promotion Analysis

Promotional campaigns were analyzed to understand their relationship with revenue.

The analysis includes:

Number of promotional days
Unique promotional campaigns
Discount depth
Revenue during promotional periods
Comparison between promotional and non-promotional periods

There were 114 promotional days across 30 unique promotions in the dataset.

10. Seasonality & Time-Based Analysis

Time-based features were engineered to investigate revenue patterns across:

Day of week
Month
Quarter
Year
Promotional periods

These features were incorporated into the analytical and predictive workflow to capture temporal patterns in revenue.

11. Machine Learning

Machine learning models were developed to predict daily revenue using historical revenue, advertising, promotional, and time-based features.

Features

The model incorporates variables related to:

Historical revenue
Advertising spend
Marketing channels
Orders
Promotions
Discount depth
Temporal patterns
Models

Multiple regression-based approaches were evaluated as part of the modeling workflow.

Model performance was evaluated using metrics such as:

R² Score
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)

The predictive model is treated primarily as a supporting analytical tool for understanding revenue drivers rather than as a highly accurate forecasting system.

12. Key Business Insights

The analysis provides insights into:

Relative performance of different advertising channels.
Advertising efficiency through channel-level ROAS.
Relationship between media spending and revenue.
Revenue behavior during promotional periods.
Impact of discount depth on promotional performance.
Seasonal and time-based revenue patterns.
Potential opportunities for advertising budget optimization.

13. Business Recommendations

Based on the analysis, the project focuses on:

Prioritizing advertising channels with stronger ROAS.
Reviewing channel performance before increasing advertising spend.
Using promotional-period analysis to improve campaign timing.
Considering discount depth when evaluating promotional effectiveness.
Incorporating seasonal patterns into campaign planning.
Using predictive modeling as an additional input for advertising decisions.
