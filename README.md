# Coffee Shop Sales Analysis Dashboard

## 1. Project Title

**Coffee Shop Sales Analysis Dashboard**

## 2. Short Description

This project analyzes coffee shop transaction data to understand sales
performance, customer purchasing patterns, and product trends. The
workbook contains transaction-level data along with pivot-table
summaries and a dashboard sheet. It can help users explore revenue,
quantity sold, transaction volume, and performance by time, store
location, and product category.

## 3. Tech Stack

-   **Microsoft Excel** --- data storage, cleaning/organization, pivot
    tables, and dashboarding
-   **Pivot Tables / Pivot Charts** --- summarizing sales and
    transaction data
-   **Excel formulas and date/time fields** --- supporting time-based
    analysis

> If the dashboard is later rebuilt in Power BI, Power Query and DAX can
> be added for data transformation and measures.

## 4. Data Sources

-   **Source file:** `Coffee Shop Sales.xlsx`
-   **Primary data sheet:** `Sheet1`
-   **Dataset size:** 149,116 transaction records and 18 columns
-   **Additional workbook sheets:** `Pivot` (summary tables) and
    `Dashboard` (dashboard layout)

### Key fields

-   Transaction details: `transaction_id`, `transaction_date`,
    `transaction_time`
-   Store details: `store_id`, `store_location`
-   Product details: `product_id`, `product_category`, `product_type`,
    `product_detail`, `Size`
-   Sales metrics: `transaction_qty`, `unit_price`, `Total_bill`
-   Time analysis fields: `Hour`, `Day Name`, `Day of Week`, `Month`,
    `Month Name`

The source workbook is the data source for this project. No external
data source is identified in the workbook.

## 5. Features

-   **Sales performance analysis** using total bill/revenue and quantity
    sold
-   **Transaction analysis** using transaction counts
-   **Time-based trends** by hour, day of week, and month
-   **Product category analysis** to compare categories such as Coffee,
    Tea, Bakery, and other product groups
-   **Product-level analysis** using product type and product detail
-   **Store/location analysis** to compare sales across store locations
-   **Pivot-table summaries** for quick aggregation and comparison
-   **Dashboard view** for presenting key sales insights in a visual
    format
-   **Interactive exploration** where supported by the workbook's
    dashboard controls
