# Brazilian E-Commerce Data Analysis & RFM Segmentation

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data_Manipulation-yellow.svg)
![Seaborn](https://img.shields.io/badge/Seaborn-Data_Visualization-lightgrey.svg)

## 📌 Executive Summary
This project analyzes a real-world Brazilian E-commerce dataset (Olist) containing over 100,000 orders from 2016 to 2018. The primary goal is to uncover actionable business insights regarding customer purchasing behavior, revenue trends, geographical distribution, and logistics performance. 

A key feature of this project is the implementation of an **RFM (Recency, Frequency, Monetary) Segmentation** model to categorize customers into actionable tiers, alongside a detailed analysis proving the direct impact of late deliveries on customer review scores.

## 🗂️ Project Structure
*   `data/` - Contains the raw CSV files (Olist dataset).
*   `notebooks/` - Contains the Jupyter Notebook (`ecommerce_analysis.ipynb`) with the complete code and visualizations.
*   `images/` - Contains exported charts used in this README.
*   `reports/` - Detailed analytical report in Word/Markdown format.

## 📊 Key Insights & Visualizations

### 1. Customer Segmentation (RFM Analysis)
Customers were segmented into 'Champions', 'Loyal Customers', 'At Risk', and 'Lost/Low Value'. The analysis reveals a highly right-skewed frequency distribution, with the vast majority of users making only a single purchase.
> ![RFM Segmentation](images/rfm_segmentation.png) *(Note: Add your RFM bar chart here)*

### 2. Revenue by Product Category
The top 10 product categories generate a disproportionate amount of total revenue, highlighting areas for focused marketing spend.
> ![Top Categories](images/top_categories.png) *(Note: Add your horizontal bar chart here)*

### 3. Geographical Dominance
The state of São Paulo (SP) accounts for the massive majority of total orders, drastically outpacing all other Brazilian states.
> ![Orders by State](images/orders_by_state.png) *(Note: Add your state distribution bar chart here)*

### 4. The Cost of Late Deliveries
There is a stark contrast in customer satisfaction based on logistics. Orders delivered on time or early receive significantly higher review scores compared to late deliveries.
> ![Delivery Satisfaction](images/delivery_satisfaction.png) *(Note: Add your On-Time vs Late review score chart here)*

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/olist-ecommerce-analysis.git
   ```
2. Install the required dependencies:
   ```bash
   pip install pandas matplotlib seaborn folium
   ```
3. Run the Jupyter Notebook located in the `notebooks/` directory.

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.