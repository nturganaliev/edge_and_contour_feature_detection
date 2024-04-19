    Brightness Gradient: This technique focuses on detecting changes in brightness across an image. It involves computing the gradient of the image intensity values. In simpler terms, areas where the brightness changes abruptly are identified as edges or contours.

    Color Gradient: Similar to brightness gradient but applied to color images, this technique detects changes in color intensity across the image. It can be useful for detecting edges or boundaries between objects of different colors.

    Texture Gradient: Texture gradient refers to detecting changes in texture patterns across an image. It involves analyzing variations in texture features such as coarseness, smoothness, or roughness. This technique is particularly useful for detecting textured regions or surfaces in an image.

    In our script:

    We load an example image and convert it to grayscale for brightness and texture gradient detection.
    We calculate the brightness gradient using the Sobel operator, color gradient using Sobel on RGB channels, and texture gradient using the Laplacian operator.
    Finally, we combine these gradients to see the overall contour detection effect.

    Manipulated images can be found in results folder.