# Photo-Quality-Enhancement-with-Deep-Learning-Auto-Encoding.
This project implements an autoencoder-based deep learning model designed to enhance images by removing noise and blur. The model takes noisy and blurred images as input and outputs enhanced images with improved clarity.

Autoencoder Overview
Autoencoders are neural network architectures used for unsupervised learning of efficient codings. The network consists of two main parts:

Encoder: Compresses the input image into a latent-space representation.
Decoder: Reconstructs the image from the latent representation.
In this project, the autoencoder is trained to denoise and deblur images, improving their quality.

Project Description
This project uses a variety of images, adds noise and blur to simulate common distortions, and then employs an autoencoder to enhance the image quality. The autoencoder consists of an encoder that compresses the noisy and blurred images into a compact representation, and a decoder that reconstructs and restores the images to their original quality. By training on altered images and their original counterparts, the model learns to effectively denoise and deblur, making it possible to increase the quality of random images

Examples:
