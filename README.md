Model to classify the claim as fast track or complex based on the claim cycle time (number of days the claims is open). Claims which were closed 10 days or lesser as fast track and other claims I classified as complex.  
  
The model is able to predict with 85% accuracy with below listed features (sorted in order of importance).  
  
1.       Loss Type code  
2.       Jurisdiction state  
3.       Claim Tier code  
4.       Glass only indicator  
5.       Fault rating code  
6.       Coverage sub type  
7.       Product type  
8.       Subrogation Indicator  
  
In the second model the claims are classified as fast track based on the owning adjuster group. The confusion matrix is better in the model where the claims are classified based on the owning adjuster group. The model based on cycle time and the model based on owning adjuster have the same prediction accuracy of 85%
  
Used the below algorithms:  
1.       Logistic regression  
2.       SVM  
3.       Gradient Boosting  
  
Reference:  
Claims_fastTrack-CYCLETIME.pdf à Model based on cycle time  
Claims_fastTrack-Owning_adjuster.pdf à Model based on the owning adjuster  
