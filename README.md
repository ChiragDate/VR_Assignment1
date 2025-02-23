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

> **Note:** The code is self-contained and will run without any additional intervention once the dependencies are installed.

---

## Repository Structure
VR_Assignment1_ChiragDate_60004190021 \n
├── VR_Assignment1_Canny.ipynb
├── VR_Assignment1_Panaroma.py
├── README.md
│   ├──coins2.jpg
│   ├── Coin_Task_output.png
│   ├── Left_image.jpg
│   ├──Right_image.jpg
│   └── stitched_result_panaroma.jpg
├── outline_detected_images.jpg


# How to Run the Code
The code is designed to run without any extra modifications or configuration.

1. Coin Detection & Segmentation
Input:

Image: images/coinsun.jpeg
Command:

bash
Copy
python coin_detection.py
Output:

Displays the segmented coins.
Saves segmented coin images.
Prints the total number of coins detected.
2. Panorama Creation
Input:

Images: images/panroma1.jpeg, images/panroma2.jpeg, images/panroma3.jpeg
Command:

bash
Copy
python panorama_creation.py
Output:

Displays the final stitched panorama.
Saves the panorama as stitched_result.jpg.



