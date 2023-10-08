# Line-Follower-Bot
using Arduino Uno and L298N

## Features

- **Line Following:** The robot is programmed to follow a black line on a white surface using infrared (IR) sensors.
- **Customization:** Easily customize the path and behavior by modifying the code.
- **Real-world Application:** Learn the fundamentals of robotics and automation with a practical example.



## Components

Here is a list of components used in this project:

  - **Arduino Uno**
  - **IR Sensor(2)**
  - **Chassis**
  - **4-wheel**
  - **4-bo motor**
  - **Jumper wire**
  - **Battery 9v**
  - **L298N Motor driver**

## Working
  The sensor of the car will detect the surface either white or black. If both sensors are on the black then the   line follower will stop and if both sensors are on
  the white surface then the robot will start to move.
  Ir sensor has an Infrared sensor that gives output according to the received light at the photosensor. At the black color, their sensor will send the 0 value. 
  Arduino received this value then compare it with the given condition and send the instruction according to the database. Arduino collects data from both of the
  sensors at the same time and compares both sensor values with the previous. Arduino sends an instruction to the motor driver as the electrical signal with 3.3v 
  amplitude which is less to drive the motor, now we have to connect the L298N driver with the Motor because without the driver Arduino can’t rotate the motor.
 
 ## Circuit Diagram

 <img width="572" alt="line-follower-bot-circuit-Diagram" src="https://github.com/Astha0123/Line-Follower-Bot/assets/97621624/fba6c36c-7d5c-4aa9-a1cc-459cbacecccb">


