# Driver-Drowsiness-Detection
Drowsiness Detection System using EfficientNet and PyTorch. This project implements a deep learning model to classify facial images for signs of drowsiness. Ideal for applications in driver safety and fatigue monitoring

Project Overview
The system is designed to detect signs of drowsiness in individuals, which can be crucial for applications such as driver safety monitoring. The model is trained on a dataset of facial images and can distinguish between different states that indicate drowsiness.
Key Features:

Utilizes EfficientNet-B0 architecture
Implements data augmentation for improved model generalization
Achieves high accuracy on test set (99.31%)
Includes visualization of training/validation curves and confusion matrix

Dataset
The dataset used for this project is structured as follows:

Training set: 2467 images
Test set: 433 images

Classes:

Open Eyes
Closed Eyes
Yawning
No Yawning

Model Architecture
The project uses a pre-trained EfficientNet-B0 model, fine-tuned for our specific classification task.
Training Process

Number of epochs: 30
Optimizer: Adam
Learning rate scheduler: ReduceLROnPlateau
Data augmentation techniques: Random resized crop, horizontal flip, rotation, and color jitter

Results

Test Accuracy: 99.31%
Detailed performance metrics for each class are provided in the classification report.


Future Work

Deploy the model for real-time drowsiness detection using a webcam feed
Experiment with other EfficientNet variants or architectures
Collect and incorporate more diverse data to improve model robustness
