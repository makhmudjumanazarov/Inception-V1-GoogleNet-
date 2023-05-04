# Building InceptionV1(GoogLeNet) model using Tensorflow(TF) from scratch

### Building an InceptionV1(GoogLeNet)

- InceptionV1(GoogLeNet) is a deep convolutional neural network that was proposed by Szegedy et al. [1]. This network won the ImageNet Large-Scale Visual Recognition Challenge 2014 (ILSVRC-2014) where 92.3% classification performance was achieved. In particular, this model was designed in a special architecture that allows for increasing the depth and width of the network but keeping the computing resource.

- The VGG model has in total 22 layers and it is composed of 9 Inception blocks. 

- Although the InceptionV1(GoogLeNet) is complicated to implement, the parameter number of the whole model is not large. The Dense layers always take a majority of parameters. Besides, the appearance of the global average pooling layers helps to reduce significantly the parameter number, thus reducing the computational complexity of the model.

- The parameter number of this model is 6x smaller than the Alexnet model and much smaller than the VGG model. Especially, it outperforms these models...

For more information, please refer to the  <a href= "https://github.com/makhmudjumanazarov/Residual-Network-Architectures-ResNet34-and-ResNet50/blob/main/ResNet.ipynb">link below</a>,

