# CNN Line Detection

## Introduction
This project is focused on detecting road lines using a Convolutional Neural Network (CNN). It includes a comprehensive Jupyter Notebook (`Line_detection.ipynb`) that details the entire process from image preprocessing to line detection.

## Project Overview
- The project starts with the basic image preprocessing techniques, including converting images to grayscale, blurring, and applying Canny edge detection.
- Masking the region of interest in the images is performed to focus on the road lines.
- The Hough transform technique is employed to detect lines in the masked region.
- Further optimization is done to refine the detected road markings, making the lines more accurate and reliable.
- An example image (`road_testing.jpg`) is used to demonstrate the line detection process.
- The notebook also includes code for applying this technique to video streams, allowing for real-time line detection.

## Technologies Used
- Python
- OpenCV for image processing
- Matplotlib for image visualization
- Jupyter Notebook for interactive development

## Installation and Setup
Clone the repository and ensure you have Python along with OpenCV and Matplotlib installed. Open the `Line_detection.ipynb` notebook to view the project.

## Usage
The notebook is self-contained and walks through each step of the line detection process. Run each cell to understand the process and see the results on the sample image and video files.


