# Objective

This project focuses on examining customer patterns and behaviors through comprehensive analysis of the Superstore retail dataset. Using five targeted analytical approaches, we will identify key insights about customer retention, purchasing value, loyalty dynamics, buying behaviors, and regional trends. The findings will inform strategic customer segmentation and evidence-based marketing initiatives.

The analysis seeks to understand how customers interact with the retail platform across multiple dimensions, revealing actionable intelligence that can enhance customer relationship management and drive business growth through data-informed decision-making processes.

# Methods Used

1. RFM Segmentation - Classifies customers based on Recency, Frequency, and Monetary value

2. CLTV Estimation - Calculates the lifetime value of each customer based on AOV, frequency, and lifespan

3. Cohort Analysis - Examines customer retention by first purchase month and subsequent activity

4. Repeat Purchase Behavior - Identifies how often customers make multiple purchases and in what categories

5. Geo Loyalty Analysis - Compares regional performance based on CLTV and customer volume


## 1. RFM Segmentation

**Objective:** Segment customers based on recency, frequency, and total spending

**Approach:**
 
* Recency: Days since last purchase
* Frequency: Unique orders per customer
* Monetary: Total spending
* Customers scored from 1 to 5 for each metric
* Segments assigned as 'Champions', 'Loyal', 'Potential', or 'At Risk'

**Insight:**
    
* Majority of customers are in the "Loyal" and "Potential" segments.
* Very few are "Champions", highlighting an opportunity to increase high-value retention.

**Recommendation:**

* Implement a loyalty rewards program for "Potential" and "Loyal" customers to push them to "Champion" status.

 <img width="472" alt="image" src="https://github.com/Gursimransachar/Superstore_Customer_Behaviour_Analysis/blob/Visuals/RFM.png" />


## 2. CLTV Estimation

**Objective:** Estimate how much revenue a customer brings over their lifetime

**Formula Used:**
    
* AOV (Average Order Value) = Total Sales / Orders per Customer
* Frequency = Orders per Customer ID
* Lifespan = Time between first and last purchase (in months)
* CLTV = AOV × Frequency × Lifespan

**Insight:**

* CLTV distribution is heavily right-skewed; most customers have moderate values, a few contribute disproportionately.
    
**Recommendation:**

*  Focus marketing and retention strategies on high CLTV customers.
*  Use predictive modeling to identify potential high-CLTV customers early.


## 3. Cohort Analysis

**Objective:** Understand how customer retention changes month-to-month after first purchase

**Approach:**

* Grouped customers by the month of their first purchase
* Tracked active customers each month thereafter
* Visualized using a heatmap (cohort index)


**Insight:**

*  Most cohorts drop sharply after month 1, indicating low retention beyond the first order.
*  Certain older cohorts (e.g., early 2014) showed better long-term retention.


**Recommendation:**
    
* Re-engage new customers early with email campaigns, upsells, or onboarding guides.
* Study past successful cohorts to replicate their behavior.



## 4. Repeat Purchase Behavior

**Objective:** Identify how frequently customers return and which categories they prefer

**Findings:**
    
* Most customers made only 1 order, while a few made multiple
* Furniture and Office Supplies had higher repeat buyers than Technology


**Recommendation:**
    
* Create category-specific bundles or incentives to drive repeat purchases.
* Use cross-selling for categories with fewer repeat purchases.


## 5. Geo Loyalty Analysis

**Objective:** Identify regions with the most loyal/high-value customers

**Metrics Used:** Average and total CLTV by Region

**Findings:**
    
* Regions like the West and East had the highest total CLTV
* Central and South regions showed potential for growth

**Recommendation:**
 
* Double down on retention strategies in top-performing regions.
* Launch localized promotions or customer outreach in lower CLTV areas.


# Strategic Business Recommendations


* **Champion Nurturing:** Build VIP programs for high-RFM, high-CLTV customers
* **Onboarding Triggers:** Automate personalized emails for new customers to improve retention
* **Geo-targeted Campaigns:** Promote region-specific offers where CLTV is low but potential is high
* **Product Focus:** Encourage repeat purchases in high-margins categories with loyalty incentives
* **Predictive Targeting:** Use top RFM + CLTV segments for focused advertising spend


# Conclusion

This project presents a comprehensive analysis of customer behavior using the Superstore dataset, blending statistical metrics with business insights. Together, these findings support a data-driven customer strategy focused on high-value retention, early lifecycle engagement, targeted offers, and geographic optimization. Businesses adopting such insights can not only retain more customers but also maximize lifetime value and increase return on marketing investments.
