# Customer Segmentation Project

## Project Overview

This project focuses on segmenting customers based on their purchasing behavior and demographic characteristics.

The main goal is to identify different groups of customers so that businesses can understand their customers better and create targeted marketing strategies.

## Objective

- Segment customers based on annual income and spending score.
- Identify different customer groups using clustering.
- Analyze customer demographics and purchasing behavior.
- Visualize customer segments and key characteristics.
- Generate useful business insights from the identified segments.

## Dataset

The project uses the Mall Customers Dataset.

The dataset contains 200 customer records with the following attributes:

- CustomerID
- Genre
- Age
- Annual Income (k$)
- Spending Score (1-100)

## Technologies Used

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

## Methodology

### 1. Data Loading
The dataset was loaded using Pandas.

### 2. Data Inspection
The dataset was checked for:
- Number of rows and columns
- Data types
- Missing values

No missing values were found in the dataset.

### 3. Feature Selection

The following features were selected for customer segmentation:

- Annual Income (k$)
- Spending Score (1-100)

### 4. K-Means Clustering

The K-Means clustering algorithm was used to group customers with similar purchasing behavior.

The Elbow Method was used to determine the appropriate number of clusters.

The analysis resulted in 5 customer segments.

## Customer Segments

### 1. Average Customers

Customers with moderate income and moderate spending behavior.

### 2. High-Value Customers

Customers with high income and high spending scores. These customers are highly valuable to the business.

### 3. Low-Income High Spenders

Customers with lower income but high spending scores. They show strong purchasing engagement.

### 4. High-Income Low Spenders

Customers with high income but low spending scores. They represent an opportunity for targeted marketing campaigns.

### 5. Low-Income Low Spenders

Customers with lower income and lower spending scores.

## Key Insights

- High-Value Customers should be retained through loyalty programs and personalized offers.
- Low-Income High Spenders show strong customer engagement despite having lower income.
- High-Income Low Spenders can be targeted with personalized promotions.
- Average Customers have moderate income and spending behavior.
- Low-Income Low Spenders have relatively low purchasing activity.

## Visualizations

The project includes:

- Elbow Method Plot
- Customer Segmentation Scatter Plot
- Customers in Each Segment
- Genre Distribution by Customer Segment
- Average Spending Score by Segment
- Average Income by Segment

## Conclusion

Customer segmentation helps businesses understand different types of customers based on their income and spending behavior.

Using K-Means clustering, five distinct customer segments were identified. These insights can help businesses develop targeted marketing strategies, improve customer engagement, and focus their resources on valuable customer groups.

## Project Output

The final segmented dataset is saved as:

Customer_Segmentation_Final.csv