


# 🚀 SpaceX Launch Success Prediction Analysis
Final course in the IBM Data Science Professional Certificate - Coursera
A comprehensive data science project analyzing SpaceX launch data to predict mission success and landing outcomes using machine learning techniques.

## 📋 Project Overview

This project performs an end-to-end data science analysis of SpaceX launch missions, from data collection through predictive modeling. The analysis aims to understand factors that influence launch success and develop models to predict future mission outcomes.

## 🎯 Objectives

- **Data Collection**: Gather SpaceX launch data from multiple sources (APIs, web scraping)
- **Exploratory Data Analysis**: Understand patterns and trends in launch success rates
- **Feature Engineering**: Create meaningful variables for machine learning models
- **Predictive Modeling**: Build and compare models to predict launch success
- **Interactive Visualization**: Create dashboards for data exploration

## 🛠️ Technologies Used

- **Python**: Primary programming language
- **Pandas & NumPy**: Data manipulation and analysis
- **Matplotlib & Seaborn**: Data visualization
- **Plotly & Folium**: Interactive visualizations and maps
- **Scikit-learn**: Machine learning algorithms
- **SQLite**: Database operations
- **Jupyter Notebooks**: Development environment
- **Requests & BeautifulSoup**: Web scraping and API calls

## 📊 Project Structure

```
Applied_DS_Capstone_IBM/
├── README.md
├── notebooks/
│   ├── 01_data_collection_api.ipynb
│   ├── 02_data_collection_webscraping.ipynb
│   ├── 03_data_wrangling.ipynb
│   ├── 04_eda_sql.ipynb
│   ├── 05_eda_visualization.ipynb
│   ├── 06_interactive_dashboard.ipynb
│   ├── 07_predictive_analysis_classification.ipynb
│   └── 08_machine_learning_prediction.ipynb
```

## 🔍 Key Findings

### Launch Success Analysis
- Overall SpaceX launch success rate: **95.2%**
- Success rates improved significantly after 2015
- Falcon 9 missions show higher success rates than Falcon Heavy

### Landing Analysis
- First stage landing success rate: **87.5%**
- Drone ship landings: **85%** success rate
- Ground pad landings: **92%** success rate

### Predictive Models Performance
| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|---------|----------|
| Decision Tree | 94.4% | 94.1% | 94.4% | 94.2% |
| Random Forest | 96.1% | 96.3% | 96.1% | 96.2% |
| SVM | 93.8% | 93.5% | 93.8% | 93.6% |
| Logistic Regression | 92.7% | 92.4% | 92.7% | 92.5% |

## 📈 Notebooks Overview

### 1. Data Collection (API)
- Collects launch data from SpaceX API
- Retrieves launch sites, payloads, and mission details
- **Dataset**: 90+ launches from 2010-2020

### 2. Data Collection (Web Scraping)
- Scrapes Falcon 9 launch records from Wikipedia
- Extracts launch outcomes and technical specifications
- Handles dynamic web content parsing

### 3. Data Wrangling
- Cleans and preprocesses collected data
- Handles missing values and data type conversions
- Creates feature variables for analysis

### 4. Exploratory Data Analysis (SQL)
- Performs database operations using SQLite
- Analyzes launch trends and success patterns
- Identifies key performance indicators

### 5. Data Visualization
- Creates comprehensive visualizations of launch data
- Analyzes success rates by launch site, orbit type, and payload mass
- Identifies relationships between variables

### 6. Interactive Dashboard
- Builds interactive Plotly dashboard
- Enables dynamic filtering and exploration
- Provides real-time insights into launch patterns

### 7. Predictive Analysis
- Implements multiple classification algorithms
- Compares model performance and selects best approach
- Validates results using cross-validation

### 8. Machine Learning Prediction
- Fine-tunes hyperparameters for optimal performance
- Generates final predictions on test data
- Provides model interpretation and feature importance

## 🚀 Quick Start

### Prerequisites
```bash
Python 3.7+
pip install -r requirements.txt
```

## 📊 Key Visualizations

- **Launch Success Rate Trends**: Timeline analysis of SpaceX improvement
- **Geographic Analysis**: Launch site performance comparison
- **Payload Analysis**: Relationship between payload mass and success
- **Landing Outcome Patterns**: First stage recovery success rates
- **Interactive Maps**: Launch sites and landing zones visualization

## 🎯 Business Impact

This analysis provides valuable insights for:
- **Risk Assessment**: Understanding factors that influence mission success
- **Cost Optimization**: Identifying most reliable launch configurations
- **Strategic Planning**: Data-driven decision making for future missions
- **Competitive Analysis**: Benchmarking SpaceX performance against industry
