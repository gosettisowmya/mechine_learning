Neural Network Model – Task 1 (Without Normalization)

This project implements a Neural Network (ANN / MLP) model using Python and Scikit-learn.
The model is trained and evaluated without applying any normalization or feature scaling, as required for Task-1.

Objective

Load and preprocess the given dataset

Perform basic exploratory data analysis (EDA)

Train a Neural Network model on raw data

Evaluate model performance using standard metrics

Dataset

Format: Excel (.xlsx)

Type: Tabular data

Features: All columns except the last

Target: Last column (Bed Form)

Missing Values: Removed

Normalization: ❌ Not applied

Tools & Libraries

Python

Jupyter Notebook

Pandas

Scikit-learn

Methodology

Load the dataset using Pandas

Remove rows with missing values

Generate summary statistics for EDA

Split data into training and testing sets

Train a Neural Network (MLPClassifier)

Evaluate the model using classification metrics

Model Details
Parameter	Value
Model	MLPClassifier
Hidden Layers	1
Neurons	16
Activation	ReLU
Optimizer	Adam
Normalization	No
Evaluation Metrics

Accuracy

Precision

Recall

F1-Score

Observations

The model works on raw, unscaled data.

Performance is limited due to lack of normalization.

Results serve as a baseline for comparison with normalized models.

Conclusion

This task demonstrates a baseline neural network model trained without normalization.
The outcome highlights the importance of feature scaling, which is addressed in the next task.

