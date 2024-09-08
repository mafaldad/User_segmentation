# Project Title: Mobile Applications: User Segmentation and Behavior Analysis

**Overview:** This project provides an in-depth analysis of user behavior within the "Trash to Treasure" mobile app, focusing on segmenting users based on their actions. The goal is to improve engagement, retention, and conversion rates by identifying distinct user segments and testing behavioral hypotheses. Using k-means clustering, we grouped users into meaningful segments and applied hypothesis testing to understand the impact of acquisition sources on user behavior. The project integrates data preprocessing, exploratory data analysis (EDA), machine learning, and statistical hypothesis testing to deliver actionable insights for app improvement.

**Key Skills & Concepts:**

* Data Preprocessing: Merged and cleaned datasets, handled missing values, standardized columns, and reformatted event logs for accurate analysis.
* Exploratory Data Analysis (EDA): Explored user activity, event distributions, and source effectiveness through comprehensive visualizations.
* User Segmentation (K-Means Clustering): Clustered users into four groups based on metrics like event frequency, engagement with key features, and recency of activity.
* Hypothesis Testing: Performed a chi-square test to assess differences in conversion rates between users acquired via Bing and Google, ensuring the results were statistically valid.
* Data Visualization: Created visual representations of event activity, user segmentation, and key behavioral metrics using advanced plotting techniques.

**Key Insights:**

* Event Distribution: The tips_show event (recommended ads) was the most frequent, indicating its pivotal role in driving user engagement.
* User Activity: Most users are lightly active, but a small segment shows exceptionally high engagement, contributing significantly to app metrics.
* User Segmentation: Four clusters were identified, with Cluster 3 being the most engaged (most extended usage, highest event count) and Cluster 0 having the highest churn risk (shorter sessions, low engagement).
* Conversion Analysis: No significant difference was found in conversion rates (viewing contact information) between Bing and Google users, suggesting acquisition source did not affect this behavior.
* Retention Trends: Users who joined after October 7, 2019, showed a steep decline in retention after the first interaction, indicating potential improvements in onboarding and early engagement strategies.

**Tools Used:**

* Python (Pandas, Seaborn, Matplotlib, Scikit-learn): For data cleaning, manipulation, clustering, and visualization.
* SQL: Queried datasets to retrieve meaningful insights.
* Statistical Testing (SciPy): Used for hypothesis testing and statistical validation of user behavior differences.
