# 📦 India’s Imports: Trade Insights from Asian Countries Using Python (2023–2024)

## 📊 Domain
**Finance (International Trade Analytics)**

---

## 🧾 Project Overview

This project analyzes India’s import trade data from Asian countries using Python. The dataset contains transaction-level information such as country, commodity, quantity, unit of measurement, and import values in INR and USD.

The primary goal is to transform raw trade data into actionable insights through structured data cleaning, statistical analysis, and visualization. The analysis helps uncover trade patterns, identify key contributors, and understand how import behavior varies across countries, commodities, and time.

---

## 📁 Dataset Information

- **Source:** Indian Open Data Portal  
- **Region:** Asia  
- **Available Timeline:** 2015 – June 2025  
- **Selected Period:** 2023 – 2024  

### 📌 Dataset Includes:
- Transaction Date  
- Country & Sub-region  
- Commodity Details (HS Code + Name)  
- Unit of Quantity  
- Quantity Imported  
- Import Value (INR & USD)  

> Data was filtered to recent years for better relevance and performance.

---

## ❗ Problem Statement

Trade datasets are large and complex, making it difficult to derive meaningful insights without proper analysis. Understanding import patterns is essential for:

- Identifying key trading partners  
- Tracking high-value commodities  
- Supporting strategic decision-making  

---

## 🎯 Objectives

- Understand dataset structure  
- Clean and preprocess raw data  
- Handle missing values and inconsistencies  
- Perform exploratory and statistical analysis  
- Visualize trends and relationships  
- Generate business insights  

---

## ⚙️ Tech Stack

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Google Colab  

---

## 🔍 Stage 1: Data Understanding

### ✔ Steps:
- Loaded dataset from GitHub  
- Checked structure (`head()`, `info()`, `describe()`)  
- Identified missing values and duplicates  

### 🔎 Insights:
- Large transactional dataset suitable for analysis  
- Numerical columns stored as strings  
- Minor missing values in unit column  
- No duplicate records  

---

## 🧹 Stage 2: Data Cleaning & Preprocessing

### ✔ Key Steps:

#### 🔹 Removed Redundant Columns
- Dropped **Region Name** and **Region Code**  
- Sub-region provides more detailed classification  

#### 🔹 Handled Missing Values
- Mode → Categorical  
- Median → Numerical  

#### 🔹 Fixed Data Types
- Converted quantity and value columns to numeric  

#### 🔹 Cleaned Unit Column
- Standardized valid units (Kgs, Nos, Mtr, etc.)  
- Replaced invalid values and imputed  

#### 🔹 Final Validation
- No missing values  
- Correct data types  

### 🔎 Insights:
- Real-world data contains inconsistencies  
- Unit cleaning was critical  
- Median works best for skewed data  

---

## 📊 Stage 3: EDA, Statistical Analysis & Visualization

### 📈 Statistical Analysis
- Mean, Median, Mode  
- Variance & Standard Deviation  
- Skewness & Kurtosis  

### 🔎 Insights:
- Data is **right-skewed**  
- High variability in import values  
- Presence of outliers  
- Not normally distributed  

---

### ⏳ Time-Based Analysis
- Extracted Year & Month  

### 🔎 Insights:
- Import activity varies over time  
- Indicates seasonal trends  

---

### 📉 Univariate Analysis

### 🔎 Findings:
- Majority transactions are small  
- Distribution is skewed  
- Few countries dominate  
- Kgs & Nos are common units  

---

### 🔗 Bivariate Analysis

### 🔎 Relationships:
- Country vs Value → concentrated trade  
- Commodity vs Value → dependency  
- Quantity vs Value → positive relation  
- Time vs Value → fluctuating trend  

---

### 🔄 Multivariate Analysis

### 🔎 Insights:
- Strong INR–USD correlation  
- Moderate quantity–value relation  
- Trade depends on country + commodity + time  

---

## 💡 Stage 4: Insights & Recommendations

### 🔑 Key Insights

- Imports concentrated among few countries  
- Few commodities dominate trade  
- Data is highly skewed  
- Most transactions are low-value  
- Trade varies over time  

---

### 📊 Business Insights

- Dependency on specific countries → risk  
- High-value commodities are critical  
- Opportunity for trade diversification  
- Seasonal trends impact imports  

---

### ✅ Recommendations

- Diversify import sources  
- Focus on high-value commodities  
- Use trends for forecasting  
- Monitor high-value transactions  
- Improve supply chain strategies  

---

### 🚀 Future Enhancements

- Add latest data  
- Build dashboards (Power BI/Tableau)  
- Apply machine learning  
- Include economic indicators  

---

## 🏁 Conclusion

This project successfully transformed raw import trade data into meaningful insights using Python. The analysis highlights trade concentration, skewed distribution, and key dependencies, supporting better decision-making in international trade.

---

## ⭐ Support

If you found this project useful, feel free to ⭐ the repository!
