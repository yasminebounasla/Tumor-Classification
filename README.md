**Breast Tumor Classification with Machine Learning**

**Project Overview:**
In this project, I built a machine learning model to predict if a breast tumor is benign (not harmful) or malignant (harmful). This can help doctors detect cancer early.

**Steps:**

1. Preparing the Data:
   I got the data in a .csv file.
   I cleaned the data by checking for any missing values and removed the id column because it doesn’t help in predicting the tumor.
   
3. Splitting the Data:
    I split the data into two parts:
    Training Set: Used to teach the model.
    Test Set: Used to check how well the model performs.
   
5. Using SMOTE to Balance the Data
   The data was imbalanced (more benign tumors than malignant ones), so I used SMOTE to balance it. SMOTE helps create more synthetic examples of the minority class (malignant tumors), so the model learns better.
   
7. Scaling the Data:
   I scaled the features (data values) to make sure everything is in the same range. This helps the model perform better.

9. Model Training with Random Forest:
   I used the Random Forest algorithm because it’s a high-performance model that works well with different types of data and helps avoid overfitting (where the model learns too much from the training data and doesn’t perform well on new data).
   
11. Results:
   The model reached 98.75% accuracy during training.
   After testing, it gave correct predictions.


Conclusion:
    This project built a Random Forest model that can predict whether a tumor is benign or malignant with high accuracy, which can be useful for early detection of cancer.
