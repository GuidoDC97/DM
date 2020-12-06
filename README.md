# Data Mining
Repository for Data Mining project.

Individual project consisting in building a classifier for recognizing Alzheimer disease.

AY 2020/2021

## Solution

Project has been completely developed in **Python**, using popular libraries for data analysis and machine learning such as **pandas** and **scikit-learn**.

The search for the best machine learning algorithm to adopt for the specific classification task consists of the following steps:
* **Data preparation**: which is articulated in:
  * **Data cleaning**: consists in the correction of incoherent data in the dataset where possible.
  * **Data imputation**: consists in replacing missing values with reasonably values.
* **Model selection**: the aim is to find out the most promising algorithm for the problem under study. This step is acomplished by performing a repeated stratified K-fold cross validation with inner grid search for finding best hyperparameters for algorithm.
* **Hyperparameter tuning**: once the model selection has been acomplished, the hyperparameter of the selected model can be tuned with a K-fold cross validation and an inner grid search for hyperparameters.
* **Model evaluation**: with the hyperparameter gfound at the previous step, it is possibile to train the model with them and to evaluate its performances. The evaluation phase is used again a K-fold cross validation.
* **Prediction**: finally, the model is retrained on the whole dataset with the specified hyperparameters foud during tuning phase and new instances can be predicted. 

## Documentation & Code

Complete description of assignment can be found **[here](/Assignment.pdf)**.

Source code of project can be found **[here](/AlzheimerClassification.ipynb)**.
