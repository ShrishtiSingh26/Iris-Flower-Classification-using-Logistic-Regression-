# AI-Club-Technical-Team-Task-round
### Iris Flower Classification
This project classifies iris flowers into one of three species **Setosa, Versicolor, and Virginica** based on four features: sepal length, sepal width, petal length, and petal width. The dataset and model development follow a standard machine learning workflow, using Python and scikit-learn.

## Project Overview
The goal of this project is to build a simple yet effective machine learning model to classify iris flowers. Using logistic regression, the model achieves 100% accuracy on the test set. This project includes data preprocessing, model training, evaluation, and visualization.

## Dataset
The Iris dataset is a classic dataset in machine learning, containing 150 instances of iris flowers with the following attributes:

# Features:
Sepal Length
Sepal Width
Petal Length
Petal Width
# Target Classes:
Setosa
Versicolor
Virginica
The dataset is included with `scikit-learn` and can be loaded using `load_iris()`.

## Solution Approach

The solution involves the following steps:

- **Loading the Dataset:** Use `load_iris` from `sklearn.datasets` to load the Iris dataset.
- **Splitting the Dataset:** Split the data into training and testing sets (80% training, 20% testing).
- **Data Preprocessing:** Scale the features using `StandardScaler` to standardize the data.
- **Training the Model:** Train a logistic regression classifier on the training set.
- **Model Evaluation:** Evaluate the model on the test set using metrics like accuracy, precision, recall, and F1-score.
- **Visualization:** Display a confusion matrix to visualize the model's performance.

## Requirements

-Python 3.7 or higher

# Required libraries:

```bash
pip install -r requirements.txt
```

where requirements.txt contains:
 ```bash
scikit-learn
matplotlib
seaborn
```

## Results
# Classification Metrics
The classification report and confusion matrix indicate a perfect classification, with an accuracy of 1.0 and no misclassifications.

# Accuracy: 100%
# Precision, Recall, and F1-Score: All are 1.0 for each class (Setosa, Versicolor, Virginica).
# Confusion Matrix
The confusion matrix visualizes that each class was correctly identified, with no errors in prediction.

![image](https://github.com/user-attachments/assets/41d9a05f-4508-4b0a-9a65-31d7ad911b49)

## How to Run

Clone the repository:

```bash
git clone https://github.com/your-username/iris-flower-classification.git
cd iris-flower-classification
```
Install dependencies:
```bash

pip install -r requirements.txt
``` 
Run the main script:
```bash

python iris_classification.py
```
