# Convolutional-Neural-Networks-with-CIFAR10-data-set
To classify the test images by training a convolutional neural network using training images and labels
In this assignment,I learnt how to train a convolutional neural network for an image classification problem on a moderate, popular dataset, titled CIFAR-10.

Preparation:We  will  use the popular  CIFAR-10  dataset  for  this  assignment. This dataset consists  of6000032x32coloredimages representing 10 different  image classes.The  training and  testing  sets  are  fixed:  there  are  50000 trainingimages  and 10000  test  imageswithcorresponding  labels.To  prepare  for  this  assignment:  first  you will  need  to  download  the CIFAR-10  dataset  which  is  not  included  with  this  homework  assignment. The  official  website fordataset isgiven below:http://www.cs.toronto.edu/~kriz/cifar.html Please  use  above  website  to  download the  original  dataset.  The  code  you  will  prepare  should assume  that  dataset  files  are  located  in a sub  folder named  as “cifar-10-batches-py”.Do  not change the 

Objective:We want to classifythetest images by training a convolutional neural network using trainingimages and labels. Network   

Definition:The   dataset   is   already   normalized   and shuffled so   no   further processing or modification is required.You need to build a convolutional neural network with the following properties:-Please notice that the input images are colored which means you will have three channels for the first (input) layer.-Your network will have 4 hidden layers.-1stlayer and 2ndlayer will be the convolutional layers with 64 filters in each layer using a kernel size of 5x5.-Activation functions should be chosen as Rectified Linear Units (except the output layer, see below).-Use max-pooling with a filter size of 2x2 and stride of 2.-3rdand  4thlayers  of  your  network  should  be  fully  connected  with  384  and  192  neurons respectively.-The  last  layer  (output)  should  consist  of  10  neurons  for  the  10  classes  and  use  softmax activation functions for classification.I

Goals:

1 Printclassification  accuracyon  the test  setafteryourtraining  is  done.(Python help: print("Classification accuracy on the test set:"+str(test_accuracy)))

2 Plotcross-entropyerror  curveson  your trainingand testingset  as  a function  of epochson thesame figure.How does the error change on the training set with increasing number of epochs? How does it change on the testing set? 

3 Show the coefficients  of the  first  5  filters in  the 1st and 2nd convolutional  layers as images after training is done, on a single figure as subplots.

