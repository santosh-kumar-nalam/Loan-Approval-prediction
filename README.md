                                                    Loan Approval Prediction

  ![Loan-approval](https://github.com/santosh-kumar-nalam/Loan-Approval-prediction/assets/167790146/7eb10fc7-ebf0-4197-8e15-6e517fab43bd)


Introduction:

   The Loan Approval Prediction project aims to develop a robust machine learning model capable of accurately predicting whether a loan application should be approved or rejected. This is a critical task for financial institutions to streamline their lending process and mitigate risks associated with defaulting loans. After experimenting with various machine learning algorithms, finally, we used the AdaBoost algorithm, a powerful ensemble learning technique, to enhance predictive performance and achieve an exceptional accuracy rate of 98%.

Dataset:

   The dataset used for this project consists of historical loan application data, including various features such as applicant information, financial attributes, credit history, and loan approval status. The dataset is preprocessed to handle missing values, encode categorical variables, and normalize numerical features to ensure optimal model performance.


Methodology

1. Data Loading: 

  Importing data from the external file.

2. Exploratory data analysis (EDA):    In this phase, we conducted various analyses as follows:
  
      i) Uni-Variant Analysis
   
      ii) Multi-Variant Analysis
  
3. Feature Engineering:
   
      Feature Engineering is the step which involves the handling of missing values, handling outliers, feature transformation, and finally feature scaling.
   
4. Model Selection:

   In this step, we conducted experiments on the dataset with various machine learning algorithms to find out the best algorithm with the best hyperparameter. This step is also known as hyper parameter-tuning. Hyper Tuning is done by a powerful optimizer technique called GridSearchCV.
   
5. Model Building:

   After finding the best algorithm, we built the machine learning model on the training data, which is split into train and test datasets, and predicted the data using the test dataset.
   
6. Model Evaluation: 

   Evaluate the performance of the trained model using appropriate evaluation metrics such as accuracy, precision, recall, and F1-score. Utilize techniques such as cross-validation to assess        model generalization and avoid overfitting.

7. Results:

   After rigorous experimentation and model refinement, the Loan Approval Prediction model using AdaBoost achieves an impressive accuracy rate of 98%. This indicates that the model can effectively       
   differentiate between approved and rejected loan applications with high precision and recall. The robustness of the model is validated through cross-validation and sensitivity analysis, ensuring its   
   reliability in real-world scenarios.
