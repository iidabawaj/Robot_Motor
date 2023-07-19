# Robot_Motors
Task 2 of the Electrical Engineering path.

. Servo Motor Circuit

. DC Motor Circuit

## Servo Motor
The first motor is a Servo motor which is a popular and widely used motor for robotics projects, automation, and RC models.

A servo motor is a closed-loop system that uses position feedback to control its motion and final position. Its main feature is the ability to precisely control the position of its shaft, the angle of the motor is 0 - 180 degrees.

https://github.com/iidabawaj/Robot_Motor/assets/139181626/990dfe8b-e0e0-444f-8321-95ae10b4d53f

### Requirements
. Arduino Uno R3

. Breadboard Small

. Micro Servo


### Circuit 
Servo motors have three wires: power, ground, and signal. The power wire is connected to the 5V pin on the Arduino board, The ground wire is connected to a ground pin on the board, and the signal pin is connected to pin number 9. Because digital ports have either 0 or 1 ( which refers to either off or on) signals, we connect the signal pin to pin 9 (or any pin with a Tilda sign) which is a PWM pin that contains pulse modulation that turns the digital port into an analog port which varies the time between the on signal and off signal to create a value then use the value to control things, in our case, control the servo motor.


### Code 
Because the Servo motor rotates in 1-180 degrees, we use a for loop called a "time loop" that counts up from position 0 to position 179, then counts down from position 179 to position 0, and the loop goes on.

## DC Motor 
The second motor is a DC (Direct Current) motor which is a type of electric machine that converts electrical energy into mechanical energy.

https://github.com/iidabawaj/Robot_Motor/assets/139181626/e057f1b7-9354-47e3-8548-c1e8595b3342

### Requirement 
.Arduino Uno R3

.Breadboard

.DC Motor

.NPN Transistor

.5.10 V Zener Diode 

.270 Ohm Resistor 


### Circuit 
DC motors normally have just two wires: power and ground, one positive and one negative. If you connect these two leads directly to a battery, the motor will rotate. If you switch the leads, the motor will rotate in the opposite direction. The DC motors are used in applications where continuous rotation is required. Such as Remote controlled cars, fans, and elevators.




