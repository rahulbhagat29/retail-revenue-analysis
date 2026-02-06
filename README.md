📊 Retail Revenue Analysis & Executive Dashboard

📌 Problem Statement
Retail transaction data often contains inconsistencies such as missing values, refunds, zero-quantity transactions, and pricing mismatches.  
These issues make raw revenue numbers unreliable for business decision-making.
The objective of this project was to clean, validate, and analyze retail sales data to produce **finance-safe KPIs** and an **executive-ready dashboard** that stakeholders can trust.

🛠 Tools Used
- Microsoft Excel  
  - Data Cleaning & Validation  
  - Calculated Fields  
  - Pivot Tables  
  - Executive Dashboard Design  

📊 Data Overview
The dataset contains transaction-level retail sales data including:
- Date
- Region
- Product Category
- Quantity
- Revenue
- Transaction Type (Sale, Refund, Zero-Quantity)

Special cases such as refunds, zero-quantity rows, and pricing inconsistencies were explicitly handled rather than removed.

🔍 Analytical Approach
1. Preserved raw data and created calculated fields to avoid overwriting original values.
2. Identified and handled missing, zero, and negative values using business logic.
3. Differentiated transactions into Sale, Refund, and Zero-Quantity categories.
4. Recalculated revenue to validate pricing accuracy.
5. Defined finance-aligned KPIs such as:
   - Gross Sales
   - Net Revenue
   - Refund Impact
6. Built an executive dashboard focused on performance, trends, and risk indicators.

📈 Key Insights
- Net revenue is closely aligned with gross sales, indicating strong pricing discipline and minimal leakage.
- Significant regional performance gaps exist, highlighting operational or execution differences.
- Sales exhibit high volatility over time, reducing forecast reliability.
- Revenue is concentrated in a small number of product categories, creating dependency risk.
- Refund impact is low, suggesting stable product quality and customer satisfaction.

🎯 Business Recommendations
- Maintain strict pricing and discount controls to preserve revenue integrity.
- Investigate underperforming regions to address staffing or process gaps.
- Reduce revenue volatility by identifying causes of zero-sales days.
- Diversify revenue across more product categories to reduce dependency risk.
- Continue monitoring refunds as a KPI, with investigation triggers if thresholds are breached.

⚠️ Limitations
- The dataset does not contain Order IDs, so metrics such as Average Order Value (AOV) are approximated.
- Analysis is limited to available transactional data and does not include customer demographics or marketing data.
- Insights are based on historical data and may vary with seasonality or future business changes.

🔮 Next Steps
- Extend analysis using SQL and Python for customer-level insights.
- Build an interactive dashboard using Power BI or Tableau.
- Incorporate customer and marketing data to enhance retention analysis.
