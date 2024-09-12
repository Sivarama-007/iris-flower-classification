# Iris Flower Classification 

This repository contains the code and files related to the **Iris Flower Classification** task, where we classify iris flowers into three species (setosa, versicolor, and virginica) based on their measurements using a Decision Tree Classifier.

## Table of Contents
1. [Project Description](#project-description)
2. [Installation](#installation)
3. [Dataset](#dataset)
4. [Model and Code](#model-and-code)
5. [Results](#results)
6. [How to Run](#how-to-run)
7. [License](#license)

## Project Description
The goal of this project is to classify iris flowers into three species based on their physical measurements. We use a machine learning model, specifically a **Decision Tree Classifier**, to perform this classification. 

The model is trained on the **Iris dataset**, a widely-used dataset for classification tasks.

## Installation
1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/iris-flower-classification.git
    ```
2. Navigate into the project directory:
    ```bash
    cd iris-flower-classification
    ```
3. Install the required Python libraries using the following command:
    ```bash
    pip install -r requirements.txt
    ```

## Dataset
The dataset used for this task is the famous **Iris dataset**:
- **Features**: sepal length, sepal width, petal length, petal width
- **Target**: Species (setosa, versicolor, virginica)

The dataset can be loaded directly from Scikit-learn, or you can use the CSV file provided in the repository: `iris_dataset.csv`.

## Model and Code
- The machine learning model used is a **Decision Tree Classifier** from Scikit-learn.
- The notebook and Python script (`.ipynb` and `.py`) contain all the code to load the dataset, train the model, and evaluate the performance.

## Results
The model achieves an accuracy score of `{{ accuracy_score }}` on the test set. Below is a sample confusion matrix and feature importance plot:

1. **Confusion Matrix**:
    ![Confusion Matrix](confusion_matrix.png)

2. **Feature Importance**:
    ![Feature Importance](feature_importance.png)

## How to Run
1. If using Jupyter Notebook or Google Colab, simply run the `iris_classification.ipynb` file.
2. If running the Python script:
    ```bash
    python iris_classification.py
    ```

## License
This project is licensed under the MIT License.
