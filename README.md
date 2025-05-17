# Latent Space Manipulation using Deep Convolution GAN (dcGAN)

## Overview
This project explores **latent space manipulation** in Generative Adversarial Networks (GANs) using a **Deep convolution GAN (dcGAN)** architecture. The goal is to control and modify the generated outputs by navigating and altering points in the latent space, conditioned on specific class labels or attributes.

Latent space manipulation enables:
- Generating diverse samples conditioned on input attributes.
- Smooth interpolation between different generated outputs.
- Targeted editing of generated images by tweaking latent vectors.

## Features
- Implementation of a dc GAN model.
- Training on a labeled dataset (e.g., MNIST, CIFAR-10, or custom).
- Visualization tools for latent space traversal and interpolation.
- Conditioning on class labels to generate controlled outputs.
- Interactive manipulation of latent vectors to observe attribute changes.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/invi-bhagyesh/lateGAN.git
   cd lateGAN
