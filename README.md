# Credit Card Scoring Analysis
This repository contains the analysis and modeling code for a credit card scoring project. The goal of the project is to predict whether an applicant for a credit card will default on their payments or not. The analysis and modeling are based on a dataset of credit card applicants, which includes various features such as age, income, and credit history.

### Getting Started
To run the analysis and modeling code, I use Python and import the following packages:

- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
Install these packages using pip, a Python package manager. To install them, run the following command:
          pip install pandas numpy scikit-learn matplotlib seaborn

### Dataset
The dataset used in this project is a publicly available dataset from Kaggle. The dataset contains information about credit card applicants, including demographic information and credit history, as well as whether or not they defaulted on their payments.

### Analysis and Modeling
The analysis and modeling are performed in a Jupyter notebook. The notebook contains the following sections:

- Data Exploration: Explore the dataset and visualize the distributions of the features.
- Data Preprocessing: Data preprocessing by scaling the features and splitting the data into training and testing sets.
- Modeling: Decisiontree and Randomforest machine learning models were used to the train data and evaluating their performance on the testing data.
- Model Selection: Select the best performing model and tune its hyperparameters.
- Final Model: Train the final model on the entire dataset and save it for deployment.

Results
The final model achieved an accuracy of 78% on the testing data. This model was then used on new data to predict whether an applicant for a credit card is likely to default on their payments or not.

