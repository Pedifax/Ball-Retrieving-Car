# Ball-Retrieving-Car
_Codes for a ping-pong ball retrieving car. It's a project for the "Special Project of Circuit Design Techniques" course._
### demo video included in the repository.

## Architecture of the Car
1. An object-detection model as the eye/brain of the car. The detection and decision making codes run in an NVIDIA Jetson Nano board.
2. Decisions output from Jetson Nano are delivered to an Arduino board that controls and empowers motors.
3. Ball-collecting gadgets
