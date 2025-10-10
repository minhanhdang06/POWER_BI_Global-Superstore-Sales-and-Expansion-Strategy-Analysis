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
<img width="1231" height="691" alt="image" src="https://github.com/user-attachments/assets/22cbc499-3643-4e3d-b0af-211dc6353860" />

### Product analyst
<img width="1024" height="575" alt="image" src="https://github.com/user-attachments/assets/c671bb61-cdfd-44a1-86c0-b0a1f8309fec" />


### Insight and Recommendations
<img width="1023" height="575" alt="image" src="https://github.com/user-attachments/assets/5eff7124-49f8-4962-98f7-b9961af2961a" />



## IV. Insight & Recommendation

### Overview

Overall, revenue and profit performance has grown year by year. Significant increase in Total orders along with stable profit margins shows the company's business growth potential.

**Core Markets**: APAC and EU that bring bring the highest revenue to the company to the company with strong YoY growth (~51-55%).

**The return rate** tends to decrease (from 4.71% to 4.55% in 2014).

**The product categories** have a fairly even revenue distribution (Technology brings in the highest revenue with 4.74M and a profit margin of ~14%).

### Market Expansion

Currently, the company has a good revenue and profit stream in global markets. Instead of entering a completely new market, we recommend focusing on promoting existing markets.

- **APAC, EU:** These are the markets with the highest revenue and profit along with stable profit margins (12%-12.7%) → Continue to maintain business and management strategies.
- **LATAM and US** have quite solid revenue but suboptimal profitability with low YoY growth (48.5% and 46.9% respectively) → should optimally adjust costs, pricing policies, and product allocation strategies.
- **Canada:** Although Canada has a much lower revenue than the remaining markets (possibly due to infrastructure issues, not many stores, etc.), this market has a very large growth rate and a high Profit Margin (26.62%), thereby showing the potential to bring development to the company.

→ It is necessary to build a strategy (open more branches, develop products according to the preferences and habits of local people, etc.) to reach more customers in this market.

- **Africa and EMEA**: are the 2 least effective markets with a high number of buyers but low profits, in which the profit growth rate is high → consider withdrawing from these markets.

### **Product Performance**

Overall The products that bring in the highest revenue are the Smart Phone lines, showing the consumer preference for Technology products.

- Phones, Copiers, Chairs are the products that bring in the highest revenue → It is suggested that copiers and phones be positioned as a strategic product for the

For 4 years, Tables have brought in negative profits, which negatively affects the company's performance → Consider adjusting pricing or eliminating this product.
