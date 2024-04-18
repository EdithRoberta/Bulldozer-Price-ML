# Bulldozer-Price-ML

### The project is a machine learning regression problem.

This notebook looks into develop a ML model that is able to predict the price of bulldozers based on its characteristics and previous sales. To build a model it will be used Python-based ML and Data Science libraries, such as Pandas, NumPy, Matplotlib and Scikit-Learn.

## Project files:
* **environment.yml** - has all the packages of the environment

* **bulldozer-price-regression.ipynb** - contains the steps for building, evaluating and improving the regression model
* data folder:
  * **Data Dictionary.xlsx** - has informations about each column of the data
  * **Test.csv** - test dataset
  * **Train.zip &rarr; Train.csv** - train dataset
  * **Valid.zip &rarr; Valid.csv** - validation dataset
  * **TrainAndValid.zip &rarr; TrainAndValid.csv** - train & validation datasets
  * **test_predictions_submission.csv** - predictions of the trained model in the test data

More informations about the Bulldozers dataset on Kaggle: https://www.kaggle.com/c/bluebook-for-bulldozers/overview

Download whole data: https://www.kaggle.com/c/bluebook-for-bulldozers/data

## Steps to install the environment:
The environment is created and managed through Conda.

**environment.yml** contains all the packages needed for this project.

1. Open Anaconda Prompt
2. Create a new project directory
`mkdir <name_folder>`
3. Create the environment on the new project directory
`conda env create --prefix ./env -f ./environment.yml`
4. Activate the environment
`conda activate ./env`
5. Open Jupyter Notebook
`jupyter notebook`
