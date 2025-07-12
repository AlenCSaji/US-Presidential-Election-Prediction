# 🗳️ The Oval Office - US Presidential Election 2024 Prediction

**Team Cognify | Loyalist College**

## 📌 Overview

This project predicts the outcome of the **2024 US Presidential Election** using advanced machine learning models, interactive dashboards, and comprehensive data integration. Our model achieved an impressive **96% prediction accuracy**, with only a 10-seat difference in electoral results.

We built a full-stack solution comprising:
- Machine learning models (Random Forest, AdaBoost, Neural Networks, etc.)
- Interactive visualizations (R Shiny, Tableau, Power BI)
- Real-time deployment using **Google Cloud Platform** and **BigQuery**
- Web scraping with Selenium and BeautifulSoup
- End-user accessible dashboards for analysis

## 🎯 Objective

To deliver an end-to-end election forecasting system that:
- Accurately predicts presidential outcomes at the state level
- Provides insight into voting behavior and demographics
- Empowers analysts, strategists, and the public with interactive tools

---

## Methodology

### Data Acquisition
- **Sources:** FiveThirtyEight, US Census Bureau, Bureau of Labor Statistics, Polymarket
- **Tech:** Web scraping using `Selenium` and `BeautifulSoup`
- **Storage:** MySQL and Google BigQuery (35 structured census and polling datasets)

### Preprocessing & EDA
- Missing value treatment, normalization, and categorical encoding
- SMOTE for class imbalance
- Correlation and pattern discovery using Python & R

### Machine Learning Models
- Built using `scikit-learn`, `TensorFlow`, `Keras`
- Models: Decision Tree, Random Forest, AdaBoost, Neural Network
- Evaluation: Accuracy, Cross-Validation, and Generalization Metrics

### Visualization Tools
- **R Shiny & ggplot2**: Interactive dashboards
- **Tableau**: Geospatial insights
- **Power BI & D3.js**: Advanced reporting
- **Python (GeoPandas, Folium)**: Election maps

### Deployment
- **GCP BigQuery**: Central data repository
- **Web App (Flask)**: Connected to prediction model and dashboards
- **Live UI Features:** State-wise winner, electoral seat counts, prediction confidence
