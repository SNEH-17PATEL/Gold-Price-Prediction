# 🪙 Gold Price Prediction

This project predicts **gold prices (GLD)** using machine learning with a **Random Forest Regressor** in Python.  
It includes data exploration, feature correlation analysis, model training, evaluation, and comparison of predicted vs actual prices.

---

## 📊 Project Overview

The dataset contains historical gold price data, including various market features.  
This project performs:
- Data exploration and preprocessing  
- Correlation analysis of features  
- Distribution analysis of gold prices  
- Model training using Random Forest Regressor  
- Evaluation using R² score  
- Visualization of actual vs predicted gold prices  

---

## 🧰 Tech Stack

- **Python 3**  
- **NumPy** — for numerical computations  
- **Pandas** — for data manipulation  
- **Matplotlib** — for plotting  
- **Seaborn** — for advanced visualizations  
- **Scikit-learn** — for machine learning  

---

## 📂 Dataset

- **File used:** `gld_price_data.csv`  
- Columns typically include:
  - `Date`: Date of the record  
  - `GLD`: Gold price (target variable)  
  - Other market feature columns (e.g., commodity indices, interest rates, or exchange rates)  

Ensure the dataset is formatted correctly with features and target for model training.

---

## 🚀 Features & Visualizations

1. **Correlation Heatmap**  
   Visualizes correlation between gold price and features.  
   📁 Output: `correlation_heatmap.png`

2. **Gold Price Distribution**  
   Histogram showing distribution of gold prices.  
   📁 Output: `gld_distribution.png`

3. **Model Training & Prediction**  
   Random Forest Regressor trained on historical data.  

4. **Actual vs Predicted Prices**  
   Line plot comparing actual gold prices to predicted values.  
   📁 Output: `actual_vs_predicted.png`  

---

## ⚙️ How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/SNEH-17PATEL/Gold-Price-Prediction.git
cd Gold-Price-Prediction
```

### 2. Install Dependencies
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### 3. Add Dataset
Place the `gld_price_data.csv` file in the project directory.
