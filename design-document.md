## Electronics

### Arduino Board 
#### Rev3
<p align="center">
<img src="https://i.imgur.com/cXYPimo.png" width="500">
</p>
#### Rev4
<p align="center">
<img src="https://i.imgur.com/BRROWqP.png" width="500">
</p>
### Motors
#### Stepper vs. Servo
Motors can be considered one of the core elements of my project.
There are different types of motors, however for my purposes specific precision was required. The main options were: Stepper and Servo motors.

After some further research I found such comparison of both motor types.

A stepper motor if your application meets any of the following criteria:

- Low speed and high accuracy
- Short, rapid repetitive movements
- High torque and low speed
- You prefer simple control

Steppers have the advantages of lower system costs, minimum system tuning, low maintenance, and rugged construction.

Go with a servo motor if your application meets any of these requirements:

- Control of the applied force
- Requirements for high speeds
- Dynamic motion profiles

After reading this points it becomes clear that the best choice for me is to use **stepper motors** in my project

### CNC shield
**Computer Numeric Control (CNC)** shield is a circuit board that connects to Arduino and in my case is required to control stepper motors.

<p align="center">
<img src="https://i.imgur.com/QzwmnPU.png" width="500">
</p>

### Moving axes

This is the main issue which I assume will require a long time to find a good soulution to it. Despite of that, after several sketches and assumptions I came to a conclusion that the mechanism will have to move the axes with rubber bands. The main reason for choosing this solution is the stability and percisions of a such solution. 

The smallest axis which is responsible for lifting up and lowering down the "pen" can be considered rather special due to the fact that it does not need a stepper motor which may save some costs. 

### Time Plan


| Time Period | Task |
| ---- | ---- |
| April-May     | Order and receive main materials, start creating first prototypes (a simple structure to test an idea with axes and rubber bands)|
|  June-July    | Confirm at least one working solution (definition of "working" – the plotter can move continuously at least on one axis without causing any issues)|
| Summer Break | Research the best file format and complete a general software part research.
| August-October | Further work on hardware, combination of two axes, if success start working on the lifting mechanism. |
