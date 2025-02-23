# Coin Detection, Segmentation, and Panorama Creation

**Author:** Chirag Date 
**ROLL NO:** MT2024034

---

## Overview

This repository contains implementations for two computer vision tasks:

1. **Coin Detection & Segmentation:**  
   Detect and segment coins from an input image, then count the total number of coins.

2. **Panorama Creation:**  
   Stitch multiple overlapping images to create a seamless panoramic image using feature extraction, matching, homography estimation, and image warping.

-----


# How to Run the Code

1. Coin Detection & Segmentation
Input:

Image: images/coins2.jpg
Command: 

bash python vr_assignement1_canny.py


Output:

![alt text](https://github.com/ChiragDate/VR_Assignment1/blob/main/images/outline_detected_images.png)


Displays the segmented coins.

Prints the total number of coins detected.

2. Panorama Creation

Input:

Images: images/Left_image.jpg, images/Right_image.jpg
Command:

bash python vr_assignment_panaroma.py

Output:

![alt text](https://github.com/ChiragDate/VR_Assignment1/blob/main/images/stitched_result_panaroma.jpg)

Displays the final stitched panorama.
Saves the panorama as stitched_result.jpg.



