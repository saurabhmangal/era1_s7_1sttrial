```python
I have started the base from the 10th code taught in the session 7. 

Model is seperated in model.py and then called from 1st_change.ipynb

The following are the observations done by myself by executing all the 10 files taught in class. 

ERA1S7F1
1.	Target: To run the model and understand the working
2.	Results:
1.	Parameters: 6.3M
2.	Best Training Accuracy: 99.99
3.	Best Test Accuracy: 99.24
3.	Analysis:
1.	Extremely Heavy Model for such a problem
2.	Model is over-fitting
 
ERA1S7F2
1.	Target: To reduce the complexity of the model so as to reduce overfitting
2.	Results:
a.	Parameters: 1.94M
b.	Best Training Accuracy: 99.52
c.	Best Test Accuracy: 98.83
3.	Analysis:
a.	Little less complex model 
b.	Model is still over-fitting
c.	Test accuracy reduced further

ERA1S7F3
1.	Target: To reduce the complexity of the model so as to reduce overfitting
2.	Results:
a.	Parameters: 10,790
b.	Best Training Accuracy: 99.1
c.	Best Test Accuracy: 98.85
3.	Analysis:
a.	Comparatively very light model  
b.	Epoch 0 accuracy is very less.
c.	Comparatively Good Model
d.	Does not have overfitting

ERA1S7F4
1.	Target: To increase the accuracy of train and test by introducing batch network
2.	Results:
a.	Parameters: 10,970
b.	Best Training Accuracy: 99.91
c.	Best Test Accuracy: 98.18
3.	Analysis:
a.	Same model with batch normalization at each layer
b.	Epoch 0 starts with comparatively high train accuracy than the of F3.
c.	Model starts seeing overfitting/
d.	Going further, will increase the difference between train and test.

ERA1S7F5
1.	Target: Introducing the regularization parameter i.e. dropout to decrease overfitting. Behaving like God over here right now. Only suitable for MNIST data. For other complex data. Dropout has to be less and at every layer level. 
2.	Results:
a.	Parameters: 10,970
b.	Best Training Accuracy: 99.44
c.	Best Test Accuracy: 99.20
3.	Analysis:
a.	Model now has batch normalization and dropout.
b.	Model parameters will remain same as before. 
c.	Very less overfitting. However, need to increase the test accuracy. 

ERA1S7F6(a)
1.	Target: Introducing the global average pooling in the last layer in order to increase the accuracy.   
2.	Results:
a.	Parameters: 6,070
b.	Best Training Accuracy: 98.74
c.	Best Test Accuracy: 98.66
3.	Analysis:
a.	Model now has batch normalization, dropout, and global average pooling.
b.	Drastic Reduction in Model parameters from before.
c.	Very less overfitting and accuracy has further decreased. Not to be compared with previous model as the number of parameters has decreased drastically. 

ERA1S7F6(b)
4.	Target: Introducing the adaptive average pooling in the last layer in order to increase the accuracy.   
5.	Results:
a.	Parameters: 6,070
b.	Best Training Accuracy: 98.68
c.	Best Test Accuracy: 98.59
6.	Analysis:
a.	Model now has batch normalization and dropout and adaptive average pooling. 
b.	Little reduction in time and overfitting. However, need to increase overall accuracy. 

ERA1S7F7
1.	Target: increasing number of parameters by increasing the layers.    
2.	Results:
a.	Parameters: 11,994
b.	Best Training Accuracy: 99.21
c.	Best Test Accuracy: 98.40
3.	Analysis:
a.	Increasing the number of parameters have increased the accuracy of train and test. However, overfitting has again occurred. This would be because of a certain layer causing the same.

ERA1S7F8
1.	Target: Changing the maxpooling layer 
2.	Results:
a.	Parameters: 13,808
b.	Best Training Accuracy: 99.21
c.	Best Test Accuracy: 98.40
3.	Analysis:
a.	Test Accuracy is more than Train accuracy in most of the epochs. 
b.	For Epoch 15, was able to touch 99.4 mark for test accuracy and train accuracy is 99.25. 
c.	However, the accuracy has just touch 99.94 mark. It needs to be consistent. 
ERA1S7F9
1.	Target: Changing the maxpooling layer 
2.	Results:
a.	Parameters: 13,808
b.	Best Training Accuracy: 99.21
c.	Best Test Accuracy: 99.40
3.	Analysis:
a.	Test Accuracy is more than Train accuracy in most of the epochs. 
b.	For Epoch 15, was able to touch 99.4 mark for test accuracy and train accuracy is 99.25. 
c.	However, the accuracy has just touch 99.94 mark. It needs to be consistent. 
ERA1S7F9
1.	Target: Augmenting the image to have consistency in higher accuracy
2.	Results:
a.	Parameters: 13,808
b.	Best Training Accuracy: 99.04
c.	Best Test Accuracy: 99.49  (16th Epoch)
3.	Analysis:
a.	Train accuracy is less than Test Accuracy and Test accuracy has reached more than 99.4. This has happened as we have made the train data tougher to train.  
b.	Test accuracy occurred more than once greater than for first 20  Epochs.
ERA1S7F10
1.	Target: Using step wise learning rate to train the model in a better way.
2.	Results:
a.	Parameters: 13,808
b.	Best Training Accuracy: 99.04
c.	Best Test Accuracy: 98.48 (15th Epoch)
3.	Analysis:
a.	Test Accuracy is more than Train accuracy in most of the epochs. 
b.	Consistent 99.4 test accuracy. 
--------------------------------------------------------------------------------------------------------------------------------------

Coming back to the assignment:
1st change that was done is to reduce the number of epochs to 15. 
2nd change is to change the skeleton of the convolution network. 

Target:
    1. In order to reduce the number of parameters change the skeleton of the convolution network
    2. I have used two maxpooling in order to achieve less number of parameters with more receptive field in the end.
    
Resut:
    Train Accuracy: 98.84
    Test Accuracy: 99.25
        
Analysis:
    Total number of parameters: 8,108
    The accuracy has been reduced to 99.25 and it is inconsistent
    
    


```
