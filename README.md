# Bayesian
Naive Bayes classifier and Bayesian network classifier C++ implementation

https://en.wikipedia.org/wiki/Naive_Bayes_classifier
https://en.wikipedia.org/wiki/Bayesian_network

Usage:

bayesian [training data file] [input test file] [configuration file] [method]

method :

0 : naive bayesian
1 : bayesian network


Example:

bayesian data.txt test.txt cfg.txt 0




Training & Test data format:

[ attribute 1 of data 1 ]  [ attribute 2 of data 1 ] ........ [ result of data 1 ]
[ attribute 1 of data 2 ]  [ attribute 2 of data 2 ] ........ [ result of data 2 ]
[ attribute 1 of data 3 ]  [ attribute 2 of data 3 ] ........ [ result of data 3 ]


Configuration file format:

[number of training instance] [number of test instance]  [number of attributes]

[ attribute 1 is discrete(0) or continunous(1) ]   [ attribute 2 is discrete(0) or continunous(1) ]  ......

[number of types for attributes 1]   [number of types for attributes 2 ]  .......[ number of classes for prediction result ]  //P.S. For continuous data, the number of types for attributes should be 2.

