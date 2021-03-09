# Ball-Retrieving-Car
#### Codes for a ping-pong ball retrieving car. It's a project for the "Special Project of Circuit Design Techniques" course.
demo video in the repository.

![01](https://user-images.githubusercontent.com/56227873/110399343-aa053700-80b0-11eb-948a-32b0b207e43b.png)
![02](https://user-images.githubusercontent.com/56227873/110399348-abcefa80-80b0-11eb-953c-aff0c291ffb1.png)
![03](https://user-images.githubusercontent.com/56227873/110399351-ad002780-80b0-11eb-9466-c98b1327330c.png)


## Architecture of the Car
1. An object-detection model as the eye/brain of the car. The detection and decision making codes run in an NVIDIA Jetson Nano board.
2. Decisions output from Jetson Nano are delivered to an Arduino board that controls and empowers motors.
3. Ball-collecting gadgets
