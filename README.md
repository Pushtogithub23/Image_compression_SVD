# Image Compression Using Singular Value Decomposition (SVD) in Mathematica

This repository contains a Mathematica notebook demonstrating image compression using Singular Value Decomposition (SVD). Singular Value Decomposition (SVD) is a mathematical technique that decomposes a matrix into three other matrices. It is commonly used in various fields, such as signal processing, statistics, and image processing.

Applications of SVD include:
1. Image compression: By applying SVD to an image matrix, we can retain only the most important information (represented by the largest singular values) and discard the rest, leading to compression with minimal loss of quality.
2. Dimensionality reduction: SVD can reduce the dimensionality of data while preserving important information, making it easier to analyze and visualize.
3. Noise reduction: SVD can help remove noise from data by filtering out the components corresponding to small singular values.
4. Collaborative filtering: SVD is used in recommendation systems to analyze and predict user preferences based on past interactions.

To use SVD for image compression, we follow these steps:
1. Convert the image into a matrix representation.
2. Apply SVD to the image matrix to decompose it into three matrices: U, Σ, and V^T.
3. Keep only the most significant singular values by truncating the Σ matrix.
4. Reconstruct the compressed image using the truncated matrices.
5. Compare the compressed image quality with the original image to assess the compression ratio and quality trade-off.



## Usage
To run the code, you must install Wolfram Mathematica on your machine. You can download Mathematica from the [Wolfram website](https://www.wolfram.com/mathematica/).

1. Clone the repository to your local machine.
2. Open the `ImageCompression.nb` notebook in Mathematica.
3. Modify the input image path and the desired number of singular values to keep.
4. Run the notebook to compress the image and view the results.


## References

- [Wolfram Mathematica Documentation](https://www.wolfram.com/mathematica/documentation/)
- [Singular Value Decomposition](https://math.mit.edu/classes/18.095/2016IAP/lec2/SVD_Notes.pdf)

