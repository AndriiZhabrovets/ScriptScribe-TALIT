## Electronics

### Arduino Board 
Due to a specific circuit board required for my project (CNC shield), the Arduino UNO was chosen. Both Rev3 and Rev4 are compatible with the CNC shield and my initial idea was to use Rev3 due to its potentially lower price. However, I managed to find Rev4 with a lower price than Rev3. So the Rev4 model is listed in the price table.

*Note: If a cheaper Rev3 is found, I am always open to buying it instead.*
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
Motors can be considered one of the core elements of my project. There are different types of motors available, but for my purposes a specific precision was required. The main options were Stepper and Servo motors.

After some further research I found a comparison of the two types of motor.

A stepper motor if your application meets any of the following criteria

- Low speed and high precision
- Short, fast, repetitive movements
- High torque and low speed
- You prefer simple control

Steppers have the advantages of lower system cost, minimal system tuning, low maintenance and robust construction.

Choose a servo motor if your application meets any of these requirements:

- Control of applied force
- High speed requirements
- Dynamic motion profiles

After reading these points, it is clear that the best choice for me is to use *stepper motors* in my project.
### CNC shield
**The Computer Numeric Control (CNC)** shield is a circuit board that connects to the Arduino, and in my case is needed to control stepper motors.

<p align="center">
<img src="https://i.imgur.com/QzwmnPU.png" width="500">
</p>

### Moving axes

This is the main problem and I suspect it will take a long time to find a good solution. Nevertheless, after several sketches and assumptions, I have come to the conclusion that the mechanism will have to move the axes with rubber bands. The main reason for choosing this solution is the stability and precision of such a solution.

The smallest axis, which is responsible for raising and lowering the "pen", can be considered quite special because it does not need a stepper motor, which can save some costs.

### Time Plan


| Time Period | Task |
| ---- | ---- |
| April-May     | Order and receive main materials, start creating first prototypes (a simple structure to test an idea with axes and rubber bands)|
|  June-July    | Confirm at least one working solution (definition of "working" – the plotter can move continuously at least on one axis without causing any issues)|
| Summer Break | Research the best file format and complete a general software part research.
| August-October | Further work on hardware, combination of two axes, if success start working on the lifting mechanism. |


### Price Table

| Index | Name                                                             | Link                                                                                                                                                                                                                                                                                                                                                                                                               | Price per Unit  | Amount | Price        |
| ----- | ---------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------- | ------ | ------------ |
| 1     | Uno Rev 4 WiFi                                                   | [hhttps://www.distrelec.ch/en/uno-rev-wifi-arduino-abx00087/p/30411157?trackQuery=Arduino%20Uno&pos=10&origPos=10&origPageSize=50&track=true&sid=92b1475d43ed1d626ded56036a9938e5dabea087&itemList=searchttps://www.distrelec.ch/en/uno-rev-wifi-arduino-abx00087/p/30411157?trackQuery=Arduino%20Uno&pos=10&origPos=10&origPageSize=50&track=true&sid=92b1475d43ed1d626ded56036a9938e5dabea087&itemList=search](https://www.distrelec.ch/en/uno-rev-wifi-arduino-abx00087/p/30411157?trackQuery=Arduino%20Uno&pos=10&origPos=10&origPageSize=50&track=true&sid=92b1475d43ed1d626ded56036a9938e5dabea087&itemList=search) |      25,90 CHF  | 1      |   25,90 CHF  |
| 2     | Stepper motor - NEMA-17 size - 200 steps/rev, 12V 350mA          | [https://www.adafruit.com/product/324](https://www.adafruit.com/product/324)                                                                                                                                                                                                                                                                                                                                       |      12,45 CHF  | 2      |   24,90 CHF  |
| 3     | CNC Shield A4988 Arduino für 3D Drucker und Fräsmaschinen (GRBL) | [https://www.bastelgarage.ch/cnc-shield-a4988-arduino-fur-3d-drucker-und-frasmaschinen-grbl](https://www.bastelgarage.ch/cnc-shield-a4988-arduino-fur-3d-drucker-und-frasmaschinen-grbl)                                                                                                                                                                                                                           |        8,90 CHF | 1      |     8,90 CHF |
| Total | | | | |59,70 CHF | 
