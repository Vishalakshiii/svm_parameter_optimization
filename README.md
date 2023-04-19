# Parameter Optimization of SVM
This is the assignment for course UCS654 presented by Vishalakshi (102017189)

## Introduction

Parameter optimization is a critical step in maximizing the performance of support vector machines (SVMs) for classification tasks. The two key parameters that need to be optimized in SVMs are the regularization parameter (C) and the kernel parameter (γ).
We can fine-tune these parameters to achieve Best Accuracy. The regularization parameter controls the trade-off between the complexity of the decision boundary and the level of misclassification, while the kernel parameter controls the flexibility of the decision boundary.
One common approach to parameter optimization is grid search, which involves searching over a predefined set of parameter values to find the optimal combination that maximizes the performance on a validation set. Now, we will be doing this using GridSearchCV for optimizing the parameters.
We will also be using Fitness Function .

## Dataset

Steel Industry Energy Consumption Dataset Data Set
https://archive.ics.uci.edu/ml/machine-learning-databases/00618/

The target attribute for classification is a category (Light load,Medium Load,Maximum Load)

Number of Instances: 35040

Number of Attributes: 11

## Result

<img width="281" alt="image" src="https://user-images.githubusercontent.com/91335213/233190497-76dc3351-3b59-4c3c-994a-36312f132a1d.png">

## Convergence Graph
<img width="504" alt="image" src="https://user-images.githubusercontent.com/91335213/233190744-706c9786-acf4-4892-8595-01d5a5dbbc7b.png">

## Conclusion
It concludes that as the number of iterations increases, the model becomes well trained and parameters have been optimised .
Sample 6 and 10 has the best accuracy of 0.9955.
