# Medlytics Week 1 Challenge Project
## Background
The challenge involved predicting whether a patient has **hypothroidism** and determining which attributes from the dataset are meaningful and useless for the models. Creator: Lyle Lalunio.

## Dataset
2800 patients with 29 features with some misisng data. 20% of the data was set for testing data. http://archive.ics.uci.edu/ml/datasets/thyroid+disease  

## Presentation
Our team looked at the ROC curves, correlation heatmap, and used random forest for feature selection to determine that entries, 'TSH', 'T3', 'TT4', and 'FTI'. We then did another random forest and saw that 'TSH' was the more impactful classifer and ended up producing an inaccurate ROC curve. We can improve this model by using a better machine learning model or conducting literature review on hypothroidism.

Here is the random forest on all features:
![Screenshot of code of the random forest doing feature selection on entire dataset](https://github.com/angellicodigo/Medlytics-Week1/blob/main/Challenge%20Project/random_forest_1.png)

Here is random forest on the four important features, 'TSH', 'T3', 'TT4', and 'FTI'.
![Screenshot of code of the random forest doing feature selection on features 'TSH', 'T3', 'TT4', and 'FTI'.](https://github.com/angellicodigo/Medlytics-Week1/blob/main/Challenge%20Project/random_forest_2.png)

Here is our ROC curve of using 'TSH' for our logistic regression.
![ROC Curve](https://github.com/angellicodigo/Medlytics-Week1/blob/main/Challenge%20Project/ROC_result.png)

And our confusion matrix:
```
[488 12]
[0 38]
```


# What else does Medlytics Week 1 contain?
This is the repository for all lectures, assignments, and datasets for Week 1 of the BeaverWorks Medlytics course for 2022. The slides are provided here for easy reference, but will be presented in lecture format. You should fork this repository at the beginning of the week and work on your own copy when completing notebooks and challenge projects.

Datasets Used in this Repo:

PIMA Indians diabetes dataset: https://www.kaggle.com/uciml/pima-indians-diabetes-database/version/1   
Depression Dataset from UFHealth Biostatistics Open Learning Textbook: http://bolt.mph.ufl.edu/2012/08/02/learn-by-doing-exploring-a-dataset/   

## Notebooks
* Contains Jupyter Notebook lessons where students will need to write their own code
* Contains Jupyter Notebook Solutions (will be uploaded after lesson notebooks are completed by students)
