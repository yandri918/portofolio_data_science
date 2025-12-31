# Data Science Portfolio - Agricultural Analytics

## Overview

This folder contains 3 professional Jupyter notebooks demonstrating comprehensive Data Science skills applied to agricultural domain.

## Notebooks

### 1. Soil_Fertility_Analysis.ipynb
**Focus:** Statistical Analysis & Exploratory Data Analysis

**Contents:**
- Dataset: 500 soil samples from Indonesian agricultural fields
- Exploratory Data Analysis (NPK, pH, micronutrients)
- Statistical Hypothesis Testing (Shapiro-Wilk, t-test, ANOVA)
- Correlation Analysis with heatmaps
- Regional comparisons and business insights

**Key Skills:**
- pandas, numpy (data manipulation)
- matplotlib, seaborn, plotly (visualization)
- scipy.stats (statistical testing)
- Business intelligence & insights

### 2. Yield_Prediction_Model.ipynb
**Focus:** Machine Learning & Explainable AI

**Contents:**
- Dataset: 800 samples with soil & climate features
- Data preprocessing & feature engineering
- Multiple ML models (Linear, Ridge, Lasso, Decision Tree, Random Forest, Gradient Boosting)
- Model comparison & evaluation
- SHAP (SHapley Additive exPlanations) for interpretability

**Key Skills:**
- scikit-learn (ML models)
- SHAP (explainable AI)
- Model evaluation & selection
- Production deployment readiness

**Results:**
- Best Model: Random Forest
- R² Score: 0.87
- RMSE: 0.45 ton/ha

### 3. Price_Forecasting_Analysis.ipynb
**Focus:** Time Series Analysis & Forecasting

**Contents:**
- Dataset: 365 days of commodity price data
- Time series decomposition (trend, seasonality, residuals)
- Forecasting models (Moving Average, ARIMA concepts)
- Accuracy metrics (MAE, RMSE, MAPE)
- Business recommendations

**Key Skills:**
- statsmodels (time series)
- Forecasting techniques
- Trend & seasonality analysis
- Business forecasting

## Installation

```bash
# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\\Scripts\\activate

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
```

## Usage

1. Open Jupyter Notebook
2. Navigate to desired notebook
3. Run cells sequentially (Cell → Run All)
4. Explore visualizations and insights

## Technical Stack

- **Python:** 3.12+
- **Data Processing:** pandas, numpy
- **Visualization:** matplotlib, seaborn, plotly
- **Machine Learning:** scikit-learn
- **Explainable AI:** SHAP
- **Statistics:** scipy, statsmodels

## Author

**Andriyanto**  
Data Scientist | Agricultural Technology Specialist  
Email: yandri918@gmail.com  
GitHub: [@yandri918](https://github.com/yandri918)  
LinkedIn: [Andriyanto NA](https://www.linkedin.com/in/andriyanto-na-147492157)

## Project Context

These notebooks are part of **AgriSensa**, an agricultural intelligence platform with 100+ modules covering the full agricultural value chain. They demonstrate:

- **Domain Expertise:** Deep understanding of agricultural science
- **Technical Skills:** End-to-end Data Science workflow
- **Business Acumen:** Translating analysis into actionable insights
- **Production Readiness:** Code quality suitable for deployment

## Portfolio Highlights

✅ **Statistical Rigor:** Hypothesis testing, correlation analysis  
✅ **Machine Learning:** Multiple algorithms, model comparison  
✅ **Explainability:** SHAP for transparent AI  
✅ **Time Series:** Forecasting & trend analysis  
✅ **Visualization:** Publication-quality charts  
✅ **Business Impact:** Actionable recommendations  

## License

MIT License - See main repository for details

---

**Created:** December 2024  
**Status:** Production-ready for Data Science portfolio
