# Credit Card Fraud Detection

This project demonstrates the use of machine learning, specifically logistic regression, to detect fraudulent credit card transactions.

## Dataset

The project utilizes the "creditcard.csv" dataset. This dataset contains information about credit card transactions, including features such as transaction amount, time, and various anonymized features.

## Methodology

1. **Data Loading and Preprocessing:** The code begins by loading the dataset using Pandas and performing basic data exploration. It checks for missing values, describes the dataset's statistics, and examines the class distribution (fraudulent vs. legitimate transactions).

2. **Data Balancing:** Since the dataset is imbalanced (with a significantly higher number of legitimate transactions), a new dataset is created by undersampling the majority class (legitimate transactions) to balance the class distribution.

3. **Model Training:** The code then splits the balanced dataset into training and testing sets. It uses logistic regression as the classification model and trains it on the training data.

4. **Model Evaluation:** The trained model is evaluated on both the training and testing sets using accuracy as the evaluation metric.

## Usage

To run the code, you will need to have the following libraries installed:

- Pandas
- NumPy
- Scikit-learn
- Matplotlib

1. Upload the "creditcard.csv" dataset to your Google Colab environment.
2. Execute the code cells in the provided notebook sequentially.
3. Observe the output, including the training and testing accuracy scores.

## Results

The code will print the accuracy of the model on both the training and testing sets. Additionally, it will generate a plot comparing the predicted values with the actual values for the test set.

## Conclusion

This project provides a basic implementation of credit card fraud detection using logistic regression. Further improvements can be explored, such as using different classification algorithms, feature engineering, and hyperparameter tuning, to enhance the model's performance.
