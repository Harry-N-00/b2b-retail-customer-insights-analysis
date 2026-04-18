# 🛒 B2B Online Retail Analysis

## 📌 Overview
This project explores a B2B online retail dataset through data cleaning, preprocessing, and exploratory data analysis in Python. It focuses on understanding revenue patterns, customer behaviour, product performance, and business risks such as cancellations and returns. It also includes RFM (Recency, Frequency, Monetary) customer segmentation and customer lifetime value analysis to identify high-value customers and actionable business insights.

## 🛠️ Tools & Technologies
- Python (pandas, matplotlib, seaborn)
- Jupyter Notebook

## 📁 Project Structure
- Cleaning & Preprocessing
- Exploratory Data Analysis (Revenue, Customers, Products, and Risk Analysis)

## 🚀 Features
- [✓] Data cleaning and preprocessing (handling missing values, irrelevant transactional data, and invalid entries)
- [✓] Revenue analysis across invoices, time, customers, and countries
- [✓] Customer behaviour analysis including order patterns and lifetime value
- [✓] RFM segmentation to identify high-value, loyal, and at-risk customers
- [✓] Product performance and market basket (product pairing) analysis
- [✓] Time-based sales trends (monthly, daily, hourly patterns)
- [✓] Cancellation and return analysis with revenue loss estimation

## 📷 Screenshots
<img width="1489" height="590" alt="RFM_Distributions" src="https://github.com/user-attachments/assets/533394df-2446-4547-bfbf-6ce60dcaa0af" />

*Figure 1: Figure 1: Customer RFM segmentation with corresponding customer and revenue distribution subplots, illustrating concentration of revenue within high-value customer segments.*

 <img width="1233" height="470" alt="Revenue_AOV_Hour" src="https://github.com/user-attachments/assets/529ff205-1fc4-4eae-b9bd-65a2758222b6" />
 
 *Figure 2: Figure 2: Subplot showing revenue by hour alongside average order value (AOV) by hour. The line plot displays both the full dataset and the top 10% of customers on the same line graph for comparison.*

## 🔍 Key Insights
- Revenue concentration is highly skewed: A small percentage of customers contribute a large proportion of total revenue, highlighting the importance of key accounts.
- Customer segmentation reveals clear value groups: RFM analysis identifies high-value, loyal, and at-risk customers for targeted business strategies.
- Product demand is concentrated: A small number of products account for a significant share of revenue, indicating opportunities for inventory optimisation.
- Seasonal and time-based trends affect sales: Revenue varies by month, day, and time, suggesting predictable purchasing patterns.
- Geographic performance varies significantly: Certain countries dominate sales activity, showing core markets for business focus.
- Cancellations and returns reduce profitability: A measurable portion of revenue is lost due to cancellations, highlighting operational inefficiencies.
- Product pairing insights suggest cross-selling opportunities: Certain products are frequently purchased together, supporting bundle or recommendation strategies.
- Customer lifetime value highlights long-term value differences: A small group of customers contributes disproportionately to long-term revenue.

## 📦 Installation (for Python project)

### Python:
```bash
git clone https://github.com/Harry-N-00/b2b-retail-customer-insights-analysis.git
cd b2b-retail-customer-insights-analysis
python -m venv .venv
source .venv/bin/activate   # On Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

### Data:
- `Online Retail.xlsx`
