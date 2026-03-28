# Week 08 — GAN Latent Space Exploration

## Objective
To generate artistic images using a GAN generator by exploring the latent space and observing how different latent vectors affect outputs.

## Approach
- Implemented a DCGAN-style generator
- Initialized generator weights
- Generated images using random latent vectors
- Performed interpolation between two latent vectors
- Visualized outputs using grids

## Model Details
- Architecture: DCGAN Generator
- Latent Dimension: 100
- Activation: ReLU (hidden), Tanh (output)

## Training Details
- No training performed
- Generator initialized with random weights

## Outputs
- Random generated image samples
- Interpolated latent space transitions

## Files

### Dataset
- dataset/gan_random_samples.png
- dataset/gan_interpolation.png

### Notebook
- notebook/CSET419_GenAI_Lab8.ipynb

### Report
- report/E23CSEU1343-Kabir-CSET419-Lab8.pdf

## Conclusion
The generator produces abstract outputs due to lack of training. However, interpolation demonstrates smooth transitions in latent space, highlighting how GANs generate diverse outputs from different vectors.
