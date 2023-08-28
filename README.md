# VAE Training with NASNet

![GitHub contributors](https://img.shields.io/github/contributors/Integrio-Team/vae-training-nasnet)
![GitHub last commit](https://img.shields.io/github/last-commit/Integrio-Team/vae-training-nasnet)
![GitHub repo size](https://img.shields.io/github/repo-size/Integrio-Team/vae-training-nasnet)

This repository contains a script for training a Variational Autoencoder (VAE) using the NASNetLarge neural network architecture. The script is designed for flexibility and customization, making it suitable for various image generation tasks.

## Authors
- [Integrio Team](https://github.com/Integrio-Team)
- [oblivisheee](https://github.com/oblivisheee)

## Usage
1. Clone this repository to your local machine or your preferred environment.
2. Ensure you have the required dependencies installed by following the installation instructions.
3. Customize the script to meet your specific project requirements, such as input image dimensions, dataset paths, and model hyperparameters.
4. Run the script to train your VAE model.

## Installation
You can install the required dependencies using the following commands:

```python
!pip install safetensors
!pip install matplotlib


# NASNet Model
This script uses the NASNetLarge model for feature extraction. You can choose to load weights from either ImageNet or provide custom weights.

# Model Configuration and Compilation
  Configure the VAE model with various hyperparameters, including latent space size, filter sizes, and regularization parameters.
  The model is compiled using the Adam optimizer.
# Dataset Configuration
  You should specify the path to your training and validation data directories.
  Data augmentation options such as rotation, shift, shear, zoom, and flip are available for data preprocessing.
# Training
  The script supports training for a specified number of epochs with a learning rate schedule.
  You can choose to save model checkpoints at the end of each epoch.
  Training progress is recorded, including loss values and learning rate adjustments.
# Testing
  After training, you can use the trained model to generate images by providing an input image path.
  The generated image will be displayed alongside the original image for visual comparison.
*Feel free to customize and extend this script to suit your specific VAE training needs.*
