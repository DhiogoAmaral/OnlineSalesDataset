# OnlineSalesDataset
Online Sales Dataset - Popular Marketplace Data

This project was inspired by: https://www.youtube.com/watch?v=-C6lhl69ayc
Data used for the project is available at: https://www.kaggle.com/datasets/shreyanshverma27/online-sales-dataset-popular-marketplace-data

# 🛒 Online Sales Data Analysis

This project analyzes an e-commerce sales dataset to uncover trends, answer business questions, and extract actionable insights related to payment methods, regional preferences, and product performance.

## 📊 Project Objectives

- Answer key business questions using data analysis.
- Identify trends in sales over time.
- Investigate the impact of payment methods on revenue.
- Compare product category performance across different regions.
- Highlight top-selling products for inventory and marketing optimization.

---

## ✅ Key Business Questions & Answers

| Question | Answer |
|---------|--------|
| **Q1. Was there any discount on purchases?** | No, all purchases were made at full price. |
| **Q2. Which payment method is most important?** | Credit card – most commonly used and highest revenue. |
| **Q3. Are payment methods different across regions?** | Yes – Credit card (North America), PayPal (Europe), Split: Credit/Debit (Asia). |
| **Q4. Do product categories differ in payment method?** | No, each category consistently uses a single payment method. |

---

## 🔍 Insights

- 📉 **Sales decrease over the year**, indicating a seasonal trend. *(Sheet: I1Analysis)*
- 🌍 **Product category popularity varies by region**. *(Sheet: I2Analysis)*
- 💳 **Payment methods affect sales volume and revenue**. *(Sheet: Q2Analysis)*
- 🏆 **Top-selling products identified per category**. *(Sheet: I4Analysis)*
- 🎯 **Different product categories perform better in different regions**, guiding targeted campaigns. *(Sheet: I2Analysis)*

---

## ⚙️ Data Preparation & Analysis Steps

1. Uploaded dataset to Google Drive.
2. Imported data into Google Sheets.
3. Created a working copy: `Copy of Online Sales Data`.
4. Cleaned and formatted data (column types, duplicates).
5. Created new columns:
   - `Total Revenue (without discounts)`
   - `ifNoDiscount` (to detect possible discounts)
6. Built multiple pivot tables and charts:
   - Q2Analysis – Payment method impact
   - Q3Analysis – Regional payment differences
   - Q4Analysis – Payment method by category
   - I1Analysis – Sales trends by quarter
   - I2Analysis – Category performance by region
   - I4Analysis – Top-selling products per category

---

## 🧰 Tools Used

- **Google Sheets** – Data cleaning, pivot tables, charts
- **Google Slides** - Presentation
- **Google Drive** – File management

---

## 📁 File Structure

```text
├── README.md
├── OnlineSalesData.xlsx
└── Presentation.pptx
