Neural Network Model – Task 1 & Task 2

This project demonstrates the development and evaluation of a Neural Network (ANN / MLP) model on the given dataset under two conditions:

Task 1: Training without normalization

Task 2: Training with normalization

The comparison highlights the impact of feature scaling on neural network performance.

Objectives

Build a baseline ANN model without normalization (Task 1)

Apply feature normalization and retrain the same ANN (Task 2)

Compare model performance using the same evaluation metrics

Dataset

Format: Excel (.xlsx)

Type: Tabular data

Features: All columns except the last

Target Variable: Last column (Bed Form)

Missing Values: Removed during preprocessing

Tools & Libraries

Python

Jupyter Notebook

Pandas

Scikit-learn

Task 1: Model Development (Without Normalization)
Description

In Task 1, the neural network model is trained using raw, unscaled data.
This task serves as a baseline to understand ANN performance without feature scaling.

Methodology

Load dataset

Remove missing values

Perform basic EDA (summary statistics)

Split data into training and testing sets
Evaluation Metrics

Accuracy

Precision

Recall

F1-Score

Task 2: Model Development (With Normalization)
Description

In Task 2, feature normalization is applied to improve learning stability and performance.
The same ANN architecture and hyperparameters from Task 1 are used to ensure a fair comparison.

Normalization Technique

StandardScaler (mean = 0, standard deviation = 1)

Applied after train–test split

Fitted only on training data to avoid data leakage

Methodology

Split data into training and testing sets

Apply normalization to features

Train the same ANN architecture

Evaluate model performance using the same metrics
Key Observations

Neural networks are sensitive to feature scale.

Normalization improves gradient stability and convergence.

Using the same architecture ensures a fair and valid comparison.

Task 2 consistently outperforms Task 1.

Conclusion

This project demonstrates the importance of data preprocessing in neural network models.
While Task 1 establishes a baseline using raw data, Task 2 shows how normalization significantly improves model performance without changing the network architecture.
Train ANN without applying normalization

Evaluate model performance
