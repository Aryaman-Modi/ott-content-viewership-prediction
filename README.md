# 🎬 OTT Content Viewership Prediction using Linear Regression

A Machine Learning regression project that predicts **first-day content viewership** for OTT platform releases using historical engagement, marketing, and release-related features.

The project helps identify the major factors influencing content performance and provides actionable business recommendations for improving audience engagement.

---

## 📌 Business Problem

ShowTime is an OTT streaming platform that releases movies and web series throughout the year.

The company wants to understand what drives first-day content viewership so they can optimize marketing campaigns, schedule releases strategically, and maximize audience engagement.

The objective of this project is to build a Linear Regression model that predicts first-day views and identifies the most influential business variables.

---

## 📊 Dataset

The dataset contains **1,000 content releases** with information about platform traffic, advertising, release timing, and content characteristics.

### Features

- Visitors
- Ad Impressions
- Major Sports Event
- Genre
- Day of Week
- Season
- Trailer Views

### Target Variable

- First-Day Content Views

---

## 📈 Exploratory Data Analysis

The analysis includes:

- Distribution of first-day content views
- Genre distribution
- Day-wise viewership analysis
- Seasonal viewership trends
- Trailer views vs content views
- Correlation heatmap
- Outlier detection
- Feature relationship analysis

---

## ⚙️ Data Preprocessing

- Missing value verification
- Duplicate record check
- Categorical variable encoding
- Feature selection
- Train-Test Split

---

## 📉 Regression Model

A Multiple Linear Regression model was developed to predict first-day content viewership.

The project also validates important regression assumptions including:

- Linearity
- Multicollinearity (VIF)
- Homoscedasticity
- Normality of Residuals

---

## 📊 Model Evaluation

Performance was evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## 📁 Repository Structure

```
ott-content-viewership-prediction
│
├── data
├── notebooks
├── reports
├── images
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Statsmodels
- SciPy
- Jupyter Notebook

---

## 📌 Key Insights

- Trailer views showed the strongest positive relationship with first-day content views.
- Platform visitors significantly influenced overall viewership.
- Content released during major sports events generally received lower first-day engagement.
- Seasonal and release-day trends had moderate influence on performance.
- Marketing strategy and trailer engagement are among the strongest drivers of successful launches.

---

## 🚀 Future Improvements

- Ridge Regression
- Lasso Regression
- Elastic Net Regression
- XGBoost Regressor
- Interactive dashboard using Power BI or Tableau
- Model deployment using Streamlit

---

## 📄 Business Report

A detailed business report explaining the exploratory analysis, regression modelling process, evaluation metrics, and business recommendations is available in the **reports** folder.

---

## 👨‍💻 Author

**Aryaman Modi**

LinkedIn: www.linkedin.com/in/aryaman-modi-8a834a200
