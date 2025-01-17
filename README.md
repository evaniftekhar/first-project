# Gym Equipment Profit Sales Analysis

Table of Contents

- [Project Background](#project-background)
- [Executive Summary](#executive-summary)
- [Insights Deep-Dive](#insights-deep-dive)
    - [Yearly Profit Trends](#yearly-profit-trends)
    - [Monthly Profit Trends](#monthly-profit-trends)
    - [Top Performance by Category](#top-performance-by-category)
    - [Top Performance by Supplier](#top-performance-by-category)
    - [Top Performance by Brand](#top-performance-by-brand)
    - [YoY and MoM Growth Trends](#YoY-and-MoM-Growth-Trends)
    - [Market Share Analysis](#market-share-analysis)
- [Recommendations](#recommendations)
- [Assumptions and Caveats](#assumptions-and-caveats)

***

## Project Background

This project is analyzing the gym equipment market to evaluate yearly and monthly profit trends, category, supplier, and brand performance for the gym equipment industry, providing actionable insights and recommendations for sustained growth and profitability.

## Executive Summary

Gym Equipment sales analysis of 1,233 records from years 2018-2024 shows monthly profits, YTD and MAT Profits across 9 gym brands, 3 suppliers (3 brands for each supplier), and 3 categories of gym equipment. 

From 2018 to 2024, Airbikes is the leading gym equipment category with $5.76M total profits (37% market share), noting that 6/9 brands sells airbikes while 5/9 brands sell rowing machines and treadmills. Peak Performance Gear leads supplier profit contributions with $5.77M total (37% market share). Steel Power is the top performing gym brand with $2.88M total profits (19% market share), noting that they are the only brand selling in all 3 categories while the others sell in 1 or 2 categories. 

In 2024 so far, Apex Athletics currently leads the airbikes market share contributing 18% of sales with Peak Performance Gear suppling them; Elevate Fitness leads the rowing machines market share contributing 21% of sales with Peak Performance Gear also suppling them, and Spartan Sports leads the treadmills market share contributing 21% of sales with Iron Strength Equipment supplying them.

![image_alt](https://github.com/evaniftekhar/first-project/blob/main/Gym%20Equipment%20Dataset%20ERD.png?raw=true)                          
Gym Equipment Market Dataset ERD

## Insights Deep-Dive

### Yearly Profit Trends
![image_alt](https://github.com/evaniftekhar/first-project/blob/main/Yearly%20Profit%20Trends%20(exc%202024).png?raw=true)
**Insights**: 
- Profits have shown a declining trend over the years (excluding 2024). Some potential causes could be market saturation, economic or consumer shifts

### Monthly Profit Trends
![image_alt](https://github.com/evaniftekhar/first-project/blob/main/Monthly%20Profit%20Trends%20(exc%202024).png?raw=true)
**Insights**: 
- Significant spikes in profits during May, August, and December. Key Drivers for May could be Pre-summer fitness preparations; for August it could be back-to-school promotions; for December it could be holiday shopping and New Year’s resolutions.

### Top Performance by Category
![image_alt](https://github.com/evaniftekhar/first-project/blob/main/Top%20Performance%20by%20Category.png?raw=true)
**Insights**:
- Airbikes are significantly outperforming other categories.
- Rowing Machines and Treadmills are closely competitive but lag behind Airbikes.

### Top Performance by Supplier
![image_alt](https://github.com/evaniftekhar/first-project/blob/main/Top%20Performance%20by%20Supplier.png?raw=true)
**Insights**:
- Peak Performance Gear leads, but Iron Strength and Titan Fitness Supply are close competitors.

![image_alt](https://github.com/evaniftekhar/first-project/blob/main/Top%20Performance%20by%20Supplier%20and%20Category.png?raw=true)
**Insights**:
- .

### Top Performance by Brand
![image_alt](https://github.com/evaniftekhar/first-project/blob/main/Top%20Performance%20by%20Brand.png?raw=true)
**Insights**:
- Steel Power significantly outperforms others, while Elevate Fitness and Titan Training are close competitors.

### YoY and MoM Growth Trends
![image_alt](https://github.com/evaniftekhar/first-project/blob/main/YoY%20and%20MoM%20Growth%20Rate.png?raw=true)                          
**Insights**:
- Titan Fitness Supply is the most volatile, with sharp declines (2020, 2022) and strong recoveries (2021, 2023).
- Iron Strength Equipment has consistently modest growth with limited fluctuations.
- Peak Performance Gear has a steady recovery from double-year declines in 2019–2020.

### Market Share Analysis
![image_alt](https://github.com/evaniftekhar/first-project/blob/main/Brand%20Market%20Share%20%25%20for%20Airbikes.png?raw=true)
![image_alt](https://github.com/evaniftekhar/first-project/blob/main/Brand%20Market%20Share%20%25%20for%20Rowing%20Machines.png?raw=true)
![image_alt](https://github.com/evaniftekhar/first-project/blob/main/Brand%20Market%20Share%20%25%20for%20Treadmills.png?raw=true)

**Insights**: 
- Airbikes: Apex Athletics has the biggest market share increase while Spartan Sports has the biggest decline in market share.
- Rowing Machines: Elevate Fitness has the biggest market share increase while Titan Training has the biggest decline in market share.
- Treadmills: Spartan Sports has the biggest market share increase while Hercules Gear has the biggest decline in market share.

## Recommendations

Capitalize on Monthly Trends

- **Seasonal campaigns**: Focus marketing and inventory efforts on high-profit months (May, August, December).

***

Maximizing Product Offerings

- **Expand High-Performing Categories**: Brands should expand their offerings to include all 3 categories like Steel Power did, which resulted them in performing the best over time.

***

Optimize Supply Chain

- **Work Closely with high-performing suppliers**: Iron Strength Equipment dominates in rowing machines while Peak Performance dominates in Airbikes. For treadmills, you could go with either Peak Performance or Titan Fitness Supply as they have nearly the same market share.

***

## Clarifying Questions, Assumptions, and Caveats

### Questions for Stakeholders Prior to Project Advancement

***

- See the raw data and my cleaning, analysis, and pivot tables in the [Excel workbook](Exploration/bytex_ecommerce_analysis.xlsx).
- See my SQL queries in the [SQL file](Exploration/ecommerce_exploration.sql).
- See the notebook for data cleaning, visualization, and analysis in the [Python Notebook](Exploration/ecommerce_analysis.ipynb).
- For more  and data journey, visit my [portfolio website and reach out](https://ruizdelcarmen.me/)!

