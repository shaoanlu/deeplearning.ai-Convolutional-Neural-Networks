# deeplearning.ai-Foundations-of-Convolutional-Neural-Networks
Foundations of Convolutional Neural Networks, deeplearning.ai coursera course

## Week 1

Introduction to Convolution, pooling and paddnig.

1. Familiar formula: conv layer output size = (n + 2*p - k)/s + 1

2. Number of params in ten 3x3x3 filtres: (3x3x3 + 1[bais]) x 10 = 280

**Assignment 1:** Implement conv layer in numpy (forward/backward)

**Assignment 2:** Intro. to TensoeFlow

## Week 2

1. ResNet
 - Residual block: [image to be updated]
 
 - Why it works? Skup-connection make NNs easy to laern. Prevent gradient vanishing.

2. Inception
 - Bottleneck layer: Apply 1x1 conv to shrink channle size
 
 - Concatenate outptu of diffeernt conv routes


**Assignment 1: ** Intro. to Keras
 - Input(shape=...) => Conv2D/BN/ReLU => model=Model(input, output) => mdoel.compile(...) => model.fit(...)

**Assignmnet 2: ** ResNet50
 - convolutoin block: A bolck that contains Conv2D stride2 to reduce dimnesion
 
 - identity bolck: Con2B/BN/ReLU => Conv2D/BN => Add => ReLU
  
## Week 3

## Week 4
