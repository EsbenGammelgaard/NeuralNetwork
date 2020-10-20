# Digit recongnition using Neural Network in RStudio, Python & SAS

## Database
The database used in all three examples is the MNIST database of handwritten digits. The database is created by: Yann LeCun, Courant Institute, NYU, Corinna Cortes, Google Labs, New York, and Christopher J.C. Burges, Microsoft Research, Redmond. The database is found at http://yann.lecun.com/exdb/mnist/.

#### CSV version
In these examples the more conviniet .CSV file created by Joseph Redmon is used. It can be downloadet from: https://pjreddie.com/media/files/mnist_train.csv.

## Experiment setup
The goal is to use the NN algorithm to classify the digits in the 10 different classes ranging from 0 to 9. The split between training and test is 50/50. Amount of observations included is 1000 training and 1000 test, with the K-value of 1.

## RStudio Results
#### Confusion Matrix

| Prediction / Reference | 0  | 1  | 2  | 3  | 4  | 5  | 6  | 7  | 8  | 9  |
|------------------------|----|----|----|----|----|----|----|----|----|----|
| 0                      | 87 | 0  | 1  | 2  | 0  | 2  | 1  | 0  | 0  | 0  |
| 1                      | 0  | 88 | 2  | 1  | 0  | 0  | 1  | 2  | 10 | 0  |
| 2                      | 3  | 3  | 74 | 1  | 2  | 4  | 2  | 5  | 5  | 0  |
| 3                      | 0  | 3  | 13 | 61 | 2  | 9  | 2  | 2  | 4  | 2  |
| 4                      | 0  | 1  | 3  | 0  | 89 | 4  | 5  | 0  | 0  | 7  |
| 5                      | 2  | 0  | 4  | 2  | 0  | 72 | 3  | 3  | 3  | 0  |
| 6                      | 3  | 2  | 3  | 0  | 4  | 3  | 90 | 0  | 1  | 0  |
| 7                      | 1  | 1  | 0  | 1  | 3  | 2  | 2  | 91 | 1  | 5  |
| 8                      | 2  | 1  | 2  | 3  | 3  | 9  | 1  | 1  | 61 | 2  |
| 9                      | 2  | 0  | 0  | 2  | 14 | 0  | 1  | 12 | 0  | 79 |

#### Accuracy 
The accuracy aqired was 0.79
#### Run Time
The run time for the prediciton inlducing both training and testing was 8.86 seconds. 

## Python Results
#### Confusion Matrix
| Prediction / Reference |

#### Accuracy 
The accuracy aqired was 
#### Run Time
The run time for the prediciton inlducing both training and testing was  seconds. 

## SAS Results
#### Confusion Matrix
| Prediction / Reference |

#### Accuracy 
The accuracy aqired was 
#### Run Time
The run time for the prediciton inlducing both training and testing was  seconds. 

##  Results Conclusions



