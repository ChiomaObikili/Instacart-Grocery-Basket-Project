<h2>Description</h2>
Instacart already has very good sales, but they want to uncover more information about their sales patterns. My task is to perform an initial data and exploratory analysis of some of their data in order to derive insights and suggest strategies for better segmentation based on the provided criteria.
<h2>Goal</h2>
To uncover customer shopping behavior and segment purchasing patterns in order to support more effective marketing and product placement strategies for Instacart.

<h2>Tools Used</h2>
Python (Pandas, NumPy, OS), Matplotlib, Seaborn.

<h2>Steps Taken</h2>
I Cleaned and merged multiple datasets.
Created new variables to better describe behavior.
Analyzed purchase frequency by weekday, time of day, and department.
Segmented customers by income, age, and parental status.
Visualized shopping behavior across regions and demographics.
<h2>Key Challenges and Solutions</h2>
The dataset lacked financial or demographic data and so I fabricated realistic attributes to enrich segmentation and mimic real-world modeling.

Identifying trends across thousands of products so I aggregated purchases at the department level and applied filters to reveal patterns.

<h2>Analysis and Result</h2>
To understand customer ordering patterns, I analyzed order volume by day of the week and time of day. The data revealed that Sundays and Mondays consistently had the highest number of orders, with Saturdays also performing well. In contrast, Tuesdays and Wednesdays saw the lowest activity, suggesting slower midweek engagement.When looking at order timing, 10 a.m. and 11 a.m. emerged as the peak hours, indicating that most customers place orders in the late morning.

  
<img width="450" height="400" alt="polished_order_hours" src="https://github.com/user-attachments/assets/a999f775-7b4f-4207-909a-26680c9eed8f" /> <img width="450" height="400" alt="polished_busiest_days" src="https://github.com/user-attachments/assets/61b9e8cc-73b1-43c6-be75-800714e5e1ae" />




A histogram of order activity showed that most orders are placed during daytime hours, especially between 9 a.m. and 5 p.m., with very little activity overnight. The quietest period was between midnight and 5 a.m., making 3 a.m. to 4 a.m. the best time for website maintenance with minimal impact on users.Based on peak activity, the most effective window for advertising and promotions is between 10 a.m. and 4 p.m., when customer engagement is at its highest.Spending analysis across regions revealed that most customers are low spenders, regardless of location. However, the South stood out with the highest number of both high and low spenders, while the Northeast had the fewest customers overall in both categories.


<img width="450" height="400" alt="image" src="https://github.com/user-attachments/assets/8510c895-438b-439b-a262-aa5a87e3f9a6" />   <img width="450" height="400" alt="image" src="https://github.com/user-attachments/assets/aeb1eff2-45bd-4d5f-b735-1815d4c2d3ea" />


To better understand customer purchasing behavior, I analyzed transactions by income level and age group. The results showed that low-income customers made the highest number of purchases, highlighting the importance of affordability in driving sales.Among age groups, seniors were the most active purchasers, suggesting that older customers may have stronger brand loyalty, more consistent buying habits, or specific content preferences.These patterns point to key drivers behind customer behavior—price sensitivity and age-related preferences—which can inform both marketing strategies and product offerings.


<img width="450" height="400" alt="polished_customer_age_groups" src="https://github.com/user-attachments/assets/09c25f27-685f-403e-a37c-55c28bfb96d7" />
<img width="450" height="400" alt="polished_customer_income" src="https://github.com/user-attachments/assets/2d4394d1-80d9-4174-8802-ee17c517d4cf" />






I examined purchasing patterns by marital and parental status, and the data revealed that parents consistently made more purchases than single individuals across all income levels. Notably, low-income parents led in total purchases. This suggests that being a parent has a stronger influence on buying behavior than income level, likely due to the increased needs of a household.Next, I explored product category preferences. The produce department had the highest number of purchases, followed by dairy and eggs—indicating a focus on essential, perishable items. In contrast, the bulk and 'other' categories saw the fewest purchases, reflecting lower demand in those areas.


<img width="450" height="400" alt="polished_income_parent_status" src="https://github.com/user-attachments/assets/46e0bf88-ef9f-4482-9aff-11b725b971c4" />
 <img width="450" height="400" alt="image" src="https://github.com/user-attachments/assets/23ed684c-4810-4daa-ab7a-38c7bfbdb281" />





<h2>Insights</h2>
This project helped me learn the important things that can improve how the company markets, manages products, and handles daily operations. We found that most customers prefer mid-priced products, which offer good value for money. There weren’t many purchases of expensive items, but that might be because there aren’t many high-end options available—this could be an opportunity to add more.

The South region stood out because it has the most customers who spend both a little and a lot, so it’s a key area to focus marketing and sales efforts. We also saw that produce and dairy/eggs sell the most, so investing in those departments makes sense. On the other hand, categories like bulk and other don’t sell as well, so they might need extra attention or new ideas to boost sales.

Looking at when people shop and visit the website, the best time to do website maintenance is between 3 and 4 a.m. when few customers are online. The best times to show ads are between 10 a.m. and 4 p.m. The busiest order days are Sunday, Monday, and Saturday, so staff and inventory should be planned accordingly. Also, having good website support during the busiest hours (10–11 a.m.) will improve customer experience.

<h2>Key Success</h2>
We found useful patterns to help improve marketing, sales, and operations.

<h2>Challenges</h2>
We didn’t have enough data on expensive products to know for sure if adding more would help.

<h2>Lessons Learned</h2>
Customers care about more than just price—things like product choice, when they shop, and where they live all matter.
In summary, this project gave me a clear information to make smarter decisions and better serve customers.

<h2>Data Source</h2>
Instacart Grocery Orders (Kaggle) Customer data & product prices were fabricated for project.




