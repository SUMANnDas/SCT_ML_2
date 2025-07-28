🛍️ Customer Segmentation using K-Means Clustering
This project is part of my SkillCraft Internship and represents Task 2 of my Machine Learning journey. The goal is to group retail store customers into segments based on their purchasing behavior using unsupervised learning (K-Means Clustering).

📌 Project Objective
To segment customers based on:

Age

Annual Income (in thousands)

Spending Score (1–100)

This segmentation helps businesses identify different customer types to tailor marketing strategies, improve customer retention, and drive sales growth.

📂 Dataset Features
The dataset includes the following columns:

Column	Description
CustomerID	Unique ID for each customer
Gender	Male/Female
Age	Age of the customer
Annual Income (k$)	Customer's annual income in $1000s
Spending Score (1–100)	Score assigned by store (1–100)

🧠 Machine Learning Technique
Algorithm: K-Means Clustering (Unsupervised Learning)

Preprocessing:

Gender encoding

Feature scaling with StandardScaler

Optimal k Selection: Elbow Method

Libraries Used: pandas, matplotlib, seaborn, scikit-learn

📈 Visualizations
Elbow plot for optimal k

2D scatter plot of customer clusters using Annual Income vs Spending Score


jupyter notebook customer_segmentation


📊 Output
Each customer is assigned to a cluster

Visual representation of clusters

Insights into customer group behaviors

📚 Learnings
Through this task, I learned how to:

Perform clustering on real-world data

Preprocess and scale features

Visualize results meaningfully

Select the right number of clusters with the Elbow Method
