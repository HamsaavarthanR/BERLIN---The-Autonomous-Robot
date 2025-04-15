# "BERLIN" The Autonomous Robot
Project: ENPM701 Autonomous Robots

![BERLIN](https://github.com/user-attachments/assets/e8aa95a4-56ea-4754-83fe-ad20cc66f8c5)

## Accomplishments
* Fabricated a fully autonomous robot, achieving level 4 autonomy: High Automation by implementing modelling and controls, perception, localization and SLAM, planning, and decision making, showcasing strong problem-solving skills.
* Programmed on RaspberryPi, remotely over SSH, to manipulate encoders, camera, servo and DC motors, and IMU - Arduino, using Server-Client protocol for sensor fusion accomplishing near ~100% autonomy.
* Accomplished task sequence with 98% motion execution accuracy by incorporating PID closed loop feedback control system for motion control, and interpret industrial hardware and software troubleshoot approach.

## About BERLIN
### Hardware
* Berlin is the fully autonomous robot that I built from the scratch for this course to set it all up for the grand challenge, equiped with RaspberryPi, camera, IMU, US sensor, encoder, servomotor, DC motor
* All of the program codes and the entire control of the robot is taken care by a single on-board computer called RaspberryPi 3B+ module, which has its own linux-based operating system running on it, and provides a variety of hardware interfacing functionalities. In layman’s term, we can say that, the RaspberryPi is the brain of the robot.
* Furthermore, it has got 4 senses or electronic sensory units to perceive the environment and provide feedback, which are the camera to provide visual perception of the environment, ultrasonic sensor to estimate the distance of any object or obstacle in front of it, the Inertial Measurement Unit or IMU that provides the exact orientation of the robot, and finally the encoders attached to the DC motors to detect how much the wheels have turned.
* Apart from that, Berlin can move around with the help of 4 brushed DC motors attached to the wheels and encoders, and a servomotor that controls the gripper arm to safely retrieve the blocks.

### Software
Now with enough foundation of the hardware informations and the structural built of the robot, let’s look into the most critical part, which is the software aspect that provides intelligence to the robot.
* I used a Secure Shell or (SSH) Network protocol to wirelessly communicate with the raspberryPi on-board computer from My Mac and all the programs required for the grand challenge was written using python scripting language.
* The entire problem of the grand challenge itself can be segmented as multiple layers and can be peeled off one layer at a time to finally reach the goal.
* We can classify the software problem further into three parts:
*   ‘Perception and Sensing’
*   ‘Locomotion and Control’
*   ‘Planning and Localisation’

## Tasks
* ENPM701-Autonomous Robotics, which is a hands-on course that expects us to build a robot, to accomplish the ultimate goal, that is the Grand Challenge.
* In the grand challenge, a 10ft-by-10ft arena is provided with a number of coloured blocks randomly scattered anywhere in the arena, and the robot located in one of the corners.
* Initially, the robot has to sense a red block from the cluttered environment in the arena, orient itself towards the block, traverse to it and retrieve the red block. After successfully retrieving a block, the robot has to carry it and place the red block inside a 4ft-by-4ft construction zone, located at the bottom corner of the arena.
* Similarly, now the robot has to look for a green block from the arena, retrieve it and place it in the construction zone. And then, followed by a blue block.
* The same procedure is looped again thrice, making it a retrieval of 9 blocks in total, expected to be done in the specified order within duration of 10 mins.
* In addition to that, the round will be considered disqualified if the robot touches any of the walls or the points would be deducted if the robot fails to retrieve blocks in the given order, that is red, green and blue.
* All these tasks should be performed by the robot that we build, which has to be fully autonomous, means, No Internet connection, No GPS, No Remote control, or No nudging in-between to help it get unstuck.

## Links
https://www.youtube.com/watch?v=v-Ko-MkVFOY
