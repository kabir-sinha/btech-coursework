# Week 07 — Neural Style Transfer (NST)

## Objective
To implement Neural Style Transfer using a pretrained VGG19 model to combine content and style from two images.

## Approach
- Loaded content and style images
- Used pretrained VGG19 for feature extraction
- Computed content and style features
- Used Gram matrix for style representation
- Optimized target image using content and style loss

## Model Details
- Pretrained Model: VGG19
- Content Layer: conv4_2
- Style Layers: conv1_1, conv2_1, conv3_1, conv4_1, conv5_1

## Training Details
- Optimizer: Adam
- Epochs: 400
- Content Weight: 1e3
- Style Weight: 1e5

## Outputs
- Stylized image combining content and style

## Files

### Dataset
- dataset/nst_result.png

### Notebook
- notebook/CSET419_GenAI_Lab7.ipynb

### Report
- report/E23CSEU1343-Kabir-CSET419-Lab7.pdf

## Conclusion
Neural Style Transfer successfully preserves the content structure while applying stylistic features such as texture and color from the style image, producing an artistic output.
