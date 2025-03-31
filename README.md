# Stacking Ensemble for Sales & Fraud Analysis: Forecasting, Detection, and Clustering
![Image](https://github.com/user-attachments/assets/823397ef-ba90-4c1c-9142-a2298f3095ac)

![Image](https://github.com/user-attachments/assets/78c7c80a-1577-4c5c-9674-f8c6d1f17bc2)


## Project Description
This project implements **Stacking Ensemble Learning** for **sales forecasting and fraud detection** using a multi-model approach. The project consists of three main aspects:
1. **Forecasting**: Predicting fertilizer sales using regression techniques.
2. **Classification**: Detecting credit card fraud using classification techniques.
3. **Clustering**: Segmenting customers based on transactions.

## Dataset
The dataset includes **1,000 sales records** and credit card transaction data for fraud detection. The models were developed using various machine learning algorithms and compared to determine the best performance.

## Methodology
### 1. **Sales Prediction** (Regression)
The stacking regression model consists of the following algorithms:
1. Ridge Regression  
2. Lasso Regression  
3. Polynomial Regression  
4. Decision Tree Regressor  
5. Random Forest Regressor  
6. Gradient Boosting Regressor  
7. XGBoost Regressor  

**Results:**
The stacking model with **3 best features** achieved an **R² = 0.8243**, outperforming individual models.

### 2. **Fraud Detection** (Classification)
The stacking classification model uses the following algorithms:
1. Random Forest  
2. Gradient Boosting Classifier  
3. XGBClassifier  
4. KNeighborsClassifier  
5. DecisionTreeClassifier  

**Results:**
The stacking model achieved **97.92% accuracy**, surpassing individual models.

### 3. **Customer Segmentation** (Clustering)
Clustering was used to divide customers into **3 clusters**:
- **Cluster 1** has the highest number of transactions.
- **The highest average transaction amount for customers** is in clusters **1, 0, and 2**.
- **The highest average transaction amount for merchants** is in clusters **2, 0, and 1**.

#### Cluster Characteristics:
- **Yellow Cluster**: Largest customer group with diverse transactions, distributed across various locations.
- **Purple Cluster**: Local customers with small but frequent transactions, mostly within a specific area.
- **Green Cluster**: High purchasing power customers, making larger but less frequent transactions.

Most customers belong to **the Yellow Cluster**, indicating a broad business reach across regional and national locations.

## Technologies Used
- **Python**: Scikit-learn, XGBoost, Pandas, Numpy
- **Machine Learning**: Stacking Ensemble for regression and classification
- **Clustering**: K-Means for customer segmentation
- **Visualization**: Matplotlib, Seaborn

## Result

### Reregession
![Image](https://github.com/user-attachments/assets/f225872a-58fe-4d10-a69d-11c7da557964)

![Image](https://github.com/user-attachments/assets/ed90c08e-e33f-449c-918a-8fec526c76b1)

### Classification
![Image](https://github.com/user-attachments/assets/eb1027f1-fc72-41f7-b6c5-b1fc9f6610d4)

![Image](https://github.com/user-attachments/assets/5b3da618-98bf-4961-9423-ce76e231eef7)

![Image](https://github.com/user-attachments/assets/c8cbd13d-dc67-4d91-933c-0643d7d93a9d)

![Image](https://github.com/user-attachments/assets/a1c0f810-23fd-43e6-8f5d-67eef1742979)

### Clustering
![Image](https://github.com/user-attachments/assets/c16920d8-4b87-40bd-b9e6-a9b32c1c62a2)

![Image](https://github.com/user-attachments/assets/b8b3a61b-f5ac-4225-9bc9-3f6c91155d98)

![Image](https://github.com/user-attachments/assets/22b183e5-c2a2-4aad-986a-079c965eb666)

## Conclusion
The **Stacking Ensemble Learning** technique provides better results compared to individual models in **sales forecasting, fraud detection, and customer segmentation**. This implementation can help businesses make more accurate decisions.
