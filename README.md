Decathlon Retail Performance Dashboard | Power BI

📌 Project Overview

This project focuses on analyzing retail sales performance, profitability, order activity, and product performance using Power BI. The dashboard provides an interactive view of key business metrics and allows users to compare Year-to-Date (YTD) performance with the corresponding period of the previous year.

**Note:** This is a portfolio project. The displayed figures are based on the project dataset and should not be interpreted as verified internal financial results from Decathlon.

 🎯 Business Objectives

- Monitor sales and gross profit performance.
- Track year-over-year business growth.
- Analyze sales across sports, product types, regions, and brands.
- Understand gross margin and average order value trends.
- Enable interactive analysis through dashboard filters.
- Identify areas that require further business investigation.

🛠️ Tools & Technologies

- **Power BI** — Dashboard development and data visualization
- **DAX** — KPI calculations and time-intelligence measures
- **Power Query** — Data preparation and transformation
- **Data Modeling** — Relationships between sales and date data
- **Excel / Dataset** — Data review and preparation, where applicable

📊 Key Performance Indicators

The following values are displayed in the current dashboard and should be validated against the underlying data model before being treated as final results.

| KPI | Dashboard Value |
|---|---:|
| Net Sales YTD | ₹55.26M |
| Net Gross Profit YTD | ₹21.72M |
| Gross Margin YTD | 39.3% |
| Units Sold YTD | 47.77K |
| Net Orders YTD | 24.08K |
| Net Average Order Value | ₹2.29K |
| Year-over-Year Sales Growth | 17.5% |

**Reporting period:** 1 January 2026 to 15 September 2026, compared with the equivalent period in 2025.

 📈 Dashboard Features

The dashboard includes:

- **KPI Cards:** Net Sales, Gross Profit, Gross Margin, Units Sold, Orders, and Average Order Value.
- **Monthly Sales Trend:** Comparison of current-year and previous-year sales.
- **Sales by Sport:** Analysis of sales contribution across sports categories.
- **Product Type Performance:** Comparison of sales and gross margin, with order volume represented by bubble size.
- **Regional Performance:** Net sales analysis by region.
- **Brand Growth:** Comparison of sales growth across brands.
- **Interactive Filters:** State, Sport, Colour, Payment Method, and Promotion.

💡 Business Questions

This dashboard is designed to help answer questions such as:

1. How are sales and profitability performing compared with the previous year?
2. Which sports and product types contribute most to sales?
3. Which regions generate the highest sales?
4. How does gross margin vary across product types?
5. Which brands show stronger or weaker sales growth?
6. Which areas require further investigation to improve business performance?

 🔍 Data Validation & Analysis

Before making business decisions, the following checks should be completed:

- Reconcile category-level sales with the total sales KPI.
- Verify the reporting period and year-over-year calculations.
- Validate gross profit, gross margin, order count, and average order value.
- Confirm how returns and quantities are handled.
- Check slicer defaults and filter interactions.

These checks help ensure that the dashboard provides consistent and reliable insights.

📁 Repository Structure

```text
Decathlon-Retail-Performance-Dashboard/
│
├── README.md
├── Decathlon_Project.pbix
├── images/
│   └── dashboard-screenshot.png
└── reports/
    ├── Decathlon_Retail_Performance_Executive_Report.pdf
    └── Decathlon-Dashboard-Business-Requirements.pdf
```

*Replace filenames with your actual filenames. Include only files you have saved and are authorized to share.*

🚀 How to Explore the Project

1. Open the dashboard screenshot in the `images` folder.
2. Review the executive report in the `reports` folder.
3. Download the `.pbix` file and open it using Microsoft Power BI Desktop, if included.
4. Use the dashboard filters to explore performance across different categories.
5. Review the data validation considerations before interpreting the results.

⚠️ Limitations

- The dashboard metrics are based on the project dataset and have not been independently verified against Decathlon's internal reporting.
- Potential data-model or filter-context inconsistencies must be resolved before drawing definitive conclusions.
- The dashboard identifies areas for further investigation; it does not establish the commercial root cause of performance changes.

👨‍💻 Skills Demonstrated

Power BI · DAX · Power Query · Data Visualization · KPI Reporting · Business Analysis · Data Modeling · Year-over-Year Analysis · Data Validation

👤 Author

**Harshada Shirke**

Aspiring Data Analyst | SQL | Python | Power BI | Excel

---

*Created as a Data Analyst portfolio project to demonstrate business-focused dashboard development and retail performance analysis.*
