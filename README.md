## Overview
This is a Python web app project that allows you to convert any image into a Avatar using OpenCV and machine learning. It's a simple and basic-level project suitable for learning purposes. You can also modify this system to develop a more advanced project tailored to your requirements.

## Features
- Directly select an image for conversion to a Avatar.
- Transform images into captivating Avatars.
- Easy-to-use web application.

## Required Modules
- **CV2**: Imported to use OpenCV for image processing.
- **easygui**: Imported to open a file box, enabling the selection of any file from your system.
- **Numpy**: Used to store and process images as arrays.
- **Imageio**: Reads the chosen file using a path.
- **Matplotlib**: Used for visualization and plotting.
- **OS**: Used for OS interaction, including reading file paths and saving images.
- **Flask**: A micro web framework written in Python for building the web app.

## Steps to Develop
1. Importing the required modules.
2. Build a file box to choose a particular image.
3. Understand how an image is stored.
4. Transform the image to grayscale.
5. Smoothen the grayscale image.
6. Retrieve the edges of the image.
7. Prepare a mask image.
8. Apply a Avatar Effect.
9. Plot all the transitions together.
10. Implement functionality for save or download buttons.

## System Requirements
- Python 3.7
- TensorFlow 2.1.0
- tf_slim 1.1.0
- FFmpeg 3.4.8
- CUDA version 10.1
- Operating System: Windows 10
  
## Installation

### Application tested on:

- python 3.7
- tensorflow 2.1.0 
- tf_slim 1.1.0
- ffmpeg 3.4.8
- Cuda version 10.1
- OS: Linux (Ubuntu 18.04)


### Using `virtualenv`

1. Make a virtual environment using `virutalenv` and activate it
```
virtualenv -p python3 cartoonize
source cartoonize/bin/activate
```
2. Install python dependencies
```
pip install -r requirements.txt
```
3. Run the webapp. Be sure to set the appropriate values in `config.yaml` file before running the application.
```
python app.py
```
