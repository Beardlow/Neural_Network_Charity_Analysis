# Neural_Network_Charity_Analysis

## Overview
This analysis was brought on by Aphabet Soup, a charity organization. Their intent is to use Machine Learning to help decide which fund requests will be the most effective use of their donations. This analysis uses neural networks to help create a model for this purpose.

### Methodology
The column "Is Successful" is the taget column. The model uses other columns to predict whether this column will be a 1 or a 0. The features used to create the model are application type, ask amount, and special considerations.

### Execution
A Neural Network cosisting of 3 layers was initially used. The layer breakdown is as follows.
* Input Layer
  *   80 units
  *   sigmoid

* Second Layer
  *   20 units
  *   relu

* Output Layer
  *   1 unit
  *   linear


### Results
This model acheived an accuracy of 72.5% over 60 epochs. Additional runs did not improve results.

### Attempts at Optimization
Several attempts were made at increasing the model's accuracy; however, the results were more or less the same as the initial model. See below:

![Optimization Attempts](https://github.com/Beardlow/Neural_Network_Charity_Analysis/blob/main/Optimization_Attempts.png)

Aditional hidden layers with different activation fuctions and/or number of units did not make much of a difference in performance. Additional epochs also did not improve predictive performance. Additional time may need to be spent reducing the number of input variables for this model or collecting data to better train the model.

