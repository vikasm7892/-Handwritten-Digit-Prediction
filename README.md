# Handwritten Digit Prediction - Classification Analysis

## Project Overview
This project uses the Digits dataset, consisting of 8x8 pixel grayscale images of handwritten digits (0-9), to build a machine learning model for digit classification. The objective is to preprocess the data, train a model, and evaluate its performance in accurately predicting the digits.

## Dataset
The dataset is available in the `sklearn.datasets` module and contains 8x8 pixel grayscale images. Each image is associated with a target label representing the digit (0-9).

## Steps Involved
1. **Data Preprocessing**: 
   - The 8x8 pixel images are reshaped into 1D arrays.
   - The pixel values are scaled using `StandardScaler`.
   
2. **Train-Test Split**: 
   - The data is split into training and testing sets using `train_test_split`.

3. **Modeling**: 
   - A Random Forest Classifier is used to train the model on the training data.

4. **Model Evaluation**: 
   - The model's performance is evaluated using accuracy score and classification report.

5. **Prediction**: 
   - The model is used to predict the labels of test data.

## Libraries Used
- **pandas**: For data manipulation.
- **numpy**: For numerical operations.
- **matplotlib**: For data visualization.
- **scikit-learn**: For machine learning tools (model training, evaluation, and dataset loading).

## Requirements
To run the project, you need the following Python libraries:
```bash
pip install pandas numpy matplotlib scikit-learn
