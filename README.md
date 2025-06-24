Image Processing Toolkit
Overview
This repository provides Python implementations of fundamental image processing techniques using OpenCV, including:

Contrast Enhancement: Histogram equalization

Morphological Operations: Erosion, dilation, opening, closing

Edge Detection: Morphological gradient

Image Segmentation: Thresholding, k-means clustering, contour detection

Installation
bash
pip install opencv-python numpy matplotlib
Usage
Each technique is implemented in a standalone Python script with example usage:

python
import cv2

# Example: Histogram equalization
img = cv2.imread('image.jpg', 0)
equ = cv2.equalizeHist(img)
Techniques Implemented
1. Histogram Equalization
Enhances image contrast by redistributing pixel intensities

histogram_equalization.py

2. Morphological Operations
Erosion: Shrinks foreground objects (erosion.py)

Dilation: Expands foreground objects (dilation.py)

Opening: Erosion followed by dilation (opening.py)

Closing: Dilation followed by erosion (closing.py)

3. Edge Detection
Uses morphological gradient (difference of dilation and erosion)

edge_detection.py

4. Image Segmentation
Thresholding (thresholding.py)

K-means clustering (kmeans_segmentation.py)

Contour detection (contour_detection.py)

Example Results
https://docs/results_sample.png

Contributing
Pull requests are welcome. For major changes, please open an issue first.

License
MIT

#Keywords: Computer Vision, Image Processing, OpenCV, Python
