# Project Title: Pizza Business Performance Analysis and Growth Strategies

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Objective](#objective)
- [Analysis Approach](#analysis-approach)
- [Key Findings](#key-findings)
- [How to Use](#how-to-use)
- [Technologies Used](#technologies-used)
- [Results & Visualizations](#results--visualizations)
- [Recommendation](#recommendation)
- [Contact](#contact)

## Overview: 

This report provides an in-depth analysis of sales trends, product performance, customer behavior, and ingredient usage to uncover strategic opportunities for driving revenue growth and enhancing operational efficiency. By examining patterns in sales volume, peak times, customer preferences, and ingredient consumption, we aim to align business operations with consumer demand and peak performance periods.

Key findings reveal seasonal sales peaks, specific time frames with high revenue potential, and insights into customer preferences that favor group dining and certain product categories. The analysis also highlights underperforming time slots and products, offering clear opportunities for improvement. Through targeted recommendations, such as optimizing pricing strategies, adjusting operational hours, and refining the menu, this report aims to guide the business towards more efficient and profitable operations.

## Dataset

The analysis is based on the [data_pizza.xlsx](data_pizza.xlsx)
- Time period Covered: 2015
- Number of Record: 21288 rows
- Number of Features: 10
- Key Variables: according to [data_dictionary.xlsx](data_dictionary.xlsx)

**Objectives:** 

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

## How to use
1.  Loading the dashboard (pbix file) in Power BI
- Open Power BI Desktop and go to File > Open to load the existing dashboard ([my_dashboard.pbix](PhanChenh_pizza_business_dashboard.pbix)) from the repository.

## Technologies Used
- Power BI: Used for data visualization and report creation. Various charts, graphs, and slicers were implemented to analyze key supply chain metrics.
- DAX (Data Analysis Expressions): Used to calculate important metrics like total sales, quantity, order, muilti and single order.

## Results & Visualizations

![BIsalesAnalysis](https://github.com/user-attachments/assets/8d67c86c-7979-48ae-990e-8890c18ada82)
Figure 1: Sales Trend Analysis


-----
## Findings and Analysis

### A.	Sales trend analysis
1. Descriptive Metrics
-	Total Sales: $817.86K
-	Total Quantity Sold: 49,574 units
-	Total Orders: 21,350

Average Sales:
- Per Month: ~$68.2K
- Per Week: ~$15.4K
- Per Day: ~$2.2K
- By Weekday: ~$116.8K
  
2.	High-Performance Periods

By Month:
- July: ~$72.6K, driven by Independence Day activities.
- November: ~$70.4K, coinciding with Thanksgiving and Black Friday.
- May and March also show strong performance due to holidays like St. Patrick’s Day and Cesaz Chavez Day.

By Week:
- Week 48 (November): ~$19.2K, corresponding with Black Friday.
- Week 27 (June–July): ~$17.5K, around Independence Day.

By Weekday:
- Highest sales on Fridays (~$136.1K), followed by Thursdays and Saturdays.

3.	Low-Performance Periods

By Month:
- October: ~$64K, impacted by consistent closures on Mondays.
- September: ~$64.2K, affected by Yom Kippur closures.
- December: ~$64.7K, affected by Christmas closures.
- February: ~$65.2K, shorter month with fewer sales day

By Weekday:
- Lowest sales on Sundays (~$99.2K).

4.	Operational Patterns

Peak Hours:
- 11 AM–1 PM: Sales peak at ~$87.6K.
- 5 PM–7 PM: Consistent strong performance ~$82.7K.

Lowest Sales Hours:
- Early hours (9–10 AM) generate minimal revenue (~$83 for 9AM, ~$303 total across 7 days at 10 AM).

Closures:
- Days off (e.g., 25/12/2015 for Christmas, 24–25/9/2015 for Yom Kippur).

Irregular Openings:
- Opening at 9 AM or 10 AM results in negligible sales increases.

![BIsalesAnalysis](https://github.com/user-attachments/assets/8d67c86c-7979-48ae-990e-8890c18ada82)
Figure 1: Sales Trend Analysis

### B.	Product performance analysis
1.	Overview of Product Portfolio
-	Pizza Categories: Classic, Supreme, Chicken, Veggie
-	Number of Pizza Types: 32
-	Pizza Size-Types: 91 unique combinations
2.	Category Performance
-	Top Categories: The classic and supreme categories rank highest in both sales and quantity, with classic consistently leading across both metrics.
-	Chicken and Veggie: While chicken slightly outperforms veggie in sales, veggie surpasses chicken in terms of quantity sold, indicating balanced customer demand for both price and volume.
3.	Performance of 32 Pizza Types
-	High Sales, Low Quantity: Pizzas like California Chicken and Spicy Italian generate high sales but have relatively low quantity sold, suggesting a premium pricing strategy that appeals to a smaller, more targeted audience.
-	Low Sales, High Quantity: Hawaiian and Pepperoni are sold in large quantities but generate relatively lower sales. This could indicate customer preference for lower-priced, higher-volume pizzas.
4.	Pizza Size and Sales Performance:
-	General Trend: Large (L) pizzas dominate sales across categories, followed by medium (M) and small (S).
-	Category-Specific: Chicken, Veggie, and Supreme: L > M > S reflects a preference for sharing-sized options. Classic: Small (S) leads, followed by large (L), medium (M), XL, and XXL, suggesting individual or small-group consumption.
-	XL and XXL Sizes: Only available in the classic category, they underperform due to perceived value or portion size mismatch.
![BIproduct](https://github.com/user-attachments/assets/73fe5533-c33d-4614-8eaa-80087200d9fa)
Figure 2: Product Performance Analysis

### C.	Customer purchase analysis
1.	Orders behaviour and peak time insights
-	Customers prefer multi-orders (61.6%) over single orders (38.4%), indicating that groups or families are a key customer segment
-	The restaurant experiences two distinct peak times, each with different customer behaviours:

    First Peak Time (e.g., lunch breaks): Single orders dominate, indicating that these customers are likely individuals looking for quick meals, such as during work or lunch breaks.
    
    Second Peak Time (e.g., evening family dinners): Multi-orders dominate, suggesting that group dining or family dinners are more common during this time, where customers order multiple pizzas to share.
2.	Pizza size preferences
-	From Small to Larger sizes (S, M, L) are the preferred choice across all 4 categories, indicating they are popular for group or sharing situations.
-	Bigger sizes (XL, XXL) in Classic underperforming. This may be due to perceived value or portion size mismatch for this pizza type.
3.	Performance of 91 Pizza Type-Size Combinations
-	Pizzas like Five cheese L, four cheese L and M, big meat S generate high sales but only has a few sizes. Get to know customers preference and their portion to add more size. Adding sizes might attract customers looking for personal portions or a lower price point. This could increase overall sales if there's demand for these sizes.
-	Pizza like Greek pizza with XXL has low sales but other sizes sales not bad. 
-	Green Garden pizza: Despite offering three sizes, Green Garden has weak overall sales. Focus efforts on promoting the size S, which leads in demand.
-	Brie Carre: Despite being available only in size S, it has achieved strong sales (~$11.6K). This suggests potential for expansion to larger sizes (M, L) to increase overall sales.
4.	Top 10 Common Pizza Combinations
-	Big Meat S consistently appears in the majority of top pizza combinations, indicates that customers are favouring it as a single pizza choice, especially when combined with larger-sized pizzas for group or family orders. However, Big Meat only has 1 size only, if it has more size then the revenue might increase since the demand is high. 
-	The consistent pairing of Big Meat S with larger pizzas (L and M sizes) suggests that customers often opt for a combination of individual servings (Big Meat S) along with larger pizzas for sharing.

![Screenshot 2025-02-10 124117](https://github.com/user-attachments/assets/94d6ac5d-2e3e-4704-9811-5f3f8ae6b952)

Figure 3: Top 10 most common pizza combinations

![BIcustomer](https://github.com/user-attachments/assets/a9130c93-00c0-48cd-8f54-b3a5499728f0)
Figure 4: Customer Purchase Analysis

### D.	Ingredients & Price analysis
1.	Most Used Ingredients
The top five most used ingredients, including garlic, tomatoes, red onions, red peppers, and chicken, are integral to our highest-performing pizza types across multiple categories.
2.	Least Used Ingredients
The least used ingredients are predominantly found in Brie Carre pizza, which has the lowest sales and quantity.
3.	Popular Ingredient Configurations
-	6 Ingredients (~18.2K orders): The most popular configuration, especially in Supreme pizzas. This balance between variety and simplicity makes it appealing to a wide range of customers.
-	5 Ingredients (~11.6K orders): A versatile configuration, popular across several categories, though it underperforms in Supreme pizzas.
4.	Pizza Type Performance Insights
-	Chicken Pizzas: Typically feature 5-8 ingredients, with 6 ingredients being the most common in high-performing options. This suggests that a balance of flavour complexity and ingredient cost drives success.
-	Supreme Pizzas: These pizzas exhibit a variety of ingredient counts (3, 5, 6, 8), with 6 ingredients dominating sales. This reflects customer preferences for a balanced yet flavourful pizza.
-	Veggie Pizzas: Perform best with 5 or 8 ingredients, with 5 being the most popular. Simple, well-balanced combinations are preferred by the audience for veggie pizzas.
-	Classic Pizzas: Ranging from 2-6 ingredients, Classic pizzas are most frequently ordered with 5 ingredients, reflecting a preference for simplicity and variety.
5.	Price Sensitivity Analysis
-	Sales Trends:

    Chicken, supreme, and veggie pizzas show increased sales at higher price points.
    
    In contrast, classic pizzas experience reduced sales as prices rise.
-	Quantity Trends:

    Chicken pizzas exhibit higher quantities sold at increased prices.
    
    Classic pizzas see a decline in quantity with rising prices.
    
    Supreme and veggie pizzas maintain consistent quantities regardless of price changes.

![BIprice_ingredience](https://github.com/user-attachments/assets/707c01ab-6048-4000-824e-5cfde3f4fb75)
Figure 5: Ingredients & Price Analysis

## Conclusions

In conclusion, the analysis has revealed several key opportunities to enhance business performance, focusing on optimizing pricing, refining the menu, and adjusting operations to align with customer demand. By implementing dynamic pricing for high-performing items and adjusting operating hours to focus on peak sales periods, the business can significantly increase revenue. Additionally, menu refinement and targeted customer promotions will help meet customer preferences and boost sales during slower periods.

## Recommendations
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



Secondary recommendations that support long-term growth include:
- Discounts or Promotions for Low-Demand Days: Introduce discounts or bundle deals on Sundays and Mondays to boost sales during slower periods.
- Cross-Selling and Combo Deals: Offer meal bundles like “Big Meat S + Four Cheese L” to increase average order value.
- Customer Loyalty Program: Launch a rewards program to encourage repeat purchases, especially during low-sales periods.

By implementing these strategies, the business can enhance operational efficiency, improve customer satisfaction, and maximize revenue.

## 📬 Contact & Contributions

Feel free to fork, open issues, or suggest improvements!

📧 Email: pearriperri@gmail.com

🔗 [LinkedIn](https://www.linkedin.com/in/phan-chenh-6a7ba127a/) | Portfolio

