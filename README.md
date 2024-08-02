# DeFungi-Images-Classification
DeFungi Image Classification
Project Overview
The DeFungi Image Classification project is an initiative to build a sophisticated image classification model using the DeFungi dataset. This dataset comprises microscopic images of superficial fungal diseases caused by yeasts, molds, and dermatophytes. The goal is to accurately classify these images into one of five predefined classes, improving the speed and accuracy of fungal disease diagnosis through automated image processing.

Data Description
Dataset: The DeFungi dataset includes 3,025 uncurated and unlabeled images, and 660 labeled images, depicting superficial fungal infections.
Data Source: Images sourced from Sony’s DSC W830 compact camera.
File Type: .jpg files
Resolution: Ranges from 640×480 pixels to 5152×3864 pixels.
Methods and Models
EfficientNetV2-S Model:

Utilizes a compound scaling method.
Optimizer: AdamW with a learning rate of 0.0001.
Epochs: 50
Achieves state-of-the-art performance in image classification tasks.
Simple CNN Model:

Three convolutional layers followed by two fully connected layers.
Optimizer: AdamW with a learning rate of 0.0001.
Epochs: 50
Effective for image classification, object detection, and segmentation tasks.
DNN Model:

Multiple layers of interconnected nodes.
Suitable for various tasks such as image recognition, speech processing, and natural language tasks.
Techniques
Data Augmentation: Techniques include resizing, cropping, flipping, affine transformations, and random erasing to enhance model robustness.
Transfer Learning: Used to improve model performance.
Results
The project demonstrated successful implementation of image classification using CNN, DNN, and EfficientNetV2-S models. The EfficientNetV2-S model showed efficiency in resource-constrained environments, while CNN and DNN provided versatility and robust performance across applications.

Conclusion
This project showcases a comprehensive approach to image classification, leveraging diverse neural network architectures to achieve accurate results in classifying superficial fungal diseases. Regular monitoring and maintenance practices are recommended to adapt the models to changing data distributions and enhance accuracy over time.

Dataset Link
DeFungi Dataset
