# Convolutional Neural Networks with Fashion MNIST


## Overview
This project involves training and validating convolutional neural networks (CNNs) using the Fashion MNIST dataset. The primary objective is to gain hands-on experience with CNN models, focusing on different architectural variants to enhance performance. This experience serves as foundational knowledge for more complex assignments.

## Key Features
- **Fashion MNIST Dataset**: Utilizes 60k training and 10k test grayscale images across ten clothing categories.
- **CNN Variants**: Develops five model variants, each differing by one architectural feature to study their impact on performance.
  - Baseline (LeNet-5): Modified to accommodate 28x28 input images, uses max pooling and ReLU activation.
  - Variant 1 (3x3 Kernel): Uses smaller kernels in convolutional layers to enhance detail capture.
  - Variant 2 (Leaky ReLU): Incorporates Leaky ReLU to address the dying ReLU problem.
  - Variant 3 (Dropout): Adds dropout regularization to improve model generalization.
  - Variant 4 (Average Pooling): Switches from max to average pooling to smooth feature representations.
- **Performance Evaluation**: Evaluates models using a validation set, with extensive testing including a test set performance comparison.

## Results
Detailed performance metrics, including accuracy and loss graphs for all models, are included in the project report. Insights into architectural impacts and data augmentation effects on model robustness are discussed.

## Software and Installation
- **Python 3.6+**: Recommended for all development and testing.
- **PyTorch**: Primary framework used for model development.
- **CUDA GPU**: If available, enables significant speed-up in model training.

## Installation
Clone the repository to your local machine:
git clone [[https://github.com/aalexa201222/Voxel-based-3D-reconstruction.git](https://github.com/aalexa201222/Convolutional-neural-networks-CV4)](https://github.com/aalexa201222/Convolutional-neural-networks-CV4)

## Contributors
[Andreas Alexandrou](https://www.linkedin.com/in/andreas-alexandrou-056528242) <br />
Sotiris Zenios
