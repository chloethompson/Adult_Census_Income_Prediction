# Census Income Analysis

The Census Income Dataset allows for predictions of income pre year greater than or less than 50K with certain features. This project analyses the dataset through visualisations noting it's key features and bias. Using this information models are developed and analysed to understand how the features in the dataset affect the fairness outcome of predictions.


## Description

The project is split into two simple areas, data analysis and visualisations and model predictions and evaluation. The focus is primarily on data bias, fairness of prediction and explainability of the chosen model. 

The model chosen for analysis was a Decision Tree, which in itself is not a complex model, compared to NN's or Deep Learning Approaches. However, this technique has the ability to be well explained in the decisions that were taken for the predictions, which was an important aspect of the project. 

The notebooks in this project contain:

* Data Analysis of the Census Income Dataset 
* Correlation Analysis of Features
* Initial Model training and evaluation - including fairness feature understanding
* Model HyperTuning - via Grid Search
* Analysis of prediction outcomes


## Getting Started

### Dependencies

Simply run the requirements.txt file to install all the needed libraries and versions. 

### Installing

The notebooks themselves have the imports for the code in a single file - Library_Imports.ipynb

### Dataset

You can download the dataset from:
https://www.kaggle.com/datasets/uciml/adult-census-income