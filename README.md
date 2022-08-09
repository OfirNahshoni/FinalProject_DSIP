# FinalProject_DSIP
Final Project. Course: DSIP = Data Signals Information Proccessing. 3rd year Degree

This project, implemented in Python3 (notebook file), trains a logistic classifier (with accuracy of 96%), using the Gradient Descent algorithm to optimize the his accuracy. The classifier needs to decide whether the input image that he gets is fake or real picture. The program is training the classifier, from a start point of given it random coefficients vector. Then the program invokes the gardient descent on the confusion matrix to improve results, by m steps. See accuracy and cross entropy of the classifier as a function of m (number of steps in gradient descent), by this graphs:

<img width="410" alt="image" src="https://user-images.githubusercontent.com/58309185/183515520-e61507a8-6ebe-478a-a11d-9066708c1681.png">

<img width="416" alt="image" src="https://user-images.githubusercontent.com/58309185/183515583-e381e428-cb45-4ae6-9972-cfa9896eb39e.png">

To activate the program you need to download the ipynb (python notbook file) file. The start of coefficients is random choosen.
The input of the classifier is 1000 images. Training set is 750 images, 250 images.
The Gradient Step is implemented in a function called "gradientDescent(w,X,t,itter,alpha)".
This function is activated 1000 times, but it would be better to run even more steps the optimisation.

The code is well commited, so you can understand every line of code or function that were wrote.
Enjoy :-)
