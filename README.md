# RetinaMNIST Disease Classification with MONAI Models

## Motivation

## Previous Work

## Objective 

## Methods
### Dataset
The model used in this analysis is the RetinaMNIST dataset. It is structured as follows:

Split - 1,080/120/400 (1,600 total)
- Train/Validation/Test
  
Image size - 3 x 28 x 28
- 3 → RGB
- 28 x 28 → Image Dimensions
  
Task - Original Regression (5)
- Disease Classification Scale of 1-5

### Proposed Pipeline

<img src="./images/proposed_pipeline.png" alt="Alt text" width="650" height="400"/>

### Models
**SimpleNet**

A lightweight neural network framework or architecture used for educational purposes or as a starting point for small-scale machine learning projects. It’s designed to be simple to understand and easy to implement, making it ideal for learning about the basics of neural networks, training algorithms, and deep learning. 

![Alt text](./images/simplenet_architecture.png)

**DenseNet**

A deep learning architecture that connects each layer to every other layer in a dense, direct fashion. In other words, each layer receives input from all previous layers and passes its own feature maps to all subsequent layers.

![Alt text](./images/densenet_architecture.png)

Variations:
- DenseNet121 - 121 layers
- DenseNet201 - 201 layers

**ResNet**

A deep learning architecture designed to address the challenges of training very deep neural networks. It introduces the concept of residual learning, which helps mitigate the problems of vanishing gradients and degradation of accuracy as the network depth increases. Instead of directly learning the mapping of input to output, ResNet layers learn the residual (or difference) between the input and the desired output. This allows the network to focus on learning incremental changes rather than learning the entire transformation.

![Alt text](./images/resnet_architecture.png)

Variations:
- HighResNet - enhances ResNet by focusing on maintaining higher resolution features to improve spatial accuracy, especially for tasks like segmentation.
- SEResNet50 - improves ResNet by adding the Squeeze-and-Excitation module to improve channel-wise feature selection and enhance the network's ability to focus on the most relevant features.

## Results
### Performance Comparison

### Example Predictions

### Saliency

## Limitations
