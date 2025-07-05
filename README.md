# Integrated-Store-Optimization-Forecasting-Sales

A comprehensive machine learning and analytics project aimed at **enhancing retail store performance** through forecasting, customer segmentation, markdown analysis, and cross-selling strategies — all integrated into a user-friendly **Streamlit web app**.

> 🚀 [Live App](https://integrated-store-optimization-forecasting-sales-st3vybltwtqs5h.streamlit.app/)

---

## 📌 Project Type

Advanced Machine Learning – **Forecasting, Clustering, Feature Engineering, Deployment**

---

## 🧠 Problem Statement

Leverage historical sales and economic data to:
- Forecast **short-term and long-term weekly sales**
- Analyze **seasonality and holiday impacts**
- **Segment stores and departments** for personalized insights
- Suggest **product associations** and cross-selling strategies

---

## 📝 Project Summary

### 🧹 Phase 1: Data Cleaning & Feature Engineering
- Merged multiple datasets into one unified view
- Imputed missing values in markdowns
- Converted `IsHoliday` boolean to binary
- Extracted `year`, `month`, `week` from dates
- Engineered features to better reflect markdowns and seasonality

### 📅 Phase 2: Time Series & Seasonal Analysis
- Visualized weekly sales trends
- Analyzed impact of holidays (Christmas, Thanksgiving)
- Compared store vs. department-level behaviors

### 🎯 Phase 3: Clustering & Product Association
- **K-Means** clustering for:
  - Store segmentation (markdown usage, avg. sales)
  - Department segmentation (sales patterns)
- Discovered co-occurring product sales
- Suggested **cross-sell opportunities**

### 🔮 Phase 4: Forecasting Models
#### 📆 Short-Term Forecasting:
- Features: economic + markdown data
- Model: **XGBoost Regressor**
- RMSE: ~6864

#### 📊 Long-Term Forecasting:
- Features: store, department, markdowns, economic data
- Models: **Random Forest** & **XGBoost**
- RMSE: ~6080
- R² Score: ~0.89

---

## 🌐 Streamlit Web App

- Clean, modern UI with sidebar controls
- Real-time prediction with XGBoost
- Forecast visualization (bar chart)
- Ideal for business stakeholders and planning teams

🔗 [Try the App](https://integrated-store-optimization-forecasting-sales-st3vybltwtqs5h.streamlit.app/)

---

## 🧰 Tech Stack

| Tool / Library     | Role                          |
|--------------------|-------------------------------|
| Python             | Programming language          |
| Pandas, NumPy      | Data manipulation             |
| Matplotlib, Seaborn| Visualization                 |
| Scikit-learn       | ML preprocessing & models     |
| XGBoost, RandomForest | Forecasting models         |
| KMeans             | Clustering                    |
| Streamlit          | Web app deployment            |
| Jupyter Notebook   | Analysis and experimentation  |

---

## 📁 File Structure

📁 Retail-Store-Optimization/
│
├── 📄 Store Optimization.ipynb # Complete project notebook
├── 📄 requirements.txt # (Optional) Required packages
├── 📄 README.md # Project overview
└── 📁 streamlit_app/
