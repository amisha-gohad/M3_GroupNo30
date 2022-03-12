# REPORT

## INTRODUCTION
A Remote Keyless Entry system consists of a remote, which, when activated within a certain range, can lock, unlock, alarm and approach light functions within a car. A remote keyless system works with the help of radio waves. This Remote Keyless Entry systems allow you to unlock and lock the doors of your vehicle by only pressing few buttons on the Remote, without using a traditional key. This terminology of Remote Keyless System is commonly used in Automotive technology. This system is commonly used to protect vehicles from theft.
<br/>

## DETAILED REQUIREMENTS
### High Level Requirements
| ID | Description | 
| ----- | ----- | 
| HLR01 | The car should LOCK |
| HLR02 | The car should UNLOCK |
| HLR03 | It should Activate/Deactivate the alarm |
| HLR04 | It should glow Approach lights for indication |

### Low level Requirements
| ID | Description | HLR ID |
| ------ | --------- | ------ |
| LLR01 | When button will pressed for 1 time, all LED should ON | HLR01 |
| LLR02 | When button will pressed for 2 times, all LED shouLd OFF| HLR02 |
| LLR03 | When button will pressed for 2 times, all LED should glow in clockwise direction | HLR03 |
| LLR04 | When button will pressed for 4 times, all LED should glow in anticlockwise direction | HRL04 |
<br/>
<br/>


## 5W's and 1'H
### What
- Keyless entry systems are used to remotely lock, unlock and can have various function.

### When
- Within a range of distance when a button is pushed, it sends a coded signal by radio waves to a receiver unit in a car, which locks or unclocks the door and do the task require.

### Who
- Those who have access to the car.

### Why
- Remote keyless entry systems alarm the vehicle against theft and lock and unlock the doors.

### Where
- Can operate from inside and outside the car.

### How
- Keyless entry to a vehicle is usually attained by sending a radio frequency signal from a remote transmitter to the receiver in the car.
<br/>

## SWOT analysis 
![SWOT](https://user-images.githubusercontent.com/98867361/157837421-d474736e-bfa2-428c-a5bc-46cb44707dc0.png)
<br/>

## Applications
-  Can be used in Automotive applications.
<br/>

# ARCHITECTURE

## Behavioral Diagram
### High Level Flow Chart Behavioral Diagram
<img width="480" alt="High Level Flow chart Behavioral Diagram" src="https://user-images.githubusercontent.com/98808752/157857611-21108c8a-1d2d-4309-a90c-d01993727cf6.png">

### Low Level Flow Chart Behavioral Diagram
<img width="382" alt="Low Level Flow chart Behavioral Diagram" src="https://user-images.githubusercontent.com/98808752/157858214-b49bbc8a-b3c4-49f6-87b9-7736adefc53b.png">
<br/>

## Structural Diagram
### High Level UML Use Case Structural Diagram
<img width="755" alt="High Level UML Use Case Structural Diagram" src="https://user-images.githubusercontent.com/98808752/157858273-967edf23-e16e-4d91-a8d9-a9c5b125971d.png">

### Low Level UML Use Case Structural Diagram
<img width="492" alt="Low Level UML Use Case Structural Diagram" src="https://user-images.githubusercontent.com/98808752/157858282-0a829c12-087f-47e0-a476-cd461734bb79.png">
<br/>

# Test plan and output

## HIGH LEVEL TEST PLAN / Integrated test plan

| Test ID | Description | Input | Expected output | Actual Output | PASSED/NOT |
| --- | --- | --- | --- | --- | --- |
| 01 | LOCK | PRESS USER BUTTON ONCE  | Shall LOCK THE CAR | SHALL LOCK THE CAR  | SUCCESS |
| 02 | UNLOCK | PRESS USER BUTTON TWICE | Shall UNLOCK THE CAR |  SHALL UNLOCK THE CAR | SUCCESS |
| 03 | ALARM ACTIVATE / DEACTIVATE | PRESS USER BUTTON THRICE | SHALL ACTIVATE / DEACTIVATE ALARM  | Shall ACTIVATE / DEACTIVATE ALARM | SUCCESS |
| 04 | APPROACH LIGHT | PRESS USER BUTTON FOUR TIMES | SHALL TURN ON THE approach light | SHALL TURN ON APPROACH LIGHT | SUCCESS |
<br/>

## LOW LEVEL TEST PLAN

| Test ID (for LOCK)| Description | Input | Expected output | Actual Output | PASSED/NOT |
| --- | --- | --- | --- | --- | --- |
| 01 | Check for LOCK | UPRESS USER BUTTON ONCE  | Shall ON all THE LED's as per ENCRYPTION | Shall ON all THE LED's as per ENCRYPTION | SUCCESS |
| 02 | Check for UNLOCK | PRESS USER BUTTON TWICE  | Shall OFF all THE LED's as per ENCRYPTION | Shall OFF all THE LED's as per ENCRYPTION | SUCCESS |
| 03 | Check IF THE ALARM ACTIVATE/DEACTIVATE | PRESS USER BUTTON THRICE | Shall ON THE LED's ONCE clockwise as per ENCRYPTION |  Shall ON THE LED's ONCE clockwise | SUCCEESS |
| 04 | Check for THE APPROACH LIGHT | PRESS USER BUTTON FOUR TIMES | Shall ON LED's once anti-clockwise as per ENCRYPTION |  Shall ON LED's once anti-clockwise | SUCCEESS |
<br/>
