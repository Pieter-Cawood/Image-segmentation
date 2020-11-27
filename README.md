# Image-segmentation
Background Segmentation using a Gaussian Mixture Models &amp; VGG16/UNet Deep Learning model.

## Gaussian Mixture Model (GMM)
GMM model implemented from first principles. The GMM attempts to cluster hand-crafted features to 
perform segmentation of the input images as either background or foreground.

**90+ % accuracy**

## VGG16/Unet 
VGG16/Unet (Keras module). The famous UNet architecture constructed with the VGG16 pre-trained ImageNet weights.
Includes a third class of corners, to detect the corner locations of the puzzle images.

**99+ % accuracy**

