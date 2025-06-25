
# ✈️ Airline Passenger Forecasting (1949–1960)

This project involves **time series analysis and forecasting** using monthly airline passenger data from 1949 to 1960. The goal is to identify historical patterns and forecast future passenger counts using statistical techniques like ARIMA or Exponential Smoothing.

---

## 📁 Dataset

- **File**: `airline-passengers.csv`
- **Source**: Monthly airline passengers data (in thousands)
- **Duration**: January 1949 – December 1960
- **Columns**:
  - `Month`: Monthly timestamp (`YYYY-MM`)
  - `Passengers`: Number of airline passengers

---

## 🧰 Tech Stack

- **Language**: Python (Jupyter Notebook)
- **Libraries**:
  - `pandas` – Data handling
  - `matplotlib`, `seaborn` – Visualization
  - `statsmodels` – Time series modeling
  - `Prophet` or `pmdarima` (optional) – Advanced forecasting

---

## 🔍 Key Steps

### 1. Data Preparation
- Parsed dates and converted columns to proper types
- Checked for missing values and ensured time continuity

### 2. Exploratory Data Analysis
- Time-series plot of monthly passenger growth
- Rolling means and smoothing applied to observe trends
- Seasonal trends evident (e.g., higher travel mid-year)

### 3. Time Series Decomposition
- Decomposed data into:
  - **Trend** – General growth in passenger numbers
  - **Seasonality** – Recurring travel patterns by month
  - **Residuals** – Noise after removing trend and seasonality

### 4. Forecasting
- Forecasted future passenger numbers using:
  - **ARIMA/SARIMA**
  - (Optional) Holt-Winters or Prophet
- Compared predictions vs actual values with visual plots

### 5. Visualization
- Actual vs Predicted graph
- Confidence intervals for predictions
- Residual plots to check model assumptions

---

## 📈 Output

- 📊 Forecasts show continued growth with seasonal fluctuations
- 🧠 Model effectively captures yearly travel surges (e.g., summer)
- 🔍 Residual analysis suggests model reliability

---

## 🎯 Use Cases

- **Airline operations planning**
- **Marketing campaign timing**
- **Staff and fleet scheduling optimization**

---

## 🤝 Author

Made with 📈 by [mrharit](https://github.com/mrharit)  
*Open to feedback, collaboration, and contributions!*
