# Week 05 — Image-to-Image Translation using Encoder–Decoder Network

## Objective

The objective of this laboratory experiment is to implement an encoder–decoder convolutional neural network for image reconstruction and translation using the CIFAR-10 dataset.

## Methodology

An encoder–decoder architecture was implemented using convolutional and transposed convolutional layers in PyTorch. The model was trained using L1 loss to reconstruct input images. Training performance was monitored using loss curves and qualitative visual comparisons between original and reconstructed images.

## Folder Structure

- notebook/
  - CSET419_GenAI_Lab5.ipynb — Implementation notebook  

- report/
  - E23CSEU1343-Kabir-CSET419-Lab5.pdf — Lab report  

- dataset/
  - baseline_loss_curve.png — Training loss visualization  
  - baseline_translation_results.png — Reconstruction comparison  
  - baseline_encoder_decoder.pth — Trained model weights  

- NOTES.md — Lab learning notes  

## Outcome

The encoder–decoder network successfully learned to reconstruct CIFAR-10 images, demonstrating the fundamentals of image-to-image translation and convolutional autoencoder behavior in generative modeling workflows.
