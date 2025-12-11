# Credit Risk Prediction Task:

### Objective:

The objective of this task is to Predict whether a loan applicant is likely to default on a loan dataset using Python.

### Approach:

The following steps were taken to complete the task:
- Importing Libraries
- Loading the Dataset
- Data Inspection (EDA) 
- Handle Missing Values 
- Check Inconsistency 
- Data Visualizations
- Distribution
  - Bar plots, scatter plots, box plots for relationship between features
- Normalization
  - using SMOTE mathod
- Label Incoding
- Split Data
- Model Train
  - Logistic Regression
  - Decision Tree Classifier
- Evaluate Model
- Confusion Matrix
- Classification Report
### Results and insights:
#### 🌳 Decision Tree:
- Accuracy: 88.51%
- Captures both classes well, especially defaults (class 1).
- Strong choice for imbalanced datasets.
- Slightly more false positives, but better recall.
#### 📈 Logistic Regression:
- Accuracy: 83.71%
- Performs well on majority class (paid loans).
- Misses many defaults — lower recall for class 1.
- More conservative, fewer false alarms.
  
Decision Tree Classifier accuracy is better than Lagistic Regression



