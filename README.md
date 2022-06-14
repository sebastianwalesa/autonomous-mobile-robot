# autonomous-mobile-robot

Autonomous Mobile Robot is the design of a mobile robot that is autonomous through camera image processing. The vehicle moves autonomously using deep neural networks (specifically ResNet18) to teach it to follow a set route. In addition, it can detect obstacles and stop in front of them. It recognizes traffic lights on a traffic signal set along its route. The platform used is JetRacer manufactured by Waveshare. The robot has 4 wheels and a torsion front axle. It is powered by 2 motors placed on its rear part. The camera is mounted on the front of the vehicle, and in the middle is a Nvidia Jetson Nano-a minicomputer with pre-programmed algorithms. It has a dedicated version of Linux installed, and the programming process is done using the Python language, specifically the OpenCV and Tensorflow libraries.

Authors of project: Adrian Świderski & Sebastian Wałęsa

![alt text](https://github.com/sebastianwalesa/autonomous-mobile-robot/blob/main/JetRacer.jpg?raw=true)

https://user-images.githubusercontent.com/25770845/173637449-97190a15-ce7b-45ae-a5a3-77c09da976ee.mp4

Files with "ad" in name contain code provides autonomous driving, "ca" in name means collision avoidance. 
