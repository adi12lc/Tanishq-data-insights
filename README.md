# Tanishq-data-insights

1. **Product Catalog Insights**
2. **User Segmentation Based on Browsing Activity**
3. **Factors Affecting User's Buying Decisions**

## Product Catalog Insights

The report begins with an analysis of product catalog data, focusing on customer preferences, pricing strategies, stock management, and search trends. The analysis reveals insights such as:

- Women's preference for white gold engagement rings with high diamond clarity.
- The impact of pricing and discounts on the popularity of items.
- The need for frequent restocking of certain subcategories.
- The popularity of categories and subcategories online.

## User Segmentation Based on Browsing Activity

The second part of the report focuses on user segmentation based on browsing activity. The analysis uses features like action_type, object_type, user_type, epoch (timestamp), referrer, city/state, country, latitude, longitude, platform, browser, day_of_year, datetime, and hour. The insights include:

- Majority of users are utilizing the Android platform.
- Most browsing activity occurs among guest users.
- Users tend to utilize the website more on Saturdays and Fridays.
- People tend to engage in browsing activities more frequently during the afternoon.

## Factors Affecting User's Buying Decisions

The final part of the report identifies the major factors affecting user's buying decisions. Two machine learning models were built using XGBoost, one as a multiclassification problem and the other as a regression problem. The insights include:

- The model with 'Action Type' as the target achieved an accuracy and F1 score of 0.74.
- The model with 'Time Duration' as the target accurately predicted the user's duration on the site with less error.

## Note

This README file is a simplified summary of the report. For a comprehensive understanding, please refer to the original report.
