# VAE Training Script with NASNet

![GitHub contributors](https://img.shields.io/github/contributors/oblivisheee/VAE-NASNet)
![GitHub last commit](https://img.shields.io/github/last-commit/oblivisheee/VAE-NASNet)
![GitHub repo size](https://img.shields.io/github/repo-size/oblivisheee/VAE-NASNet)

This script is designed for training a Variational Autoencoder (VAE) using the NASNetLarge neural network architecture. It is currently in alpha version, and improvements are being actively worked on.

## Authors
- [oblivisheee](https://github.com/oblivisheee)
- [Integrio Team](https://github.com/Integrio-Team)

## Usage
1. Copy this script to your Google Drive and customize it as needed for your specific project.
2. Ensure you have the required libraries installed by running the provided installation commands.
3. Adjust the script's parameters as needed, such as input image dimensions, training data paths, and hyperparameters.
4. Run the script in your preferred environment (e.g., Google Colab) to train the VAE model.

## Installation
You can install the required dependencies using the following commands:

```python
!pip install safetensors
!pip install matplotlib
```

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
