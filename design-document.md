## Electronics

### Arduino Board 
#### Rev3
![](https://i.imgur.com/cXYPimo.png)
#### Rev4
![](https://i.imgur.com/BRROWqP.png)
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

<img src="https://i.imgur.com/QzwmnPU.png" width="200">
