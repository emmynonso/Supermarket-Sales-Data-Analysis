# Supermarket-Sales-Data-Analysis
The purpose of this Sales Tracker Analysis is to provide data-driven insights that optimize business decision-making in sales, pricing, inventory, and profitability.

**PURPOSE:** The purpose of your Sales Tracker Analysis is to provide data-driven insights that optimize
business decision-making in sales, pricing, inventory, and profitability. Specifically, this analysis aims to:

* Monitor sales performance by tracking revenue, profit margins, and sales trends over time
* Enhance pricing strategy by comparing unit selling price with wholesale price to refine markup
decisions
* Understand customer behavior by identifying patterns in purchases, best-selling categories, and
discount effectiveness
* Optimize inventory management by analyzing loss rates and returns, reducing stock waste
* Improve business efficiency by ensuring resources are allocated effectively based on data-backed
insights.

**METHODOLOGY** 🛠
1. DATA SOURCES
Data was collected an online platform named Kaggle, after which it was imported into Power BI
for cleaning, modelling and visualization.
2. Data Preparation and Cleaning
* Imported the dataset containing all four tables into Power BI after the data was collected from
kaggle.
* Removing of duplicates.
* Standardized columns and values
3. DATA VISUALIZATION
Power BI was used for creating various visualizations, such as bar charts, column charts, doughnut
charts, and area charts to represent the data visually and make it easier to understand and
interpret.
* DASHBOARD SLICERS
To enhance insights, we added slicers for sales or return, discount rate and date, enabling easy
data segmentation and trend analysis across different products.
* DAX Measure: DAX was used to create new measures for Total Profit, Total Revenue, Total Cost
and Profit Margin.

**KEY PERFORMANCE INDICATORS OVERVIEW:**
The key performance indicators (KPIs) obtained from the analysis were;
* TOTAL REVENUE: This is the total sum earned from the supermarket sales over the stipulated
time.
* TOTAL PROFIT: This is the net profit realized after sales and other expenses has been factored in.
* AVERAGE UNIT SELLING COST: The average selling cost for the products available.
* AVERAGE LOSS RATE: This is the average loss rate for all products during sales time.

**KEY INSIGHTS AND ANALYSIS**
**TOTAL REVENUE PER YEAR:** 📉

