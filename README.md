# POWER BI-Global Superstore Sales and Expansion Strategy Analysis
## I. Introduction

### 📌 Overview

📘 **What is Project about:** 

This project aims to build a Power BI dashboard using the Global Superstore Sales dataset, which includes data on transactions **(Orders)**, sales representatives **(People)**, and product returns **(Returns)**. The goal is to provide senior managers with data-driven insights to:

- **Understand current business performance**
- **Optimize market expansion strategies**
- **Identify strategic products for growth**

❓ **Business Question :**

The needs of Senior Managers revolve around 3 main questions:

☑️ What is the current business overview?

☑️ Which markets should Superstore expand into to increase revenue ?

☑️ Which products should be prioritized for strategic growth?


### 📁 Introduction to Dataset

- **Dataset**: Global Superstore Sales

Dataset stores sales information of some products of a company worldwide

- **Size:** The **Orders** table contains 51,290 records.
- **Format**: CSV

Consists of 3 data tables:

🛒 **Table 1: Orders**: Contains detailed transaction and customer information

👥 **Table 2: People**: Information of Sales person.

🔁 **Table 3:** Returns: Information of Returned orders

📊 **Relationships**
<img width="913" height="482" alt="image" src="https://github.com/user-attachments/assets/b61debed-21dd-4693-af9e-e8222d9532bc" />


| **From Table** | **To Table** | **Join Key** | **Relationship Type** |
| --- | --- | --- | --- |
| Orders | People | Region | Many-to-One (multiple orders belong to one region) |
| Orders | Returns | Order ID | One-to-One or Left Join (not all orders are returned) |
## II. Design Thinking

Here is the process of Design Thinking.

### 1️⃣ Step 1: Empathize
<img width="964" height="540" alt="image" src="https://github.com/user-attachments/assets/565bd222-fbd1-4bd3-9842-22261c4019a5" />

<img width="963" height="542" alt="image" src="https://github.com/user-attachments/assets/4292cc43-3789-40d5-8e9a-086bd01ca3bd" />

### 2️⃣ Step 2: Define POV
<img width="961" height="540" alt="image" src="https://github.com/user-attachments/assets/747a142f-e18f-4551-bdb1-64d66205dde4" />

### 3️⃣ Step 3: Ideate ideas
<img width="956" height="537" alt="image" src="https://github.com/user-attachments/assets/0dd80fc2-5ffd-47f2-b731-1a90474b0412" />

<img width="960" height="535" alt="image" src="https://github.com/user-attachments/assets/2a04a4e9-b327-4d08-a2a4-87fab3f6224c" />

<img width="962" height="540" alt="image" src="https://github.com/user-attachments/assets/5cee86be-b134-4d5e-a731-b2f4dd2a15d2" />


### 4️⃣ Step 4: Prototype, Iteration and Review
This part in the Dashboard
## III. Visualization

### Overview
<img width="1024" height="575" alt="image" src="https://github.com/user-attachments/assets/cdf6de84-c0ac-44f5-9ccb-6fe9d31bfd84" />

### Market analyst
<img width="1025" height="572" alt="image" src="https://github.com/user-attachments/assets/613820c3-a21e-4874-b1eb-bc3e1adbc3e5" />

### Product analyst
<img width="1024" height="575" alt="image" src="https://github.com/user-attachments/assets/c671bb61-cdfd-44a1-86c0-b0a1f8309fec" />


### Insight and Recommendations
<img width="1025" height="571" alt="image" src="https://github.com/user-attachments/assets/2eb2bd50-2d16-44bd-a138-bf7023271dd6" />



## IV. Insight & Recommendation

### Market Expansion

1. **Market Overview**: The company has established presence in all major global markets. Rather than entering a completely new market, it is recommended to expand within the existing market. Canada market is recommended.

Despite its strong Year-over-Year (YoY) growth rate and profit margin, Canada’s customer base remains limited, resulting in lower revenue.

-> It is proposed to develop a strategy to reach a broader customer segment in Canada.

1. **Sales Agent**: Nicole Hansen is currently responsible for the Canadian market. The revenue, profit margin, and YoY growth rate indicators are performing well. It is advisable to continue his/her oversight of this market.
2. **Product Strategy**: Phone, Copiers, Chairs, Bookcases are the company’s best-selling product overall. It is suggested that copiers and phone be positioned as a strategic product for the company.

### Current Market Optimization

- **APAC Market**: Maintain the current strategy for this market as this market has been the best performer overall. Continue to invest heavily in APAC, focusing on high-performing categories like Technology and Furniture (each generating over 1.3M in revenue). Slightly improve the return rate (currently around 6–7%) to boost profit margin further.
- **The EU market** generates ~3M in revenue with a 10–13% profit margin and strong ~55% YoY growth. Focus on expanding Technology and Office Supplies, while maintaining product quality as return rates are stable (6–6.8%).
- **US Market**: Focus on increasing revenue, as the US market shows excellent profitability. Consider expanding product offerings or ramping up marketing efforts.
- **LATAM Market**: Invest cautiously: LATAM has strong growth but low margins.
- **Ineffective Markets:** Africa and EMEA are underperforming, with high customer numbers but negative total profits.

-> It is recommended to investigate the causes behind these issues to develop appropriate strategies for either improvement or withdrawal from these markets.

**Product Performance:**

- Tables have shown poor performance with negative profit margins over the past four years, resulting in losses with each sale --> Discontinue this product or adjust its pricing.
- The return rate for Canon Copier has reached 20% --> Investigate the causes behind this high return rate and implement corrective measures.
