# football_analysis_using_roboflow


hello there

We’re developing a smart football analysis system that can detect and track players, referees, and the ball using YOLO one of the top object detection models out there. Our goal is to enhance the models accuracy by training it on custom data.

To automatically identify which team a player belongs to, we will use KMeans clustering to analyze the color of their jerseys so no manual labeling is needed.

From there, we will track ball possession, giving us insights into which team controls the game over time.

We are also going a step further by applying optical flow techniques to account for camera movement. This way, we can more accurately measure how players move on the field.

To convert pixel-based movement into real-world distances, we will apply perspective transformation letting us calculate a players speed and the total distance they cover in meters.

This project ties together several powerful concepts from computer vision and machine learning, and its a great real-world challenge for both beginners and experienced engineers.

![image](https://github.com/user-attachments/assets/024fd3e2-7ca2-472a-8422-0ea2cbe4f3ca)



I got my project and dataset from Roboflow 

To run this project, you need to have the following requirements installed:

Python 3.x

ultralytics

supervision

OpenCV

NumPy

Matplotlib

Pandas
