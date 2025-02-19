# Project Title: Pizza Business Performance Analysis and Growth Strategies 2015

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Objective](#objective)
- [Analysis Approach](#analysis-approach)
- [Key Findings](#key-findings)
- [How to run code](#how-to-run-code)
- [Technologies Used](#technologies-used)
- [Results & Visualizations](#results--visualizations)
- [Recommendation](#recommendation)
- [Contact](#contact)

## Overview

This report provides an in-depth analysis of sales trends, product performance, customer behavior, and ingredient usage to uncover strategic opportunities for driving revenue growth and enhancing operational efficiency. By examining patterns in sales volume, peak times, customer preferences, and ingredient consumption, we aim to align business operations with consumer demand and peak performance periods.

Key findings reveal seasonal sales peaks, specific time frames with high revenue potential, and insights into customer preferences that favor group dining and certain product categories. The analysis also highlights underperforming time slots and products, offering clear opportunities for improvement. Through targeted recommendations, such as optimizing pricing strategies, adjusting operational hours, and refining the menu, this report aims to guide the business towards more efficient and profitable operations.

## Dataset

The analysis is based on the [data_pizza.xlsx](data_pizza.xlsx)
- Time period Covered: 2015
- Number of Record: 21288 rows
- Number of Features: 10
- Key Variables: according to [data_dictionary.xlsx](data_dictionary.xlsx)

## Objectives

The primary purpose of this report is to provide actionable insights and recommendations that will help the business maximize revenue, optimize operations, and refine its product offerings. This analysis focuses on identifying areas for improvement, such as adjusting operational hours, refining the menu, implementing dynamic pricing strategies, and utilizing promotional efforts during high-demand periods. The report aims to support decision-making and guide the business in aligning its strategies with customer preferences and peak sales periods to ensure sustained growth and operational efficiency.

## Analysis Approach

The analysis was conducted using Power BI, leveraging data preparation, modeling, and DAX calculations. The key steps included:

1. Data Preparation: Data was sourced, cleaned, and transformed to ensure accuracy.

2. Data Modeling & ERD: Relationships between tables were established, creating a clear structure to link tables together as seen in [pizza_ERD](pizza_ERD.png)

3. DAX Calculations: Key metrics like total sales, product performance, peak times, and ingredient usage were calculated using DAX. For example, measures were created to identify peak sales periods, rank products, and calculate ingredient usage.

4. Power BI Dashboards: Interactive visualizations were created to explore sales trends, product performance, and customer behavior, with dynamic filtering options for deeper insights.

5. Interpretation and Insights: Data-driven insights were drawn to identify trends, such as peak sales times, popular products, and customer preferences, revealing opportunities for growth and optimization.

6. Recommendations: Based on the findings, strategic recommendations were made, including optimizing pricing, refining the product menu, adjusting operational hours, and leveraging cross-selling opportunities to maximize revenue.

## Key Findings
- Sales Trends: Revenue peaks occur in July and November, driven by holidays, while Sundays and Mondays consistently underperform. Sales are highest between 11 AM–1 PM and 5 PM–7 PM.

- Product Performance: Supreme and Classic pizzas are the top performers, while products like Big Meat S and Brie Carre show potential for expansion into additional sizes.

- Customer Behavior: Evening sales are dominated by multi-orders, suggesting a preference for group dining, while individual pizzas perform well at lunchtime.

- Ingredient Usage: Garlic, tomatoes, and red onions are the most frequently used ingredients, indicating their importance in the menu. Pizzas with 5–6 ingredients tend to perform best.

- Cross-Selling Opportunities: Products like Big Meat S pair well with larger pizzas, offering opportunities for effective cross-selling.

## How to run code
1.  Loading the dashboard (pbix file) in Power BI
- Open Power BI Desktop and go to File > Open to load the existing dashboard ([my_dashboard.pbix](PhanChenh_pizza_business_dashboard.pbix)) from the repository.

## Technologies Used
- Power BI: Used for data visualization and report creation. Various charts, graphs, and slicers were implemented to analyze key supply chain metrics.
- DAX (Data Analysis Expressions): Used to calculate important metrics like total sales, quantity, order, muilti and single order.

## Results & Visualizations

![BIsalesAnalysis](https://github.com/user-attachments/assets/8d67c86c-7979-48ae-990e-8890c18ada82)
Figure 1: Sales Trend Analysis

Findings:
- High-Performance Periods:
  + Monthly Peaks: July and November lead with strong sales due to holidays (Independence Day, Thanksgiving, Black Friday).
  + Weekly Peaks: Week 48 (November) and Week 27 (June–July) show high sales around key events.
  + Weekday Trends: Fridays drive the highest sales (~$136.1K), followed by Thursdays and Saturdays.
  + Peak Hours: Sales are highest from 11 AM–1 PM and 5 PM–7 PM.

- Low-Performance Periods:
  + Monthly Lulls: October, September, December, and February show lower sales due to closures and shorter periods.
  + Weekday Lulls: Sundays consistently underperform with ~$99.2K in sales.
  + Early Hours: Sales are minimal (around ~$83 at 9 AM), showing early openings have limited impact.

![Screenshot 2025-02-17 231829](https://github.com/user-attachments/assets/166204c6-c714-40e8-a8bb-135d9d75f548)

Figure 2: Product Performance Analysis

Findings:
- Top Product Categories: Classic and Supreme pizzas consistently outperform in both sales and quantity, with Classic leading in both metrics.

- Balanced Demand for Chicken and Veggie: Chicken slightly outperforms Veggie in sales, but Veggie has a higher quantity sold, indicating a balanced demand for both higher-priced and higher-volume options.

- Sales vs. Quantity Dynamics:

  + High Sales, Low Quantity: Premium pizzas like California Chicken and Spicy Italian attract a targeted audience with higher pricing.
  + Low Sales, High Quantity: Hawaiian and Pepperoni pizzas are popular due to lower pricing, driving higher quantities sold.

- Size Preferences:

  + Large (L) Dominates: L-sized pizzas are most popular across most categories, except for Classic, where Small (S) leads, indicating preferences for individual vs. group consumption.
  + XL and XXL Sizes: These sizes, available only in Classic, underperform, potentially due to value or portion mismatch with customer preferences.

![Screenshot 2025-02-10 124117](https://github.com/user-attachments/assets/94d6ac5d-2e3e-4704-9811-5f3f8ae6b952)

Figure 3: Top 10 most common pizza combinations (graph from [pythoncode](pizaCombination.ipynb))

![BIcustomer](https://github.com/user-attachments/assets/a9130c93-00c0-48cd-8f54-b3a5499728f0)

Figure 4: Customer Purchase Analysis

Findings:
- Order Behavior:

  + 61.6% of orders are multi-orders, indicating group or family dining.
  + Peak Times: Single orders dominate during lunch breaks, while multi-orders are more common in the evening.

- Size Preferences: Small to Large sizes are most popular for sharing, while XL and XXL sizes underperform in the Classic category.

- Pizza Type-Size Combinations:

  + High-performing pizzas like Five Cheese and Big Meat S could benefit from more size options to attract a broader customer base.
  + Green Garden Pizza performs better in Size S, while Brie Carre shows strong sales in Size S, suggesting potential for expansion to larger sizes.

- Top Combinations: Big Meat S is frequently paired with larger pizzas, indicating strong demand. Expanding its size options could increase revenue.

![Screenshot 2025-02-17 233504](https://github.com/user-attachments/assets/987c4d78-6a4a-4fe3-b7fe-79b69f822f2b)

Figure 5: Ingredients & Price Analysis

Findings:
- Most Used Ingredients: Garlic, tomatoes, red onions, red peppers, and chicken are key to top-performing pizzas across categories.

- Ingredient Configurations:

  + 6 Ingredients is the most popular and performs well in Supreme pizzas.
  + 5 Ingredients is versatile but underperforms in Supreme pizzas.
- Pizza Type Insights:

  + Chicken Pizzas: Best with 6 ingredients, balancing flavor complexity and cost.
  + Supreme Pizzas: Preferably 6 ingredients, offering a balanced, flavorful taste.
  + Veggie Pizzas: Perform well with 5 or 8 ingredients.
  + Classic Pizzas: Most popular with 5 ingredients, focusing on simplicity.
- Price Sensitivity: Chicken, Supreme, and Veggie pizzas sell better at higher prices, while Classic pizzas see a sales drop as prices increase. Classic pizzas also experience reduced quantity at higher prices.

## Recommendation
Based on the analysis, the following strategies should be prioritized:
1.	Operating Hours Optimization:
-	Focus on peak sales times (11 AM–1 PM, 5 PM–7 PM). Open slightly earlier on Fridays, Saturdays, and holidays (10:30 AM). Reevaluate closures on Mondays and low-sales Sundays.
-	Preparing ingredients and staff at peak times and specific busy days.
-	Investigate local demographics to determine the relevance of closures for holidays like Yom Kippur. Adjust operations if significant customer demand exists during these periods.
2.	Menu Expansion:
-	Offer additional sizes for popular items like Big Meat and Brie Carre to meet customer preferences and boost sales.
3.	Marketing Strategies:
-	Promote large (L) pizzas in chicken, veggie, and supreme categories.
-	Use combo deals featuring top combinations (e.g., "Big Meat S + Four Cheese L") to attract group diners.
-	Enhance promotions for small (S) pizzas to appeal to individual diners.
4.	XL and XXL Sizes:
-	Analyse barriers for XL and XXL sizes in the classic category and explore introducing them in other categories.
5.	Price Testing:
-	Experiment with price elasticity for low-sales items like Hawaiian or high-sales, low-quantity items like California Chicken to optimize pricing strategies.
-	Supreme and Veggie pizzas likely have inelastic demand, suggesting customers are less sensitive to price changes. These products may be perceived as premium or essential, sustaining consistent sales even at higher price points.
-	Marketing or promotional strategies could also explain the stable performance of Supreme and Veggie pizzas, even with price increases.
-	For Classic pizzas, pricing strategies should carefully consider the sensitivity to price, as both sales and quantities are negatively impacted by higher prices.
6.	Ingredient and Recipe Innovation:
-	Develop pizzas highlighting popular ingredients (garlic, tomatoes, red onions).
-	Focus on recipes with 5–6 ingredients for optimal sales performance.
7.	Operational Efficiency:
-	Streamline kitchen processes for peak times and train staff to handle individual and group orders effectively.
8.	Customer Engagement:
-	Introduce loyalty programs to incentivize repeat purchases and boost sales during slower periods.
9.	Holiday Adjustments: 
-	Review closures during holidays like Yom Kippur based on local demand.

By implementing these strategies, the business can enhance operational efficiency, improve customer satisfaction, and maximize revenue.

## Contact

📧 Email: pearriperri@gmail.com

🔗 [LinkedIn](https://www.linkedin.com/in/phan-chenh-6a7ba127a/) | Portfolio

