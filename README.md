<h2>This is the 1st trial readme notebook of the assigment 7. The task was to get the test accuracy of 99.4 with parameters limit of 8,000 and in less than 15 Epochs. I have started the base from the 10th code taught in the session 7. </h2>

<h3>Model is seperated in model.py and then called from the main file which is in this case 1st_change.ipynb</h3>

The following are the observations done by myself by executing all the 10 files taught in class. 

<h3>ERA1S7F1</h3>
1.	Target: To run the model and understand the working
2.	Results:
&nbsp;&nbsp;a.	Parameters: 6.3M
&nbsp;&nbsp;        b.	Best Training Accuracy: 99.99
&nbsp;&nbsp;        c.	Best Test Accuracy: 99.24
3.	Analysis:
&nbsp;&nbsp;        a.	Extremely Heavy Model for such a problem
&nbsp;&nbsp;        b.	Model is over-fitting
------------------------------------------------------------------------------------------------------------------------------------------------ 
<h3>ERA1S7F2</h3>
1.	Target: To reduce the complexity of the model so as to reduce overfitting
2.	Results:
&nbsp;&nbsp;a.	Parameters: 1.94M
&nbsp;&nbsp;b.	Best Training Accuracy: 99.52
&nbsp;&nbsp;c.	Best Test Accuracy: 98.83
3.	Analysis:
&nbsp;&nbsp;a.	Little less complex model 
&nbsp;&nbsp;b.	Model is still over-fitting
&nbsp;&nbsp;c.	Test accuracy reduced further
-------------------------------------------------------------------------------------------------------------------------------------------
<h3>ERA1S7F3</h3>
1.	Target: To reduce the complexity of the model so as to reduce overfitting
2.	Results:
&nbsp;&nbsp;a.	Parameters: 10,790
&nbsp;&nbsp;b.	Best Training Accuracy: 99.1
&nbsp;&nbsp;c.	Best Test Accuracy: 98.85
3.	Analysis:
&nbsp;&nbsp;a.	Comparatively very light model  
&nbsp;&nbsp;b.	Epoch 0 accuracy is very less.
&nbsp;&nbsp;c.	Comparatively Good Model
&nbsp;&nbsp;d.	Does not have overfitting
-------------------------------------------------------------------------------------------------------------------------------------------
<h3>ERA1S7F4</h3>
1.	Target: To increase the accuracy of train and test by introducing batch network
2.	Results:
&nbsp;&nbsp;a.	Parameters: 10,970
&nbsp;&nbsp;b.	Best Training Accuracy: 99.91
&nbsp;&nbsp;c.	Best Test Accuracy: 98.18
3.	Analysis:
&nbsp;&nbsp;a.	Same model with batch normalization at each layer
&nbsp;&nbsp;b.	Epoch 0 starts with comparatively high train accuracy than the of F3.
&nbsp;&nbsp;c.	Model starts seeing overfitting/
&nbsp;&nbsp;d.	Going further, will increase the difference between train and test.
-------------------------------------------------------------------------------------------------------------------------------------------
<h3>ERA1S7F5</h3>
1.	Target: Introducing the regularization parameter i.e. dropout to decrease overfitting. Behaving like God over here right now. Only suitable for MNIST data. For other complex data. Dropout has to be less and at every layer level. 
2.	Results:
&nbsp;&nbsp;a.	Parameters: 10,970
&nbsp;&nbsp;b.	Best Training Accuracy: 99.44
&nbsp;&nbsp;c.	Best Test Accuracy: 99.20
3.	Analysis:
&nbsp;&nbsp;a.	Model now has batch normalization and dropout.
&nbsp;&nbsp;b.	Model parameters will remain same as before. 
&nbsp;&nbsp;c.	Very less overfitting. However, need to increase the test accuracy. 
-------------------------------------------------------------------------------------------------------------------------------------------
<h3>ERA1S7F6(a)</h3>
1.	Target: Introducing the global average pooling in the last layer in order to increase the accuracy.   
2.	Results:
&nbsp;&nbsp;a.	Parameters: 6,070
&nbsp;&nbsp;b.	Best Training Accuracy: 98.74
&nbsp;&nbsp;c.	Best Test Accuracy: 98.66
3.	Analysis:
&nbsp;&nbsp;a.	Model now has batch normalization, dropout, and global average pooling.
&nbsp;&nbsp;b.	Drastic Reduction in Model parameters from before.
&nbsp;&nbsp;c.	Very less overfitting and accuracy has further decreased. Not to be compared with previous model as the number of parameters has decreased drastically. 
-------------------------------------------------------------------------------------------------------------------------------------------
<h3>ERA1S7F6(b)</h3>
1.	Target: Introducing the adaptive average pooling in the last layer in order to increase the accuracy.   
2.	Results:
&nbsp;&nbsp;a.	Parameters: 6,070
&nbsp;&nbsp;b.	Best Training Accuracy: 98.68
&nbsp;&nbsp;c.	Best Test Accuracy: 98.59
3.	Analysis:
&nbsp;&nbsp;a.	Model now has batch normalization and dropout and adaptive average pooling. 
&nbsp;&nbsp;b.	Little reduction in time and overfitting. However, need to increase overall accuracy. 
-------------------------------------------------------------------------------------------------------------------------------------------
<h3>ERA1S7F7</h3>
1.	Target: increasing number of parameters by increasing the layers.    
2.	Results:
&nbsp;&nbsp;a.	Parameters: 11,994
&nbsp;&nbsp;b.	Best Training Accuracy: 99.21
&nbsp;&nbsp;c.	Best Test Accuracy: 98.40
3.	Analysis:
&nbsp;&nbsp;a.	Increasing the number of parameters have increased the accuracy of train and test. However, overfitting has again occurred. This would be because of a certain layer causing the same.
-------------------------------------------------------------------------------------------------------------------------------------------
<h3>ERA1S7F8</h3>
1.	Target: Changing the maxpooling layer 
2.	Results:
&nbsp;&nbsp;a.	Parameters: 13,808
&nbsp;&nbsp;b.	Best Training Accuracy: 99.21
&nbsp;&nbsp;c.	Best Test Accuracy: 98.40
3.	Analysis:
&nbsp;&nbsp;a.	Test Accuracy is more than Train accuracy in most of the epochs. 
&nbsp;&nbsp;b.	For Epoch 15, was able to touch 99.4 mark for test accuracy and train accuracy is 99.25. 
&nbsp;&nbsp;c.	However, the accuracy has just touch 99.94 mark. It needs to be consistent. 
-------------------------------------------------------------------------------------------------------------------------------------------
<h3>ERA1S7F9</h3>
1.	Target: Changing the maxpooling layer 
2.	Results:
&nbsp;&nbsp;a.	Parameters: 13,808
&nbsp;&nbsp;b.	Best Training Accuracy: 99.21
&nbsp;&nbsp;c.	Best Test Accuracy: 99.40
3.	Analysis:
&nbsp;&nbsp;a.	Test Accuracy is more than Train accuracy in most of the epochs. 
&nbsp;&nbsp;b.	For Epoch 15, was able to touch 99.4 mark for test accuracy and train accuracy is 99.25. 
&nbsp;&nbsp;c.	However, the accuracy has just touch 99.94 mark. It needs to be consistent. 
-------------------------------------------------------------------------------------------------------------------------------------------
<h3>ERA1S7F9</h3>
1.	Target: Augmenting the image to have consistency in higher accuracy
2.	Results:
&nbsp;&nbsp;a.	Parameters: 13,808
&nbsp;&nbsp;b.	Best Training Accuracy: 99.04
&nbsp;&nbsp;c.	Best Test Accuracy: 99.49  (16th Epoch)
3.	Analysis:
&nbsp;&nbsp;a.	Train accuracy is less than Test Accuracy and Test accuracy has reached more than 99.4. This has happened as we have made the train data tougher to train.  
&nbsp;&nbsp;b.	Test accuracy occurred more than once greater than for first 20  Epochs.
-------------------------------------------------------------------------------------------------------------------------------------------
<h3>ERA1S7F10</h3>
1.	Target: Using step wise learning rate to train the model in a better way.
2.	Results:
&nbsp;&nbsp;a.	Parameters: 13,808
&nbsp;&nbsp;b.	Best Training Accuracy: 99.04
&nbsp;&nbsp;c.	Best Test Accuracy: 98.48 (15th Epoch)
3.	Analysis:
&nbsp;&nbsp;a.	Test Accuracy is more than Train accuracy in most of the epochs. 
&nbsp;&nbsp;b.	Consistent 99.4 test accuracy. 
-------------------------------------------------------------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------------------------------------------------------------

</h2>Coming back to the assignment:</h2>
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
