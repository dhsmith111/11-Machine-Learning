# 11-Machine-Learning

### Unit 11 Machine-Learning Homework - Dan Smith
#### Evaluating Credit Risk:
* Logistric Regression Classifiers with Imbalanced Learn Libary Resampling: [./credit_risk_resampling.ipynb](./credit_risk_resampling.ipynb)
* Ensemble Learning Classifiers: [./credit_risk_ensemble.ipynb](./credit_risk_ensemble.ipynb)  

  
#### Summary: Resampling and Logistric Regression Classifiers   

**Balanced Accuracy:**  
> The **SMOTE Oversampled** model had the **best balanced accuracy** score, at **~0.662**  
> 
> Logistic Regression Models' balanced accuracy scores:  
> * Naive Random Oversampled:                   0.6503524738582371
> * SMOTE Oversampled:                          0.6621602612787003
> * Cluster Centroids Undersampled:             0.5442459178097417
> * SMOTEENN Combo Sampled:                     0.6461047268197353

**Recall:**
> The **SMOTEENN over- and under-resampled** model had the **best recall** score of high_risk predictions, at **0.71**  
>
>  Logistic Regression Models' recall scores: 
> * Naive Random Oversampled (high_risk):       0.69
> * SMOTE Oversampled (high_risk):              0.63
> * Cluster Centroids Undersampled (high_risk): 0.67
> * SMOTEENN Combo Sampled (high_risk):         0.71

**Geometric Mean:**
> The **SMOTE Oversampled** model had the **best geometric mean** score of high_risk predictions, at **0.66**  
>
>  Logistic Regression Models' recall scores: 
> * Naive Random Oversampled (high_risk):       0.65
> * SMOTE Oversampled (high_risk):              0.66
> * Cluster Centroids Undersampled (high_risk): 0.53
> * SMOTEENN Combo Sampled (high_risk):         0.64


#### Summary: Ensemble Learning Classifiers

**Balanced Accuracy:**
> The **Easy Ensemble AdaBoost** model had the **best balanced accuracy** score, at **~0.932**
>  
> Ensemble Learners' balanced accuracy scores:  
> * Balanced Random Forest:  0.7855052723466922
> * Easy Ensemble AdaBoost:  0.9316600714093861

**Recall:**
> The **Easy Ensemble AdaBoost** model had the **best recall** score of high_risk predictions, at **0.93**  
> 
> Ensemble Learners' recall scores: 
> * Balanced Random Forest (high_risk):  0.67
> * Easy Ensemble AdaBoost (high_risk):  0.92


> The **Easy Ensemble AdaBoost** model had the **best geometric mean** score of high_risk predictions, at **0.92**  
>
> Ensemble Learners' recall scores: 
> * Balanced Random Forest (high_risk):  0.78
> * Easy Ensemble AdaBoost (high_risk):  0.93

**Top Features:**  
> The top three features are:
> * loan_amnt:                           0.09175752102205247
> * int_rate:                            0.06410003199501778
> * installment:                         0.05764917485461809