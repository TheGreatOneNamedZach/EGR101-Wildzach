Wildzach - An AprilTag image detection script.

Author(s):  Zachary Bratten

Assignment: EGR 101-005 Week 14; Final Project

Changed: November 28th, 2023

Purpose:
  This script can detect AprilTags using image detection and machine
  learning. I chose this for my project because machine learning will
  play a major role in my career going forward. Whether I work on AI or
  research brain-machine interfaces, I will use machine learning as a
  computer scientist.

Additional Notes:
  This script is made possible by the power of blood, sweat, and tears.


  Make sure the AprilTag is upright! Else, the tracking is off.
  Make sure that the AprilTag is not even slightly obstructed!


  This is by far the most complicated code I have ever written in MATLAB.
  Even though I have taken steps against it, this script will probably
  not work on devices other than mine.


  P.S. MATLAB stores pixel coordinates for images as (y, x).
  Who does that?



# Instructions

YOUTUBE VIDEO: https://youtu.be/Vck66jXTtSQ

1.) Print out the AprilTags:
https://drive.google.com/file/d/1PkqGuDfVzx3a7IQNXvlJt00seDHg3iqa/view

2.) Download the project folder in MATLAB's working directory.
  (Basically, don't put this project's folder "Wildzach" inside
  another folder inside MATLAB)
3.) Add the "Wildzach" folder and subfolders to MATLAB's path

4.) Install all the requirements (listed after the instructions)

5.) Run the script and choose a webcam.

6.) Hold up the AprilTag to the webcam until the battery aligns with the
  AprilTag. 
 
7.) Move the AprilTag to move the battery. Move the battery into the
  battery holder to power the TV (and see the answer to the question
  above the AprilTag). If the battery is too big/small, move the AprilTag
  closer or farther from the webcam.

8.) Each AprilTag has a different question and answer. The 6th AprilTag
  is the roadmap.

9.) The script will automatically shut off after ten minutes. Using the
  keybind Ctrl + C in MATLAB will terminate the script.

Requirements:

  MATLAB R2023b or higher
  
  Computer Vision Toolbox v23.2 or higher
  
  Image Processing Toolbox v23.2 or higher
  
  MATLAB Support Package for USB Webcams v23.2.0 or higher
