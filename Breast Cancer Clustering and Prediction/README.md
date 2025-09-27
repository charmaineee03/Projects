# Breast Cancer: Clustering and Prediction 

---
## Project Overview 
This project aims to analyse and explore both supervised and unsupervised machine learning methods to classify tumours: Malignant (M) or Benign (B) using the **Breast Cancer Winconsin dataset**. 

This project strives to: 
- Address multicollinearity using Principal Component Analysis (PCA) using R. 
- Apply K-Means clustering on the PCA-reduced data and evaluate cluster quality in R.
- Build and compare Support Vector Machine models using both original features and PCA-reduced features by utilising Python. 

---

## Methodology

1. Data preprocessing (R) 
- Renaming of variables for efficiency.
- Checked for missing values and duplicates. 
- Applied encoding to categorical variable (e.g. diagnosis) and scaled numerical variables. 
- Generated summary statistics of the variables to observed the distribution of the variables.
- Conducted a correlation heatmapto justify the use of Principal Component Analysis (PCA).

2.  PCA (R) 
- Retained 5 Principal Components, which retained a cummulative variance of 84.7%.
- Generated a biplot using the first 2 principal componenets for visualisation.

3. Clustering (R)
- Applied K-Means to form 2 clusters on the PCA-reduced data.
- Evaluated the clustering quality using Adjusted Rand Index (ARI) and Normalised Mutual Information (NMI)
- Created a new dataset consisting of the first 5 PCs and diagnosis.

4. Prediction (Python) 
- Used Support Vector Machine (SVM) models on two datasets: the original cleaned dataset and PCA-reduced dataset.
- Data was split to 80% training and 20% testing sets. 
- Evaluation metrics used: Accuracy, Precision, Recall, F1-score, ROC-AUC curve and Confusion Matrix.
- 
--- 

## Results 
1. Correlation heatmap showed strong correlations among variables, which supported the use of PCA.
2. Applying K-Means on the PCA-reduced data resulted an ARI of 0.671, and NMI of 0.544. This indicates a moderate alignment with the true diagnosis labels. 
3. The SVM model trained on the PCA-reduced data showed a slightly outperformed the model trained on the original features. Hence, PCA has improved the efficiency and reduced noise while preserving predictive power of the original data. 

---

## Future Work 
1. Explore other clustering methods such as Gaussian Mixture Models (GMM) or Hiarachical Clustering which may yield stronger alignment with the diagnosis labels.
2. Extend  supervised learning models by testing additional models (e.g. Random Forests, Logistic Regression etc.) to compare predictive performance with the PCA-reduced dataset. 
3. Conduct feature engineering to enhance predictive performance and the model's interpretability.

---

## Policy and Practical Implications 
-  Robust and accurate classification models is essential for early diagnosis, which helps healthcare providers to detect malignant tumours at earlier stages.
-  Hospitals could use classifcation models to prioritise high-risk patients, ensuring follow-ups and required treatment. This allows healthcare systems to allocate resources more efficiently when treating patients.
  
