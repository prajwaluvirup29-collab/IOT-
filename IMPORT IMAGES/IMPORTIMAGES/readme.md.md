Image Size Analyzer - Project Report
1. Introduction
This report explains the Image Size Analyzer Python project. The program scans a folder of
images, displays them, extracts dimensions (width and height), computes area, identifies the
largest and smallest images, and stores all collected data in a CSV file.
2. Features
• Reads JPG, JPEG, and PNG images.
• Displays each image using Matplotlib.
• Extracts width, height, and area.
• Detects the largest and smallest images based on area.
• Saves results to image_sizes.csv.
3. Requirements
Python libraries used:
• Pillow (PIL)
• Matplotlib
• CSV (built-in)
• OS module (built-in)
4. Python Script Overview
The script performs the following steps:
1. Reads all images from the target folder.
2. Displays each image using plt.imshow().
3. Gathers metadata (filename, width, height, area).
4. Uses max() and min() functions to determine image size extremes.
5. Saves results into a CSV file.
5. Output Files
• image_sizes.csv: Contains details of all scanned images.
• Console output: Displays largest and smallest image details.
6. Conclusion
This project demonstrates how Python can be used for image analysis, data extraction, and
automation. It is helpful for photographers, developers, and students who want to analyze bulk
images efficiently.
Author: Prajwal V