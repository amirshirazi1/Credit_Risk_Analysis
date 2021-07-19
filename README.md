# **Credit Risk Analysis**

## **Purpose**
The purpose of this project was to create and evaluate different supervised Machine Learning models to see which one could accurately predict credit risk using the SKLearn library.

## **Results**
### **Naive Random Oversampling:**
- **Balanced Accuracy Score**

![naive_balance](images/naive_balanced.png)

- **Precision and Recall**

![naive_pr](images/naive_pr.png)

### **SMOTE Oversampling:**
- **Balanced Accuracy Score**

![smote_balanced](images/smote_balanced.png)

- **Precision and Recall**

![smote_pr](images/smote_pr.png)

### **ClusterCentroids Undersampling:**
- **Balanced Accuracy Score**

![cluster_balanced](images/cluster_balanced.png)

- **Precision and Recall**

![cluster_pr](images/cluster_pr.png)

### **SMOTEENN Combination Sampling:**
- **Balanced Accuracy Score**

![smoteenn_balanced](images/smoteenn_balanced.png)

- **Precision and Recall**

![smoteenn_pr](images/smoteenn_pr.png)

### **Balanced Random Forest Classifier:**
- **Balanced Accuracy Score**

![forest_balanced](images/forest_balanced.png)

- **Precision and Recall**

![forest_pr](images/forest_pr.png)

### **Easy Ensemble AdaBoost Classifier:**
- **Balanced Accuracy Score**

![easy_balanced](images/easy_balanced.png)

- **Precision and Recall**

![easy_pr](images/easy_pr.png)

## Summary
- The machine learning model with the best balanced, precision and recall scores was the Easy Ensemble AdaBoost Classifier. It held a .92 Balanced Accuracy Score, and a high-risk precision and recall score of .06 and .91 respectively while holding a low-risk precision and recall score of 1.00 and .94 respectively. I would recommend using the Easy Ensemble AdaBoost Classifier model to predict credit risk because it has the highest accuracy meaning it has the greatest chance of success in predicting things correctly.
- The machine learning model with the worst scores was the ClusterCentroids Undersampling model. It had by far the lowest balanced accuracy score at .54. It also held low high- and low-risk precision and recall scores. High-risk scores were: .01 and .69. Low-risk scores were: 1.00 and .40. Therefore, I would not recommend using the ClusterCentroids Undersampling model.