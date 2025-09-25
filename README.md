# Mina Gong Data Portfolio
Mina Gong, PhD | Atlanta, GA | mathminagong@gmail.com | [linkedin.com/in/minagong824](https://linkedin.com/in/minagong824)

## About me
Hi there! I'm a calm and methodical Data Scientist with over 10 years of experience training data practitioners and transforming complex data into actionable insights using rigorous statistical analysis and machine learning. I'm an expert in predictive modeling, feature engineering, and survey design, and I'm fluent in Python, SQL, and R. I'm driven by a love of structured problem-solving and continuous learning, focused on helping teams make smarter, faster decisions by delivering clarity from raw data that drives real-world impact.

My goals are: To leverage my expertise in predictive modeling and statistical consulting to solve challenging, ambiguous problems in data science and continue to build tools that have a measurable impact on public health, finance, or business strategy.

My top skills are:

* Machine Learning: scikit-learn, XGBoost, model evaluation, feature selection
* Statistical Analysis: hypothesis testing, A/B, ANOVA, factor analysis, LDA
* Programming: Python (numpy, pandas, statsmodels), R, SQL
* Data Visualization: matplotlib, seaborn, plotly, ggplot2, Tableau
* Cloud Tools: Google Big Query

I invite you to explore my projects. Feel free to email me at mathminagong@gmail.com with any questions or feedback!

# Projects

## Project 1: Credit Card Fraud Detection using Machine Learning 
[Link to the project](https://github.com/MinaGong/fraud_detection/)

### Description
Developed and optimized a supervised machine learning model to accurately classify high-volume credit card transactions as either legitimate or fraudulent, addressing data imbalance challenges inherent in fraud detection.
Key skills used: Classification (XGBoost), Feature Engineering, Python (scikit-learn)

### The problem
Financial institutions lose significant revenue due to fraudulent transactions, necessitating a highly accurate, low-latency detection system that minimizes false positives while capturing nearly all true fraud instances.

### My insights:
* Achieved a high recall score (e.g., 90%+) on the positive (fraudulent) class by using techniques like SMOTE and weighted loss functions to handle the heavily imbalanced dataset.
* Identified the most predictive features, such as transaction velocity and geographical deviation, significantly improving model performance over baseline methods.
* XGBoost outperformed traditional logistic regression models, demonstrating superior generalization capability on unseen data.
* Optimizing the classification threshold was crucial for balancing the trade-off between minimizing false positives (customer inconvenience) and maximizing fraud detection (financial protection).

### My recommendations :
* Deploy the final optimized XGBoost model into a real-time scoring pipeline to flag suspicious transactions instantly.
* Implement an automated feature store to ensure consistency and freshness of engineered features for model serving.
* Set up an alert system for human review of transactions scored above the optimized classification probability threshold.


## Project 2: Predictive Modeling of G20 GDP Per Capita
[Link to the project](https://github.com/MinaGong/gdp_prediction)
### Description
Developed and optimized a Random Forest Regressor using World Bank time-series data to predict GDP per capita for G20 countries, specifically evaluating the predictive role of stock market activity.
### Key skills used
Random Forest Regressor, Feature Engineering (Lag Variables), R, Statistical Analysis

### The problem
Governments and multinational firms require timely and accurate forecasts of economic well-being (GDP per capita) to inform investment, policy planning, and assess global economic conditions.

### My insights:
* Converting all predictors to lag-1 variables (previous year's values) proved essential, as GDP per capita is more likely influenced by historical indicator values.
* The Total Value of Stock Trading emerged as a significant predictor, substantially improving model performance over baseline regression and Random Forest models (baseline $R 
^2$≈0.48).
* The final Random Forest Regressor achieved a robust $R^2$ of 0.89 and an RMSE of 5,355 on the test set after hyperparameter tuning.
*The most influential predictors included 'Stock traded total value', 'School enrollment (secondary)', 'Life expectancy at birth', and 'Mobile cellular subscriptions'.

### My recommendations:
* Integrate the Stock Traded Total Value indicator into all economic forecasting and policy planning models due to its demonstrated high predictive power.
* Explore advanced time-series models (e.g., ARIMA, LSTM) to potentially further enhance prediction accuracy by capturing temporal dependencies.
* Expand the model scope to include additional financial indicators like market capitalization and volatility indices for a more comprehensive predictive framework.
