# 📓 Notebooks

This directory contains the analysis pipeline. **Run in this order:**

## 🔢 Execution Sequence

### 1. `01_data_collection_api.ipynb`
- Collects launch data from SpaceX API
- **Output**: Raw dataset for analysis

### 2. `04_eda_sql.ipynb` 
- SQL analysis of launch patterns
- **Key insights**: Success rates by site, payload, and year

### 3. `08_machine_learning_prediction.ipynb`
- Predictive models for launch success
- **Models tested**: Decision Tree, Random Forest, SVM, Logistic Regression
- **Best performance**: Random Forest (96.1% accuracy)

## 🚀 Quick Start

```bash
jupyter notebook
# Run notebooks 01 → 04 → 08
```

## 📊 Main Outputs

- **Data**: Launch success patterns and trends
- **Models**: Trained classifiers for prediction
- **Visualizations**: Charts and performance metrics
