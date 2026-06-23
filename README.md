# CelebA Face Generation using GAN

## Overview

This project implements a Basic Generative Adversarial Network (GAN) to generate realistic human face images using the CelebA dataset. The GAN consists of two neural networks—a Generator and a Discriminator—that compete against each other to learn and create synthetic facial images.

## Features

* Trained on the CelebA face dataset
* Generates realistic celebrity face images
* Implemented using PyTorch/TensorFlow
* Demonstrates adversarial learning concepts

## Dataset

The model is trained on the CelebA (CelebFaces Attributes) dataset, which contains over 200,000 celebrity face images with various attributes.

## Model Architecture

* **Generator:** Creates fake face images from random noise vectors.
* **Discriminator:** Distinguishes between real and generated images.
* Both networks are trained simultaneously to improve image quality.

## Results

The trained GAN successfully learns facial features and generates realistic-looking face images after multiple training epochs.

## Technologies Used

* Python
* PyTorch/TensorFlow
* NumPy
* Matplotlib

## Future Improvements

* Implement DCGAN for better image quality
* Train for more epochs
* Add conditional image generation
* Experiment with advanced GAN architectures

## Author

Advait Jadhav
Artificial Intelligence & Machine Learning Student
