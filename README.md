[Machine.Learning.on.Diabetes.Dataset_Odia.Akioya.pptx](https://github.com/odia101/CEBD_1160_PROJECT/files/2999465/Machine.Learning.on.Diabetes.Dataset_Odia.Akioya.pptx)


# cebd1160_project_template
Instructions and template for final projects.

| Name | Date |
|:-------|:---------------|
|ODIA AKIOYA | 03-30-2019|

-----

### Resources
This repository contains the following:

- Python script for our analysis: newscript.py
- Results figure/saved file: Plots/
- runtime-instructions in a file named RUNME.md

-----

## Research Question

1 sentence description of your research question.

### Abstract

4 sentence longer explanation about your research question. Include:

- opportunity (what data do we have)
- challenge (what is the "problem" we could solve with this dataset)
- action (how will we try to solve this problem/answer this question)
- resolution (what did we end up producing)

### Introduction

Brief (no more than 1-2 paragraph) description about the dataset. Can copy from elsewhere, but cite the source (i.e. at least link, and explicitly say if it's copied from elsewhere).

### Methods

Before modeling the dataset, the data itself was organized into a matrix, otherwise known as a heat map as shown in Figure 1 below. From this matrix, all feature to feature correlation as well as feature to target correlation can be observed. The methods used in modeling this dataset are Decision Tree, Random Forest, and Gradient Boosting. These regression models and algorithms are in-built in scikit-learn and their pseudocode can be found [here](http://scipy-lectures.org/packages/scikit-learn/index.html#introduction-problem-settings). 

- pseudocode for this method (either created by you or cited from somewhere else)
- why you chose this method

| ![Heatmap_Diabetes](https://user-images.githubusercontent.com/47048059/55043879-843f0e80-500e-11e9-8d1f-113b3e63b1bc.png) | 
|:-------|
|Fig. 1: Heat Map | 

### Results

Brief (2 paragraph) description about your results. Include:

| ![Decision_Tree](https://user-images.githubusercontent.com/47048059/55043471-d2eba900-500c-11e9-9f01-03627c8d3393.png) | ![Random_Forest](https://user-images.githubusercontent.com/47048059/55043474-d848f380-500c-11e9-892a-143fff7696ba.png) | ![Gradient_Boosting](https://user-images.githubusercontent.com/47048059/55043478-de3ed480-500c-11e9-95ea-6e4a1e039c61.png) |
|:-------|:---------------|:---------------|
| Fig. 2: Decision Tree | Fig. 3: Random Forest | Fig. 4: Gradient Boosting |

| Performance Analysis | Decision Tree | Random Forest | Gradient Boosting |
|:-------|:---------------|:---------------|:---------------|
|Accuracy on Training Set | 1.000| 0.917| 0.539|
|Accuracy on test set | 0.094| 0.430|0.387|

- At least 1 figure
- At least 1 "value" that summarizes either your data or the "performance" of your method
- A short explanation of both of the above

### Discussion
Brief (no more than 1-2 paragraph) description about what you did. Include:

- interpretation of whether your method "solved" the problem
- suggested next step that could make it better.

### References
All of the links

-------
