# Image Deblurring Project

## Overview
This project focuses on developing a system for restoring clarity in images that have been degraded due to different types of blur, such as motion blur or out-of-focus blur. The main objective is to design an image deblurring model that takes a blurry image as input and outputs a sharp, restored version while retaining the original structure and texture.

## Models Explored
- **U-Net**
- **Generative Adversarial Networks (GANs)**
- **Fine-tuned VGG16**
- **Convolutional Autoencoder (CAE)**

## Dataset
The project uses a subset of the **CelebA** dataset, consisting of:
- 8,000 images for training
- 2,000 images for testing

## Requirements
- TensorFlow
- Keras
- NumPy
- Matplotlib (for visualization)
- GPU support (recommended for faster training)

## Results
The **Convolutional Autoencoder (CAE)** model achieved the best results:

- **PSNR**: 26.11  
- **SSIM**: 0.7719

