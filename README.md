📊 Exploratory Data Analysis (EDA) on Shopping Trends
📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a retail shopping dataset to identify customer purchasing behavior, spending patterns, and shopping trends. The analysis leverages statistical summaries and visualizations to extract meaningful insights that can support data-driven business decisions.

The dataset contains 3,900 customer records with 18 attributes, covering demographics, product details, payment behavior, and purchase frequency.

📂 Dataset Description

File Used:
shopping_trends_updated.csv

Size:

Rows: 3,900

Columns: 18

Key Features:

Customer demographics (Age, Gender, Location)

Product details (Category, Item, Size, Color, Season)

Purchase behavior (Amount, Frequency, Previous Purchases)

Marketing impact (Discount Applied, Promo Code Used)

Payment and delivery preferences

The dataset is complete with no missing values, making it suitable for direct exploratory analysis.

🛠️ Libraries & Tools Used

NumPy – Numerical computations

Pandas – Data manipulation and analysis

Matplotlib & Seaborn – Static visualizations

Plotly Express – Interactive visualizations

WordCloud – Text-based visual analysis

🔍 Analysis Workflow
1. Data Loading & Inspection

Loaded CSV data into a Pandas DataFrame

Checked shape, data types, column names, and memory usage

Verified absence of missing values

2. Feature Understanding

Analyzed unique values for categorical variables

Converted age into meaningful age groups using binning

Age Categories:

Child

Teen

Young Adults

Middle-Aged Adults

Old

📈 Key Business Questions Explored
1️⃣ Age Distribution of Customers

Customers are widely distributed across age groups

Average customer age ≈ 44 years

2️⃣ Purchase Amount Across Categories

Average spending is fairly consistent across categories

Footwear shows slightly higher average spending

3️⃣ Gender-wise Purchase Behavior

Purchase amounts across genders are comparable

No extreme gender-based spending imbalance observed

4️⃣ Most Purchased Items by Category

Clothing and Accessories dominate overall purchases

Specific items like Pants, Blouses, Jewelry, and Jackets are frequently purchased

5️⃣ Seasonal Spending Trends

Purchases are relatively even across seasons

Spring shows marginally higher activity

6️⃣ Product Ratings by Category

Review ratings are consistent across categories

No category shows significantly poor customer satisfaction

7️⃣ Subscription vs Non-Subscription Behavior

Subscription status does not significantly impact average purchase amount

Indicates subscriptions may affect loyalty more than immediate spending

8️⃣ Preferred Payment Methods

Debit and Credit Cards show slightly higher average spending

Digital and traditional payment methods are both widely used

9️⃣ Impact of Promo Codes

Promo code usage does not strongly increase total spending

Suggests promotions drive engagement rather than higher ticket size

🔟 Purchase Frequency Across Age Groups

Middle-aged and young adults dominate frequent purchases

Older customers show lower purchase frequency

📊 Visualizations Included

Histograms (Age distribution, Seasonality)

Bar charts (Category spending, Ratings, Payment methods)

Sunburst charts (Promo code usage, Purchase frequency)

Interactive plots using Plotly

📌 Key Insights

Customer spending is stable across demographics and categories

Seasonal impact exists but is not extreme

Promotions and subscriptions influence behavior, not spending volume

Middle-aged customers form the core purchasing segment

🚀 Future Improvements

Add correlation analysis for numeric variables

Apply customer segmentation (K-Means / RFM)

Build predictive models for purchase amount or churn

Create an interactive dashboard (Streamlit / Power BI)

📎 Output Files

shopping_trends_updated.xlsx – Excel version of the dataset

📬 Conclusion

This EDA provides a strong foundation for deeper analytics, customer segmentation, and predictive modeling. The insights can be used to improve marketing strategies, inventory planning, and personalized customer experiences.
