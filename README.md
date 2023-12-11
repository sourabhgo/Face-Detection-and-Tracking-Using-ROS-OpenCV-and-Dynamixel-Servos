# Face-Detection-and-Tracking-Using-ROS-OpenCV-and-Dynamixel-Servos

A simple face tracker that can track face only along the
horizontal axis of the camera. The face tracker hardware consists of a webcam, Dynamixel
servo called AX-12, and a supporting bracket to mount the camera on the servo. The servo
tracker will follow the face until it aligns to the center of the image from the webcam. Once
it reaches the center, it will stop and wait for face movement. The face detection is done
using an OpenCV and ROS interface, and the controlling of the servo is done using a
Dynamixel motor driver in ROS.
