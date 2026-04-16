# Sales Data Analysis Project

## Business Objective
Analyze 200 sales transactions to identify top-performing products and regions, uncover sales trends, and provide actionable recommendations to increase revenue.

## Tools Used
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Google Colab

## Dataset
- **Rows**: 200  
- **Columns**: 7  
- **Columns**: `OrderID`, `Date`, `Product`, `Region`, `Quantity`, `UnitPrice`, `Revenue`

---

## Project Overview
This project analyzes sales data from 2025 to understand product and regional performance and deliver clear, data-driven recommendations.

## Key Insights

1. **Product Performance**
   - **Clothes** is the top revenue generator with **₦140,476** (27.9% of total).
   - **Shoes** follows with **₦103,048**.
   - **Laptops** was the weakest with **₦77,550**.

2. **Regional Performance**
   - **West** region leads with **₦156,565** (31.1% of total revenue).
   - **East** is second with **₦124,625**.

3. **Overall Metrics**
   - Total Revenue: **₦503,060**
   - Average Order Value: **₦2,515**
   - Average Quantity per Order: **4.87 units**

## Business Recommendations
- Prioritize **Clothes** with increased marketing and stock, especially in the **West** region.
- Expand operations/promotions in the **West** region.
- Investigate low performance of **Laptops** and introduce bundle offers.
- Expected impact: Focused strategy could increase revenue by **15–25%**.

## Visualizations

**Revenue by Product**  
![Revenue by Product](revenue_by_product.png)

**Revenue by Region**  
![Revenue by Region](revenue_by_region.png)

**Monthly Revenue Trend**  
![Monthly Revenue Trend](monthly_revenue_trend.png)

## How to Run the Project
1. Open the notebook [`Sales_data_Analysis.ipynb`](Sales_data_Analysis.ipynb) in Google Colab.
2. Upload `sales_data.csv` when prompted.
3. Run all cells.

## Future Improvements
- Add customer segmentation (RFM analysis)
- Build an interactive dashboard using Streamlit or Power BI
- Integrate SQL version of the analysis

## Author
**Anuforo Boniface**  
Location: Owerri, Imo, Nigeria
