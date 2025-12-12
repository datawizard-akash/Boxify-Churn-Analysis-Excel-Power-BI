# Boxify-Churn-Analysis-Excel-Power-BI
Boxify is an online subscription box service delivering monthly lifestyle products. Over the past year, the company has observed a rise in customer churn subscribers canceling before completing 6 months. Management wants to understand why customers leave and take action to improve 

## 2.Project Objective
The analysis focuses on the following business objective:
* •	Reduce churn rate by 5–10% over the next 6 months.
* •	Identifying high-risk customer segments.
* •	Recommend strategies to retain subscribers and increase loyalty.
## 3. Dataset Description.
* •	Source of data – Kaggle.com
* •	Time Period – 2023-2025
* •	Rows – 1,200
* •	Columns – 11 (customer_id,join_date,cancel_date,age,gender,location,subscription_type,total_spent,boxes_received,engagement_score,	payment_mode)


## 4. Tools Used.
*	Microsoft Excel - Initial data exploration and validation.
* 	Power BI – Data modelling, DAX measures, and interactive dashboard creation.
## 5. Data Cleaning & Preparation.
*	Data Import & Cleaning:  Loaded the CSV file into Power Query, removed duplicates, fixed data types, Handled missing values in the cancel date column and derived Subscription Status column, Subscription Tenure column, Age segment and a new Cancel date column without the missing values.
*	Measure Creation: Created key DAX measures like Total Revenue, Active Customers, Average CLV, Churn Rate, Average Tenure of Churn Customers, Customers Lost and  Total Customers.
*	Visualization: Designed an interactive dashboard showing Churn by age group, Active customer by age group, Churn by gender, Total customers and Churn rate by age group, Active and Inactive customers, Average CLV Active vs Inactive customers.
*	Insight Generation: Interpreted the visualisations to answer business questions and
create recommendations. 
## 6. Key Insight.
*	Overall Churn Performance: The dashboard shows that the company has lost 216 customers, resulting in an 18% churn rate. Despite this loss, the business generated a total revenue of ₹15M. The average tenure of churned customers is 7.09 months, indicating that customers stay for a considerable period before leaving. This provides a reasonable window for improving engagement and implementing retention strategies before customers decide to churn.
*	Churn Distribution by Age Group: The churn analysis reveals that senior customers account for the highest share of churn at 36.11%, followed closely by mid-age customers at 35.65%. Young customers contribute 28.24% of total churn. Since the senior and mid-age groups together represent more than 70% of churn, they appear to be the most vulnerable segments. Focusing on improving satisfaction and value for these age groups may significantly reduce overall churn.
*	Gender-Based Churn Patterns
The gender breakdown shows that female customers experience slightly higher churn at 51.85%, compared to 45.83% for male customers. A small portion, about 2.31%, falls under the “Other” category. The higher churn among female customers suggests possible differences in expectations, preferences, or product fit that should be explored further to improve retention.
*	City-Level Customer Activity: The distribution of active and inactive customers indicates that some cities face higher disengagement. Hyderabad and Chennai each have 30 inactive customers, making them the most affected locations. Kolkata and Lucknow also show noticeable inactivity with 23 and 22 inactive customers respectively. Cities such as Bengaluru and Jaipur maintain relatively lower inactivity levels. This pattern suggests that customer satisfaction or engagement issues may be influenced by regional factors, highlighting the need for localized interventions.
*	Age Group Performance Trends
The combined view of total customers and churn rate shows that senior and mid-age customers not only represent large portions of the total customer base but also face churn rates close to 18 percent. In contrast, the young segment shows a slightly lower churn rate. This indicates that although older segments have strong representation, they remain at higher risk of leaving. Enhancing the experience and value proposition for these groups could help stabilize churn and improve overall retention.
 

## 7. Recommendation.
*	Strengthen Retention Efforts for Senior and Mid-Age Customers
Since these two age groups account for over 70% of total churn, targeted retention programs should be designed specifically for them. This may include personalized communication, loyalty-based rewards, simplified product offerings, or dedicated customer support to address their needs and concerns. Improving the experience for these groups is likely to make the largest impact on reducing churn.
*	Investigate and Improve Female Customer Experience
With female customers showing the highest churn percentage, it is important to understand the root causes of dissatisfaction within this segment. Conducting short surveys, feedback sessions, or analysing behavioural patterns can uncover gaps in service or product design. Enhancing features that matter most to female users and ensuring a smoother customer journey may substantially reduce churn rates among this group.
*	Focus on Underperforming Cities with High Inactivity
Cities such as Hyderabad, Chennai, Kolkata, and Lucknow show significantly higher inactive customer counts. These regions may benefit from location-specific engagement strategies such as targeted marketing campaigns, improved service quality, better onboarding, or localized offers. Strengthening customer relationships in these cities can bring inactive users back and prevent further churn.
*	Enhance Early-Stage Engagement to Reduce Mid-Term Drop-Off
With the average churn tenure at around seven months, customers tend to disengage after the initial period of usage. Strengthening engagement during the first few months—through personalized recommendations, onboarding guidance, proactive check-ins, or reward programs—can help prevent customers from losing interest over time and reduce the likelihood of churn around the seven-month mark.
*	Leverage CLV Insights to Prioritize High-Value Customers
Since active customers generate more than double the lifetime value of inactive ones, investing in retention programs targeting high-CLV customers will yield strong returns. Offering premium support, exclusive benefits, or tier-based loyalty programs can ensure that top-value customers remain engaged and continue contributing to long-term revenue growth.
*	Implement Data-Driven Personalization Across Customer Segments
Using the behavioural and demographic insights captured in the dashboard, the company can implement more personalized customer journeys. Tailoring offers, communication styles, and product recommendations based on age, gender, and location can significantly enhance user experience and improve retention outcomes across all segments.

## 8. Conclusion.
The churn analysis reveals that while the company maintains strong revenue performance, customer retention remains a critical area of improvement. Higher churn among senior, mid-age, and female customers, along with inactive clusters in specific cities, highlights the need for targeted engagement efforts. Strengthening early-stage interaction, improving customer experience in high-risk segments, and leveraging CLV insights can significantly reduce churn and enhance long-term profitability. Overall, focused retention strategies will not only stabilize the customer base but also unlock substantial growth potential for the business.
