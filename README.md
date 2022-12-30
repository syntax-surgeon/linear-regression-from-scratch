# linear-regression-from-scratch

> A simple, single variable linear regression algorithm to understand the underlying training mechanism.
>
> #### Author: _Siddharth Yadav (syntax-surgeon)_

### linear_regression_from_scratch.ipynb

- Contains version-1.0 of the main program which tries to implement a **single-variable linear regression algorithm**
- A single class **_'LinearRegressionAlgorithm'_** is provided to intialize the model, train the model and plot the results
- At the heart of the algorithm is a **simple update function** which adjusts the model parameters (weight and bias) by incrementally moving the regression line closer to the points in the dataset (_see 'update_parameters' function in the 'LinearRegressionAlgorithm' class_)
- A plotting function ( \<model\>.plot ) is included to visualize the results of the training.
  - Two plots are generated: (_see figure 1 below_)
    - Scatterplot of the data with the best regression line and numpy polyfit line
    - The total error (RMSE) per epoch
- A randomly generated dataset is provided to test the algorithm and plot the results

> #### **(_Figure 1_)** Results of training the linear regression algorithm on a randomly generated dataset
>
> ![alt text](https://github.com/syntax-surgeon/linear-regression-from-scratch/blob/main/readme_assets/training_results.png?raw=true)
