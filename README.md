# Self-Driving-Car-Engineer---Finding-Lanes-Project

The aim of this project is to find the lane lines from different road images.
Then by applying various image processing techniques the lane lines are drawn on the original image to check whether if they are coinciding or not.

The image processing pipeline includes:
       a) Converison to grayscale
       b) Gaussian blur and canny edge detection
       c) Marking the region of interest and masking the remaining image
       d) Creating the hough lines and drawing the lanes
       e) Embedding the drawn lanes on original image for sanity check
       
The draw_lines() method in the jupyter notebook is the crucial piece of code for lane line detection.