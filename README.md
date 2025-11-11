                                🛍️ Customer Shopping Behavior Analysis

📘 Overview
This end-to-end data analytics project explores customer shopping behavior to uncover insights that guide product, marketing, and operational strategies.

The analysis spans data cleaning and transformation in Python, advanced querying in PostgreSQL, interactive visualizations in Power BI, and storytelling through an AI-generated presentation using Gamma.

🧾 Dataset
1. Source: Publicly available synthetic dataset simulating e-commerce transactions.
2. Total Records: 3,900 purchases
3. Columns: 18 customer and purchase attributes
4. Key Features:
-Demographics (Age, Gender, Location)
-Purchase details (Category, Amount, Discount, Shipping Type)
-Engagement metrics (Review Rating, Subscription Status, Previous Purchases)
5. Missing Data:
Only 37 missing values in review_rating, handled with median imputation per category for accuracy.

🧰 Tools & Technologies
1. Python (Jupyter Notebook): Data loading, cleaning, transformation, and feature engineering
2. PostgreSQL (pgAdmin + SQLAlchemy): Database integration and analytical queries
3. SQL: Business-driven insights and segmentation
4. Power BI: Interactive dashboards and data storytelling
5. Gamma (AI Presentation Tool): Automated generation of final insight presentation
6. Documentation: Comprehensive written report summarizing process and findings

⚙️ Project Steps
1. Data Preparation in Python
Loaded dataset and explored structure using Pandas
Cleaned and standardized columns
Imputed missing ratings by category median
Engineered new columns:
age_group → Bucketed customers by age
purchase_frequency_days → Derived frequency metric
Validated and exported clean data

2. Database Integration
Created PostgreSQL database: customer_behavior
Loaded the cleaned DataFrame via SQLAlchemy connection
Ran SQL queries to answer key business questions

3. SQL Business Analysis
-Revenue by Gender
-Top 5 Products by Review Rating
-Discount Impact on Revenue
-Customer Segmentation (New, Returning, Loyal)
-Age-Group Revenue Distribution

4. Dashboard Creation
Built an interactive Power BI dashboard to visualize:
Gender-wise revenue
Product category performance
Discount-dependency trends
Customer segmentation and subscription behavior
Age-group contribution to revenue

5. Insight Report & Presentation
Report (PDF): Summarizes findings, key metrics, and recommendations.
Presentation (PPT via Gamma): Highlights actionable insights through visuals and narratives.

📊 Key Insights
1. Gender Gap: Male customers generate 2.1× more revenue than females.
2. Subscription Paradox: Non-subscribers contribute 73% of revenue, despite lower average spend.
3. Top Products: Gloves, Sandals, and Boots lead in ratings and revenue.
4. Loyalty Segments: 80% of customers are repeat buyers; opportunity to convert them into subscribers.
5. Express Shipping: Users spend ~$2 more on average than standard shipping customers.

🚀 Strategic Recommendations
1. Introduce loyalty programs to reward repeat buyers.
2. Launch targeted subscription campaigns for high-spend customers.
3. Optimize discount strategies for products overly reliant on promotions.
4. Promote top-rated and high-margin products in marketing campaigns.
5. Focus on Young Adult demographics and express-shipping users for premium offerings.

💡 Outcome
This project demonstrates how to integrate Python, SQL, and BI tools to deliver actionable business insights and strategic recommendations from raw data. It highlights technical proficiency, analytical thinking, and storytelling — crucial for data-driven decision-making in real business contexts.
