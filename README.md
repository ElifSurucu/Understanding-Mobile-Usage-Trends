# Understanding Mobile Usage Trends

The dataset I used was found on this Kaggle page: [https://www.kaggle.com/datasets/bhadramohit/smartphone-usage-and-behavioral-dataset/data
]

There are two main notebooks in this project:

- Data Analysis Notebook

- Modeling Notebook

In the Exploratory Data Analysis (EDA) notebook, I conducted a thorough analysis of the app usage dataset to understand its structure and identify key features that could inform the machine learning process. This step helped uncover patterns and relationships between different features, such as app usage hours, demographics, and time of day, which were crucial for predictive modeling.

For the predictive modeling notebook, I used insights from the EDA to develop and train models that classify the type of app usage (e.g., Productivity, Social Media, Gaming) based on user behavior and demographics. After experimenting with several machine learning models, including Random Forest and XGBoost, I found that the XGBoost model achieved a slightly higher accuracy score of 96% compared to 95% with Random Forest. Given this performance, I proceeded with XGBoost as the final model due to its higher accuracy and robustness in handling complex patterns in the data.

Initially, I considered framing this problem as a regression task, but classification proved more appropriate and feasible given the categorical nature of the target variable. This classification approach ultimately allowed me to gain meaningful insights into user engagement patterns, providing actionable information for optimizing app usage strategies based on user segments.

This project aims to enhance user engagement and maximize ad revenue potential by analyzing mobile usage behavior patterns. By examining smartphone usage habits across different demographic groups, we provide strategic insights and recommendations that enable marketing agencies to target their advertisements more effectively.

Our approach focuses on identifying usage trends and user preferences to optimize ad placement and timing, ensuring that marketing efforts resonate with specific user segments. By tailoring advertising strategies to align with peak usage times, preferred app types, and demographic-specific behaviors, agencies can improve engagement rates and optimize the return on ad spend. Additionally, these insights empower agencies to craft campaigns that not only increase brand visibility but also foster greater user loyalty.

With this project:

- Ad engagement and conversion rates are anticipated to improve,
- Demographic-based marketing strategies will be optimized,
- A targeted advertising approach will be established, tailored to user segments and peak engagement times. 

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
