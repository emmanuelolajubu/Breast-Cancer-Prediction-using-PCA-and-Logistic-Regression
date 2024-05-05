# Breast-Cancer-Prediction-using-PCA-and-Logistic-Regression

Overview
This project demonstrates how to predict breast cancer malignancy using Principal Component Analysis (PCA) and logistic regression. I reduced the dataset's dimensionality with PCA and then train a logistic regression model for accurate predictions.

Prerequisites
- Python (3.6 or higher)
- Libraries: `numpy`, `pandas`, `scikit-learn`, `matplotlib`

Steps
1. Load the Dataset:
   - I used the breast cancer dataset from `sklearn.datasets`.
   - Features include cell nucleus characteristics (e.g., radius, texture, smoothness).
   - Target variable: 0 (benign) or 1 (malignant).

2. Standardize Features:
   - Standardize features to have zero mean and unit variance.
   - Helps PCA work effectively.

3. Apply PCA:
   - Use PCA to reduce dimensionality.
   - Choose the top-k principal components (e.g., k=2).

4. Train Logistic Regression Model:
   - Split data into training and testing sets.
   - Initialize a logistic regression model.
   - Fit the model to the training data.

5. Evaluate Model Performance:
   - Calculate accuracy, precision, recall, F1-score.
   - Plot the Receiver Operating Characteristic (ROC) curve.

Usage
1. Clone this repository:
   
   git clone https://github.com/emmanuelolajubu/Breast-Cancer-Prediction-using-PCA-and-Logistic-Regression
   

2. Install required libraries:
   
   pip install numpy pandas scikit-learn matplotlib
   

3. Run the script:
   
Results
- The model predicts breast cancer malignancy based on input features.
- Evaluate the model's performance using metrics.
- Adjust hyperparameters as needed.

Acknowledgments
- Dataset source: [Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))

Feel free to contribute or enhance this project!
