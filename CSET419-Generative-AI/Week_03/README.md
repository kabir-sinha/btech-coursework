# Week 03 — Variational Autoencoder (VAE) on MNIST

## Objective
The objective of this laboratory experiment is to implement a Variational Autoencoder (VAE) to learn the latent representation of handwritten digits and generate synthetic samples.

## Methodology
A fully connected VAE architecture consisting of encoder, latent sampling using the reparameterization trick, and decoder was implemented using PyTorch. The model was trained on the MNIST dataset and evaluated through reconstruction quality, generated samples, and latent space visualization.

## Folder Structure

- notebook/
  - CSET419_GenAI_Lab3.ipynb — Implementation notebook  

- report/
  - E23CSEU1343-Kabir-CSET419-Lab3.pdf — Lab report  

- dataset/
  - vae_loss_curve.png — Training loss plot  
  - vae_reconstructions.png — Reconstruction results  
  - vae_generated_samples.png — Generated samples  
  - vae_latent_space.png — Latent visualization  
  - vae_mnist_model.pth — Trained model  

- NOTES.md — Lab notes and observations

## Outcome
The experiment demonstrates representation learning using Variational Autoencoders and the ability to generate synthetic handwritten digit samples from the learned latent space.
