# Heart-Disease-Prediction-
This project implements a logistic regression model to predict the risk of heart disease in patients based on clinical features. Logistic regression was chosen for its interpretability and effectiveness in binary classification tasks. The approach leverages common predictors from clinical datasets to assign a probability of heart disease presence.
# Heart Disease Prediction: Building a Predictive System

This project builds a predictive system for heart disease using a logistic regression model. After completing data collection and processing, the workflow includes splitting the dataset, target feature selection, model training, and evaluation. 

## Workflow

1. **Data Collection and Processing:**  
   Data was collected from a reliable source and processed to handle missing values, encode categorical features, and normalize numerical attributes.

2. **Splitting the Data:**  
   The dataset was split into training and test sets, ensuring that the model is trained and evaluated on distinct data portions.

3. **Target Feature Selection:**  
   The target variable, indicating the presence or absence of heart disease, was separated from the features for training.

4. **Model Training:**  
   A logistic regression model was trained using the training data.

5. **Model Evaluation:**  
   The model was evaluated on the test data with the performance metric provided below.

## Results

- **Accuracy on Test Data:** 0.819672131147541

This indicates that the model correctly predicts heart disease presence or absence in approximately 82% of the cases in the test set.

## How to Run

1. **Install Dependencies:**  
   Make sure you have Python 3.x installed along with the necessary libraries:
   ```bash
   pip install numpy pandas scikit-learn
