# CNN Line Detection

## Introduction
This project is focused on detecting road lines using a Convolutional Neural Network (CNN). It includes a comprehensive Jupyter Notebook (`Line_detection.ipynb`) that details the entire process from image preprocessing to line detection.

## Project Overview
- `Line_detection.ipynb` is the central file of this project, detailing each step in the line detection process.
- The process begins with image preprocessing, including converting to grayscale, blurring, and Canny edge detection.
- A region of interest is defined in the images to focus exclusively on the road lines.
- The Hough transform method is utilized for detecting lines in the specified region.
- Additional optimization is performed to refine the road markings, enhancing the accuracy and reliability of the line detection.
- An example image (`road_testing.jpg`) demonstrates the line detection technique.
- The notebook also provides code for applying line detection to video streams, enabling real-time application.

## Technologies Used
- Python
- OpenCV for image processing
- Matplotlib for image visualization
- Jupyter Notebook for interactive development

## Installation and Setup
Clone the repository and ensure you have Python along with OpenCV and Matplotlib installed. Open the `Line_detection.ipynb` notebook to view the project.

## Usage
The notebook is self-contained and walks through each step of the line detection process. Run each cell to understand the process and see the results on the sample image and video files.


