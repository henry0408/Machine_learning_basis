# Machine_learning_basis
ELEC3612 Project1 Human faces classfication

The Sheffield Face Database was used to achieve a human face classification task in this project. 

Each person’s face is shown in a range of poses, which are from profile to frontal views. 

The whole dataset (cropped.zip) is separated into directories labelled 1a, 1b, … 1t and images are numbered consecutively as they were taken.

Some basic Machine Learning techniques and algorithms are used and we got the final accuracy based on the confusion matrix.

The whole process can be seperated into:

1. Using different sampling methods (Random split/sampling and Stratified sampling as improvement) from Dataset to get training and testing set.

2. Support-Vector-Machine (SVM) with Gaussian and Polynomial kernel for classification. Then we also consider the overfitting problem.

3. Principle-Component-Analysis (PCA) for featureextraction (image matrix dimension reduction) and we got the Mean-face and Eigen-face. Then, we used the eigenfaces for reconstructed the image.

4. Binary Logistic Regression and OvA (OvR) algorithms for classification.

5. LDA for multi-class classification and got the Fisher-face

![image](https://user-images.githubusercontent.com/58734009/184889252-210fc293-b485-4bd8-89bf-66f1ae72988e.png)

![image](https://user-images.githubusercontent.com/58734009/185101675-f0b0b958-2586-42d4-8116-35edd128d51d.png)

![image](https://user-images.githubusercontent.com/58734009/184889616-c91fab61-c7fa-490c-8441-ce150fab0c4d.png)


