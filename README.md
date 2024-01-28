<h1>SAMPLING ASSIGNMENT</h1>
<h3>About the dataset</h3>
<p>The dataset contains 772 entries with two classes class 0 and class 1. The dataset is not balanced as it contains 763 entries for class 0 and only 9 for class 1. So, SMOTE is used to balance the dataset. SMOTE stands for Synthetic Minority Oversampling Technique. It works by randomly picking a point from the minority class and computing the k-nearest neighbors for this point.</p>
<h3>Sample size calculation</h3>
The sample size is calculated as:
<i>n=Zsup(2).p.(1-p)/Esup(2)</i>
<p>where n=sample size, p=standard deviation , Z= z-score , E= margin of error</p>
<h3>Sampling techniques used</h3>
<ol>
  <li>Simple Random Sampling</li>
  <li>Systematic Random Sampling</li>
  <li>Cluster Sampling</li>
  <li>Bootstrap Sampling</li>
</ol>  
<h3>Models used for evaluation</h3>
<ol>
  <li>Logistic Regression</li>
  <li>Support Vector Classifier</li>
  <li>XGBoost Classifier</li>
  <li>Random Forest</li>
   <li>Gaussian Naive Bayes</li>
</ol>  
<h3>Accuracy Scores</h3>
|          | Model 1 | Model 2 | Model 3 | Model 4 | Model 5 |
| ------   | ------ | ------- | ------- | ------- | ------- |
| Sample 1 |  0.88  | 0.87  | 0.83  |   0.93   |    0.97     |
| Sample 2 | 0.90   | 0.87  | 0.84  |   0.99   |    1 (overfit)    |
| Sample 3 | 0.92   | 0.87  | 0.79  |   0.97   |     0.98    |
| Sample 4 | 0.96   | 0.94  | 0.87  |   0.98   |      1 (overfit)|


