# ML-Project-

Predicting whether the mammogram is benign or malignant with Python, public dataset retrieved
from https://archive.ics.uci.edu/ml/datasets/Mammographic+Mass.

Cleaned the data by removing columns with mostly NaN values, dropping the records with NaN
attributes, converting it into NumPy arrays and normalized using the StandardScaler module.

Splits the filtered dataset into 80% training set and 20% test set, reduced overfitting with 10 folds of
cross-validation and achieved highest accuracy of 81.7% by using SVM “rbf” kernel.
