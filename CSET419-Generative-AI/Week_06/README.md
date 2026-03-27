# Week 06 — Pix2Pix (Image-to-Image Translation)

## Objective
To implement a Pix2Pix model using a Conditional GAN for image-to-image translation.

## Approach
- Created paired dataset (edge → image) using Canny edge detection
- Implemented U-Net based Generator
- Implemented PatchGAN Discriminator
- Trained model using adversarial + L1 loss

## Model Components
- Generator: U-Net architecture with skip connections
- Discriminator: PatchGAN (local patch-based classification)

## Training Details
- Dataset: CIFAR-10
- Image Size: 64x64
- Epochs: 10
- Loss Functions:
  - GAN Loss (BCEWithLogitsLoss)
  - L1 Loss

## Outputs
- Generated images from edge inputs
- Loss values during training

## Files

### Dataset
- dataset/pix2pix_results.png
- dataset/pix2pix_generator.pth

### Notebook
- notebook/CSET419_GenAI_Lab6.ipynb

### Report
- report/E23CSEU1343-Kabir-CSET419-Lab6.pdf

## Conclusion
Pix2Pix successfully learns a mapping from edge images to real images. The generated outputs are structurally aligned with inputs but may appear blurry due to limited training.
