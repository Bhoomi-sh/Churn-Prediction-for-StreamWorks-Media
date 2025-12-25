Churn Prediction for StreamWorks Media 
📌 Project Overview

This project focuses on predicting customer churn for StreamWorks Media, a UK-based video streaming platform. The objective was to analyze customer behavior, identify churn drivers, and build predictive models to support customer retention strategies.

🗂️ Dataset

1,500 customer records

Demographics, subscription plans, engagement metrics, promotions, and churn status

🧹 Data Cleaning

Handled missing values (notably in monthly_fee)

Standardized data types and formats

Encoded categorical variables

Final dataset contained zero missing values

⚙️ Feature Engineering

tenure_days – customer activity duration

is_loyal – users active for more than 180 days

watch_per_fee_ratio – engagement relative to cost

heavy_mobile_user – mobile usage > 70%

One-hot encoding for categorical features

📊 Analysis & Modeling

Statistical tests (Chi-square, T-test) to explore churn relationships

Logistic Regression for churn prediction (binary classification)

Linear Regression for watch-time prediction (engagement analysis)

📈 Key Results

Logistic Regression accuracy ≈ 49.7%, AUC ≈ 0.47

Linear Regression performed strongly with R² ≈ 0.82

Higher tenure and watch time strongly linked to retention

Basic subscription users showed the highest churn rates

💡 Business Insights

Promotions slightly reduce churn

Low engagement users are more likely to cancel

Mobile-dominant users show marginally higher churn

Engagement metrics are more predictable than churn itself

✅ Recommendations

Target Basic-plan users with retention offers

Re-engage low watch-time users with personalized content

Improve mobile app performance

Use tenure and engagement as early churn indicators

🛠️ Tools & Skills

Python (Pandas, NumPy, Matplotlib, Scikit-learn)

Exploratory Data Analysis (EDA)

Statistical Testing

Predictive Modeling
