<div align="center">

# 📊 Priorizacion de hipotesis y analisis estadisticos de un test A-B

### Análisis de Datos para Decisiones Estratégicas

<img src="https://img.shields.io/badge/Proyecto-Marketing%20Analytics-green" />
<img src="https://img.shields.io/badge/Python-Data%20Analysis-blue" />
<img src="https://img.shields.io/badge/Métricas-LTV%20%7C%20CAC%20%7C%20ROMI-orange" />
<img src="https://img.shields.io/badge/Estado-Completado-brightgreen" />

---

### 👤 Autor
**Yessid Diaz Gutierrez**

---

🎯 *Este proyecto analiza el comportamiento del usuario, el rendimiento de campañas y la rentabilidad por canal de marketing.*

📊 Medición inteligente.  
💰 Inversión eficiente.  
🚀 Escalar lo que funciona.

---

</div>

## 📌 Project Overview

This project focuses on optimizing marketing spending by analyzing user activity, purchase behavior, and advertising investments.  
The objective is to identify the most profitable marketing sources and improve decision-making through business metrics.

## 🧠 Business Objectives

- Understand user behavior across sessions and purchases  
- Identify high-performing acquisition channels  
- Reduce wasted advertising spend  
- Improve profitability per user  
- Optimize marketing strategy based on data

## 📊 Key Metrics

- ✅ DAU / WAU / MAU  
- ✅ Customer Acquisition Cost (CAC)  
- ✅ Lifetime Value (LTV)  
- ✅ Return on Marketing Investment (ROMI)  
- ✅ Conversion Rate  
- ✅ Average Order Value

## 🛠️ Tools & Technologies

- 🐍 Python  
- 🧮 Pandas & NumPy  
- 📊 Matplotlib & Seaborn  
- 📐 Statistical Analysis  
- 🧪 Hypothesis Testing  
- 📈 Data Visualization  
- 🧹 Data Cleaning & Transformation

## 🔍 Methodology

### 1️⃣ Data Preprocessing
- Removal of duplicates  
- Handling missing values  
- Converting date formats  
- Outlier detection

### 2️⃣ User Behavior Analysis
- DAU / WAU / MAU 
- Session duration  
- Returning users  
- Activity trends

### 3️⃣ Sales Performance
- Average purchase value  
- Orders per customer  
- Revenue trends  
- LTV by cohort

### 4️⃣ Marketing Analysis
- Cost by source  
- CAC by channel  
- ROMI calculation  
- Performance comparison

## 📈 Results & Insights

### 🧍 User Behavior
- Only 4% of users return monthly  
- 16% return weekly  
- Indicates a need for retention campaigns

### 💰 Revenue
- Average order: **$5**  
- Peaks observed during December promotions  
- Most users make one purchase per month

### 📢 Marketing Performance

✅ Best performing source: **Source 1**  
- Low cost  
- High conversion  
- High ROMI

❌ Worst performing sources:
- Source 7  
- Source 9  
- Source 10  

## 🎯 Recommendations

- ✅ Invest more in Source 1  
- ❌ Stop spending on Sources 7, 9, and 10  
- ⬇️ Reduce budget for Source 3  
- 🚀 Focus on user retention strategies  
- 📊 Monitor monthly performance metrics

## 📚 Dataset Description

### visits
| Column | Description |
|--------|-------------|
| Uid | User ID |
| Device | Device Type |
| Start Ts | Session start |
| End Ts | Session end |
| Source Id | Marketing source |

### orders
| Column | Description |
|--------|-------------|
| Uid | User ID |
| Buy Ts | Purchase date |
| Revenue | Order revenue |

### costs
| Column | Description |
|--------|-------------|
| source_id | Marketing source |
| dt | Date |
| costs | Daily cost |

## 🏁 Final Conclusion

This analysis allowed clear identification of profitable and unprofitable campaigns.  
Marketing investment should focus on channels that generate real business value.

✅ Data-driven marketing = Better results  
✅ Optimized spending = Higher ROI

## 📂 Repository Structure

```text
📁 project_root  
 ┣ 📜 README.md  
 ┣ 📓 notebook.ipynb  
 ┣ 📂 data  
 ┗ 📂 reports  
