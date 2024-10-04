# Customer Satisfaction Analysis
![Banner](https://static-blog.omniconvert.com/blog/wp-content/uploads/2024/07/09094340/1610950510043-800x400.png)

## Overview
Customer Satisfaction Analysis is the process of collecting, analyzing, and interpreting data on customer experiences regarding products, services, and overall satisfaction. This analysis helps businesses make data-driven decisions to improve customer retention, loyalty, and business performance.

## Dataset
The dataset used in this analysis contains the following features:
- **CustomerID**: Unique identifier for each customer.
- **Age**: Age of the customer.
- **Gender**: Gender of the customer (Male/Female).
- **PurchaseAmount**: Total amount spent by the customer.
- **PurchaseFrequency**: Number of purchases made by the customer.
- **ProductQualityRating**: Customer rating for product quality (1-5).
- **DeliveryTimeRating**: Customer rating for delivery time (1-5).
- **CustomerServiceRating**: Customer rating for customer service (1-5).
- **WebsiteEaseOfUseRating**: Customer rating for website ease of use (1-5).
- **ReturnRate**: Proportion of products returned by the customer.
- **DiscountUsage**: Amount of discount used by the customer.
- **LoyaltyProgramMember**: Whether the customer is a loyalty program member (Yes/No).

## Key Findings

### Summary Statistics:
- **Age**: The average customer age is 44 years, with a range from 18 to 69 years.
- **Purchase Amount**: Average of $1065, with high variability in spending.
- **Purchase Frequency**: Customers purchase on average 14 times, with some making up to 29 purchases.
- **Ratings**: Average ratings around 3 for product quality, delivery time, customer service, and website ease of use, indicating moderate satisfaction.
- **Return Rate**: Average return rate is 25%, with some customers returning up to 50% of purchases.
- **Discount Usage**: Average discount usage is around $251, with significant variability.

### Distribution Insights:
- **Age**: Even distribution with peaks in the 30s and 60s.
- **Purchase Amount**: Right-skewed distribution, with most customers spending less than $1000.
- **Purchase Frequency**: Varied, with peaks around 10 and 20 purchases.
- **Ratings**: Most satisfaction ratings cluster around 3 (moderate satisfaction).
- **Return Rate**: Peaks at 0.1 and 0.4, showing varying return behavior.
- **Discount Usage**: Evenly spread with no significant trend.

### Segment Analysis:
#### Satisfaction Ratings by Age and Gender:
- Younger customers (18-29) rate product quality slightly higher.
- Females aged 40-49 give the highest satisfaction ratings.
- Delivery time satisfaction is consistent across age groups, with females aged 60-69 rating it highest.
- Customer service ratings peak among younger males (18-29), while males aged 60-69 rate it the lowest.

#### Impact of Loyalty Program Membership:
- **Product Quality**: Loyalty members rate it higher (2.95) than non-members (2.92).
- **Delivery Time**: Members show higher satisfaction (3.09) than non-members (2.92).
- **Customer Service**: Higher rating by members (3.16) than non-members (2.99).
- **Website Ease of Use**: Non-members rate it slightly higher (3.11) than members (3.06).
- **Return Rate**: Similar for both members and non-members (0.25).
- **Discount Usage**: Members use slightly more discounts ($241).

### Root Cause Analysis of Low Satisfaction:
- Low ratings are seen across customers of all age groups, with notable peaks around ages 30-40 and 50-60.
- High return rates correlate with low ratings, especially for product quality and website ease of use.
- Low satisfaction is observed among both high and low spenders, indicating issues beyond spending behavior.

## Conclusion
Customer Satisfaction Analysis provides deep insights into customer behavior and satisfaction levels. This project demonstrates how to analyze customer feedback and ratings to identify key areas for improvement. The root cause analysis of dissatisfaction can help businesses address customer pain points and enhance overall satisfaction.

## Tools Used
- **Python**: For data analysis and visualization.
- **Libraries**: `pandas`, `matplotlib`, `seaborn`, `numpy`.
- **JupyterLab**: For interactive data exploration.

## How to Run
1. Clone this repository.
2. Install the required dependencies.
3. Run the notebook `Customer_Satisfaction_Analysis.ipynb` to explore the dataset and insights.

### 🚀 About Me
#### Hi, I'm Amay Jaiswal! 👋
I am a Data Analytics Enthusiast and  Data science practitioner

[Linkedin](https://www.linkedin.com/in/heyamay/)

