# Week 08 Notes — GAN Latent Space

GAN Latent Space:
- A vector space from which images are generated
- Each point represents a possible output

Generator:
- Converts latent vector into an image
- Uses ConvTranspose layers

Latent Vector:
- Random noise input (z)
- Dimension = 100

Interpolation:
- Smooth transition between two latent vectors
- Shows continuity in latent space

Observations:
- Outputs are noisy due to no training
- Interpolation is smooth and continuous
- Demonstrates how GANs generate variations

Key Insight:
Even without training, latent interpolation reveals structure in how generators map vectors to images.
