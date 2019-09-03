# Self-Driving-RC-Car
A self-driving RC car using Raspberry Pi, Arduino and open source software. The Raspberry Pi collects inputs from the Pi camera module and sends this information  through a machine learning model for detecting STOP signs. The Machine Learning Model was used from a pre-existing model which was OpenCv’s haar Cascade. When the python program on the Raspberry Pi determined that it detects a STOP sign only a few centimeters away from the RC car, it sends a message via USB cable(Serial Communication) to the Arduino which is controlling the motors. The Arduino would then stop for 2 seconds before moving again.




# Goal
To have the RC Car move forward and when RC Car detects the Stop Sign within a certain range, it will stop for 2 seconds and will continue moving forward. 

# Improvments 
Training the model to detect certain objects and having the car to turn right or left. 
Creating a RC Car shell to hide the hardware and wiring.  


