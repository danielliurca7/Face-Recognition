# Face-Recognition
Convolutional neural network built for recognizing faces in images and identifying the person. The data set used is Labeled faces in the Wild.

## The network structure

Layer Name | Type | Filter Size / Stride
-----------| ---- | --------------------
Conv1 | convolution | 5x5 / 1
Conv2 | convolution | 5x5 / 1
Pool1 | max pooling | 2x2 / 2
Dropout1 | dropout(25%)
Conv3 | convolution | 3x3 / 1
Conv4 | convolution | 3x3 / 1
Pool2 | max pooling | 2x2 / 2
Dropout2 | dropout(25%)
Dense1 | fully connected
Dropout3 | dropout(40%)
Dense2 | fully connected
Dropout4 | dropout(40%)
Softmax | softmax
