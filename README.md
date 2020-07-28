# Virtual paint:
This code helps you to understand and track your hand movement using webcam. And the color of the pen 
through which you are trying to track your hand movement will be painted on the screen

# Packages required:
(a) opencv
(b) numpy

# commands for the installation of the packages:
-> pip install numpy

-> pip install opencv-python

# Steps to build this project are as follows:
(1) At first we will be importing the required packages

(2) Open the inbuilt Camera

(3) Now we will capture the frames from the camera

(4) Now we will perform the color detection for various colors by using trackbars. 

(5) Set the correct values for hue min,hue max,saturation min,saturation max,value min,value max. The program for this has been implemented in the color_detection.py

(6) Find the contours for the pen

(7) finally we need to draw the color on the canvas accoriding to the hand movement

# Working:

# Execution
-> python virtual_paint.py
