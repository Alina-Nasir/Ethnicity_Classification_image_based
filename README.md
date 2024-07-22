## Ethnicity Classification on Images
### Project Overview
This project involved performing ethnicity classification on images using a convolutional neural network (CNN). The CNN was trained to classify ethnicity based on pixel data from the input images.
### CNN Architecture for Ethnicity Classification
#### Input Layer
Accepts an image with a single channel (grayscale).
#### Convolutional Layer 1
  - Filters: 16
  - Kernel Size: 3x3
  - Padding: 1
  - Activation: ReLU
  - Max Pooling: 2x2
  - Batch Normalization: Applied to the output
  - Dropout: 0.2 dropout rate
#### Convolutional Layer 2
  - Filters: 32
  - Kernel Size: 3x3
  - Activation: ReLU
  - Max Pooling: 2x2
  - Batch Normalization: Applied to the output
  - Dropout: 0.2 dropout rate
#### Convolutional Layer 3
  - Filters: 64
  - Kernel Size: 3x3
  - Activation: ReLU
  - Max Pooling: 2x2
  - Batch Normalization: Applied to the output
  - Dropout: 0.2 dropout rate
#### Convolutional Layer 4
  - Filters: 128
  - Kernel Size: 3x3
  - Activation: ReLU
  - Max Pooling: 2x2
  - Batch Normalization: Applied to the output
  - Dropout: 0.2 dropout rate
#### Flatten Layer
Flattens the output from the convolutional layers into a one-dimensional array.
#### Fully Connected Layer 1
  - Units: 128
  - Dropout: 0.5 dropout rate
#### Fully Connected Layer 2
  - Units: 256
  - Dropout: 0.5 dropout rate
#### Output Layer
  - Units: 5 (representing the number of ethnicity classes)
  - Produces the final classification scores.

By using this convolutional neural network architecture, the model was able to learn and classify ethnicity based on the pixel data of input images. The combination of convolutional layers for feature extraction, pooling layers for dimensionality reduction, and fully connected layers for classification enabled the model to achieve robust performance on the ethnicity classification task.
