# Coin Detection, Segmentation, and Panorama Creation

**Author:** Chirag Date MT2024034

---

## Overview

This repository contains implementations for two computer vision tasks:

1. **Coin Detection & Segmentation:**
   
   Detect and segment coins from an input image, then count the total number of coins.

3. **Panorama Creation:**
   
   Stitch multiple overlapping images to create a seamless panoramic image using feature extraction, matching, homography estimation, and image warping.

-----


# How to Run the Code

**1. Coin Detection & Segmentation**
#Input:

Image: images/coins2.jpg

![alt text](https://github.com/ChiragDate/VR_Assignment1/blob/main/images/coins2.jpg)

# Command: 

bash python vr_assignement1_canny.py


# Output:

![alt text](https://github.com/ChiragDate/VR_Assignment1/blob/main/images/outline_detected_images.png)


Displays the segmented coins.

Prints the total number of coins detected.

**2. Panorama Creation**

# Input:

# Images: images/Left_image.jpg, images/Right_image.jpg

# Command:

bash python vr_assignment_panaroma.py

# Output:

![alt text](https://github.com/ChiragDate/VR_Assignment1/blob/main/images/stitched_result_panaroma.jpg)

Displays the final stitched panorama.

Saves the panorama as stitched_result.jpg.


**Software & Libraries:**

•	Python Version: >=3.0.0

•	Libraries:

o	OpenCV 

o	NumPy 

o	Matplotlib 


**Results:**

# Coin Detection & Segmentation:
•	The algorithm detects the edges of coins and draws contours around them.

•	Each coin is segmented using bounding boxes. For example, if six coins are detected, the output prints:

"Total number of coins detected: 6"

# Panorama Creation:

•	The stitching process successfully merges overlapping images into a panoramic view after extracting features, matching them, estimating the homography, and warping the images.

•	The outputs include examples of both two-image and three-image panoramas.


**Observations:**

# Coin Detection & Segmentation:

•	Accuracy: The use of proper thresholding in edge detection and area filtering of contours yields accurate coin detection.

•	Challenges: Incorrect area thresholds may result in false positives or missed detections, and varying lighting conditions might introduce noise.

# Panorama Creation:

•	Feature Overlap: Sufficient overlap between images is critical for effective stitching.

•	Blending Issues: Visible seams can occur if there are significant exposure differences between images.

•	Robustness: The RANSAC algorithm helps manage outliers, although good keypoint coverage is essential for accurate homography estimation.

**Conclusion:**

•	The coin detection and segmentation task offers valuable experience in edge detection, contour analysis, and image segmentation.

•	The panorama creation task demonstrates practical techniques for feature-based alignment, homography estimation, and image stitching.




