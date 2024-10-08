# Distributed Machine Learning for Banking Data Insights

## Project Overview
This project demonstrates how distributed machine learning can be applied to large-scale banking data to generate actionable insights. Using the "bank.csv" dataset, the project simulates a real-world banking environment, enabling efficient data management, predictive analytics, and real-time transaction monitoring. By leveraging distributed technologies like Hadoop, Hive, Apache Spark, and Spark Streaming, the project highlights how banks can understand customer behavior, forecast trends, and make informed decisions.

## Key Objectives
- **Data Management**: Use Hadoop and Hive to store and query large volumes of banking data.
- **Exploratory Data Analysis (EDA)**: Perform EDA using Apache Spark to identify trends, patterns, and anomalies in the dataset.
- **Predictive Modeling**: Build machine learning models with Spark ML to predict customer behavior and loan default probabilities.
- **Real-Time Analysis**: Implement Spark Streaming to simulate and process real-time banking transactions for monitoring and insights.
- **Data Parallelism**: Explore and apply data parallelism techniques to improve processing efficiency of large datasets.

## Installation and Setup
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/banking-ml-insights.git
    cd banking-ml-insights
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Ensure you have Hadoop, Hive, and Apache Spark installed and configured on your system.

4. Place the `bank.csv` dataset inside the `data/` directory.

## Usage

### Data Management
Run the script to store and query banking data using Hadoop and Hive
