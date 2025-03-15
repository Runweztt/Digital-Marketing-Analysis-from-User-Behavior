# Digital-Marketing-And-User-Behavior-Analysis
Project Overview This project focuses on analyzing the performance of digital marketing campaigns by looking at user engagement, conversion rates, and revenue across different devices, traffic sources, and regions. The goal is to identify patterns that can inform better decision-making in marketing strategies.

We started by investigating missing data in the "Campaign" column to understand why certain campaign details were not recorded. Through this, we explored how missing values could be connected to specific dates, traffic sources, or device categories.
We also took a deep dive into user engagement, looking at metrics like session duration and page views to see how users engage with different campaigns across devices. Additionally, we analyzed campaign performance, identifying which campaigns led to the highest conversion rates and revenue. We compared how different devices affected conversion rates and explored how different traffic sources and mediums impacted results.
Finally, we performed a predictive analysis to estimate the likelihood of users converting based on their engagement metrics. The project aims to provide actionable insights that businesses can use to optimize their marketing efforts and improve customer engagement.


**Objectives**

1 User Engagement Analysisa
 What is the average session duration and page views per campaign, device, source, etc.?
2 Campaign Performance Comparison
Which campaigns lead to the highest conversion rates and revenue?
3 Device Category Insights
 How do conversion rates and average session durations differ by device?
4 Source and Medium Traffic Effectiveness
 Which traffic sources and mediums are most effective in driving conversions and revenue?
5 Geographical Analysis
 Are users from specific countries more likely to convert?
6 New vs. Returning Users
 How do new and returning users differ in conversion and revenue generation?
Predictive Analysis
7 Predicting Conversion Likelihood
 Can we predict the likelihood of conversion based on session metrics and campaign data?





**1Handling Missing Data:**

We noticed that a good chunk of the "Campaign" data was missing – about 24.9% (2,490 entries). So, we dug deeper to find out why. We checked if the missing data was linked to specific dates, sources, or even devices. Turns out, the missing data wasn't tied to any particular time or device but seemed to be a bigger issue with the way the data was recorded.
To investigate why the Campaign data is missing, I followed this approach:
1.	Check Missing Data by Date
Checking if missing campaign values are concentrated around specific dates. This helps determine if certain days have missing campaign data.
2.	Analyse Missing Campaign Data by Source and Medium
Checking if missing values are concentrated in certain sources or mediums can help identify issues. For instance, if "Direct" traffic has most missing values, it might suggest campaigns weren’t tracked for direct traffic.
3.	Identify Patterns in Engagement Metrics
Looking at metrics like Session_Duration and Page_Views for users with missing campaign data. This helps to see if their behavior is similar to those under specific campaigns.
4.	Check by Device and Country
Investigating if missing campaign data is related to specific devices or countries.

What We Found:
•	Missing data was spread across different sources, devices, and countries. No clear patterns showed up, so it looks like a technical issue rather than something specific like a certain campaign or region.
•	Users with missing campaign data had similar session durations and page views compared to users with campaign data, so it might not affect user engagement much.

**2 User Engagement Insights:**

•	Desktop Users: Organic and Social traffic were driving more page views, while Direct traffic had longer session times. So, people who come directly to the site might already be interested.
•	Mobile Users: Direct traffic also performed well, with good session duration and page views.
The visualize Insights
1. Average Session Duration by Campaign & Device Category
•	The session durations across campaigns and devices are fairly consistent, with no significant variations. Each device category (Desktop, Mobile, Tablet) appears to have similar session durations within each campaign.
2. Average Page Views by Source & Campaign
•	 Similar to session duration, the average page views per campaign seem relatively consistent across different sources.

