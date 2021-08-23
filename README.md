# Credit Risk Analysis

## Overview of the analysis

The purpose of this analysis it to utilize supervised machine learning to evaluate credit card risk for the LendingClub. In particular we utilized multiple models & oversampling techniques in order to mitigate any potential unbalanced classification problems in the data set. 

## Results

The following are the balanced accuracy, precision, and recall scores for all 6 models utilized. 

### Random Over Sampling 

-	![SS1](https://user-images.githubusercontent.com/67031885/130385926-3bcc9a31-a4cd-4ce3-a25f-87ba7ddc844f.PNG)

### SMOTE Oversampling

-	![SS2](https://user-images.githubusercontent.com/67031885/130385934-0b31525f-b906-4591-bb07-1b1ce687a5a8.PNG)

### ClusterCentroids Under sampling 

-	![SS3](https://user-images.githubusercontent.com/67031885/130385956-fce18112-1237-4981-be56-5730a0701294.PNG)

### SMOTEENN over and under sampling 

-	![SS4](https://user-images.githubusercontent.com/67031885/130385966-21be5ec2-e585-46de-83bb-20256ff75209.PNG)

### Balanced Random Forest Classifier Model 

-	![SS5](https://user-images.githubusercontent.com/67031885/130385981-b767728b-056c-4d2a-8062-33b92817d4e2.PNG)

### Easy Ensemble AdaBoost Model 

-	![SS6](https://user-images.githubusercontent.com/67031885/130385989-5f00b098-abaa-4a50-a3fd-b53a0fe59772.PNG)



## Summary
In summary, it appears that most of the 6 models utilized in this analysis struggle with accuracy. It is possible that the models utilized are not suitable for evaluating risk with this data set.  If I were to recommend one model, the Easy Ensemble AdaBoost Model or Balanced Random Forest Classifier Model appeared to perform more accurately than the others. 

