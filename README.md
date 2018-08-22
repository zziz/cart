# cart
Classification and Regression Trees (CART) in python from scratch.   
Yields same result as scikit-learn CART.   
```
Classification Tree
 if X[2] <= 2.45
    then {value: 0, samples: 35}
    else if X[2] <= 4.75
        then if X[3] <= 1.65
            then {value: 1, samples: 34}
            else {value: 2, samples: 1}
        else if X[2] <= 5.15
            then {value: 2, samples: 16}
            else {value: 2, samples: 26}
This Classification Tree Prediction Accuracy:    0.9736842105263158
Sklearn Library Tree Prediction Accuracy:        0.9736842105263158


Regression Tree
 if X[0] <= 3.13275045531
    then if X[0] <= 0.513901088514
        then {value: 0.0523606779563, samples: 11}
        else {value: 0.713825681714, samples: 40}
    else if X[0] <= 3.85022857897
        then {value: -0.451902639773, samples: 14}
        else {value: -0.868642556986, samples: 15}
This Regression Tree Prediction:            [-0.86864256]
Sklearn Library Regression Tree Prediction: [-0.86864256]
```
