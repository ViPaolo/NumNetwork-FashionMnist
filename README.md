# NumNetwork-FashionMnist

A neural network implementation for classifying images from the Fashion MNIST dataset.
This model uses two layers (and can be expanded) with ReLU and softmax activations, and employs functions for forward and backward propagation, parameter updates, and training with gradient descent.

The objective of this project was to learn how to structure a simple neural network without the use of Pytorch / Keras or other ML libraries. 

The results were satisfying for a learning project. With just a 2 hidden layer network in the dataset reached around 84% of accurary in the test set with 1000 iterations.  
Adding a new layer provided an increase in accuracy from 78% to 84% in the test set with the same parameters and iteration. 


### Data source
The test and train data are from the Fashion MNIST dataset found on kaggle [here](https://www.kaggle.com/datasets/zalando-research/fashionmnist). 
To comply with Github's policy on large files, I divided the train dataset in 2 pieces, which are merged instantly.


### Dependencies and download


- `Numpy` v. 1.26.3
- `Pandas` v. 2.1.4


You can extract this repo as a zip file, extract it and change the directory path to your actual path for running it.

### Licence
This software is under the GNU GPLv3 license. Read LICENSE file for details. 
