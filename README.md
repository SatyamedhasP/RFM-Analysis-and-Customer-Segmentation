# RFM Analysis and Customer Segmentation
Description:
This project focuses on performing RFM (Recency, Frequency, Monetary) analysis and K-means clustering on the Online Retail dataset. The goal is to gain insights into customer behavior, segment customers based on their transactional patterns, and identify distinct customer groups for targeted marketing strategies.

- Libraries used: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Plotly, SciPy, Calendar
- Notebook Link: [RFM Analysis and Customer Segmentation]
- Tableau Workbook:
- Dataset source: [Online Retail](https://archive.ics.uci.edu/dataset/352/online+retail)

The project includes:

1. Data Loading and Exploration:
- Performed initial data exploration. Assessed the data structure, handled missing values, and gained an understanding of the available variables.

2. RFM Analysis:
- Calculated the RFM metrics (Recency, Frequency, Monetary) for each customer based on their transaction history. Determined the recency of their last purchase, the frequency of purchases, and the total monetary value.
- Analyzed the RFM metrics to understand customer segments and their characteristics. Identified high-value customers, frequent purchasers, and customers with significant monetary contributions.

3. K-means Clustering:
- Applied K-means clustering algorithm to group customers based on their RFM scores. Determined the optimal number of clusters using the elbow method.
- Assigned cluster labels to each customer, enabling the identification of distinct customer segments with similar transactional patterns.

4. Customer Segment Analysis:
- Analyzed the characteristics of each customer segment identified through K-means clustering.
- Visualized the distribution of customers among different segments to gain insights into their transactional behavior and value.
