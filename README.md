# Canny Edge Detection using OpenCV

---

## Aim

To implement the Canny Edge Detection algorithm on a sample image using OpenCV, analyze the detected edges, and study the impact of different parameter settings on the resulting edge map.

---

## Author

**Name:** Deepak S

**Register Number:** 212224230053

---

## Software Requirements

* Python 3.7 or above
* OpenCV (`opencv-python`)
* NumPy
* Matplotlib
* Jupyter Notebook / Anaconda

---

## Algorithm

### Step 1

Import the required libraries such as OpenCV, NumPy, and Matplotlib.

### Step 2

Load the input image from the specified path.

### Step 3

Convert the image into grayscale format for easier edge detection.

### Step 4

Apply Gaussian Blur to reduce noise and unwanted details.

### Step 5

Use the `cv2.Canny()` function to detect edges by specifying lower and upper threshold values.

### Step 6

Generate the edge-detected image.

### Step 7

Display both the original image and the detected edges using Matplotlib.

---

## Output

### Original Image

Input image used for edge detection.

### Edge Detected Image

Edges extracted using the Canny Edge Detection algorithm.

---

## Impact of Different Parameter Settings

### Low Threshold Values

* Detects more edges.
* Captures fine details.
* May introduce noise and false edges.

### High Threshold Values

* Detects only strong edges.
* Reduces noise significantly.
* Some important weak edges may be lost.

### Gaussian Blur Kernel Size

* Smaller kernel preserves details but may retain noise.
* Larger kernel removes noise but may smooth important edges.

### Lower and Upper Threshold Ratio

* A proper ratio helps distinguish between strong and weak edges.
* Improper threshold selection can either miss edges or detect excessive noise.

---

## Result

The Canny Edge Detection algorithm was successfully implemented using OpenCV. The detected edges accurately represented object boundaries in the image.
