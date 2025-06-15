# 🏠 House Price Prediction (EDA + Feature Engineering)

This project focuses on analyzing and predicting housing prices based on various property features using statistical analysis, visualizations, and feature engineering techniques.

---

## 📌 Objective

- Understand factors affecting house prices
- Perform exploratory data analysis (EDA)
- Identify trends across property types, sizes, and locations
- Build features for predictive modeling

---

## 📊 Dataset Overview

The dataset includes 18 columns related to residential property characteristics:

- **Price** (target variable)
- **Bedrooms**, **Bathrooms**, **Floors**
- **Sqft_living**, **Sqft_lot**, **Sqft_above**, **Sqft_basement**
- **View**, **Condition**, **Waterfront**
- **Year Built**, **Year Renovated**
- **City**, **Statezip**, **Country**

---

## 🧹 Data Cleaning & Preprocessing

- Handled missing values and corrected data types
- Removed outliers using IQR and domain knowledge
- Encoded categorical variables (label/one-hot/ordinal)
- Created new features like age, total space, and renovated status

---

## 🔍 Key Insights

- **Mid-sized homes (1500–2500 sqft)** dominate the market
- **Living space, bathrooms, and view quality** highly influence price
- **Land area (sqft_lot)** has weak correlation with price
- **Waterfront** properties are priced significantly higher
- **City-level** analysis shows Clyde Hill and Mercer Island have top average prices

---

## 🧠 Feature Engineering

- Property age and renovation status
- Total usable space (living + basement)
- View rating category
- Condition grouping

---

## 📈 EDA Techniques Used

- Univariate and bivariate histograms with KDE curves
- Correlation heatmaps
- Boxplots by view, condition, and location
- Multivariate scatter plots to study interactions

---

## ✅ Recommendations

- Focus on building mid-sized homes
- Enhance key features like bathrooms and views
- Prioritize premium city zones for higher returns
- Use engineered features to improve prediction accuracy

---

## 👨‍💻 Author

**Jotheeswaran S**  
Data Analyst | Python | Power BI | Real Estate Analytics

