This repository contains the solutions to the exercises from the course "Deep Learning For Computer Vision" offered by the Chair of Computer Vision at the Technical University of Munich. The first installment of this course is being offered this summer semester, 2017. 
The assignments are motivated and build on the Stanford CS231n course assignments.

First Exercise:

1. The first sub-exercise asked us to implement a softmax classifier on the CIFAR-10 dataset. The accuracy was not impressive of course, with the model being a plain-vanilla Softmax classifier. By tweaking the hyperparameters like learning rate and regularization constant, I managed to achieve a test-set accuracy of ~40%.

2. I loved the second sub-exercise the most, since this was the first time I got to try out a Neural Network on a real world dataset. The test-set accuracy improved from 40% to ~50%. I used a little trick to deploy a LeakyReLU (with an alpha of 0.01) instead of a normal ReLU activation unit.

3. Third exercise was probably the simplest of all; the features learned from the previous two sub-exercises were extracted and used to get a softmax model which performs best on the test set. Accuracy on test-set ~62%.
