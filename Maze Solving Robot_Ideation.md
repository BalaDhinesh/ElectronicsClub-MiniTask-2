The web link for this project description:
https://www.projectideasblog.com/2012/10/maze-solving-robot.html

# Problem Statement:
Building a maze soving robot which can find its way in a line maze from start point to end point.


## Components Used:
- AT89C51 (used as the decision-making device)
- motor driver L293D
- operational amplifier LM324 (comparator)
- phototransistors (sensors)


# Ideation:


__Understand the Robot's Mechanism:__

Sensors for detecting path -> Decision making(which path to turn) -> storing the path -> Motor Rotations

The design of the maze can be made in two different ways:
-  Black dots as line following.
-  Black dots as obsatcle.



Which sensor can be used? Ultrasonic or Infrared:
| Sensors | Feasible | Advantages | Disadvantages |
| --- | --- | --- | --- |
| Ultrasonic Sensor | Easy to implement | Works well in places that are dim | Not as accurate as Infrared |
| Infrared Sensor | Yes, the best way | Small form factor   | Inability to use them in sunlight due to interference. |


Hence Infrared Sensor is used.


The suggested approach is good. There are few things which I would like to change. In this project, five Infrared Sensors are used which can be replaced by an Analog Reflective Sensor Array Circuit which has 8 sensors thereby acheiving more compact and accurate.
We can increase the difficulty of this project by extending the type of maze with slanting and curved black lines. For this, we can control the motor with different speeds like slow, medium, fast. Some additions have to be done in the code to acheive this result.
To program AT89C51 microcontroller, we need additional softwares to be used for burning the code to the microcontroller. Hence we can replace the AT89C51 microcontroller by an Arduino since it is easy to program with an integrated IDE. 


To control the speed of motors see my github page for description:
https://github.com/BalaDhinesh/ElectronicsClub-MiniTask1/blob/master/Speed%20Control%20of%20DC%20Motor%20Using%20Pulse%20Width%20Modulation.md

