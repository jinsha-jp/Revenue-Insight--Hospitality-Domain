# Revenue Insight for Atliq Properties

![image](https://github.com/user-attachments/assets/66299a36-925d-4049-ae89-eda596419144)

## Problem Statement
Atliq Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, Atliq Grands are losing its market share and revenue in the luxury/business hotels category. As a strategic move, the managing director of Atliq Grands wanted to incorporate “Business and Data Intelligence” in order to regain their market share and revenue. However, they do not have an in-house data analytics team to provide them with these insights.

Their revenue management team had decided to hire a 3rd party service provider to provide them insights from their historical data.

## Description:
The primary objective of this project is to analyze and interpret hospitality sales and booking data to derive actionable insights that will optimize hotel operations, improve guest satisfaction, and maximize revenue for the Atliq property . This analysis enables hoteliers, revenue managers, and business stakeholders to make data-driven decisions that optimize occupancy, improve guest satisfaction, and maximize profitability.

## Objective :
•	Analyze key performance indicators (KPIs) such as Occupancy Rate, Average Daily Rate (ADR), and Revenue Per Available Room (RevPAR) to identify pricing strategies and optimize room inventory management.
•	Provide stakeholders with a visual dashboard of key data points, enabling them to make real-time decisions about pricing, promotions, resource allocation, and customer service improvements.

## Data collection & data modelling
### Data Import and Cleansing in Power Query:
- The raw booking data and other dimensional tables with info regarding – date, hotel and room was imported into Power BI, and Power Query was used to clean and format the dataset.
- Promoted header and removed unwanted columns and changed data type and renamed few columns
- 	Ensured that the data types for each column were 
- Checked for any inconsistencies or errors in the data, such as invalid responses or outliers
- Created new calculated columns
### Data Modeling in Power BI:
 Established relationships between tables (e.g., booking, room description, dates etc) to ensure that the data can be analyzed cohesively across different dimensions.

 ![image](https://github.com/user-attachments/assets/b3336a37-6f0f-4c0b-8421-7ecf75c582af)

### Creating Measures and KPIs:
Developed measures to calculate key performance indicators (KPIs) that help in decision-making.


## Dashboard

![image](https://github.com/user-attachments/assets/d2400209-d2f8-49f8-b6d2-50821e68b88c)

![image](https://github.com/user-attachments/assets/deb2b98f-7ba2-49e3-8d1f-edc3c3b52f43)



## Insights

1.	19.3% of the revenue is coming from weekdays, while the remaining 80.7% is from weekends. This suggests that weekends are the primary source of revenue in the business, which is typical in many hospitality sectors, as people often travel or dine out more on weekends.
2.	Average Daily Rate (ADR) is relatively consistent, at 12.7k, whether it's a weekday or weekend.
-	This could be an indication that pricing strategy is stable across both periods, and business model is maintaining a similar rate despite the higher volume of weekend bookings. 


3.	DSRN (Daily Sellable Room Nights): 2.53k total, with 2,191 rooms available on weekdays and 385 rooms available on weekends.
-	There is  significantly higher number of sellable rooms available on weekdays (2,191) compared to weekends (385). This suggests that weekend capacity is much lower than your weekday capacity

4.	An occupancy rate of 58% suggests that property is filling about 58% of its available rooms. This indicates there’s room for improvement. weekend occupancy of 73% is significantly higher than the weekday occupancy (55%). This suggests that weekends are a strong point for your business, likely driven by leisure or event-driven travelers.
5.	A 70% realization rate could be an opportunity to review the pricing strategy. 

6.	With a 24% cancellation rate, it means that approximately 24% of the confirmed bookings are being canceled before the guest arrives
- Cancellations reduce your effective occupancy and can lead to lost revenue opportunities

7.	41% of bookings coming from "Others".20% from MakeYourTrip and 11% from LogTrip together account for a solid 31% of bookings, indicating that these booking platforms s are a key source of bookings. With only 10% of bookings coming from direct online channels, it suggests there’s a missed opportunity to grow your brand’s visibility and encourage more direct bookings.
8.	5% from direct offline bookings suggests that a small portion of guests is still choosing to book via phone, in-person, or other offline methods. While this percentage is low, it's worth understanding which segment of customers prefers offline channels.
9.	62% of bookings are from business rooms, indicating that corporate or business travelers make up the majority of your customer base
10.	among the 7 properties Atliqua Exotica, Atliq Palace, and Atlique City collectively account for 80% of the total revenue, with their individual contributions being:
- Atliqua Exotica: 18% of the total revenue
- Atliq Palace: 17% of the total revenue
- Atlique City: 16% of the total revenue
11.	Having 80% of revenue coming from just 3 properties could create some business risks. For instance, if one of these properties faces challenges (e.g., operational issues, natural disasters, or changes in customer demand), it could significantly affect your total revenue. This makes it important to diversify revenue sources or improve performance across the other 4 properties.The remaining 4 properties only contribute 20% of the total revenue. 
12.	12% of total revenue from Atlique Exotica suggests that it is a key player in the portfolio, especially if it is one of the larger properties or in a high-demand location like Mumbai. This could indicate that it has strong market positioning, great guest demand, or competitive pricing.
13.	A 3.6 rating means that guests are likely sharing mixed feedback, with some positive reviews but also areas where improvement is needed.
14.	A rating of 2.2 for Atlique Season Hotel is quite concerning, as it suggests that guests are highly dissatisfied with their experience at the property
15.	The difference in ratings between Atlique Bay in Bangalore (4.3) and Hyderabad (4.3), compared to Mumbai (2.4), is quite significant and suggests that there are major differences in the guest experience across these locations.Atlique exotica have 2.3 in hydarbad Mumbai 4.3
16.	The rating of 2.4 for Atlique Grands in Bangalore, compared to higher ratings in other cities (3 and 4.3), suggests that the property in Bangalore is facing serious challenges in guest satisfaction.


## Reccomendation


1.	If demand is higher on weekends, might consider increasing the ADR for weekends, leveraging the high demand. Conversely, offering promotions or discounted rates during weekdays could help stimulate demand during slower periods.
2.	It’s important to evaluate why the weekend DSRN is much lower. If this is due to factors like room blockages for events or maintenance, you may need to optimize internal processes to ensure that weekend availability aligns with demand.
3.	If the low weekend availability is a result of operational constraints (like staffing, maintenance, or seasonal adjustments), understanding and resolving these constraints could unlock potential revenue growth.
4.	Analysing historical booking patterns for weekends can help you forecast demand more accurately. If you’re consistently seeing higher weekend demand, you can adjust availability proactively to ensure you're capturing the maximum number of potential bookings.

5.	To Boost Weekday Occupancy: Target business travellers, offer corporate packages, or run midweek promotions to fill more rooms. Consider bundling services (like meals, parking, or activities) to make weekdays more attractive

6.	Increasing dynamic pricing or adjusting rates for peak demand periods could improve the realization percentage.
7.	Consider upselling room categories (e.g., offering premium rooms or packages) or providing add-ons (like breakfast, parking, or early check-in) to boost revenue.

8.	By refining the cancellation policy, analysing cancellation patterns, and using targeted marketing strategies, you can reduce cancellations and improve your ability to fill rooms, ultimately maximizing occupancy and revenue.








