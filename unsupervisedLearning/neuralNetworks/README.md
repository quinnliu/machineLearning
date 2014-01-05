Neural Networks
===============

<h2>How to use this code:</h2>

<h2>Neural Network Review</h2>
  - Why a new non-linear hypotheses?
    + The problem with linear & logistic regression is that when we have a large # of features say 100 the # of feature combinations that must be computed using linear or logisitic regression gets RIDICKULOUSLY large. For example when we have 100 features and we decide to create a decision boundary that is cubic then
    the # of feature combinations is about 170,000 starting with x_1 * x_2 * x_3, (x_1)^2 * x_2, ... you can image there being
    about 170,000 combinations of the terms x_1, x_2, ..., x_100.

    + For problems like computer vision, the # of features is very large. For example a 50 x 50 pixel greyscale image will have 
    2500 pixels. And then if trained linear or logistic regression with all pixel to pixel relationships then we would have 2500
    features x 2500 other features giving us 3 million plus features which is WAY TOO MUCH.

  - Model Representation 