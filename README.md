Predictive Analysis of NASDAQ Stock Exchange Closing Prices Using Big Data Technologies
📈 Project Overview
This project leverages big data and advanced analytics to analyze and predict Nasdaq stock closing price movements during the final ten minutes of trading. Our insights aim to optimize market efficiency and support advanced investment strategies.

Course: CSGY-6513 Big Data, Section B
Semester: Spring 2025
Team Members:

Ankit Chahar (ax2135)

Shreyansh Bhalani (sbb9447)

Harsh Golani (hg2948)

🧩 Objective
Integrate continuous order book and auction book data.

Process and analyze large-scale stock market data.

Extract patterns and provide actionable insights for trading decisions.

🗂️ Dataset
Source: Optiver - Trading at the Close (Kaggle)

Size: 646.7 MB

Records: Over 5 million

Structure:

200 stocks

481 trading days

55 data points per day

Data Type: Time-series data

🛠️ Technologies and Tools Used
Python: Programming and data manipulation

Apache Hadoop: Distributed data storage

Apache Spark: Real-time distributed data processing

Apache Hive: Persistent storage (data warehousing)

JupyterHub: Multi-user development environment

🧹 Data Exploration & Cleaning
Null values (except 'near' and 'far' price) handled using backward fill.

'Near' and 'Far' prices before the 300-second mark were set to zero if missing.

Data normalization applied post-cleaning for consistency.

📊 Key Analyses
Single Stock Analysis:

Visualized attribute movement across a trading day.

Examined relationships between attribute pairs.

Multi-Stock Analysis:

Identified temporal patterns and anomalies across multiple stocks.

🔥 Results and Conclusion
Revealed patterns in Nasdaq closing auction prices.

Improved understanding of stock behaviors during end-of-day trading.

Demonstrated scalable big data processing using PySpark.

🎯 Lessons Learned
Importance of Data Preprocessing and Feature Engineering.

Mastery of Big Data tools like Hadoop, Spark, and Hive.

Experience in Real-Time Data Streaming and Team Collaboration.

🚀 Future Scope
Live Deployment: Integrate model with trading APIs (e.g., Alpaca, Interactive Brokers).

Interactive Dashboard: Real-time visualization using Streamlit or Dash.

Feature Expansion: Incorporate macroeconomic indicators and sentiment analysis.

Model Enhancement: Explore Reinforcement Learning for adaptive trading strategies.

