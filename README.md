# opencv_colourdetection
Real-time color-based object detection using Python and OpenCV. Captures live webcam feed, applies HSV color space thresholding for robust color segmentation, and localizes objects using bounding boxes. Demonstrates classical computer vision techniques, efficient array processing with NumPy, and clean, modular code design.

Programming Language

Python 3

Used for rapid prototyping and real-time computer vision processing.

Chosen for its strong ecosystem of image processing and numerical computing libraries.

OpenCV (cv2)

Core library used for real-time video capture and image processing.

Key functionalities leveraged:

VideoCapture for webcam interfacing

cvtColor for BGR → HSV color space conversion

inRange for color-based segmentation

rectangle for object localization and visualization

Enabled efficient frame-by-frame processing suitable for real-time applications.

NumPy

Used for numerical operations and array manipulation.

Plays a critical role in:

Defining HSV threshold boundaries

Handling image data in matrix form

Ensures fast, vectorized computations.

Pillow (PIL)

Utilized for bounding box extraction using getbbox() on binary masks.

Simplifies region-of-interest (ROI) detection from segmented images.

🧠 Core Concepts Implemented

Color Detection using HSV Color Space

HSV is preferred over RGB/BGR for robustness under varying lighting conditions.

Dynamic hue-based thresholding is implemented for accurate color isolation.

Real-Time Video Stream Processing

Continuous frame acquisition from a live webcam feed.

Frame-wise analysis and visualization with minimal latency.

Image Segmentation

Binary mask generation using HSV thresholds to isolate a target color.

Enables effective object detection based purely on color features.

Object Localization

Bounding box computation around detected color regions.

Visual feedback using overlayed rectangles on live video frames.

Resource Management

Proper release of camera resources and window cleanup to prevent device locking.
