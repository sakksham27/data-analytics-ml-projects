# 🚗 Used Car Price Prediction Analysis
**Author**: Saksham Sharma  
**Role**: Aspiring Data Analyst | B.S. Computer Science @ Stony Brook University  
**Date**: June 2025  
**LinkedIn**: [linkedin.com/in/saksham-sharma275](https://linkedin.com/in/saksham-sharma275)  
**GitHub**: [github.com/sakksham27](https://github.com/sakksham27)  
**Dataset**: [Used Car Price Prediction | Kaggle](https://www.kaggle.com/datasets/therohithanand/used-car-price-prediction/data)

---

## 🧠 Objective
This project explores and models the factors influencing the resale price of used cars using a structured and statistically robust data science pipeline. The goal is to identify key predictors and build an interpretable and performant regression model to estimate vehicle price accurately, providing actionable insights for both dealers and consumers in the used car market.

---

## 💼 Business Impact & Applications
- **For Dealers**: Optimize pricing strategies and inventory valuation
- **For Consumers**: Make informed purchasing decisions with fair price estimates
- **For Insurers**: Assess vehicle values for coverage and claims processing
- **Market Insights**: Understand depreciation patterns and value drivers across different vehicle segments

---

## 📊 Dataset Overview
- **Source**: Kaggle - Used Car Price Prediction Dataset  
- **Records**: 10,000 car listings from used car market
- **Market Context**: Diverse range of brands and vehicle types in automotive market
- **Target Variable**: `price_usd`
- **Key Features**:
  - **Numerical**: `make_year`, `engine_cc`, `mileage_kmpl`, `owner_count`
  - **Categorical**: `fuel_type`, `transmission`, `brand`, `color`
  - **Binary**: `insurance_valid`, `service_history`, `accidents_reported`

---

## 🔍 Analysis Pipeline

### 1. **Data Cleaning & Preprocessing**
- Handled missing values, duplicates, and inconsistent formatting
- Normalized categorical fields (e.g., `fuel_type`, `color`)
- Feature engineering (e.g., age of car from `make_year`)

### 2. **Exploratory Data Analysis (EDA)**
- Distributional plots and correlation heatmaps
- Segment-based visual comparisons (e.g., insurance validity vs. price)
- Outlier inspection in `price_usd` and numerical predictors

### 3. **Statistical Testing**
- ANOVA and t-tests to assess influence of categorical variables on price
- Variance Inflation Factor (VIF) to assess multicollinearity
- Residual analysis for linear model assumptions

### 4. **Modeling & Evaluation**
- Models used:
  - **Linear Regression** (best performer)
  - **Random Forest Regressor** (baseline)
  - **XGBoost Regressor** 
- Evaluation metrics:
  - R² Score
  - Root Mean Squared Error (RMSE)
  - 5-Fold Cross-Validation for generalization

---

## 🏆 Key Insights

- **Brand, engine size, mileage**, and **fuel type** are among the top predictors of price.
- Cars with **valid insurance** and **clean service histories** fetch significantly higher prices.
- XGBoost model achieved the best cross-validated **R² of ~0.91** and lowest RMSE.

---

**Best Model**: Linear Regression with 87% variance explained and mean absolute error of $789.45

---

### Key Assumptions
- Linear relationship between numerical features and log-transformed price
- Missing data is Missing at Random (MAR)
- Feature relationships remain stable over time
- Market conditions are relatively consistent across the dataset period

---

## 🚀 Next Steps & Future Enhancements

### Model Improvements
- **Hyperparameter Optimization**: Implement Bayesian optimization for XGBoost tuning
- **Ensemble Methods**: Combine top-performing models using stacking or blending
- **Feature Selection**: Apply recursive feature elimination and LASSO regularization
- **Deep Learning**: Experiment with neural networks for complex feature interactions

### Explainability & Deployment
- **Model Interpretability**: Implement SHAP values for feature importance analysis
- **Web Application**: Deploy model using Streamlit or Flask for real-time predictions
- **API Development**: Create RESTful API for integration with external systems
- **Mobile App**: Develop user-friendly interface for consumers and dealers

### Data Enhancement
- **External Data**: Integrate market trends, economic indicators, and seasonal patterns
- **Real-time Updates**: Implement data pipeline for continuous model retraining
- **Image Analysis**: Add computer vision for vehicle condition assessment
- **Sentiment Analysis**: Incorporate customer reviews and market sentiment

---

## 🛠️ Technical Requirements

### Environment Setup
```bash
# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

### Dependencies
```python
# Core Data Science Stack
pandas==2.0.3
numpy==1.24.3
matplotlib==3.7.2
seaborn==0.12.2

# Statistical Analysis
scipy==1.11.1
statsmodels==0.14.0

# Machine Learning
scikit-learn==1.3.0
xgboost==1.7.6

# Model Interpretation
shap==0.42.1
lime==0.2.0.1

# Development Tools
jupyter==1.0.0
python-dotenv==1.0.0
```

**Python Version**: 3.9+  
**Recommended**: Python 3.10 for optimal performance with XGBoost

---

## 📞 Contact & Collaboration
Feel free to reach out for questions, collaborations, or suggestions:
- **Email**: [saksham.sharma@stonybrook.edu](mailto:saksham.sharma@stonybrook.edu)
- **LinkedIn**: [linkedin.com/in/saksham-sharma275](https://linkedin.com/in/saksham-sharma275)
- **GitHub**: [github.com/sakksham27](https://github.com/sakksham27)

---

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments
- **Kaggle Community** for providing the dataset and inspiration
- **Stony Brook University** Computer Science Department for academic support
- **Open Source Contributors** of the libraries used in this project
