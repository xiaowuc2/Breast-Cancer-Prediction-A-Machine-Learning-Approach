<p><pre align="center">
<strong>Breast Cancer Prediction: A Machine Learning Approach / <a href="https://www.youtube.com/channel/UCX7oe66V8zyFpAJyMfPL9VA">​Research Paper​</a></pre></p></strong>

### 1. Abstract
Breast cancer is the most common cancer in women world-wide. In 2020, there were 2.3 million women diagnosed with breast can-cer and 685 000 deaths globally. Incidence rates vary widely across theworld, from 27 per 100,000 in Middle Africa and Eastern Asia to 92 per100,000 in Northern America. Earlier detection of this disease can leadto proper treatment. So accurate and fast detection is most important.This proposed paper presents a comparison of six machine learning al-gorithms: XGBoost Classifier, Random Forest, KNN Classifier, Logistic Regression, SVM Classification, Decision Tree on the Wisconsin Diagnos-tic Breast Cancer dataset which is extracted from a digitised image of anMRI. After cleaning the dataset we perform feature scaling. Finally, weapplied those classification algorithm to classifies into two classes‘Ma-lignant  Tumor’, and‘Malignant  Benign’. The best overall accuracy forbreast cancer diagnosis is achieved equal to 93.24% and 94.96% respec-tively using support vector machines classifier and Logistic Regressionmodels against two widely used breast cancer benchmark datasets.

### 2. Results

#### 2.1 Variable Distribution
Some variables are taken of all data from dataset to see the distribution.
<p align="center">
  <a href="https://www.youtube.com/channel/UCX7oe66V8zyFpAJyMfPL9VA">
    <img src="https://raw.githubusercontent.com/xiaowuc2/Breast-Cancer-Prediction-A-Machine-Learning-Approach/main/Images/plot.png" alt="Distribution">
  </a>

#### 2.2 Correlation Heatmap
Plotting correlation heatmap to see corellation among the features in the dataset.
 
<p align="center">
  <a href="https://www.youtube.com/channel/UCX7oe66V8zyFpAJyMfPL9VA">
    <img src="https://raw.githubusercontent.com/xiaowuc2/Breast-Cancer-Prediction-A-Machine-Learning-Approach/main/Images/heatmap.png" alt="Heatmap">
  </a>

#### 2.3 Comparison : Classification Algorithms

| Algorithm | SVM | KNN | Logistic Regression | Decision Tree | Random Forest | XGBoost
|-------------|-------|---------|---------|---------|---|---| 
| **Accuracy**  | 92.98%    | 89.74%      | 93.85%      | 91.22%  | 90.35% | 92.98% | 

From the results we observed that Logistic Regression's results are more promising and it's a more generatized model for new unseen data for our model.

#### 2.4 Classification Report 

```
              precision    recall  f1-score   support

         0.0       0.96      0.90      0.92        48
         1.0       0.93      0.97      0.95        66

    accuracy                           0.94       114
   macro avg       0.94      0.93      0.94       114
weighted avg       0.94      0.94      0.94       114

```

### Citation 
```

```
