# SwiftLog Logistics Analytics & Business Intelligence

## Project Overview

This project was completed as part of the **AnalystLab Africa Experience Lab Internship Programme - Week 5 Data Analytics Track**.

The project focuses on analysing SwiftLog Logistics Limited's business operations using Power BI. It transforms logistics data into interactive dashboards and business insights to support decision-making, monitor performance, and identify opportunities for operational improvement.

## Business Objectives

The project aims to help SwiftLog management:

- Monitor business performance through key performance indicators (KPIs).
- Analyse revenue, orders, customers, and product performance.
- Evaluate delivery efficiency and shipment delays.
- Monitor inventory levels across warehouses.
- Understand customer purchasing behaviour and product returns.
- Support data-driven operational and strategic decisions.

## Tools and Technologies

- **Microsoft Power BI Desktop** - interactive dashboards and data visualisation.
- **Power Query** - data cleaning and transformation.
- **DAX (Data Analysis Expressions)** - KPI calculations and business metrics.

## Dashboard Pages

The Power BI report contains five pages:

1. **Executive Dashboard** - overview of revenue, orders, customers, shipments, delivery performance, and returned orders.
2. **Customer Analytics** - customer revenue, order activity, and customer trends.
3. **Inventory & Warehouse** - inventory levels, low-stock products, and warehouse comparisons.
4. **Shipment & Delivery** - shipment trends, delivery status, and delayed shipments.
5. **Supplier & Product** - supplier directory, product categories, and revenue by product.

## Key Findings

The dashboard highlights the following results from the available data:

| KPI | Result |
|---|---:|
| Total Revenue | 21.67M |
| Total Orders | Approximately 5,000 |
| Total Customers | Approximately 1,000 |
| Total Shipments | Approximately 5,000 |
| On-Time Delivery Rate | 36.28% |
| Returned-Order Rate | 9.46% |
| Average Delivery Delay | 3.57 days |
| Recorded Inventory Stock | Approximately 1,007K units |

*Note: The source data does not specify a currency. September 2026 data is partial, ending on 8 September 2026, so it should not be compared directly with complete months.*

## Data Preparation

The data preparation process included:

- Importing and inspecting the supplied datasets.
- Reviewing column names, data types, and data quality.
- Cleaning and transforming data using Power Query.
- Removing exact duplicate records from the Inventory table, reducing it from 4,000 to 3,997 rows.
- Creating relationships between compatible tables.
- Developing DAX measures for business performance monitoring.

## Business Recommendations

Based on the dashboard findings, the project recommends:

1. Investigate the causes of delayed deliveries and improve delivery monitoring.
2. Review dispatch and warehouse processes to identify avoidable delays.
3. Monitor low-stock products to support timely replenishment.
4. Improve supplier data integration to enable supplier performance analysis.
5. Record warehouse capacity to measure warehouse utilization accurately.
6. Capture dispatch and delivery timestamps to calculate delivery duration.
7. Improve regional data collection to compare delivery performance across regions.
8. Link returns to individual products or order items to identify product-specific return issues.
9. Investigate return reasons, particularly those related to late deliveries.
10. Establish regular KPI reviews to monitor progress and guide operational improvements.

## Data Limitations

Some metrics requested in the assignment could not be reliably calculated from the available fields:

- Supplier performance scoring requires a suitable relationship between supplier, product, and shipment records.
- Warehouse utilization requires warehouse capacity data.
- Delivery duration requires dispatch and delivery timestamps.
- Regional delivery analysis requires a usable region field.
- Product-level return rates require returns to be linked to products or order items.
- The inventory turnover measure is a proxy, not a standard inventory turnover ratio.

These limitations are documented to avoid presenting unsupported figures as facts.

## Project Structure

```text
swiftlog-logistics-analytics/
├── Data/
│   └── Original_Datasets/
├── Dashboard/
│   └── SwiftLog_Analytics.pbix
├── Report/
│   ├── Executive_BI_Report.pdf
│   └── Dashboard_Screenshots.pdf
├── Presentation/
│   └── Executive_Presentation.pptx
├── Images/
├── References/
└── README.md
```

## How to Explore the Project

1. Open `Dashboard/SwiftLog_Analytics.pbix` using Power BI Desktop.
2. Explore the five report pages and available interactive features.
3. Read `Report/Executive_BI_Report.pdf` for the executive summary.
4. View `Report/Dashboard_Screenshots.pdf` for static screenshots.
5. Open `Presentation/Executive_Presentation.pptx` for the executive presentation.

## Conclusion

This project demonstrates how business intelligence techniques can transform logistics data into actionable business insights. It provides a foundation for monitoring operational performance and identifying areas for improvement, while highlighting data integration gaps that should be addressed in future analytics initiatives.
