# Breast-Cancer-Classification
This project uses the Wisconsin Breast Cancer dataset from UCI Machine Learning Repository to gain a working understanding of Clasification algorithms. It also compares how Feature Scaling improves the accuracy of predictions made by the models using these algorithms.

## Tasks Accomplished

### 1. Understanding Classification Model
The project uses four different Classification algorithms from the Scikit-learn library in python namely
  1. K-Nearest Neighbors
  2. Logistic Regression
  3. Linear SVC
  4. RBF Kernel SVC
### 2. Understanding Importance of Feature Scaling
The models built using the dataset are fitted to both feature scaled and unscaled training and validation(test) data. The results compare the performance of an algorithm with respect to feature scaling.

## Libraries Used
The following python libraries are used in this project
  1. Pandas
  2. Numpy
  4. Matplotlib
  5. YellowBrick
  7. Sklearn

## Results
### 1. Visualization of Dataset

a. Training data
  ![Training data](https://github.com/ishitap11/Breast-Cancer-Classification/blob/master/Images/trainingdata.PNG)

b. Validation (Test) data
  ![Validation/Test data](https://github.com/ishitap11/Breast-Cancer-Classification/blob/master/Images/testingdata.PNG)

### 2. Classification Reports

a. K-Nearest Neighbors
 ![K-Nearest Neighbors](https://github.com/ishitap11/Breast-Cancer-Classification/blob/master/Images/KnnCR.PNG)

b. Logistic Regression
  ![Logistic Regression](https://github.com/ishitap11/Breast-Cancer-Classification/blob/master/Images/LrCR.PNG)

c. Linear SVC
  ![Linear SVC](https://github.com/ishitap11/Breast-Cancer-Classification/blob/master/Images/SvcCR.PNG)

d. RBF Kernel SVC
  ![RBF Kernel SVC](https://github.com/ishitap11/Breast-Cancer-Classification/blob/master/Images/SvcKernelCR.PNG)

### 3. Accuracy Scores with and without feature scaling

  ![Model accuracy scores](https://github.com/ishitap11/Breast-Cancer-Classification/blob/master/Images/modelbargraph.PNG)

## Inference
By the end of the project following inferences could be made:
1. Without Featres Scaling Logistic Regression performed the best with an accuracy score of ~ 95.6% whereas in case of Feature Scaling RBF Kernel SVC performed the best with an accuracy of ~ 98.24% on the validation set.

2. For all the algorithms the trained models performed better after Feature Scaling than without feature scaling. The maximum improvement was observed in the case of RBF Kernel SVC. 
