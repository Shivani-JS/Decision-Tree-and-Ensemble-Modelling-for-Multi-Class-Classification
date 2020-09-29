# Decision-Tree-and-Ensemble-Modelling-for-Multi-Class-Classification

### Software Requirement:
    -- Jupyter Notebook
    -- Anaconda
    -- Python 3.6 and above

### Data Details:
The data consist of different features of Cars with seven attributes as follows:

    -- Buying
    -- Maint
    -- Doors
    -- Persons
    -- Lug_boot
    -- Safety
    -- Classes

The dependent variable "Classes" consist of Multiple Categories such as

    -- Unacc
    -- Acc
    -- Good
    -- Vgood

### Project Description:
Following models from sklearn library were implemented for Multi-Class Classification

    -- Base DT ---> Accuracy obtained-99.22%
    -- Tuned DT ---> min_samples_leaf=5, max_depth=10--> Accuracy-94.21%
    -- Base SVM-SVC(kernel) ---> Accuracy-85.55%
    -- Tuned SVM-SVC --->COST=50 --> Accuracy-99.61%
    -- Logistic_Regg ---> Accuracy-69.94%
    -- ExtraTreesClassifier ---> Accuracy-98.44%
    -- Random_Forest_Classifier --->  Accuracy-98.26%
    -- AdaBoostClassifier ---> Accuracy obtained- 98.45%
    -- Gradient_Boosting_Classifier ---> Accuracy obtained= 99.80%
    -- Ensemble Modelling from sklearn was applied

### Model Evaluation Metrics:
    -- Accuracy Score
    -- Recall
    -- Precision
    -- F1-score
