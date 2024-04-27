# Convolutional Neural Network (CNN) Architectures

## 1. AlexNet
- **Year**: 2012
- **Developers**: Alex Krizhevsky, Ilya Sutskever, and Geoffrey Hinton
- **Key Features**: 
  - Consists of 5 convolutional layers followed by 3 fully connected layers.
  - Uses ReLU (Rectified Linear Unit) for the non-linear operations.
  - Employs dropout and data augmentation to reduce overfitting.
  - Won the ImageNet challenge by a significant margin.

## 2. GoogleNet (Inception v1)
- **Year**: 2014
- **Developers**: A team at Google
- **Key Features**:
  - Introduced the inception module, which allows the network to choose from different kernel sizes.
  - 22 layers deep.
  - Uses 1x1 convolutions to reduce dimensionality.
  - Achieved significant improvement on the ImageNet challenge.

## 3. MobileNet
- **Year**: 2017
- **Developers**: Andrew G. Howard et al., Google
- **Key Features**:
  - Designed for mobile and embedded vision applications.
  - Uses depth-wise separable convolutions to reduce the number of parameters and computation.
  - Efficient in terms of memory and processing power.

## 4. Darknet
- **Framework** rather than a model, used primarily for YOLO (You Only Look Once).
- **Developer**: Joseph Redmon
- **Key Features**:
  - Written in C and CUDA.
  - It is fast, easy to install, and supports CPU and GPU computation.

## 5. YOLO (You Only Look Once)
- **Version**: Versions from YOLOv1 to YOLOv8
- **Developer**: Joseph Redmon, and subsequently others for newer versions.
- **Key Features**:
  - Frames object detection as a single regression problem, straight from image pixels to bounding box coordinates and class probabilities.
  - Extremely fast and suitable for real-time processing.

## 6. SSD (Single Shot Multibox Detector)
- **Year**: 2016
- **Developers**: Wei Liu et al.
- **Key Features**:
  - Utilizes a single neural network to predict bounding boxes and class probabilities for these boxes.
  - Efficient for real-time detection tasks.

## 7. ResNet (Residual Network)
- **Year**: 2015
- **Developers**: Kaiming He et al., Microsoft
- **Key Features**:
  - Introduced residual blocks with skip connections to enable training of very deep networks (up to 152 layers).
  - Significantly improved the error rates in various recognition tasks.
