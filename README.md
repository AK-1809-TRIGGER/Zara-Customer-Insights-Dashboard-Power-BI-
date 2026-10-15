# Zara Customer Insights Dashboard (Power BI)

An interactive 5-page Power BI dashboard analyzing spending, loyalty, channel behavior and customer perception for **1,000 Zara customers across 6 GCC countries**.

## Business Questions
- Who are the customers and where do they shop?
- Which segments (country, income, loyalty tier, channel) drive the most spend?
- What drives satisfaction, and what pushes customers toward competitors?

## Dataset
- **Rows:** 1,000 customers (no duplicate IDs, no missing values)
- **Columns:** 24, covering demographics, channel and store type, loyalty tier, promo exposure, spend, ratings, NPS and competitor-switch risk
- **Coverage:** UAE, Saudi Arabia, Qatar, Bahrain, Kuwait, Oman (14 cities)

## Data Preparation (Power Query)
- Loaded the Excel source and promoted headers
- Set correct data types for all 24 columns
- Created an **Age Group** column (1-18, 19-35, 36-48, 48++) with a conditional column

## Dashboard Pages
| Page | What it shows |
| --- | --- |
| Customer Demographics & Overview | Total customers, age group, gender, city and income mix |
| Spending & Revenue Insights | Spend by loyalty tier, city, income bracket and promo type |
| Loyalty, Returns & Risk | Loyalty mix, returns, competitor-switch risk by income and channel |
| Customer Experience & Product Perception | Satisfaction, delivery, NPS and store experience by store type |
| Spend vs Visit Frequency | Spend and visit frequency by loyalty tier, channel mix by country |

All pages include slicers for Gender, City, Income Bracket and Loyalty Tier.

## Key Insights
- **UAE and Saudi Arabia drive ~75% of total spend** (39% and 35%). UAE has the highest average monthly spend per customer (~340 AED).
- **Omnichannel customers spend ~15% more** than store-only customers (~361 vs ~315 AED per month).
- **Loyalty gap:** 33% of customers have no loyalty tier yet contribute 33% of spend. Platinum customers spend ~21% more than Basic, but are only 5% of customers.
- **Stockouts hurt retention:** customers with frequent stockouts have a satisfaction score of 6.3 vs 7.2 for those with none, and ~32% higher competitor-switch risk (4.4 vs 3.3).
- **Satisfaction drivers:** NPS (0.77), product quality (0.70), brand affinity (0.69) and store experience (0.65) correlate most strongly with satisfaction. Discount rate shows almost no relationship (-0.03).
- **Income matters:** customers earning 35k+ AED spend ~49% more than those under 5k.
- **Flagship stores** have ~20% higher average spend than standard mall stores.

## Recommendations
- Convert non-loyalty customers (33% of base) into loyalty tiers, since higher tiers spend more.
- Prioritize stock availability for high-demand items to lower switch risk.
- Promote omnichannel usage, which shows the highest spend.
- Focus retention on product quality and store experience rather than deeper discounts.

## Tools
Power BI Desktop, Power Query, Excel

## Files
- `Zara_Customer_Insights.pbix`: Power BI report
- `/images`: dashboard screenshots
- `/data`: source dataset

## Screenshots
<img width="1331" height="775" alt="image" src="https://github.com/user-attachments/assets/7506a205-6cfd-4720-8c48-43ac035fadcd" />

<img width="1356" height="782" alt="image" src="https://github.com/user-attachments/assets/1f481298-6376-4d98-af28-7e8359315def" />
