# 🚴‍♀️ Bike Sales dataset

This dataset contains transactional data for bike sales across various countries, customer demographics, and product categories. It was used to practice and apply Excel pivot table skills and data analysis techniques.

## 📁 Dataset Overview

- **Sales Data**: Includes `Sales Order #`, `Date`, `Country`, `State`, `Product Category`, `Sub-Category`, and `Product Description`.
- **Customer Demographics**: Captures `Customer Age`, `Age Group`, and `Gender`.
- **Financial Metrics**: Contains `Order Quantity`, `Unit Cost`, `Unit Price`, `Profit`, `Cost`, and `Revenue`.

![Screenshot 2025-06-10 at 15 45 21](https://github.com/user-attachments/assets/1fa4eacb-f969-4848-8774-51c6009f8e9a)

## 📊 Key Metrics and Aggregates

- **Total Order Quantity by Country, Age Group, and Gender**:
  - Highest sales volume observed in the **Adults (35–64)** group.
  - **United States** and **Australia** were the top-performing countries in terms of order quantity.

- **Product Trends**:
  - **Mountain Bikes** were the only sub-category sold.
  - Popular models included *Mountain-200 Black*, *Mountain-400-W Silver*, and *Mountain-500 Silver*.

## 🧠 Key Learnings

From this exercise, I learned:

- How to **analsze sales performance** across different customer segments and regions.
- The importance of **age group segmentation** in understanding customer purchasing behavior.
- How to **track profitability** by comparing unit cost, unit price, and profit margins.
- How to **identify top-selling products** and regions using pivot tables.

## 🧮 Excel Features and Formulas Used

- **Pivot Tables**:
  - Created to summarise order quantities by `Country`, `Age Group`, and `Gender`.
  - Used to analyse total revenue and profit by product and region.

![Screenshot 2025-06-10 at 15 47 39](https://github.com/user-attachments/assets/478a8080-ba9f-4c90-b6b7-0d80046034a2)

![Screenshot 2025-06-10 at 15 47 59](https://github.com/user-attachments/assets/bd5d8453-f8b7-464a-98d3-53b4148e238b)

![Screenshot 2025-06-10 at 15 51 04](https://github.com/user-attachments/assets/d48c9ddc-f824-47d4-8e39-4649e6ad998c)

- **Sorting and Filtering**:
  - Applied to quickly identify top-performing age groups and countries.

- **Formulas**:
  - `=Revenue - Cost` – Calculated profit per transaction.
  - `=Unit Price * Order Quantity` – Computed total revenue.
  - `=VLOOKUP()` – Used to fetch product details or pricing from a reference table.

- **VLOOKUP Usage**:
  - Example:  
    ```excel
    =VLOOKUP([@Product_Description], ProductTable, 2, FALSE)
    ```
    Used to retrieve unit cost or category information based on product description.

- **Conditional Formatting**:
  - Highlighted high-profit transactions and low-performing regions.

## 🔍 Suggested Analyses

- Profitability by **country** and **age group**.
- Sales trends by **product model** and **region**.
- Gender-based purchasing behavior.
- Seasonal trends using the `Date` and `Month` fields.

---

This lab was a valuable exercise in applying Excel pivot tables and formulas to real-world sales data, enhancing both my analytical and technical skills.
