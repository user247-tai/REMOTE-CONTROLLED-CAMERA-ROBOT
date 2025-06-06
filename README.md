# REMOTE-CONTROLLED-CAMERA-ROBOT
A remote controlled camera car using HTTP protocol. This project builds a remote-controlled camera car through a mobile app (built with MIT App Inventor), using the HTTP protocol and the ESP32, ESP32 CAM microcontroller.
The “Remote-Controlled Camera Robot Using IoT” project aims to address the need for flexible and efficient surveillance systems that can adapt to diverse environments and scenarios, empowering users with remote control and real-time monitoring capabilities.

![Diagram](https://github.com/user-attachments/assets/f4236866-58e4-4926-b6d0-8dcaf161e36d)


We will use 1 ESP32 as the server broadcast Wi-Fi network, 1 ESP32 CAM and the user device with the control application installed as the clients connect to the Wi-Fi network broadcasted from the server. Clients and server communicate with each other via HTTP protocol.
Achievement:
- Here is a video about our achievement we achieved with our project: https://drive.google.com/file/d/1HVhV8xalqO2VKGNT3o4miHDFesW6CDvh/view?usp=drive_link
- The robot's operating range is the ESP32's Wi-Fi operating distance (about a few dozen to a few hundred meters depending on the environment) from the robot to the control device.
- The camera is streamed in real time. Although the FPS is not high, and the image quality is not very good. However, the camera module we are using is a cheap module costing only 4$, so we cannot ask for higher requirements.
  


