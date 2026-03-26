📊 Customer Segmentation using K-Means

This project applies unsupervised machine learning to segment customers based on their purchasing behavior. Using K-Means clustering, customers are grouped into distinct categories based on features like annual income and spending score.

📌 Overview

The goal of this project is to identify meaningful customer segments that can help businesses improve marketing strategies, target the right audience, and enhance customer experience.

The dataset used contains demographic and spending data of mall customers.

✨ Features
📂 Data preprocessing using Pandas
📊 Exploratory Data Analysis (EDA)
🔍 Feature selection (Income, Spending Score)
🤖 K-Means clustering implementation
📈 Visualization of customer segments
🎯 Optimal cluster selection using Elbow Method
🛠️ Tech Stack
🐍 Python
📊 NumPy, Pandas
📉 Matplotlib, Seaborn
🤖 Scikit-learn
📁 Dataset

The dataset contains the following features:

CustomerID
Gender
Age
Annual Income (k$)
Spending Score (1–100)
⚙️ Workflow
Data Loading and Cleaning
Exploratory Data Analysis
Feature Selection
Applying K-Means Clustering
Determining optimal clusters (Elbow Method)
Visualizing clusters
📊 Output
Customers are grouped into different segments such as:
High Income – High Spending
High Income – Low Spending
Low Income – High Spending
Low Income – Low Spending

These segments can be used for targeted marketing and business decision-making.

▶️ How to Run
Clone the repository
git clone https://github.com/your-username/Customer-segmentation.git
cd Customer-segmentation
Install dependencies
pip install numpy pandas matplotlib seaborn scikit-learn
Run the Jupyter Notebook
jupyter notebook
💡 Key Highlights
Implemented unsupervised learning for real-world business use case
Applied clustering to derive actionable insights
Visualized data effectively for better understanding
Demonstrates strong fundamentals of EDA and machine learning
🔮 Future Improvements
Use advanced clustering algorithms (DBSCAN, Hierarchical)
Add more features for better segmentation
Deploy as an interactive dashboard
👤 Author

Neeraj Ruwali
