# Week 07 Notes — Neural Style Transfer

Neural Style Transfer (NST) is used to combine the content of one image with the style of another image.

Content Image:
- Defines structure and objects

Style Image:
- Defines texture, colors, and artistic appearance

VGG19:
- Used as a feature extractor
- Pretrained on ImageNet
- Weights are frozen

Content Loss:
- Measures difference between content features

Style Loss:
- Uses Gram matrix to capture texture

Total Loss:
- Combination of content and style loss

Observations:
- Content structure is preserved
- Style texture is transferred
- Output appears artistic

Key Insight:
NST works by optimizing the image itself rather than training a model.
