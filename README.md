# Understanding Mobile Usage Trends

![Digital-Marketing-Data](https://www.wearetg.com/wp-content/uploads/2024/01/Digital-Marketing-Data-Dashboard-1024x640.jpeg)

The dataset for this analysis was sourced from Kaggle: [https://www.kaggle.com/datasets/bhadramohit/smartphone-usage-and-behavioral-dataset/data
]

There are two main notebooks in this project:

- Data Analysis Notebook

- Modeling Notebook

## Project Overview

This project analyzes smartphone usage behavior across various demographic segments to assist a marketing agency in refining its ad targeting strategies. By understanding user engagement patterns for different app types (Social Media, Gaming, and Productivity), we aim to provide actionable insights to improve user engagement and maximize ad revenue.

Key objectives include:

1. Enhancing ad effectiveness through targeted placements.
2. Identifying demographic preferences for app usage.
3. Optimizing ad timing to align with peak usage hours.

## Descriptive Analysis Questions

1. Which age groups use the app the most?
2. Which age group has the highest average screen time, and how does this vary by gender?
3. What are the rates of app usage types (social media, productivity, gaming, etc.) across age groups and genders?
4. How does app usage vary across locations?
5. What are the peak usage hours for different age groups and genders?

## Inferential Analysis Questions

1. Is there a significant difference in daily screen time between different age groups and genders?
2. Is there a difference in the types of apps used (e.g. social media, productivity, gaming) depending on the time of day?
3. Does the type of app usage vary from gender, age, and location?
4. Is there a significant difference in social media usage during different times of day?
5. Are productivity applications used significantly more during working hours compared to other times of day?

## Summary of Modeling

In the modeling phase, we experimented with Random Forest and XGBoost classifiers to predict users' primary app usage type. Both models provided valuable insights:

- Random Forest achieved 95% accuracy, offering interpretable feature importance, effectively identifying key factors in app usage.

- XGBoost achieved a similar accuracy of 95% but was ultimately chosen as the final model due to its robust handling of complex data patterns, making it an optimal choice for refining ad strategies.

Key Metrics: XGBoost demonstrated high precision, recall, and F1-scores across all classes, supported by a strong ROC curve, indicating balanced and accurate classification.

Conclusion: With its 95% accuracy, XGBoost is a reliable tool for user classification. The model equips the marketing agency with insights for targeted marketing, user segmentation, and engagement strategies, enabling optimal ad placement and a deeper understanding of audience behaviors.

## Business-Oriented Summary: Leveraging Model Predictions for Marketing Strategy

This machine learning model offers a strategic approach for a marketing agency to tailor its advertising by predicting users' primary app usage type. By understanding user behaviors, the agency can make data-driven adjustments that enhance engagement and maximize ad effectiveness.

1. Targeted Content Recommendations:

- Social Media Users: Prioritize social-focused campaigns, leveraging interactive content, influencer partnerships, and trending topics. Ads during peak evening hours can boost engagement.
- Gaming Users: Focus on game-related ads, in-app purchases, and gamified content, especially during late-night hours when gaming activity peaks.
- Productivity Users: Serve ads for productivity tools, work-from-home products, or educational content during business hours to align with users’ needs.

2. Optimized Ad Timing:

- Leverage model insights to adjust ad placements based on user behavior. Morning ads can target productivity-focused users, while evening and late-night ads are more effective for social media and gaming audiences.

3. Channel-Specific Strategies:

- Refined ad placements across channels allow social media ads on platforms like Instagram and Facebook, while gaming ads may be directed to in-app notifications in popular gaming apps.

Aligning ad strategies with users’ preferences and peak usage times enhances user experience, engagement, and ad ROI, building stronger brand loyalty through relevant, timely content.