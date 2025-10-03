# Melbourne Housing Market EDA  

##  Project Overview  
This project explores the **Melbourne Housing Dataset** with the goal of uncovering insights into the real estate market.  
Through **data cleaning, visualization, and exploratory data analysis (EDA)**, we answer questions like:  
- Which suburbs have the highest average house prices?  
- How do property types and number of bedrooms affect price?  
- How do housing prices trend over time?  
- What is the relationship between land size, building area, and price?  

The project is designed as a **portfolio piece** to demonstrate practical data analytics and storytelling with Python.  

---

##  Key Insights So Far  
- **Suburb Comparison**: Premium suburbs like Canterbury, Middle Park, and Malvern show significantly higher average house prices.  
- **Top Agencies**: Agencies like Buxton and Biggin handle the largest number of sales.  
- **Property Type Analysis**: Houses tend to have higher median prices than townhouses or units.  
- **Bedrooms vs Price**: Properties with unusually high bedroom counts skew averages, but 3–4 bedrooms tend to dominate the market.  
- **Time Trends**: Prices show noticeable fluctuations across years, capturing Melbourne’s real estate cycles.  
- **Correlation Study**: Price is moderately correlated with building area and number of rooms.  

---

##  Workflow  
1. **Data Cleaning**
   - Handled missing values in `BuildingArea`, `YearBuilt`, and `Landsize`  
   - Converted `Date` column to `datetime`  
   - Filtered outliers for more meaningful analysis  

2. **Exploratory Analysis**
   - Grouped by suburb, property type, and seller agency  
   - Aggregated mean/median values for better trend representation  

3. **Visualization**
   - Scatter plots to examine `Landsize vs Price`  
   - Bar charts for suburb and property type comparisons  
   - Time series trends for yearly average prices  

---

##  Tech Stack  
- **Python**: pandas, numpy  
- **Visualization**: matplotlib, seaborn  
- **Environment**: Jupyter Notebook  

---

##  Project Structure  

├── notebooks
│ └── eda_housing.ipynb # main notebook with analysis
├── data
│ └── melbourne_housing.csv (not uploaded due to size; see Kaggle link below)
├── README.md
└── requirements.txt