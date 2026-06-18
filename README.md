#Buyer Segmentation and Investment Profiling for Real Estate Market Intelligence

##Background and Context

Real estate companies operate in markets where buyer behavior is highly diverse:

• Individual home buyers

• Institutional investors

• International buyers

• High-net-worth investors

• First-time buyers
Without segmentation, companies treat all buyers the same. This leads to:

• Inefficient marketing
• Poor customer targeting
• Missed investment opportunities
Using AI-based clustering, we can discover hidden patterns in buyer behavior.

Problem Statement

Parcl currently lacks a data-driven understanding of:

• Different types of property buyers
• Investment motivations across demographics
• Geographic differences in investment behavior
• Customer financing patterns
This leads to:

• Inefficient marketing spend
• Generic property recommendations
• Poor investor targeting
Dataset Fields Description:

<img width="1404" height="1172" alt="image" src="https://github.com/user-attachments/assets/ce704ade-3f82-47c5-a055-4bf07e1b41ea" />

Data Science Methodology (Step-by-Step)

Step 1 – Data Cleaning

Tasks performed:

• Handle missing client attributes
• Normalize categorical labels & Remove duplicate client entries
Step 2 – Feature Encoding

Convert categorical fields using:

• One-Hot Encoding
• Label Encoding
• Variables encoded include:
•
client_type
•
region
•
acquisition_purpose
•
referral_channel
•
country
Step 3 – Feature Scaling

Use StandardScaler or MinMaxScaler to normalize numeric variables such as:

• Age
• Satisfaction score
Step 4 – Clustering Model Selection

Two clustering approaches are used.

• K-Means Clustering Advantages:
● Efficient
● Easy to interpret
• Hierarchical Clustering Advantages:
● Reveals nested cluster relationships
● Helps validate K-means results
Step 5 – Optimal Cluster Selection

Use evaluation methods:

• Elbow Method
Identifies the optimal number of clusters.
• Silhouette Score
Measures clustering quality.
Step 6 – Cluster Interpretation

Each cluster is analyzed based on:

• investment purpose
• geographic distribution
• loan behavior
• customer demographics
Recommended Buyer Segments

<img width="1418" height="540" alt="image" src="https://github.com/user-attachments/assets/493f958a-0a51-42fc-9c49-7aa628748d97" />

• Buyer Segmentation Overview
- ● Displays cluster distribution.
• Investor Behavior Dashboard
- ● Shows investment patterns by cluster.
• Geographic Buyer Analysis
- ● Maps buyer segments by region.
• Segment Insights Panel
- ● Provides descriptive statistics per cluster.
User Controls

Users can filter by:

• country
• region
• acquisition purpose
• client type
Deliverables and Submission

• Research paper (EDA, insights, recommendations)
• Streamlit dashboard (live analytics)
Conclusion

This project introduces AI-driven buyer intelligence into the Parcl real estate platform. By identifying hidden customer segments through clustering algorithms, the system reveals investment behaviors that traditional analytics cannot detect. Enabling Parcl to build smarter marketing strategies and drive data-driven real estate investment decisions