insights:
•	For desktop users, Organic and Social traffic worked best for driving more page views, so it might be worth focusing on these channels.
•	For mobile users, Direct traffic performed better, suggesting that improving the mobile experience could keep users more engaged.
2 Campaign Performance Comparison
•	Conversion Rate by campaign:
o	Spring Promo and Summer Sale have the highest conversion rates, followed by the Winter Campaign.
o	The Unknown campaign has the lowest conversion rate but is still close to the others.
•	Revenue by Campaign:
o	Spring Promo generates the highest revenue at $122,307, followed by Summer Sale and Winter Campaign.
o	The Unknown campaign brings in the lowest revenue at $96,217.
•	The "Spring Promo" campaign was the standout, performing best in both conversion rates and revenue. Other campaigns like "Summer Sale" and "Winter Campaign" also performed decently, but "Unknown" campaigns had the lowest conversion rates and revenue.

**3 Device Category Insights**

•	Mobile: Conversion rate of 28.15% and average session duration of 334.83 seconds.
•	Desktop: Conversion rate of 27.47% and average session duration of 331.22 seconds.
•	Tablet: Conversion rate of 27.27% and average session duration of 328.61 seconds.
insight
•	Mobile had the highest conversion rate and session duration, meaning people on mobile tend to stay longer and convert better.
•	Desktop was a close second, while Tablets had the lowest performance in terms of conversions and engagement.
The scatter plot visualize
1.	Mobile devices appear to have the highest conversion rate (around 28%) and the longest average session duration (close to 335 seconds). This suggests that mobile users not only convert more frequently but also tend to stay engaged longer.
2.	Tablet devices show the lowest conversion rate (around 27.3%) and the shortest average session duration (just under 329 seconds). This may indicate less engagement and a lower likelihood of conversion for tablet users.
3.	Desktop devices sit in the middle, with a conversion rate around 27.5% and an average session duration around 331 seconds.

**4 Source and Medium Traffic Effectiveness**

We analyzed which traffic sources (like Direct or Organic) worked best for conversions:
Top performers in conversions:
•	Direct + Organic Search: 993 conversions.
•	Direct + Direct: 979 conversions.
Revenue:
•	Direct + Direct: $99,301.
•	Referral + Direct: $98,302.
•	Direct + Organic Search: $96,217.
Conversion Rates:
•	Social + Direct has the highest conversion rate at 29.62%.
insight
•	Direct + Organic and Direct + Direct traffic had the highest conversions and revenue. This suggests that users arriving directly or via organic search were more likely to convert.
•	Social Media didn’t perform as well for conversions but might still have some value for brand awareness.

**5 Geographical Analysis**

Top Performing Countries by Conversions:
•	Canada: 2,208 conversions.
•	USA: 2,188 conversions.
•	Germany: 2,160 conversions.
Revenue Generation:
•	Canada: $222,268.
•	Germany: $220,057.
•	Australia: $211,675.
Conversion Rates:
•	France has the highest conversion rate at 28.43%.
Insights:
Countries like Canada, USA, and Germany were the top performers in both conversions and revenue. France had the best conversion rate, while the UK  had the lowest conversion rates. There’s room to improve in these regions, especially in the UK and 



**6 New vs. Returning Users**

Conversions:
•	Returning Users: 7,576 conversions.
•	New Users: 7,510 conversions.
Revenue:
•	Returning Users: $760,797.
•	New Users: $751,992.
Page Views:
•	Returning Users: 27,797 page views.
•	New Users: 26,797 page views.
Conversion Rate:
•	Returning Users: 27.25%.
•	New Users: 28.03%.
Returning users converted slightly more and generated more revenue than new users. This shows the value of customer retention, but new users also performed well, so we shouldn’t ignore them.

7** Predictive Analysis:**

i built a model to predict conversion likelihood based on session metrics and campaign data:
Model Analysis:
•	Accuracy: 74.35%.
•	Precision: 74.35%.
•	Recall: 100%
The model had 74.35% accuracy, meaning it correctly predicted conversions 74% of the time.
Recall was perfect (100%), meaning it caught every conversion, but precision could be improved to avoid predicting conversions when they don’t happen.


