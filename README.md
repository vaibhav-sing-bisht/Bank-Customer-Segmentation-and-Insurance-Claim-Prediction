# Bank-Customer-Segmentation-and-Insurance-Claim-Prediction
![image](https://user-images.githubusercontent.com/87828805/153255356-4f5b42d5-1a71-464e-a1eb-181291d5c81e.png)
## Course Data Mining  The project involved drawing inferences from 2 case studies, namely - 
Bank Marketing &amp; Insurance. The concepts of Clustering, CART, Random Forest, Artificial Neural Network are used to draw inferences from these case studies. Various performance metrics have been used to validate the performance of predictions on Test &amp; Train sets.  
### Skills and Tools -- Clustering, CART, Random Forest, Artificial Neural Networks
![image](https://user-images.githubusercontent.com/87828805/153255000-81cc18eb-244a-4f82-9a2f-0eedf5abdec2.png)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------
From the above table we can easily find out the values of Accuracy, AUC, Recall, Precision, and F-1 Score of two different model which Logistic Regression and LDA.
Inference From the above table:-
1) Accuracy is almost same for all except LR test data which is 0.65
2) 
3) AUC for LR train and LDA train has same area under the curve about 0.73 .Whereas LDA test has least AUC of abut 0.70
4) 
5) Recall for LDA test is the highest of about 0.73 and least is for LR test of about 0.51
6) 
7) Precision in LDA test is lacking of about 0.61 while rest are having a value of 065
8) 
9) F1 Score for the LDA test is the highest of about 0.66 whereas LR Test performed poorly of about 0.57
10) 
Since we are building a model to predict if a person has opted holiday package or not, for practical purposes, we will be more interested in correctly classifying 1 (having opted claim) than 0(not opted).


LDA test model is predicting 73 percent that how many of the actual True data points are identified as True data points by the model which is highest in all other model.
The F1 score which is  weighted average of Precision and Recall is 66% again shown  by LDA test model which is the highest score which takes both false positives and false negatives into account.

### So LDA is the best model for the company in predicting whether an employee will opt for the package or not.
