# Ball-Retrieving-Car
#### Codes for a ping-pong ball retrieving car. It's a project for the "Special Project of Circuit Design Techniques" course.
demo video in the repository.

![retrieve_1](https://user-images.githubusercontent.com/56227873/111905009-89f84f00-8a84-11eb-8235-350e92cb1900.gif)


## Architecture of the Car
1. An object-detection model as the eye/brain of the car. The detection and decision making codes run in an NVIDIA Jetson Nano board.
2. Decisions output from Jetson Nano are delivered to an Arduino board that controls and empowers motors.
3. Ball-collecting gadgets
