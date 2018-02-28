# DDIPy (:sparkles:[Best Beginner Hack](https://devpost.com/software/ddipy) @ [MakeCU 2018](https://www.makecu.org/):sparkles:)

This is DDIP the Differentially Driven Inverted Pendulum. DDIPy is remote controled Self balancing robot design and implemented for The MakeCU Hackathon. DDIPy is very musch so still in development (User Battery Pack melted at MakeCU :cry:), and Currently does **NOT** have a completed Readme.
# Purpose

As software focus computer science students we created DDIPy to exsplore Hardware development and Robotics.

# How to Download

# Getting Started

> Word of advice please test how your motors are set-up.
> We're not sure how our motors are set up we just tested by
> experiment.

# Problems Faced

1. We had researched the basics components of the Robots, had conceptualized the build process, and even had previous experience using some of the modules, but we didn't test all the modules we would be using ahead of time.

Down the line this lead to issues as the Gyro used I<sup>2</sup>C communication, and lacked an easy to use library. As a team of mostly first time hardware hackers I<sup>2</sup>C is an intimidating protocol to learn in only a few hours.
 * We found simple coding samples, tutorials, and the official module datasheet, to help us out.

2. Our use case for the PID Control system is very unique

3. We Struggled to get the Arduinos to communicate properly

4. Once we got the gyroscope values we didn't realize that the gyroscope was outputting the instantaneous angular velocity not the angle of the system at a given time.
* though we knew the physics of the we didn't know how to implment

# Attribution

https://github.com/yohendry/arduino_L298N - the L298N Fritzing part we used in the robot schematic.

This is the chasse we bought for the robot:
https://www.osepp.com/robotic-kits/6-2wheeler
Motor Datasheet
https://www.osepp.com/downloads/pdf/DC-Motor-Spec.pdf
