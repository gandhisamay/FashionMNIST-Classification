# FashionMNIST-Classification
The FashionMNIST dataset contains images of various things like jeans, sneakers, shoes,... which need to be classified into their respective types. Each type is associated with their one-hot encoded number so that it can be used in our neural network for processing. 

# Overview
I made a convulational neural network to classify those images into various types using Pytorch library. In this model I used the kernel of size 3 in both the convualtional layers and also applied the padding so that size of the image does not shrink due to convulational layer. Max Pooling layers have been used by me in this model with a stride of two and due to this the image height and width halves with every pooling layers.

The model has been trained using a gpu provided by [**Google Colab**](https://colab.research.google.com/notebooks/intro.ipynb#recent=true)

# Accuracy 
The model gives a high accuracy of **94.61 %** and **91.09 %** on the test dataset. I changed the learning rate many times while training the model to achieve this accuracy quickly.

![](https://github.com/gandhisamay/FashionMNIST-Classification/blob/main/FashionMNISTloss.png)

## License
Everyone is free to use to use the complete model or a part of it the model or part of it as per their choice

