# Supply Chain Analysis

[![🔗 Live Streamlit App - Click Here](https://img.shields.io/badge/Live%20Streamlit%20App-Click%20Here-00FFFF?style=for-the-badge)](https://supplychainanalysisandprediction-rxskeeaq6bww8zpmj3ajtn.streamlit.app/)

---

## 📊 Overview

This Streamlit dashboard provides a comprehensive analysis of supply chain data, focusing on key metrics such as production volumes, stock levels, order quantities, revenue, manufacturing costs, lead times, shipping costs, transportation routes, risk factors, and sustainability factors.  

The interactive visualizations allow for an in-depth understanding of the supply chain's performance and highlight areas for improvement. Additionally, the integrated revenue prediction module leverages machine learning models like **Linear Regression**, **Random Forest**, and **XGBoost** to forecast revenue trends, compare model performance, and provide data-driven insights for strategic decision-making.

---

## ⚙️ Features

- **Total Production Volumes, Stock Levels, and Lead Times** – Displays key indicators for quick overview.
- **Revenue Distribution by Location** – Pie chart visualizing revenue share by region.
- **Manufacturing Costs by Supplier** – Bar chart showing supplier-wise cost breakdown.
- **Price vs. Manufacturing Costs by Product Type** – Comparison with profit margin indicators.
- **Production Volume vs. Order Quantities** – Polar chart showcasing operational relationships.
- **Shipping Cost Distribution** – Bar chart comparing carrier-wise shipping costs.
- **Average Lead Time by Product Type** – Highlights delay variations by product category.
- **Transportation Routes and Frequencies** – Bubble chart showing logistics patterns.
- **Supply Chain Risk Distribution** – Visualizing key risk factors.
- **Sustainability Factors** – Pie chart depicting eco-efficiency measures.

---

## 🧾 Dataset Overview

We worked with a dataset containing **100 rows** and **24 columns**, providing detailed insights into multiple dimensions of the supply chain.  
The columns included are:

- Product type  
- SKU  
- Price  
- Availability  
- Number of products sold  
- Revenue generated  
- Customer demographics  
- Stock levels  
- Lead times  
- Order quantities  
- Shipping times  
- Shipping carriers  
- Shipping costs  
- Supplier name  
- Location  
- Lead time  
- Production volumes  
- Manufacturing lead time  
- Manufacturing costs  
- Inspection results  
- Defect rates  
- Transportation modes  
- Routes  
- Costs  

---

## 🌐 Deployed Web App Overview

### 📈 Analysis Page
![Dashboard Page](Output_Screenshots/Dashboard_Page.png)

### 🤖 Modelling & Revenue Prediction Page
![Revenue Prediction Page](Output_Screenshots/Revenue_Prediction_Page.png)

---

## 🧠 Model Overview and Results

For revenue prediction, we implemented three models — **Linear Regression**, **Random Forest Regressor**, and **XGBoost Regressor** — and compared their performance using key evaluation metrics.  

- **Linear Regression** achieved a **Train R² of 0.99** and **Test R² of 0.98**, with a **Test MAE of 295.94** and **Test RMSE of 343.24**, showing excellent predictive accuracy and generalization.  
- **XGBoost** followed closely with a **Train R² of 1.00** and **Test R² of 0.98**, though its **Test MAE (351.53)** and **Test RMSE (405.98)** were slightly higher, indicating mild overfitting despite strong training performance.  
- **Random Forest**, however, recorded a **Train R² of 0.90** and **Test R² of 0.73**, along with a significantly higher **Test MAE of 1280.35** and **Test RMSE of 1480.34**, suggesting weaker generalization and higher prediction errors.  

Overall, the **Linear Regression model** proved to be the most stable and accurate among the three, making it the preferred choice for reliable revenue forecasting.

---

## 👤 Author

**Ashutosh Sahoo**  
**Department of Computer Science and Engineering**  
**Specialization:** Data Science and Analytics | IIIT Nagpur  
📧 [sahooashutosh792@gmail.com](mailto:sahooashutosh792@gmail.com)

---
