# Self-Driving-RC-Car
A self-driving RC car using Raspberry Pi, Arduino and open source software. The Raspberry Pi collects inputs from the Pi camera module and sends this information  through a machine learning model for detecting STOP signs. The Machine Learning Model was used from a pre-existing model which was OpenCv’s haar Cascade. When the python program on the Raspberry Pi determined that it detects a STOP sign only a few centimeters away from the RC car, it sends a message via USB cable(Serial Communication) to the Arduino which is controlling the motors. The Arduino would then stop for 2 seconds before moving again.

![IMG_5200](https://user-images.githubusercontent.com/39424972/64136830-71e9ad80-cdc2-11e9-8e27-e51f1d757483.jpg)


# Goal
To have the RC Car move forward and when RC Car detects the Stop Sign within a certain range, it will stop for 2 seconds and will continue moving forward. 

![IMG_5211](https://user-images.githubusercontent.com/39424972/64137104-1fa98c00-cdc4-11e9-9478-47137933d3f2.PNG)


# Improvments 
Training the model to detect certain objects, having the car to turn right or left and creating a RC Car shell to hide the hardware and wiring.  
![IMG_5207](https://user-images.githubusercontent.com/39424972/64137058-cd686b00-cdc3-11e9-9cb4-2d7fe4e4b7bc.PNG)


