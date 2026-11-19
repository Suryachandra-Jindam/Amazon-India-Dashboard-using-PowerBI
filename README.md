# Amazon-India-Dashboard-using-PowerBI

An interactive Power BI dashboard for exploring Amazon India order, sales, and profit data. The project uses a sample dataset of 10,000 orders and presents key performance indicators with breakdowns by time, category, product, order status, payment method, and shipping state.

## Dashboard overview

The report includes views for:

- Overall sales and profit performance
- Monthly sales and profit trends
- Category and product performance
- Order status analysis
- Payment method and geographic analysis

Summary cards include total sales, total profit, total units sold, order count, and average order value. Report visuals can be interacted with to filter and compare the data.

## Dataset

The source workbook is `Amazon Sales Data India.xlsx`. It contains one worksheet with 10,000 order records and these fields:

| Field | Description |
| --- | --- |
| `Order_ID` | Unique order identifier |
| `Order_Date` | Date of the order |
| `Category` | Product category |
| `Product` | Product name |
| `Quantity` | Units ordered |
| `Unit_Price_INR` | Unit price in Indian rupees |
| `Discount_Pct` | Discount percentage recorded for the order |
| `Total_Sales_INR` | Total sales value in Indian rupees |
| `Profit_INR` | Profit in Indian rupees |
| `Payment_Method` | Payment method used |
| `Fulfillment` | Fulfillment channel |
| `Order_Status` | Order status |
| `Ship_State` | Shipping state or territory |

Dates in the supplied data range from 2024 through 2026. Monetary values are denominated in INR. The workbook is included as the source data for this analysis; check the terms and permissions that apply to your copy before redistributing it publicly.

## Files

```text
.
├── Amazon Dashboard.pbix       # Power BI report
├── Amazon Sales Data India.xlsx # Source workbook
└── README.md
```

If you use different file names or folders in your repository, update this list and the data source path in Power BI.

## Open the dashboard

1. Download or clone this repository.
2. Open `Amazon Dashboard.pbix` in Microsoft Power BI Desktop.
3. If Power BI prompts for the source workbook, select `Amazon Sales Data India.xlsx` from the repository folder and refresh the data.
4. Use the report pages and visual interactions to explore the results.

## Tools

- Microsoft Power BI Desktop
- Microsoft Excel (or another compatible spreadsheet application) for inspecting the source workbook

## Notes

- The report is provided as a `.pbix` file and is intended to be explored in Power BI Desktop.
- KPI values and visual results depend on the data loaded into the report and any filters applied.
- Add a dashboard screenshot to the repository (for example, `assets/dashboard-preview.png`) and link it here if you want a visual preview on GitHub.
