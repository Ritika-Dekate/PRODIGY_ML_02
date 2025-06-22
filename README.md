# PRODIGY_ML_02: K-Means Clustering for Customer Segmentation 
## Overview  
The goal of this task is to group customers into distinct clusters based on their **age**, **annual income**, and **spending score**. The project demonstrates the use of unsupervised learning techniques for customer segmentation.  

## Dataset  
The dataset used is from Kaggle https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python/data , which includes details such as customer ID, gender, age, annual income, and spending score.  

## Key Steps  
### 1. Data Preprocessing  
- Standardized features using `StandardScaler` for effective clustering.  
- Ensured data cleanliness and consistency.  

### 2. Model Implementation  
- Determined the optimal number of clusters using the Elbow Method.  
- Applied K-Means clustering with 5 clusters as the optimal choice.  

### 3. Visualization  
- Scatter plots were used to represent clusters visually based on annual income and spending score.  

### 4. Evaluation  
- Calculated the Silhouette Score (0.41) to evaluate the clustering performance.  

## Results  
- Customers were segmented into five distinct clusters, each representing unique purchasing behavior.  
- Visualizations provide insights into the characteristics of each customer group.  

## Tools and Libraries  
- **Python**  
- **Pandas**: For data handling and analysis.  
- **NumPy**: For numerical computations.  
- **Matplotlib & Seaborn**: For data visualization.  
- **Scikit-learn**: For scaling and clustering.

## How to Use

### Run on Google Colab (Recommended)
1. Open this project in Google Colab.
2. Upload the `Mall_Customers.csv` file to the Colab environment.
3. Run all the cells in the notebook.
4. After execution:
   - Visual cluster plots will be shown.

## What I Learned  
- Practical use of clustering for customer segmentation.  
- Working with the Elbow Method and Silhouette Score.  
- Improving data preprocessing and visualization techniques.  
