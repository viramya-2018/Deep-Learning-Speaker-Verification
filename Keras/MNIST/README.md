# MNIST Dataset

[Keras.io](https://keras.io/) has been used for this purpose.

### Following steps have been implemented:
- Dataset has been reshaped
- Dataset has been normalized between [0, 1]
- Model has been compiled and trained on **`X_train`** and **`Y_train`**
- Model has been tested on **`X_test`** and **`Y_test`**

### Following is the model description
- 2x **`convulation layer`** with following configuration applied:
  - **`32`** filters
  - **`3 x 3`** window size
  - **`1 x 1`** window stride
  - **`ReLU`** activation function
- **`Max-pooling`** layer of **`2 x 2`**
- **`Flatten`** and fed to **`Dense`** layer

### Further reading
> [CS231n: Convolutional Neural Networks for Visual Recognition](http://cs231n.stanford.edu/)
