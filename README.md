# Gym Equipment Profit Sales Analysis

Table of Contents

- [Project Background](#project-background)
- [Executive Summary](#executive-summary)
- [Insights Deep-Dive](#insights-deep-dive)
    - [Sales Trends and Growth Rates](#sales-trends-and-growth-rates)
    - [Key Product Performance](#key-product-performance)
    - [Customer Growth and Repeat Purchase Trends](#customer-growth-and-repeat-purchase-trends)
    - [Loyalty Program Performance](#loyalty-program-performance)
    - [Sales by Platforms & Channels](#sales-by-platforms--channels)
    - [Refund Rate Trends](#refund-rate-trends)
- [Recommendations](#recommendations)
- [Assumptions and Caveats](#assumptions-and-caveats)

***

## Project Background

This project is analyzing the gym equipment market to evaluate yearly and monthly profit trends, category, supplier, and brand performance for the gym equipment industry, providing actionable insights and recommendations for sustained growth and profitability.

## Executive Summary

Gym Equipment sales analysis of 1,233 records from years 2018-2024 shows monthly profits, YTD and MAT Profits across gym brands, suppliers, and category of gym equipment. Overall from 2018 to 2024, Airbikes is the leading gym equipment category with $5.76M total profits; Peak Performance Gear leads supplier profit contributions with $5.77M total; and Steel Power is the top performing gym brand with $2.88M total profits. 

In 2024 so far, Apex Athletics currently leads the airbikes market share contributing 18% of sales; Elevate Fitness leads the rowing machines market share contributing 21% of sales, and Spartan Sports leads the treadmills market share contributing 21% of sales.

Companies can benefit from expanding top product lines, optimizing bundling, and enhancing loyalty fitness programs to increase customer lifetime value. Targeted marketing and sales campaigns in certain monthly peaks throughout the year, along with improvements to digital channels to reach broader audience, will strengthen a companies market position and drive sustainable growth.

![ByteX Dataset ERD](Data/visualizations/ecommerce_ERD.webp)
Gym Equipment Market Dataset ERD

## Insights Deep-Dive

### Profit Trends and Growth Rates

1. Yearly Profit Trends
Observation: Profits have shown a declining trend over the years (excluding 2024).
Potential Causes:
Market Saturation: Demand for gym equipment may have stabilized.
Competitive Pressures: Increased competition may have reduced margins.
Economic or Consumer Shifts: Changes in fitness trends or economic factors.
Recommendations:
Innovate Product Lines: Introduce trending items like smart fitness or eco-friendly equipment.
Expand Markets: Target new regions or demographics to offset saturation.
Focus on High-Margin Categories: Invest in products like Airbikes, which dominate profitability.

2. Monthly Profit Trends
Observation: Significant spikes in profits during May (Month 5), August (Month 8), and December (Month 12).
Key Drivers:
May: Pre-summer fitness preparations.
August: Back-to-school promotions.
December: Holiday shopping and New Year’s resolutions.
Recommendations:
Optimize Inventory: Stock up for peak demand periods in these months.
Seasonal Campaigns:
May: “Summer Fitness Prep” promotions.
December: “New Year, New You” campaigns.
Boost Off-Peak Months:
Introduce discounts or bundle deals to stimulate demand during slower months.

3. Category Performance
Top Categories by Monthly Profit:
Airbike: $5.76M
Rowing Machine: $4.83M
Treadmill: $4.81M
Insights:
Airbikes are significantly outperforming other categories.
Rowing Machines and Treadmills are closely competitive but lag behind Airbikes.
Recommendations:
Focus on marketing and innovation for Airbikes to maintain the lead.
Investigate ways to improve profitability for Rowing Machines and Treadmills.

4. Supplier Performance
Top Suppliers by Monthly Profit:
Peak Performance Gear: $5.77M
Iron Strength Equipment Co.: $4.82M
Titan Fitness Supply: $4.81M
Insights:
Peak Performance Gear leads, but Iron Strength and Titan Fitness Supply are close competitors.
Recommendations:
Strengthen partnerships with Peak Performance Gear to maximize profitability.
Identify operational improvements for other suppliers to enhance growth.

5. Brand Performance
Top Brands by Monthly Profit:
Steel Power: $2.88M
Elevate Fitness: $1.94M
Titan Training: $1.93M
Insights:
Steel Power significantly outperforms others, while Elevate Fitness and Titan Training are close competitors.
Recommendations:
Expand Steel Power’s market presence to maintain the lead.
Position Elevate Fitness and Titan Training as alternatives for niche markets.

6. YoY & MoM Growth Trends
Supplier-Level Trends:
Titan Fitness Supply: Most volatile, with sharp declines (2020, 2022) and strong recoveries (2021, 2023).
Iron Strength Equipment Co.: Consistently modest growth with limited fluctuations.
Peak Performance Gear: Steady recovery from double-year declines in 2019–2020.
Overall Growth Insights:
Average YoY growth rates vary significantly, with suppliers showing cyclical patterns.
Recommendations:
Stabilize Volatile Suppliers:
Focus on operational efficiency for Titan Fitness Supply to reduce sharp fluctuations.
Leverage Recovery:
Use Peak Performance Gear’s growth momentum to introduce new premium products.
Drive Consistency:
Invest in predictive analytics and strategic planning for all suppliers to mitigate risks.

Final Recommendations
Capitalize on Trends:
Focus marketing and inventory efforts on high-profit months (May, August, December) and leading categories (Airbikes).
Optimize Supply Chain:
Work closely with high-performing suppliers to ensure steady profitability.
Enhance Innovation:
Develop unique products (smart or eco-friendly fitness equipment) to counteract market saturation and attract new customers.
Expand Market Reach:
Target underpenetrated regions or new demographics to drive growth and offset declining profits.


![Annual Sales and Growth Rates](Data/visualizations/annual_sales.webp)
![Monthly Metrics](Data/visualizations/monthly_metrics.webp)


### Key Product Performance

- During the pandemic, laptop sales soared, with MacBook orders increasing by 400% and ThinkPad by 220%. This trend has since reversed post-pandemic.
- Four products: monitors, AirPods, laptops, and Samsung Cable Pack, generate 96% of total revenue.
- AirPods account for 45% of all orders ($7.7M revenue).
- Monitors lead in revenue, contributing $9.8 million (35% of total sales) from 2019 to 2022.
- Samsung Cable Pack represents 20% of orders but only 2% of revenue, likely due to its low price or use in promotions.

![Product Performance Table](Data/visualizations/product_performance.webp)

### Customer Growth and Repeat Purchase Trends

- ByteX's unique customers grew steadily from 2019 to 2021, peaking at nearly 30,000 in 2021, but declined sharply by nearly 40% in 2022.
- Repeat purchase rates (≥2 orders) consistently decreased, from 20.22% in 2019 to 14.76% in 2022, indicating challenges in retaining customers after initial purchases.
- The stability in the number of repeat customers suggests a core base of loyal customers who consistently make multiple purchases each year.
- The decline in both unique and repeat customers in 2022 highlights potential shifts in market dynamics or customer preferences.

![Customer Retention Table](Data/visualizations/customer_retention.webp)


### Loyalty Program Performance

- Loyalty members make their first purchase 20 days earlier (30% less time) than non-loyalty members (50 days vs. 70 days).
- Post-pandemic, loyalty metrics surged but began slowing by 2022.
- Loyalty members now lead in key metrics, generating $500K more in revenue, spending $30 more per order, and placing 500K more orders than non-loyalty members.
- The loyalty program performs strongly in North America, while APAC and LATAM regions remain volatile, suggesting a need for targeted strategies.
- Loyalty purchases have a higher refund rate than non-loyalty purchases.

![Loyalty Program Performance Table](Data/visualizations/loyalty.webp)
![Loyalty Program Annual Metrics](Data/visualizations/loyalty_metrics.webp)


### Sales by Platforms & Channels

- Direct channel account for 83% ($23M) of ByteX's sales.
- Social media contributes 1% of sales, and affiliate channels contribute 3% ($878K).
- Affiliate channels have the highest average order value (AOV) at $303, while email campaigns have the lowest AOV at $181.
- The website generates 97% ($27M) of sales with an AOV of $304, whereas the mobile app ($867K) lags with an AOV of $47.
- Further considerations on channel performance are detailed in the assumptions and caveats section.

![Sales by Platform and Channel](Data/visualizations/channel_platform.webp)


### Refund Rate Trends

- Refund rates for high-ticket items peaked early in the pandemic but have since stabilized at 4-6%.
- In 2021, refunds decreased across all products compared to the the previous two years.
- Laptops had the highest refund rates in 2019 and 2020 (17%) but have since dropped to 6-9%, aligning with other product categories.
- Apple Airpods Headphones have the highest refund count at 2.6K (5% refund rate).
- Loyalty purchases exhibit a higher refund rate than non-loyalty purchases, potentially warranting further investigation.

![Loyalty Impact on Refund Rates](Data/visualizations/loyalty_impact_refund.webp)

## Recommendations

Maximizing Product Offerings

- **Expand High-Performing Categories**: Increase catalog variations in monitors, AirPods, and laptops to meet diverse customer needs with premium models, driving repeat purchases and solidifying market presence.
- **Optimize Samsung Cable Pack**: Reevaluate the Samsung Cable Pack's pricing strategy, bundle it with high-value items, or offer as a promotional gift to increase average order value (AOV) and revenue contribution.

***

Customer Growth and Retention

- **Boost Repeat Purchases**: Target single-purchase customers with personalized re-engagement campaigns and introduce tiered rewards within the loyalty program to incentivize frequent purchases and improve retention.
- **Revitalize Customer Acquisition**: Expand acquisition channels to include social media, influencer partnerships, and affiliate programs. Refine ByteX's messaging to re-engage past customers and attract new ones.
- **Leverage Core Customer Insights**: Analyze behaviors and preferences of repeat customers to enhance loyalty campaigns. Introduce referral incentives to drive word-of-mouth growth and increase new customer acquisition from existing networks.

***

Loyalty Program Enhancements

- **Enhance Loyalty Onboarding**: Implement targeted onboarding campaigns with first-purchase discounts or early access offers. Tiered rewards will further incentivize frequent purchases and strengthen customer loyalty.
- **Data-Driven Program Refinement**: Continuously monitor loyalty metrics to refine program offerings based on data, ensuring sustained engagement and effectiveness.

***

Maintaining Low Refund Rates

- **Sustain Successful Practices**: Replicate effective strategies from 2021, including detailed product descriptions, stringent quality control, and robust post-purchase support, to maintain low refund rates and meet customer expectations.

***

Optimizing Channels and Platforms

- **Expand Affiliate Partnerships**: Increase affiliate partnerships or offer higher commissions to attract influential marketers, enhancing brand reach and boosting AOV.
- **Enhance Mobile App Experience**: Improve the mobile app's checkout and personalization features to capitalize on rising mobile usage and increase its contribution to total sales.

***

Regional Growth Strategies

- **Focus on High-Performing Regions**: Continue allocating resources to North America and EMEA with regionalized marketing and product availability strategies tailored to local preferences.
- **Target Growth in APAC and LATAM**: Leverage localized partnerships and culturally tailored promotions to capture growth potential in APAC and LATAM, stabilizing sales in these emerging markets.

***

## Clarifying Questions, Assumptions, and Caveats

### Questions for Stakeholders Prior to Project Advancement

- **Unmatched `customer_id` Records**
    - Which table should be the primary source for `customer_id` to maintain data consistency across analyses?

- **`marketing_channel` and `account_creation_method` in the `customers` table**
    - How is this data recorded, and what does it specifically represent?
    - What factors contribute to their deterministic relationship?
    - Does `marketing_channel` capture the initial account creation touchpoint, or does it represent the origin of each individual purchase (which is more relevant for tracking sales)?

- **`loyalty_program` in the `customers` table**
    - Is `loyalty_program` account-specific or tied to individual orders?
    - Can loyalty membership status vary between orders for the same user, i.e., is it a subscription or a one-time sign-up?

### Assumptions and Caveats

- **Refund Records**: No refunds were recorded for 2022, which is an anomaly warranting further examination.
- **Deterministic Relationship in Data**: Each `marketing_channel` is uniquely linked to one `account_creation_method`, indicating a one-to-one mapping. This lack of variation may require attention from the data engineering team to confirm intended relationships.
    - ![One to One Mapping](Data/visualizations/order_count_channelxmethod.webp)
- **Loyalty Program Clarification**:
    - Ambiguity exists in the `loyalty_program` variable—it's unclear if it's tied to the user's account or is specific to individual orders.
    - Can a user be a loyalty member for one purchase and not another? This clarification is essential for accurately measuring program performance.
- **Sales and Marketing Channels**: Direct and email channels are top drivers of sales, yet the link between these channels and the loyalty program is uncertain due to deterministic channel-account-order relationships.
    - **Attribution of Purchases to Channels**: Ideally, each purchase would be attributed to the marketing channel that directly led to it, rather than defaulting all future purchases to the initial channel. However, the current dataset reflects the entry point at account creation, not at individual purchase. Despite this, the data provides insights on loyalty membership by channel:
        - **Email Channel**: Highest loyalty membership rate at 58%.
        - **Direct Channel**: Largest loyalty membership count, with 32,906 members (72% of all loyalty members).
    - These metrics could inform strategic channel emphasis to boost loyalty engagement.
- **Unmatched Customer Records**: Approximately 27k (25%) of transactions have `customer_id`s not present in the `customers` table. This discrepancy suggests missing data or data entry errors, impacting SQL queries and resulting in NULLs when joining on `customer_id`.
    - This issue arises from the segmented structure of SQL tables (`orders`, `customers`, `geo_lookup`, `order_status`). However, in Excel, where all data resides in a single table, this issue doesn't occur.

***

- See the raw data and my cleaning, analysis, and pivot tables in the [Excel workbook](Exploration/bytex_ecommerce_analysis.xlsx).
- See my SQL queries in the [SQL file](Exploration/ecommerce_exploration.sql).
- See the notebook for data cleaning, visualization, and analysis in the [Python Notebook](Exploration/ecommerce_analysis.ipynb).
- For more of my projects and data journey, visit my [portfolio website and reach out](https://ruizdelcarmen.me/)!

