# Credit Card Default Prediction using Support Vector Machines

## Project Overview

This machine learning project aims to predict credit card defaults using a Support Vector Machine (SVM) model. The dataset contains information like credit data, payment history, and demographic factors for over 30,000 credit card customers. 

The project workflow includes:

- Data Exploration and Visualization
- Data Cleaning and Preprocessing 
- Feature Engineering and Selection
- Model Development and Evaluation
- Hyperparameter Tuning to optimize SVM model
- Final Model Building and Testing

## Data Understanding  

The original dataset had 30,000 rows with 24 features like gender, education, marital status, history of past payments along with the default payment flag. As SVM performs better with smaller datasets, the records were downsampled to 2000 rows with a balance of default and non-default cases.   

## Model Performance

The optimized SVM model obtained over 81% accuracy in predicting defaults. Additional techniques like PCA and decision boundary visualization provide insights into model behavior.

## Conclusion

The high prediction accuracy demonstrates that machine learning techniques like SVM can be effective in assessing credit risk using available data on customer payment habits. Further enhancements through better features and regularization can improve performance.

This end-to-end implementation with a structured workflow serves as a template for applying SVM models to real-world classification problems. The code is available for reference in this repo.
