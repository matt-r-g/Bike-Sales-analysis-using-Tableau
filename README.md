# 🚲 Tableau Project: Bike Sales Analysis

## 📋 Project Overview

This project analyses the Bike Sales dataset using Tableau to identify key insights regarding sales performance. Specifically, the goal was to determine:

🌍 The countries with the lowest sales.
📦 The lowest selling products.
👥 The age group spread of customers.

Based on these findings, actionable recommendations will be made to help the company improve its sales strategies and product offerings.

## 🗃️ Dataset Overview

The Bike Sales dataset includes various metrics related to sales, including:

- 🛍️ Product details (e.g., category, subcategory, and product name).
- 💰 Sales data (e.g., sales revenue, quantity sold).
- 🌍 Geographical data (e.g., country, region).
- 📅 Date-related information (e.g., year, quarter).
- 👥 Customer demographics (e.g., age group, gender).

The data spans several years and provides a comprehensive overview of the company's sales performance across different markets and product categories.

## 📊 Analysis Process

### 🔻 Identifying the Lowest Countries by Sales

To determine which countries had the lowest sales, the following steps were taken:

- **Data Aggregation:** The sales data was aggregated by country to calculate the total sales for each country.
- **Sorting:** The countries were sorted in ascending order based on total sales to identify those with the lowest values.
- **Visualisation:** A map was created to visually represent the sales by country, highlighting the lowest performing countries with colour.


<img width="697" alt="Screenshot 2025-02-26 at 23 52 38" src="https://github.com/user-attachments/assets/4e188abe-d76c-46c4-b81e-f3e48b7b82e9" />


The countries with the lowest sales were identified and further analysis was done to explore potential reasons for their low sales, such as market saturation or lack of targeted marketing efforts.


<img width="745" alt="Screenshot 2025-02-26 at 23 50 10" src="https://github.com/user-attachments/assets/867937cf-1117-4a4d-ad68-118c7d60d636" />

I wanted to find if there were any trends with countries having low sales so I created a line chart to show over time the sales figures. United Kingdom and Germany have positive correlation and a stead increase year on year. 
However France and Canada have had a dip in sales the last year which needs to be addressed so that it does not continue long term.

### 📉 Identifying the Lowest Selling Products

To find the products with the lowest sales, the following steps were taken:

- **Product Categorisation:** The products were categorised based on their respective subcategories and categories.
- **Sales Analysis:** The total sales for each product were calculated, considering both quantity sold and sales revenue.
- **Sorting:** Products were then sorted by total sales in ascending order to identify those with the lowest performance.
- **Visualisation:** A bar chart  was created to illustrate the sales performance of individual products, focusing on the lower end of the spectrum.


<img width="746" alt="Screenshot 2025-02-26 at 23 52 18" src="https://github.com/user-attachments/assets/20e5f449-9e17-4327-a8e6-06a2b701c58e" />


The lowest selling products were pinpointed, and further investigation was conducted to understand why these products underperformed. Possible factors include pricing issues, poor customer demand, or lack of promotional activities. 

One noticable observation from this is that 5 of the 10 lowest selling products are from the Mountain-500 range. To combat this I would recommend a promotion for this brand of bike, reducing the price or ultimately they may have to discontinue the line if no progress is made. 

### 👥 Demographic Spread

Understanding the age group distribution of customers is crucial to assess the company’s reach across different demographics. The analysis focused on segmenting customers into key age groups/gender and visualising their sales performance. 

#### Steps Taken:
- **Age Group Categorisation:** Customers were segmented into age groups, such as 18-24, 25-34, 35-64 and 64+.
- **Sales Analysis by Age Group:** Total sales and quantity sold were analysed for each age group to understand which demographics are driving sales.
- **Visualisation:** A pie chart was created to display the proportion of sales across different age groups.

<img width="320" alt="Screenshot 2025-02-26 at 23 49 07" src="https://github.com/user-attachments/assets/007ddc09-e8de-4458-8c6a-577adbe895d9" />

The outcome showed that the split between Male and Female gender was nearly equal.

<img width="414" alt="Screenshot 2025-02-26 at 23 49 21" src="https://github.com/user-attachments/assets/0b704ede-9ae2-4616-9857-6ee8fb8f0f22" />

The results indicate that the senior age group represents the smallest segment, while the youth demographic presents a promising opportunity for increasing sales. Specifically, individuals under the age of 25 are more likely to use bicycles compared to those aged 64 and above. The visualisation can help reveal which age groups contribute most to overall sales and allow for more targeted marketing and product recommendations.


## 📝 Key Findings

### Lowest Countries by Sales
- The countries with the lowest sales were primarily located in regions with emerging markets or limited brand presence.
- Factors contributing to low sales in these countries include:
  - Limited marketing or brand recognition.
  - Distribution challenges or inefficiencies in the supply chain.
  - Economic conditions that may limit purchasing power.

### Lowest Selling Products
- The lowest selling products were mostly in specific subcategories that had lower demand in general.
- Contributing factors to low sales include:
  - Products were possibly not well marketed.
  - Products with high prices compared to similar items.
  - Lack of seasonal or targeted promotions.

### Age Group Insights
- The largest proportion of sales came from the **25-34** and **35-44** age groups, indicating that these customers are the primary drivers of sales.
- The **18-24** age group showed lower sales, suggesting that younger customers may not be as engaged with the product range or pricing.
- The **64+**  age group contributed smaller shares, possibly indicating that older customers prefer different product categories or are less likely to engage in purchasing through digital channels.

## 💡 Recommendations

Based on the findings from the analysis, the following recommendations can be made to improve sales performance:

### For Low Sales Countries
1. 📣 **Increase Marketing Efforts:** Invest in localised marketing strategies to increase brand recognition and awareness in these countries.
2. 🚚 **Optimise Distribution:** Review and enhance the distribution network to ensure products are available where demand exists.
3. 📊 **Market Research:** Conduct market research to better understand customer needs and adapt the product offerings to local preferences, or expand the business into other countries.

### For Low Selling Products
1. 💸 **Discounting and Promotions:** Offer promotional discounts or bundle deals to encourage customers to purchase underperforming products.
2. 💵 **Reevaluate Product Pricing:** Assess whether the pricing of low-selling products is competitive compared to similar offerings from competitors.
3. 📈 **Improve Product Visibility:** Increase the visibility of low-selling products through targeted advertising or placement in high-traffic areas on e-commerce platforms.

### For Age Group Demographics
1. 🧑‍🤝‍🧑 **Targeted Marketing for Younger Demographics:** Develop campaigns that appeal to the **18-24** age group, possibly by offering more affordable pricing, student discounts, or social media promotions.
2. 🎯 **Product Personalisation for Older Demographics:** Consider customising products or creating new products that cater to the tastes of the **64+** age group, prioritising comfort and detailing the health benefits.
3. 👨‍👩‍👧‍👦 **Segmented Advertising:** Create more tailored advertisements based on the age groups most likely to engage with specific products, ensuring a more focused and effective marketing strategy.

## ✅ Conclusion

This Tableau project provides valuable insights into the Bike Sales dataset, helping the company identify countries and products that require attention, as well as better understanding customer demographics. By implementing the recommended strategies, the company can aim to boost sales in underperforming markets, optimise the performance of its products across different regions and better target marketing efforts towards key customer age groups.




