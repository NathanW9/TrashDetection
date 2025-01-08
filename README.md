# TrashDetection
Machine Learn - Convolutional Neural Network

Waste Classification

This Project Focusses on the multi classification of household trash items. It aims to create a CNN to predict what type of trash something is and classify the image into the respective category.

Data is from Kaggle

Used Data Augmentation to create more images

The Model:
Conv2D Layer 1: Conv2D(32, (3, 3))

MaxPooling2D Layer 1: MaxPooling2D(pool_size=(2, 2))

Conv2D Layer 2: Conv2D(64, (3, 3))

MaxPooling2D Layer 2: MaxPooling2D(pool_size=(2, 2))

Conv2D Layer 3: Conv2D(128, (3, 3))

MaxPooling2D Layer 3: MaxPooling2D(pool_size=(2, 2))

Flatten Layer: Flatten()

Dense Layer 1: Dense(128)

Output Layer: Dense(9, activation='softmax')

Results:
Training Accuaracy - 73%

Cross Validation Accuracy - 52%

Found new data set for test set:

Test Accuarcy - 26%
