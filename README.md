[Machine.Learning.on.Diabetes.Dataset_Odia.Akioya.pptx](https://github.com/odia101/CEBD_1160_PROJECT/files/2999465/Machine.Learning.on.Diabetes.Dataset_Odia.Akioya.pptx)


# Final_Project_CEBD1160

| Name | Date |
|:-------|:---------------|
|ODIA AKIOYA | 03-27-2019|

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

In this work, a publicly available diabetes dataset has been explored and modeled through machine learning to analyze feature importance in the aspect of predicting disease progression in diabetic patients. This finding will help researchers and medical personnels narrow their focus to key features which are the key contributors to the outcome which in this case is disease progression in diabetes patients over period of one year. Three differnt models: Decision Tree, Random Forest, and Gradient Boosting have been impored in modeling our data to visualize feature importance. Their respective results and performance accuracy have been compared and analyzed.   

### Introduction

The dataset used in this project is the diabetes dataset which is one of the training datasets provided freely and publicly on the [webpage](https://scikit-learn.org/stable/datasets/index.html#toy-datasets) of scikit-learn. It consists of 10 baseline variables: age, sex, body mass index(bmi), blood pressure (bp), s1, s2, s3, s4, s5, s6 where s1 to s6 represents different blood serums. These variables are information and blood samples collect from a total of 442 diabetes patients. The data also contains an outcome or target feature which is a quantitative measure of disease progression after one year of baseline. The dataset can be downloaded [here](https://www4.stat.ncsu.edu/~boos/var.select/diabetes.html) or imported directly from the scikit-learn library.  

### Methods

Before modeling the dataset, the data itself was organized into a matrix, otherwise known as a heat map as shown in Figure 1 below. From this matrix, all feature to feature correlation as well as feature to target correlation can be observed. The regression algorithms used in modeling this dataset are Decision Tree, Random Forest, and Gradient Boosting. These regression models and algorithms are in-built in scikit-learn and their pseudocode can be found [here](http://scipy-lectures.org/packages/scikit-learn/index.html#introduction-problem-settings). 

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

These results are discussed in the next section.

### Discussion

The accuracy on training set from the decision tree model is 100% while that on the test set is poor at about 9%. This indicates that the model may be overfitting. However, the feature importance plot shows that BMI is the most important feature followed by S5 and S4 respectively. On the other hand, accuracy on training set for the Random tree model which is at about 91% yeilded an improved accuracy on test set of about 43%. This model also gives the most importance to BMI followed by S5 and BP. This may have yielded a slightly different result than the decision tree model because it forces the algorithm to consider many parameters. Random forest captures a  broader picture since it applies multiple trees compared to the Decision tree which uses only a single tree. Upon implementing the Gradient boosting model, it can be observed that both accuracies depreciated in this model compared to the Random tree even though its accuracy on test set outperformed those from the Decision Tree model. However, the feature importance plot results in a similar outcome with the other models.  

Due to the randomness and differences in the outcome of the results obtained from the three different models, it is difficult to confidently state from this work which model is best for analyzing feature importance in the diabetes dataset. Although all models favored BMI, S5, BP, S4 as the most important features, there may also be other features that were not captured by these algorithms due to overfitting and model complexity. Hence, for future work, it is recommended that stronger pre-prunning is applied to reduce overfitting. This can be achieved by limiting the maximum depth or lower the learning rate.

### References

[1] https://towardsdatascience.com/machine-learning-for-diabetes-562dd7df4d42 (Accessed March 18th, 2019)
[2] https://scikit-learn.org/stable/tutorial/statistical_inference/supervised_learning.html (Accessed March 19th, 2019)
[3] James, R., T. K. Young, C.A. Mustard, and J. Blanchard. 1998. The health of Canadians with diabetes. Health Reports. Statistics Canada, Catalogue no. 82-003. Vol. 9, no. 3. (accessed March 22nd, 2019).
[4] https://www.datacamp.com/community/tutorials/decision-tree-classification-python (Accessed March 20th, 2019)

