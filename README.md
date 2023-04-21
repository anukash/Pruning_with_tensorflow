# Pruning_with_tensorflow
Compressing the model with help of TensorFlow pruning library 

Dataset Used :- Fashion MNIST Keras

Accuracy and size comparision of normal and pruned model can be shown below.

![comparision](https://user-images.githubusercontent.com/51228517/233687566-d0179230-5c33-4162-bf11-5a3a21ada534.png)


```diff
! Note :
```
1. I am not trying to fine tune this model as it is not the motive of this case study .
2. There is also a minute decrease in prediction time as i was only predicting one data point but when scaled up, it will create a pretty good difference.
3. Major difference was seen in the decrease in file size of model which is huge.
