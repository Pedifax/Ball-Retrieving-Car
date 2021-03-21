# Ball-Retrieving-Car
#### Codes for a ping-pong ball retrieving car. It's a project for the "Special Project of Circuit Design Techniques" course.
demo video in the repository.


![r1](https://user-images.githubusercontent.com/56227873/111905911-0c830d80-8a89-11eb-93b7-548f4b3b8af0.gif)
![r2](https://user-images.githubusercontent.com/56227873/111905882-e9585e00-8a88-11eb-84b3-2b078eea73dd.gif)
![r3](https://user-images.githubusercontent.com/56227873/111905835-a26a6880-8a88-11eb-996e-4769a298c788.gif)


## Architecture of the Car
1. An object-detection model plus a webcam as the eye/brain of the car. The detection and decision making codes run in an NVIDIA Jetson Nano board.
2. Decisions output from Jetson Nano are delivered to an Arduino board that controls and empowers motors.
3. Ball-collecting gadgets
