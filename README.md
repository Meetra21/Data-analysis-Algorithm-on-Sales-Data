# Walmart Sales Data Analysis & Forecasting  

This repository contains an in-depth analysis of **Walmart's sales data** across 45 stores, aimed at uncovering trends, patterns, and predictive insights.  

The project combines **exploratory analysis**, **statistical evaluations**, and **predictive modeling** to provide actionable insights into Walmart’s sales strategies.  

---

## 📊 Project Overview  

The key questions addressed in this analysis are:  

- 🏬 Which **store shows the greatest fluctuation** in sales?  
- 🎉 Which **holidays recorded higher-than-average sales**, despite the typical negative impact of holidays?  
- 📈 Which **stores experienced significant growth in 2012**?  
- 💰 Which **stores had the highest and lowest overall sales**?  
- 📅 What are the **monthly and semester-wise sales trends** across all stores?  
- 🔮 How can we **forecast future demand and sales patterns** using predictive modeling?  

This analysis seeks to uncover insights that can guide Walmart’s **strategic decisions and future planning**.  

---

## 📂 Dataset Overview  

- **Source**: [Kaggle – Walmart Store Sales Forecasting](https://www.kaggle.com/datasets)  
- **Stores**: 45 Walmart stores across different regions  
- **Date Range**: February 5, 2010 – November 1, 2012  

### Key Features  

| Feature        | Description                                                                 |
|----------------|-----------------------------------------------------------------------------|
| `Date`         | Week associated with the sales data                                         |
| `Store`        | Unique store identifier                                                     |
| `Weekly_Sales` | Total sales for the store during that week                                  |
| `Temperature`  | Recorded temperature on the day of sale                                     |
| `Fuel_Price`   | Average fuel price in the region during that week                           |
| `CPI`          | Consumer Price Index (indicator of economic conditions)                     |
| `Unemployment` | Unemployment rate in the region                                             |
| `Holiday_Flag` | Binary flag (1 = Holiday week, 0 = Non-holiday week)                        |

---

## 🧭 Project Workflow  

### 1. **Exploratory Data Analysis (EDA)**  
- Store-level performance comparison  
- Variability in weekly sales  
- Holiday vs. non-holiday sales patterns  
- Sales trends over months and semesters  

### 2. **Statistical Analysis**  
- Growth rate analysis (focus on 2012 trends)  
- Identification of best- and worst-performing stores  
- Seasonality and demand fluctuations  

### 3. **Predictive Modeling**  
- Regression-based approaches for demand forecasting  
- Feature engineering using economic and environmental indicators (CPI, Unemployment, Temperature, etc.)  
- Evaluation of forecasting accuracy  

---

## 📂 Repository Structure  

- `EDA_Walmart_Sales.ipynb` – Exploratory Data Analysis  
- `Statistical_Analysis_Walmart.ipynb` – Growth trends, store-level comparisons, and statistical tests  
- `Sales_Forecasting_Model.ipynb` – Predictive modeling and future demand forecasting  
- `data/` – Dataset files (from Kaggle)  

---

## ⚙️ How to Run  

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/walmart-sales-analysis.git
   cd walmart-sales-analysis
