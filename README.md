# Iris Flowers Machine Learning Assignment
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alireza-es/ml-iris-flowers/blob/main/notebooks/assignment_1.ipynb)
## Overview
This repository contains my solution for the "Iris Flowers Machine Learning Assignment," which is part of the **ENSF  619 - Special Topics** course. The assignment focuses on refreshing fundamental machine learning coding skills by working with the classic Iris Flowers dataset. It covers data preparation, exploration, preprocessing, model building, evaluation, and optional hyperparameter tuning.
## Repository Structure
The repository is organized as follows:
- `code/`: Contains Python code for the assignment.
  - `notebooks/`: Jupyter Notebook files (e.g., `assignment_1.ipynb`)
- `data/`: Stores the Iris dataset CSV file (e.g., `iris_dataset.csv`).
- `results/`: Reserved for output files or results generated during analysis.
- `environment/`: Includes a `requirements.txt` file listing required Python packages.
- `images/`: (Optional) Images or plots generated in the analysis.
- `models/`: (Optional) Directory for storing trained machine learning models.

## Getting Started
You can directly open the notebook in  [Google Colab](https://colab.research.google.com/github/alireza-es/ml-iris-flowers/blob/main/notebooks/assignment_1.ipynb) or follow these steps to run the code in your local machine:
1. Set up your Python development environment with the required libraries (NumPy, Pandas, Scikit-learn).
2. Clone or download this repository.
3. Install the requirements using `pip install -r environment/requirements.txt`. You may need to run `pip3 install -r environment/requirements.txt`
4. Navigate to the `code/` directory.
5. [Open](notebooks/assignment_1.ipynb) and run the Jupyter Notebook `assignment_1.ipynb` in the notebooks' folder.

## Summary
In this sample, I tackled the task of machine learning coding skills refresher. Here’s a summary of the key points and findings:
1. **Data Exploration:** I started by exploring the Iris dataset, examining the data distribution and visualizing it using histograms and scatter plots. This step provided valuable insights into the dataset.
2. **Data Preprocessing:** I performed essential data preprocessing tasks such as handling missing values, encoding categorical variables, and splitting the data into training and testing sets. These steps ensured that the data was ready for model building.
3. **Model Building:** I selected the K-Nearest Neighbors (K-NN) algorithm for classification and built a basic model. This choice aligned well with the nature of the Iris dataset.
4. **Model Training and Evaluation:** I trained the K-NN model on the training data and evaluated its performance on the testing data. Metrics such as accuracy, precision, recall, and the confusion matrix were used to assess the model’s performance.
5. **Hyperparameter Tuning (Optional):** To fine-tune the model’s performance, I conducted a grid search over different values of n_neighbors for the K-NN algorithm. This step demonstrated the impact of hyperparameter tuning on model performance.