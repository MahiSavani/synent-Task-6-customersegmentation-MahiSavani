#  synent-Task-6-customersegmentation-MahiSavani

##  Problem Statement  
The objective of this project is to perform customer segmentation using machine learning techniques. The goal is to group customers based on their income and spending behavior to help businesses make better marketing decisions.

##  Dataset Details  
- Dataset Name: Mall Customers Dataset  
- File Name: Mall_Customers.csv  

### Features:
- CustomerID  
- Gender  
- Age  
- Annual Income (k$)  
- Spending Score (1–100)  

### Description:  
This dataset contains customer information including demographics and spending patterns, which helps in identifying distinct customer segments.

## Approach  

### Data Preprocessing  
- Loaded dataset using Pandas  
- Checked for missing values  
- Selected relevant features  

### Exploratory Data Analysis (EDA)  
- Used scatter plots to analyze relationships  
- Observed patterns between income and spending  

### Feature Selection  
- Selected:
  - Annual Income  
  - Spending Score  

### Model Implementation  
- Applied K-Means Clustering  
- Used Elbow Method to find optimal clusters  

### Visualization  
- Visualized clusters using matplotlib  
- Identified different customer groups  

##  Results  

- Successfully segmented customers into different groups  
- Identified key segments:
  - High Income – High Spending  
  - High Income – Low Spending  
  - Low Income – High Spending  
  - Low Income – Low Spending  

### Business Insights  
- Helps in targeted marketing  
- Improves customer retention strategies  
- Enables personalized offers  
