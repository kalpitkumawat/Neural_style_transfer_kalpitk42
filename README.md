## Neural Style Transfer 
Neural Style Transfer (NST) is an innovative deep learning technique that merges the content of one image with the style of another, creating visually captivating results. At its core, NST uses convolutional neural networks (CNNs) to extract high-level features from both a content image and a style image. These features are then used to construct a new image that preserves the fundamental structures and objects of the content image while adopting the colors, textures, and artistic elements of the style image. By optimizing a combination of content similarity, style similarity (measured using statistics like Gram matrices), and spatial smoothness (total variation loss), NST produces compelling artworks that blend the realism of the content image with the aesthetic appeal of the style image. This approach not only showcases the versatility of deep learning in creative applications but also offers a powerful tool for generating unique visual compositions across various domains including art, design, and multimedia.


This repository contains an implementation of neural style transfer using TensorFlow and InceptionV3. Neural style transfer is a technique that blends the style of one image with the content of another image to create visually appealing results.

## Overview

Neural style transfer involves:

Content Image: The main structural elements of the image whose content we want to preserve.


Style Image: The artistic style we want to apply to the content image.


Generated Image: The resulting image that combines the content of the content image with the style of the style image.


## Key Features

InceptionV3 Model:
Utilizes the InceptionV3 deep convolutional neural network as the feature extractor to capture both content and style representations.

Loss Functions: Content loss measures the difference in content between the generated image and the content image. Style loss calculates the difference in style using Gram matrices of feature maps.

Optimization: Uses an optimizer (e.g., Adam) to minimize the combined loss of content, style, and total variation to produce the final stylized image.

User Interaction: Offers flexibility with parameters to adjust style strength, content preservation, and smoothness.

# Running the files

- Just open the Neural_Style_Transfer.ipynb file.
- you need to just paste the path of the content image and style image in the variables style_path and content_path from your drive.
- You can also modify the values of the parameters and see the changes in your results.


## dependencies
* TensorFlow 
* Matplotlib
* NumPy
* imageio
* IPython
* Pathlib
