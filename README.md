# Merchandise Sales Analysis
- [Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiOTAzNWRiMGEtZTBiNi00NGY5LTk5ZjQtNzMzNTg4ZDkyN2IxIiwidCI6IjQ2NTRiNmYxLTBlNDctNDU3OS1hOGExLTAyZmU5ZDk0M2M3YiIsImMiOjl9)
- [LinkedIn Post](https://www.linkedin.com/posts/shellynagar_datadna-builtwithzoomcharts-dataanalytics-activity-7287108820630147072-19p3?utm_source=share&utm_medium=member_desktop)

---
## Project Overview
This project was created as part of the FP20 Analytics December 2024 Challenge. Lee Chatmen, a popular influencer from the United States with over 7 million TikTok followers, gained fame for his entertaining videos featuring miniature guitar performances. In 2023, he launched his own merchandise line. This project analyzes his merchandise sales performance to derive meaningful insights.

---
## Data Model
![Screenshot 2025-02-09 010316](https://github.com/user-attachments/assets/014c5ef8-4f4e-4d45-a282-15ce0cc15699)

---

## Steps Taken
### 1. Data Exploration
- Conducted EDA using **Power Query**.

### 2. Data Cleaning & Transformation
- Removed **extra whitespaces, duplicates, and anomalies**.
- Ensured **proper formatting and data types**.
- Created **Calendar Table** for date-based analysis.
- Created additional tables for:
  - **Measures**
  - **Labels & Titles**

### 3. Data Modeling
- Established **relationships between the fact table and dimension tables**.
- Created **necessary measures and visualizations** to address key questions.
- Designed an **advanced filter pane** with a **restore button**.

---

## Visualizations & Dashboard Preview
![Screenshot 2025-02-09 010429](https://github.com/user-attachments/assets/243bc6bc-4b54-47c0-b1ab-a82d24d539d9)

![Screenshot 2025-02-09 010544](https://github.com/user-attachments/assets/44d7858b-b8e5-4ec8-8992-58ca325e8c83)
---

## Key Questions Answered

### 1. What are the overall sales trends?
- Revenue, orders, and quantity sold exhibit similar trends.
- Least contributing months: **February, June, August, and November**.
- **Highest contribution**:
  - **May 2024** (1,116 units sold)
  - **Highest revenue**: $80,704 (May 2024)
  - **Highest orders**: 668 (Jan 2024)
- **Lowest contribution**:
  - **November 2023** (908 units sold, $62,358 revenue, 527 orders)
  - **Domestic sales exceed international sales across all months except June 2024**.

🔴 _Note: we have not included or considered Nov-24 as for this month we have only 4 days data._

### 2. Which product categories perform the best?
- **Revenue Contribution**:
  - Highest: **Clothing Category - 74.40% (Avg. sales price/order: $172.03, Avg. rating: 3.5)**
  - Lowest: **Other category - 7.41% (Avg. sales price/order: $44.25, Avg. rating: 3.58)**
- **Quantity Sold**:
  - Highest: **Clothing Category - 49.43%**
  - Lowest: **Other category - 20.02%**
- **Orders**:
  - Highest: **Clothing Category - 50.09%**
  - Lowest: **Other category - 19.39%**

### 3. What are the most and least popular products?
- **Highest Revenue**: BF1548 ($190.64K, Clothing Category)
- **Lowest Revenue**: BF1555 ($8.67K, Others Category)
- **Highest Quantity Sold**: BF1548 (2.42K units, Clothing Category)
- **Lowest Quantity Sold**: BF1555 (227 units, Others Category)
- **Highest Ordered**: BF1548 (1.5K orders, Clothing Category)
- **Lowest Ordered**: BF1555 (0.13K orders, Others Category)

### 4. How does location affect sales performance?
- **Revenue**:
  - Highest: **Sydney ($48.05K, International, Avg. shipping: $100)**
  - Lowest: **Montreal ($23.64K, International, Avg. shipping: $25)**
- **Quantity Sold**:
  - Highest: **San Francisco (746, Domestic)**
  - Lowest: **New Delhi (289K units, International, Avg. shipping: $79)**
- **Orders**:
  - Highest: **New Jersey (434 orders, Domestic)**
  - Lowest: **Paris (171 orders, International, Avg. shipping: $50)**

### 5. What impact does international shipping have on sales?
- Domestic sales outperform international sales in revenue, quantity sold and orders.
- Higher-rated products (Avg. rating: **3.66**) are associated with locations having **$100 shipping charges**.
- Minimal difference in **average order quantity** between domestic and various shipping charge categories.

### 6. What is the demographic profile of buyers?
*(To be added)*

### 7. How do ratings and reviews correlate with sales?
- **Top review**: *"Lack of delivery delays is greatly appreciated"*
  - Appeared **466 times**, Avg. Rating: **4.52**, Revenue contribution: **6.79%** (highest), Order contribution: **6.30%** (highest)
- **Least frequent review**: *"Nothing too special"*
  - Appeared **105 times**, Avg. Rating: **3**, Revenue contribution: **1.68%**, Order contribution: **1.42%**
- **Top 5 reviews (highest count)** are **positive**, focusing on delivery, discounts, design, and affordability.
- **Bottom 5 reviews** include a mix of **negative and neutral tone reviews**.

### 8. What are the trends in shipping charges?
- **Highest average shipping charges** in **February, October, and November** (~$51 avg.).
- **Lowest average quantity per order** in these months (~1.6 units).

---
## Key Findings
- **Strong Domestic Sales**: Domestic sales consistently outperform international sales across all key metrics (revenue, quantity, and orders).
- **Seasonal Variations**: Certain months (Feb, Jun, Aug, Nov) show weaker sales, which can be targeted for improvement.
- **High Shipping Charges Impact International Sales**: While high-rated products exist in high shipping charge categories, international sales are still lower.
- **Top Products Drive Revenue**: A small set of products contribute disproportionately to revenue, necessitating strategic inventory planning.
- **Customer Sentiment is Generally Positive**: The highest-rated reviews emphasize quick delivery, good pricing, and product quality.
  
---

## Recommendations & Suggestions
- **Optimize pricing strategies** based on high and low-performing products.
- **Increase promotional efforts** for underperforming months (Feb, Jun, Aug, Nov).
- **Improve shipping efficiency** to boost international sales.
- **Enhance customer engagement** by leveraging review insights for marketing.
- **Expand product offerings** in high-performing categories.
- **Analyze demographic trends** to tailor product recommendations.

---
### Tools Used
- **Power BI** – Visualization
- **Power Query** – Exploratory Data Analysis (EDA)
- **Figma** – UX Design
- **Freepik & Flaticon** – Icons

---
## Future Scope
- Enhancing **UX design** for better interactivity.
- Conducting **deeper sentiment analysis on reviews**.
- New insights to be addded.

---
🔍 For more details, feel free to explore the repository and interact with the Power BI dashboard.

If you have any queries, suggestions, or feedback regarding this project, feel free to reach out.

---
## Author
Shelly Nagar
 - LinkedIn Profile-[https://www.linkedin.com/in/shellynagar/](https://www.linkedin.com/in/shellynagar/)
 - Email- [shelly.nagar@outlook.com](mailto:shelly.nagar@outlook.com)
