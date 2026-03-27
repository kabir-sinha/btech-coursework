# Week 06 Notes — Pix2Pix

Pix2Pix is a Conditional GAN used for image-to-image translation tasks.

The model learns a mapping from input images to output images using paired data.

Input in this lab:
- Edge images generated using Canny edge detection

Target:
- Original CIFAR-10 images

Generator:
- U-Net architecture
- Uses skip connections to preserve spatial details

Discriminator:
- PatchGAN
- Classifies image patches instead of whole image

Loss Function:
- GAN Loss for realism
- L1 Loss for structural similarity

Observations:
- Generated images are blurry but structurally correct
- Training for more epochs improves quality

Key Insight:
Conditional GANs allow controlled image generation based on input data.
