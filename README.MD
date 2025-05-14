
# Retail Shelf Inventory Monitoring

## Overview

This project aims to detect products in a retail shelf image by applying basic computer vision techniques, such as thresholding and contour detection. The program identifies product areas based on size and highlights them with red bounding boxes. It can be used for monitoring shelf inventory in retail settings.

## Technologies Used

- **Python**: Programming language used for implementing the solution.
- **OpenCV**: Library for image processing tasks like thresholding, contour detection, and drawing bounding boxes.
- **NumPy**: For handling array operations.

## Installation

### Step 1: Install Dependencies

To run this program, you need to install the required libraries. You can install them using the following commands:

```bash
pip install opencv-python numpy
````

### Step 2: Prepare the Image

Ensure that you have the input image (`reference.jpg`) that contains the retail shelf. Place the image in the same directory as the script.

### Step 3: Run the Program

Once you have installed the dependencies and prepared the image, you can run the program using the following command:

```bash
python shelf_inventory.py
```

This will display two windows:

1. **Detected Shelf Products**: The image with red bounding boxes drawn around detected products.
2. **Thresholded Image**: The binary thresholded image used for detecting the contours.

### Step 4: View the Output

After running the program, you will see the results:

* The **Detected Shelf Products** window will show the image with red rectangles around the detected products.
* The **Thresholded Image** window will show the thresholded binary image, highlighting areas where the products were detected.

