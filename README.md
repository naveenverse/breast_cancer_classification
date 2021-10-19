# breast_cancer_classification
## Objective
Train a regression model to classify benign and malignant stages of breast cancer.
## Approach
The classification of the breast-cancer-wisconsin-data is basically a regression problem.
We build a Sequential model using Keras API.

    model.summary()
   <img width="379" alt="Untitled" src="https://user-images.githubusercontent.com/59974158/137920546-c424c0a9-b127-43e1-ac09-7417a06c98be.png">

Sigmoid function is used when dealing with classfication problems with 2 types of results

![1 Xu7B5y9gp0iL5ooBj7LtWw](https://user-images.githubusercontent.com/59974158/137921179-9f0f68e2-5cfa-4aef-b242-fceb843ddbfa.png)

Optimizer is chosen as adam for gradient descent.

Binary_crossentropy is the loss function used.

## Model evaluation
The model showed validation accuracy of 0.978 in training dataset at the end of 200 epochs. Evaluation metrics on test data is shown below:

    Accuracy: 91.22807017543859%
    Senstivity: 0.9285714285714286
    Specificity: 0.9027777777777778
    
### Visualisation
Confusion matrix of model perfomance on test data

![h](https://user-images.githubusercontent.com/59974158/137922259-438899e3-48fd-47d7-aeb3-a4328399ca95.png)
