# Face-Recognition-Raspberry-pi
Facial recognition using Logitech camera in Raspberry Pi 3

This project is a production ready complete intelligent Door opening system using image processing and raspberry pi.
Steps to build this project.

1. Setp the Raspberry Pi 3 with opencv and python setup properly.
Please check the instaalation guide of Adrian. Thanks for the brief setup
https://www.pyimagesearch.com/2016/04/18/install-guide-raspberry-pi-3-raspbian-jessie-opencv-3/

2. Raspberry pi come with pre-built node-red. Upgrade in node-red is recommended.

3. Import the complete project "Face-Recognition-Raspberry-pi" in one of the folder.

4. Open Node-red and paste the complete node-red-flow in one of the node red flow page.

5. Connect the USB IR sensor in one of the raspberry pi USB port. Take the reading once the IR detect any obstacle.

Working:
Once all the setup is done. Stand infront of the camera and IR sensor placed alongside. This will trigger the python script "facerec.py" and will match with the face stored earlier while running "train.py". If the face matches the Door gets open. The secret code for the smart lock will be triggered from the raspberry pi. We have to connect the smart lock of the door to the raspberry pi unit.

Enjoy your Intelligent Door :)