![image](https://github.com/user-attachments/assets/7d8c80e4-3855-43f2-90be-e8af71f98e06)

**KEY INSIGHT:**

Imagine your revenue performance as a journey. In 2020, the business was sailing smoothly with modest
revenues. In 2021, a strong wind propelled it to a peak of around $1.1M, suggesting robust market
conditions or successful strategies. However, by 2022, the winds began to slacken, and revenues fell to
about $0.9M. In 2023, a fierce headwind emerged, dropping revenues further to $0.6M. This decline hints
at challenges impacting the business's momentum.
What could have caused this downturn? It might be a combination of broader economic headwinds
reducing consumer spending, intensifying market competition, or even internal operational disruptions—
like supply chain issues or inefficiencies—that stifled the earlier momentum. Shifts in consumer
preferences or regulatory changes increasing costs may also have played a role.

**RECOMMENDATION**

To steer the business back on course, start by conducting a thorough market analysis to pinpoint external
factors like economic trends and competitor strategies. Reassess your pricing model and cost structure to
ensure competitiveness without eroding margins. Evaluate your operational processes to identify and
remedy any inefficiencies, whether in production, distribution, or supply chain management. Moreover,
investing in product innovation and targeted marketing campaigns could help regain consumer
confidence and stimulate demand. Diversifying the product portfolio might also reduce the impact if one
segment faces issues, creating additional revenue streams to hedge against market volatility.
By understanding these factors and acting upon them, you can transform recent setbacks into an
opportunity for strategic realignment and renewed growth.

**TOTAL PROFIT PER ITEM NAME:** 💹
![image](https://github.com/user-attachments/assets/f642290c-62d2-4d1a-a5b8-4b3b6ca8f047)

**KEY INSIGHTS:**

This chart above shows Total Profit Per Item, highlighting variations in profitability across different products. 
The item Xixia Mushroom (1) generates the highest profit, close to $100K, followed by Paopaojiao (Jingpin), 
Red Pepper (1), and Yunnan Lettuces, all exceeding $60K in profit. Conversely, items like Hongshujian, Caixin, 
and Yunnan Leaf Lettuce (Bag) have significantly lower profits, some nearing zero or negative values. 
This indicates a profit imbalance, where certain products contribute substantially to revenue while others underperform.

**RECOMMENDATION**

Addressing this issue starts with a closer examination of the factors influencing the revenue and sales downturn. 
Investigate whether the decline in sales is linked to changes in customer preferences, competitive pricing strategies, 
or potential supply chain disruptions that could affect product availability or quality. Once the root cause is 
identified, consider implementing targeted marketing campaigns aimed at re-engaging customers, perhaps through promotional 
offers or loyalty programs. Additionally, review the pricing strategy to ensure that the unit selling price is both 
competitive and aligned with market expectations while safeguarding the profit margin. Streamlining operations to reduce 
waste and improve efficiency may also help reverse the downward trend in profit. Finally, consider diversifying the product 
range to mitigate dependency on a narrow set of offerings, which may prove vulnerable to shifts in market demand.

**TOTAL SALES BY CATEGORY NAME** 📋
![image](https://github.com/user-attachments/assets/38bfa3b9-b575-48a8-bd4d-06c97ee22bb9)

**KEY INSIGHT** 📊
This donut chart represents Total Sales Per Category Name, showing how different vegetable categories contribute to overall sales. The Flower/Leaf Vegetables category dominates sales, accounting for 37.79%, followed by Solanum (23.68%) and Aquatic Tuberous Vegetables (16.89%). Other categories like Cabbage (9.85%), Edible Mushroom (6.68%), and Capsicum (5.11%) have relatively lower sales. The data highlights a strong reliance on Flower/Leaf Vegetables as the leading revenue driver, while Capsicum has the weakest sales performance. 

**RECOMMENDATIONS**

To maximize sales and balance category contributions, the business should increase strategic efforts for lower-performing categories like Capsicum and Edible Mushrooms through better marketing, promotions, or improved distribution strategies. Since Flower/Leaf Vegetables and Solanum already perform well, they should be prioritized in inventory and sales expansion. Understanding consumer preferences and adjusting pricing strategies can further improve overall revenue stability across all categories.

**PROFIT TREND ACCUMULATED OVER FOUR YEARS** 💰💹
![image](https://github.com/user-attachments/assets/e152ad6f-f3c4-4b28-94a6-cee50394092c)

**KEY INSIGHT** 📊

The chart, titled "Profit Trend and Total Quantity Sold Accumulated Over Four Years," shows two critical metrics—Total Profit (in dollars) and Sum of Quantity Sold (in kilograms)—tracked from 2020 through 2023. In 2020, both profit and quantity sold are at their highest levels, indicating a robust period for the business. However, there is a dramatic drop in 2021, when both metrics nearly collapse (with profit plunging to around $0.1 million and quantity sold falling to roughly 50K kilos). A modest recovery in 2022 follows, only to be derailed by another steep decline in 2023, where the values nearly reach zero. This consistent pattern of high values in 2020, a severe downturn in 2021, a partial rebound in 2022 followed by a renewed decline in 2023 suggests systemic challenges affecting both demand and operational efficiency. This narrative reveals a key insight: while the business once thrived, recurring challenges repeatedly undermine its momentum. The dramatic fluctuations suggest that external pressures such as market shifts or internal issues like operational inefficiencies might be at play.

**RECOMMENDATION**

Given the insights, several targeted actions are recommended. First, it is imperative to perform a deep-dive analysis into the significant loss of both profit and sales between 2020 and 2021, as well as the decline seen again in 2023. This investigation should include market dynamics, competitive pressures, and potential internal operational challenges. Second, the slight recovery observed in 2022 may offer clues as to effective strategies; thus, replicating the tactics from that period—such as any improved marketing initiatives or optimized pricing strategies—could help sustain sales and profit improvements. Third, a review of the supply chain and product mix is essential to understand whether stock-outs, quality issues, or other supply constraints might be contributing to the drastic declines. Lastly, reinvigorating customer engagement through targeted promotions, loyalty programs, or revising pricing models to reflect real market demand could help stabilize the downward trend and rebuild both revenue and profit over time.

**TOTAL PROFIT AND QUANTITY SOLD PER ITEM NAME**
![image](https://github.com/user-attachments/assets/c84c32ce-e10f-47e0-afbb-b0ca1a42d29d)

**KEY INSIGHT** 📊

The bar chart, titled "Total Profit and Sum of Quantity Sold (kilo) by Item Name," vividly illustrates not only the financial performance of each product but also how actively each is being sold. In this narrative, some products shine as the true stars. For example, Xixia Mushroom (1) emerges as a powerhouse, displaying a high profit margin that signals strong demand or excellent pricing strategies. Other items like Papaya (box) and Red Pepper (1) also mark noteworthy contributions, suggesting that when these products are on stage, they captivate the audience and generate both impressive sales volume and significant gains.
However, not every character in this lineup tells a tale of triumph. Some items might exhibit a decent volume of sales yet struggle with profitability, or vice versa. These differences could be a result of various factors—perhaps differences in production costs, pricing decisions, or even shifts in consumer preference. The visual contrast between the profit and the quantity sold for each product serves as an invitation to dig deeper into operational performance, supply chain factors, or even market trends that might be influencing these outcomes.

**RECOMMENDATIONS**

To rewrite this narrative towards a more consistently successful performance, begin by analyzing the factors that propel high-performing items like Xixia Mushroom (1). Ask questions such as: What makes this item so profitable? Is it the cost structure, brand perception, or perhaps a unique market demand? Replicating the best practices from top performers across other products could help balance the lineup.
Simultaneously, take a closer look at those products struggling to generate profit relative to their sales volume. A detailed cost analysis or market research could reveal underlying issues—whether it's pricing strategies that need adjustment, production inefficiencies, or even inconsistencies with market demand. By addressing these points, you can either optimize the performance of these products or consider repositioning them in your portfolio.
Finally, consider a diversification approach that leverages the strengths of your best sellers while nurturing the growth potential of underperformers. Targeted marketing campaigns or product bundling strategies might help raise the profile of the less successful items, ultimately leading to a more balanced and robust sales performance.

**TOTAL QUANTITY SOLD BY SALE OR RETURN STATUS** 💼
![image](https://github.com/user-attachments/assets/c3ed603d-1e9d-4444-a095-0d673b3b903f)

**KEY INSIGHT** 📝
Imagine this chart as a snapshot of your business performance on a single stage where two key characters—sales and returns—take center stage. The chart, titled "Total Quantity Sold (kilo) by Sale or Return," reveals that a robust 2,540 kilos were sold compared to 254 kilos returned. This striking contrast paints a positive picture at first glance, showing that the overwhelming majority of products are reaching and satisfying customers, while returns remain a relatively small fraction of the overall volume.
However, even in a story with such promising sales, it’s important to delve deeper. The returns, though significantly lower, could be symptomatic of isolated issues—perhaps certain product lines aren’t meeting customer expectations or there might be logistical challenges causing unnecessary returns. Understanding whether this 10% return rate is uniformly distributed across your product categories or concentrated in specific segments can yield further insights. It hints at the possibility that while most products perform reliably, a few might be undermining customer satisfaction or operational efficiency.

**RECOMMENDATIONS**

Given this narrative, your next steps should be to analyze the return data in greater detail. Identify if specific products have higher return rates and investigate the reasons behind these returns—be it quality issues, miscommunication in product descriptions, or logistical delays. Strengthen your quality assurance and customer feedback mechanisms to capture these insights early on. Additionally, consider performing a comparative analysis between products with low versus higher return rates to discern best practices that could be implemented across the board. Revisiting your return policies to ensure they are both customer-friendly and protective of your margins might also be a valuable step. By adopting these strategies, you can not only maintain the high volume of sales but also convert the relatively low return rates into opportunities for improving product quality and customer satisfaction.

**MAJOR TAKEAWAY**

the data being analyzed paints a picture of a business facing several challenges. The first major problem is the significant revenue volatility. While there was a promising peak in sales, the subsequent years (notably 2022 and 2023) reveal a steep decline that could be due to a mix of market headwinds, operational inefficiencies, or shifts in customer behavior. Secondly, there's an imbalance in product performance. Some items shine brightly with high profit margins and strong sales volumes, yet others lag behind or even struggle to turn a profit, suggesting issues in pricing, production costs, or market demand alignment. Lastly, while overall sales volume is robust, even a relatively low rate of returns can signal quality or logistical challenges in specific product categories that might undermine customer satisfaction if not addressed.

**SUMMARISED RECOMMENDATIONS** 

Based on these insights, a few data-driven actions seem essential. Begin with a detailed diagnostic review of the factors that led to the pronounced revenue drop: assess external market trends, scrutinize competitor behaviors, and evaluate changes in customer preferences; this will help pinpoint the real drivers of decline. Next, for the inconsistent performance across products, perform a comparative analysis to identify best practices from top performers, then replicate or adjust strategies for the underperformers—whether that involves optimizing the pricing strategy, revising production or supply chain processes, or perhaps even rethinking the product portfolio altogether. Furthermore, implementing dedicated customer feedback loops and quality control measures can help uncover and mitigate issues causing returns. Lastly, consider bolstering marketing initiatives and diversifying offerings to capture different segments of demand and reduce dependency on a narrow range of products.

**CONCLUSION**
The sales data tells a clear story. Initially, things looked promising with good revenue and strong sales. However, after reaching a peak, revenue steadily dropped in the following years. This decline may be caused by external factors like market conditions or shifts in customer behavior, as well as internal issues such as operational challenges and inconsistent product performance.
To turn things around, it's important to clearly understand what led to the drop. Investigate external trends and internal processes—like pricing, production costs, and product quality—to identify problem areas. Focus on the products that are doing well, and try to apply their successful strategies to the weaker ones. Finally, gathering customer feedback and tightening quality control can help improve overall performance.
In simple terms, by pinpointing the causes of the revenue decline and addressing them with targeted actions, the business can rebuild its growth and improve its future prospects.
