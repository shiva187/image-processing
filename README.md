# Basic Image Processing with OpenCV

## Project Description

This Python script demonstrates fundamental image processing operations using the OpenCV library. It covers reading, writing, displaying, and manipulating images, including converting them to grayscale and binary formats.

## Setup

To run this script, you need to have Python installed along with the following libraries:

*   OpenCV (`opencv-python`)
*   Matplotlib (`matplotlib`)

These libraries can typically be installed using pip:

```bash
pip install opencv-python matplotlib
```

In a notebook environment like Google Colab, these libraries are often pre-installed.

## How to Run

1.  Make sure you have an image file you want to process.
2.  Replace `"sample1.JPG"` in the script with the path to your image file.
3.  Run the Python script or execute the code cells in your notebook environment.

The script will process the image and save the results.

## Image Processing Steps

The script performs the following image processing operations:

1.  **Read an image**: Loads an image file into the script using `cv2.imread()`.
2.  **Write (save) the image**: Saves the loaded image to a new file (e.g., `sample_out.png`) using `cv2.imwrite()`. 
3.  **Display Original Image**: Converts the image from BGR (OpenCV's default) to RGB format for correct display with Matplotlib and shows it.
4.  **Accessing Pixel Values**: Demonstrates how to retrieve the BGR values of a specific pixel at given coordinates (row, column).
5.  **Convert to Grayscale**: Converts the color image to a single-channel grayscale image using `cv2.cvtColor()`.
6.  **Convert to Binary (Black & White)**: Applies a threshold to the grayscale image to convert it into a binary image, where pixels are either black or white, using `cv2.threshold()`.

## Output Files

Upon successful execution, the script will generate the following output files:

*   `sample_out.png`: The original image saved in PNG format.
*   `/content/output_gray.png`: The grayscale version of the image.
*   `/content/output_binary.png`: The binary (black and white) version of the image.
"""

print(readme_content)
