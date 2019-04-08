# CIFAR-10-Image-Classification-using-CNN-in-TensorFlow
Training a convolutional neural network using TensorFlow-GPU

CIFAR-10 dataset is a datasaet that has 10 different classes to train neural networks on for object detection.
![image](https://user-images.githubusercontent.com/35174083/55754636-269dbf80-5a1b-11e9-9a69-1a769dc30b8f.png)

## Data
The dataset is available [Here.](https://www.cs.toronto.edu/~kriz/cifar.html). It is developed by the CS department at University of Torronto.

## Analysis Performed
### Objective
Perform image classification using CNN in tensorflow.

### Approach
Using weights, bias and the classes of images as input train a convolutional neural network to classify images. Use different activation functions to visualize the changes in model performance.

### Steps
1. Load the dataset.
2. Develop helper functions for dealing with data.
3. Create a TensorFlow model for the convolutional neural network.

### Insight
Here is the sample code for loss function and the optimizer.

![image](https://user-images.githubusercontent.com/35174083/55756236-08d25980-5a1f-11e9-8064-6404de1b0c35.png)

Performance:

![image](https://user-images.githubusercontent.com/35174083/55756281-269fbe80-5a1f-11e9-9aa6-2545ddf3b4ba.png)


### Conclusion
1. The model performs better for more number of steps.
2. For great performance thesystem needs to have higher GPU versions.
