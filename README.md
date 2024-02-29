Support Vector Machine (SVM) is a supervised machine learning algorithm for data classification or regression. It is particularly useful for:

1. Dealing with high-dimensional data.
2. Handling both linear and non-linear classification.
3. Working with small to medium databases.
4. Tasks such as text classification and image recognition.

*Things to remember:*
- Ensure data categories are of integer type, not objects. You can use `.astype` to change the type.
- Utilize `param_grid` to find the best model parameters.

This project is divided into three separate files for SVM analysis based on:
1. Cell_samples (basic data for understanding SVM).
2. Breast_cancer (classification based on cancer type recognition).
3. Iris_project (classification of flowers).

*Methodology:*
1. Download required libraries (Pandas, NumPy, Scikit-learn, Matplotlib).
2. Load and explore the interesting data.
3. Understand the data and perform basic visualization and data wrangling.
4. Define the features (X) and target (y) variables for analysis.
5. Split the data into training and testing sets.
6. Build SVM models.
7. Evaluate model performance by printing the confusion matrix and classification report to analyze the results.
