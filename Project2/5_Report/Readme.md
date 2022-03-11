# Report

## DESCRIPTION
 This project is a BiCom system.
 A BiCom system is the extention of the unidirectional RKE to bidirectional RKE system
 Its Identifying feature would be displayed by led signaling.
 This system is operated by broadcasting radio waves.
<br/>

## IDENTIFYING FEATURES
* It should display window status of car for oone user button click
* It should display alarm status of car for two user button click
* It should display battery information of car for three user button click
* It shoukd display door status of car for four user button click
<br/>

## STATE OF ART AND RESEARCH 
* Accessibilty of the buttons
* Window status ,battery status, alarm status, battery status is displayed with button press
<br/>


## SWOT ANALYSIS
![BiCom swot analysis](https://user-images.githubusercontent.com/98878326/157863301-2e2d7b0f-4a7f-4c25-abb4-5012d00e94f9.jpg)



# 5 W's and 1H
![5w 1h Bicom](https://user-images.githubusercontent.com/98878326/157863381-97e93efd-e975-40b4-8e71-dc6f955f8a2f.jpg)
<br/>


# REQUIREMENTS
## HIGH LEVEL REQUIREMENTS

| ID | High level requirements |
| -- |------------------------ |
| H1| it should display window status                 |
|H2|it should display alarm status |
|H3|it should display battery status |
|H4| it should display door status|
<br/>

## LOW LEVEL REQUIREMENTS

|ID| Low level requirements |
|--|-- |
|L1 |Press blue button 1 time. All led ON at the same time |
|L2 |Press blue button 2 times.All led off at the same time |
| L3|Press blue button 3 times. All led glow in clockwise direction |
|L4|Press blue button 4 times. All led glow in anticlockwise direction |
<br/>

# Architecture
  ## Bahavirol Diagrams

   * High Level Flow Chart

![image](https://user-images.githubusercontent.com/98864424/157810949-c1c1eb21-b7ea-4afa-9c0f-ae109978fce0.png)

   * Low Level Flow Chart

![image](https://user-images.githubusercontent.com/98864424/157812441-8865bb9c-7a83-4bf0-9b1c-9494f0eee44d.png)

  ## Structural Diagram

   * High Level Use Case Structural Diagram

![image](https://user-images.githubusercontent.com/98864424/157823602-08ab8235-77ed-4bca-b8af-d2bd223d42d5.png)

   * Low Level Use Case Structural Diagram
   
![image](https://user-images.githubusercontent.com/98864424/157828246-f325cbf5-b884-47a4-a5d8-2df95b49a003.png)
<br/>

# Testing(Manual Testing)
## High Level Testing
| Test ID | Description of Test case | Input values | Expected Output | Actual Output | Status |
|:-----:|:--------------------------:|:--------------:|:-----------------:|:---------------:|:---------:|
| H1  | Window Status| Switch Press Count 1 | Print Window Status | Print Window Status |SUCCESS|
| H2  | Alarm Status | Switch Press Count 2 | Print Alarm Status | Print Alarm Status | SUCCESS |
| H3  | Car Battery Status | Switch Press Count 3 | Print Car Battery Status | Print Car Battery Status | SUCCESS |
| H4  | Door Status | Switch Press Count 4 | Print Door Status | Print Door Status | SUCCESS |

## Low Level Testing
| Test ID | Description of Test case | Input values | Expected Output | Actual Output | Status |
|:-----:|:--------------------------:|:--------------:|:-----------------:|:---------------:|:---------:|
| L1  | Switch Press Count | Switch Press Count 1 | Switch Press Count(1/2/3/4) | Switch Press Count(1/2/3/4) |SUCCESS|
| L2  | Window Status| Switch Press Count 1 | All LED On | All LED On |SUCCESS|
| L3  | Alarm Status | Switch Press Count 2 | All LED Off | All LED Off | SUCCESS |
| L4  | Car Battery Status | Switch Press Count 3 | All LED blink is Clockwise Direction | All LED blink is Clockwise Direction | SUCCESS |
| L5  | Door Status | Switch Press Count 4 | All LED blink is Anticlockwise Direction | All LED blink is Anticlockwise Direction | SUCCESS |
