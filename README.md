# diabetes_Detection
# Diabetes Prediction Using Machine learning
1. Introduction: Diabetes is a prevalent chronic disease affecting millions worldwide. Early 
detection and management are crucial for improving patient outcomes. Machine learning 
techniques offer a promising avenue for diabetes prediction using patient data. In this project, we 
explore the application of logistic regression, a popular classification algorithm, to predict diabetes 
based on various health metrics.
2. Data Description: The dataset used in this project contains several health metrics of individuals, 
including pregnancies, glucose levels, blood pressure, skin thickness, insulin levels, BMI (body mass 
index), diabetes pedigree function, and age. The target variable is binary, indicating whether an 
individual has diabetes or not.

3. Methodology:
   
        • Data Preprocessing: The dataset is preprocessed by normalizing the features using Min-Max scaling
          to ensure that all features are on  a similar scale.

        • Model Training: A logistic regression model is trained on the preprocessed data. Logistic 
          regression is chosen due to its simplicity and effectiveness in binary classification tasks.

        • Model Evaluation: The trained model is evaluated using a test set. Performance metrics 
          such as accuracy and confusion matrix are calculated to assess the model's predictive capability.

4. Results:
   
        • Confusion Matrix:
          The confusion matrix provides insight into the model's performance, 
          showing the number of true positives, true negatives, false positives, and false negatives.
   
        • Accuracy:
          The accuracy score indicates the proportion of correctly classified instances out  of all instances
          in the test set
