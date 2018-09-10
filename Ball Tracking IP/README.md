# Ball-Tracking
# Project on a robot tracking a ball using image processing
In this project I have made a small robot follow a ball. I have used image processing in OpenCV in python 3.6 to keep track of a yellow
colour ball and then follow it. I am taking the image feed from the bot through my smartphone placed on it and using IPwedcam app I am
transfering the image from it to my laptop wirelessly and process it in python 3.6 in using opencv and again returning a pid value to the 
bot for it's left and right movement and the also passing a decission to move forward or backward based in the area of the object. I am
using a node MCU to control my bot and these pid values are passed to it through wifi also wirelessly through TCP. So no actual image 
processing is done on bord. I am currently working on its modification to find distance of the object from bot using two cameras and 
processing them parallely using CUDA.
