# 📈 SARIMAX-Based Time Series Forecasting

This project demonstrates **time series forecasting** using the **SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous regressors)** model. It leverages statistical modeling to capture seasonal trends and make accurate future predictions.

---

## 🧠 Operations 

- Prepare and visualize time series data  
- Implement and tune the **SARIMAX** model  
- Evaluate model performance using residuals and accuracy metrics  
- Forecast and visualize future values  

---

## 📂 Project Structure

```
├── SARIMAX.ipynb       # Jupyter Notebook with the complete workflow
├── dataset.csv         # Time series dataset used for modeling
├── README.md           # You are here!
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git https://github.com/28p07/Time-Series-SARIMAX.git
cd Time-Series-SARIMAX
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

<details>
<summary>📋 Click to view required libraries</summary>

```
pandas  
numpy  
matplotlib  
seaborn  
statsmodels  
scikit-learn  
```

</details>

### 3. Run the Notebook

```bash
jupyter notebook experiments.ipynb
```

---

## 📊 Dataset

The dataset used (`dataset.csv`) contains time series data suitable for modeling seasonal trends. It is already cleaned and formatted for direct use in SARIMAX modeling.

---

## 🛠️ How the SARIMAX Model Works

The SARIMAX model includes:

- **AR (AutoRegression):** Dependency on lagged observations  
- **I (Integrated):** Differencing to make the series stationary  
- **MA (Moving Average):** Dependency on past forecast errors  
- **Seasonality:** To capture periodic patterns  
- **Exogenous Variables:** (optional) Other influencing factors

The model is trained by selecting optimal parameters using statistical metrics like AIC/BIC and evaluated using RMSE and MAPE.

---

## 📈 Visuals & Output

The notebook includes:

- Time series decomposition (trend, seasonality, residuals)  
- ACF/PACF analysis for parameter identification  
- Residual diagnostics and normality checks  
- Forecast plots with confidence intervals  
- Evaluation metrics for model accuracy  

---

## ✅ Example Output

> *"The SARIMAX model provides a solid forecast with seasonal awareness, closely matching real data and maintaining low residual errors."*

---

## ✨ Features

- ✔️ Lightweight & beginner-friendly  
- 📉 Accurate time series forecasting  
- 📊 Interactive visualizations  
- 🔍 Model diagnostics for better tuning  
- 🧹 Clean and modular code  

---

## 💡 Future Improvements

- Add automated hyperparameter tuning  
- Include exogenous variables for multivariate forecasting  
- Deploy using Streamlit or Flask for real-time forecasting  

---

## 🙌 Acknowledgements

- [Statsmodels Documentation](https://www.statsmodels.org/stable/index.html)  
- [Time Series Forecasting Concepts](https://otexts.com/fpp3/)  
- Python libraries: `statsmodels`, `pandas`, `numpy`, `matplotlib`, `seaborn`