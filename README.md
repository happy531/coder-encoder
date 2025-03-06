# Coder-Encoder Dogs

## Project objective
Develop a procedure consisting of preprocessing and an autocoder model with restoration of missing parts of animal images (inpainting).

## Overview

The Coder-Encoder project is a machine learning application designed to work with image datasets, specifically focusing on image reconstruction using autoencoders. The project involves loading and preprocessing images, generating masks, and training an autoencoder to reconstruct the original images from the masked versions.

## Problem
To develop a model based on an autocoder with reconstruction of missing image fragments (inpainting) of a dog with the best quality in the perception of these images by human observers.

The autocoder, on input, accepts an image with a single mask, and on output, generates an image with the mask area filled in so that the resulting image is as consistent and complete as possible.

## Features

- Load and preprocess image datasets
- Generate random masks for images
- Train an autoencoder for image reconstruction
- Validate the reconstruction performance

## Dataset

The dataset used in this project is from Kaggle. You can find the dataset [here](https://www.kaggle.com/datasets/wutheringwang/dog-face-recognition).

## Installation

To install the required dependencies, run:

```bash
pip install -r requirements.txt
```
