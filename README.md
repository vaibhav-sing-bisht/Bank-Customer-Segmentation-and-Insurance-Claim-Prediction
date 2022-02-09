# Bank-Customer-Segmentation-and-Insurance-Claim-Prediction
## Course Data Mining  The project involved drawing inferences from 2 case studies, namely - 
Bank Marketing &amp; Insurance. The concepts of Clustering, CART, Random Forest, Artificial Neural Network are used to draw inferences from these case studies. Various performance metrics have been used to validate the performance of predictions on Test &amp; Train sets.  
### Skills and Tools -- Clustering, CART, Random Forest, Artificial Neural Networks

## Below is the cluster profiling with original data set and a freq column is added at last which tells us the total number of customers grouped under a specific cluster. 
![image](https://user-images.githubusercontent.com/87828805/153256691-442019ae-9b6e-41de-aa1b-0793b2dc2372.png)
So here we have group by the clusters and taken the average of all the variable values. And taking average will not be affected as we have done the outlier treatment.

From the table cluster 0 has all the average values of all the variables with freq of 72 that means in cluster 0 total 72 customers are grouped. Similarly in cluster 1 total 77 customers are grouped and in cluster 2 total 61 customers are grouped.  

# Insurance-Claim-Prediction

![image](https://user-images.githubusercontent.com/87828805/153257019-4e0ff118-274c-487b-b23c-032a0d357f2a.png)

Below is the table of comparison of all the three models with their train and test data.
![image](https://user-images.githubusercontent.com/87828805/153257137-1b2367b4-b25d-4d50-9555-07005cd802a3.png)

![image](https://user-images.githubusercontent.com/87828805/153257244-c99cd266-be6e-448e-a864-f333ccdcf46e.png)

![image](https://user-images.githubusercontent.com/87828805/153257329-67c77df1-5dad-4256-bc28-6b0734f72848.png)

From the above two graphs we can clearly see’s that RF model has more Area under the curve as compared to CART and Neural Network models. So we will prefer RF model as it is looking best and optimized.



