[Machine.Learning.on.Diabetes.Dataset_Odia.Akioya.pptx](https://github.com/odia101/CEBD_1160_PROJECT/files/2999465/Machine.Learning.on.Diabetes.Dataset_Odia.Akioya.pptx)


# Final_Project_CEBD1160

| Name | Date |
|:-------|:---------------|
|ODIA AKIOYA | 03-30-2019|

-----

### Resources
This repository contains the following:

- Python script for our analysis: [newscript.py](https://github.com/odia101/CEBD_1160_PROJECT/blob/master/newscript.py)
- Results figure/saved file: [Plots/](https://github.com/odia101/CEBD_1160_PROJECT/tree/master/Plots)
- Runtime-instructions: [RUNME.md](https://github.com/odia101/CEBD_1160_PROJECT/blob/master/RUNME.md)

-----

## Research Question

### Can we save the time and resources spent collecting irrelevant or not so important medical information from patients by modeling the diabetes dataset to predict the key features that are most important in analyzing disease progression in confirmed diabetes patients?

### Abstract

In this work, a publicly available diabetes dataset has been explored and modeled through machine learning to analyze which features are most important in predicting disease progression in diabetic patients. This finding will help researchers and medical personnels narrow their focus to key features which are the key contributors to the outcome which in this case is disease progression in diabetes patients over period of one year. Three differnt models: Decision Tree, Random Forest, and Gradient Boosting have been impored in modeling our data to visualize feature importance. Their respective results and performance accuracy have been compared and analyzed.   

### Introduction

Brief (no more than 1-2 paragraph) description about the dataset. Can copy from elsewhere, but cite the source (i.e. at least link, and explicitly say if it's copied from elsewhere).

### Methods

Before modeling the dataset, the data itself was organized into a matrix, otherwise known as a heat map as shown in Figure 1 below. From this matrix, all feature to feature correlation as well as feature to target correlation can be observed. The methods used in modeling this dataset are Decision Tree, Random Forest, and Gradient Boosting. These regression models and algorithms are in-built in scikit-learn and their pseudocode can be found [here](http://scipy-lectures.org/packages/scikit-learn/index.html#introduction-problem-settings). 

- why you chose this method

| ![Heatmap_Diabetes](https://user-images.githubusercontent.com/47048059/55043879-843f0e80-500e-11e9-8d1f-113b3e63b1bc.png) | 
|:-------|
|Fig. 1: Heat Map | 

### Results

The results obtained from the regression models are as shown in the figures below.

| ![Decision_Tree](https://user-images.githubusercontent.com/47048059/55043471-d2eba900-500c-11e9-9f01-03627c8d3393.png) | ![Random_Forest](https://user-images.githubusercontent.com/47048059/55043474-d848f380-500c-11e9-892a-143fff7696ba.png) | ![Gradient_Boosting](https://user-images.githubusercontent.com/47048059/55043478-de3ed480-500c-11e9-95ea-6e4a1e039c61.png) |
|:-------|:---------------|:---------------|
| Fig. 2: Decision Tree | Fig. 3: Random Forest | Fig. 4: Gradient Boosting |

The table below outlines the performance accuracy of the models.

| Performance Analysis | Decision Tree | Random Forest | Gradient Boosting |
|:-------|:---------------|:---------------|:---------------|
|Accuracy on Training Set | 1.000| 0.917| 0.539|
|Accuracy on test set | 0.094| 0.430|0.387|

- A short explanation of both of the above

### Discussion
Brief (no more than 1-2 paragraph) description about what you did. Include:

- interpretation of whether your method "solved" the problem
- suggested next step that could make it better.

### References
All of the links

-------
