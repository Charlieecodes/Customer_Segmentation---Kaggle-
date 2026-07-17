Summary

What I did:

Loaded real mall customer data (200 customers, 5 columns)
Cleaned data — dropped ID, encoded gender
Explored distributions and relationships using charts
Used Elbow Method and Silhouette Score to find optimal K
Applied K-Means clustering with K=5
Profiled each cluster by average income, spending score, and age
Named each segment and gave business recommendations

Key finding: The silhouette score of ~0.55 confirms 5 distinct customer segments exist in this data. The most valuable segment — high income, high spending — should receive the majority of marketing budget.

Model used: K-Means Clustering (Scikit-learn) Evaluation metric: Silhouette Score Dataset: Mall Customers — Kaggle
