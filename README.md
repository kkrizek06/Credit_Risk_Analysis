# Credit_Risk_Analysis

**Overview of the analysis:**
The purpose of this analysis is to use machine learning to build models that can help predict credit card risk. 

**Results:**

**1) Random Oversampling model:**

![image](https://user-images.githubusercontent.com/96017493/166150750-c1514745-2319-4856-898d-680c2cee9518.png)
•	Balance accuracy: 65%
•	Precision: 1%
•	Recall score: 71%

**2) Smote Oversampling model:**

![image](https://user-images.githubusercontent.com/96017493/166150810-b86acd74-5d47-41f2-9c8a-e454a04cd24b.png)
•	Balance accuracy: 66%
•	Precision: 1%
•	Recall score: 63%

**3) Cluster Centroids model:**

![image](https://user-images.githubusercontent.com/96017493/166150832-b5542309-7e38-4ccd-8a1f-5a7c2881adb1.png)
•	Balance accuracy: 54%
•	Precision: 1%
•	Recall score: 69%

**4) Smoteenn model:**

![image](https://user-images.githubusercontent.com/96017493/166150891-426be8f5-c30c-4670-b997-a54667da9bb4.png)
•	Balance accuracy: 65%
•	Precision: 1%
•	Recall score: 72%

**5) Balanced Random Forest Classifier model:**

![image](https://user-images.githubusercontent.com/96017493/166150951-c46b0678-2ffd-4998-9990-754f45900c91.png)
•	Balance accuracy: 79%
•	Precision: 3%
•	Recall score: 70%

**6) Easy Ensemble Classifier model:**

![image](https://user-images.githubusercontent.com/96017493/166150992-9dc92eb8-8aa9-464d-bb13-ae4f12f3a0fd.png)
•	Balance accuracy: 93%
•	Precision: 9%
•	Recall score: 92%

**Summary:**
Looking at the six models, the one that predicts high risk loans the best is the Easy Ensemble Classifier model. I would not feel comfortable using any of these models for predicting high risk credit loans. This conclusion is based on the model’s precision and f1 scores. I prioritize precision over recall in this scenario based on that it would be better to turn down a loan minimizing false positives, than it would be to minimize the false negatives. 
