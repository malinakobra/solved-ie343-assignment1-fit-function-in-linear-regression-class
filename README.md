Download Link: https://assignmentchef.com/product/solved-ie343-assignment1-fit-function-in-linear-regression-class
<br>
Write a code for implementing the ’fit’ function in linear regression class (./Apps/linear regressor.py). Theoretically, this function is based on the least square method. The linear regressoion class has a member variable which represents ”weights” in this model.

In this assignment, you need to consider which polynomial feature is appropriate for improving predictability of your model. Before making your regression model, you can take a look at some examples of polynomial feature methods given equally spaced X (X = {<em>x </em>: <em>x </em>∈ [0<em>,</em>1]}) (./Apps/polynomial.py). In order to use polynomial feature method, you need a predefined dimension. Accordingly, the report should suggest the dimensions of polynomial feature that best fit this dataset and explain why you chose it. The best dimension can be demonstrated by showing average mean squared error of the entire dataset and its standard deviation. Also, you visualize training and testing data and its fitted line together. (./Apps/result (i).png)

The report includes an theoretical background for linear regression, a description of the model you’ve written and average root mean squared error and several plots within 1 page (Please write a report concisely). Also, you fill out the code in the attached python file completely.

<ol>

 <li>Data</li>

</ol>

The provided data is generated by specific polynomial equation, but it is not released for students. The number of datasets is 10 and each dataset consists of 30 training data and 10 test data. In this assignment, the regression should be trained by only one of datasets. After trained your model, you compare real ’y’ values to fitted values in terms of mean squared error(MSE) (By default, there is no need to consider how to manipulate dataset, you just run ./linear regression.py).

<ul>

 <li>The individual dataset has 30 training data and 10 test data.</li>

 <li>This data comes from a specific polynomial but it is not release.</li>

 <li>When you train and evaluate the model, you shoud use the same number of training and test data.</li>

</ul>

(There will be no problem if you use the given (data import) module).

<ol start="2">

 <li>Implementation</li>

</ol>

This code should be written using the ’Numpy’ package. Not allowed to use other packages. (Scipy, Tensorflow, pytorch and etc.) You write down least square method (’fit’ method) in (./Apps/linear regressor.py) and (./Apps/ridge regressor.py) You can also manipulate the dimensions of polynomial features (’feature dimension’ variable in ./linear regression.py)

1

<ol start="3">

 <li>Question

  <ol>

   <li>Write down the ordinary least squares estimator for ”weights” and its setting</li>

   <li>Plot the train, test data and fitted line in any dataset. and explain why you choose the dimensionality offeatures with respect to data and your model.</li>

   <li>Write down the best average MSE and its deviation when you consider a total dataset.</li>

   <li>If you set a 9 dimensionality of features, what behavior of this model have in this dataset. Also, plot onegraph among this dataset. Compare this model to the model you consider the best in terms of average MSE. and explain your opinion when you apply linear regression method to other dataset.</li>

  </ol></li>

</ol>