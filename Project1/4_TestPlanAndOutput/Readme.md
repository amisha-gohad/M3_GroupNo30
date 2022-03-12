# Test plan and output

### Test plan is created and verified

## HIGH LEVEL TEST PLAN / Integrated test plan

| Test ID | Description | Input | Expected output | Actual Output | PASSED/NOT |
| --- | --- | --- | --- | --- | --- |
| 01 | LOCK | PRESS USER BUTTON ONCE  | Shall LOCK THE CAR | SHALL LOCK THE CAR  | SUCCESS |
| 02 | UNLOCK | PRESS USER BUTTON TWICE | Shall UNLOCK THE CAR |  SHALL UNLOCK THE CAR | SUCCESS |
| 03 | ALARM ACTIVATE / DEACTIVATE | PRESS USER BUTTON THRICE | SHALL ACTIVATE / DEACTIVATE ALARM  | Shall ACTIVATE / DEACTIVATE ALARM | SUCCESS |
| 04 | APPROACH LIGHT | PRESS USER BUTTON FOUR TIMES | SHALL TURN ON THE approach light | SHALL TURN ON APPROACH LIGHT | SUCCESS |



## LOW LEVEL TEST PLAN

| Test ID (for LOCK)| Description | Input | Expected output | Actual Output | PASSED/NOT |
| --- | --- | --- | --- | --- | --- |
| 01 | Check for LOCK | UPRESS USER BUTTON ONCE  | Shall ON all THE LED's as per ENCRYPTION | Shall ON all THE LED's as per ENCRYPTION | SUCCESS |
| 02 | Check for UNLOCK | PRESS USER BUTTON TWICE  | Shall OFF all THE LED's as per ENCRYPTION | Shall OFF all THE LED's as per ENCRYPTION | SUCCESS |
| 03 | Check IF THE ALARM ACTIVATE/DEACTIVATE | PRESS USER BUTTON THRICE | Shall ON THE LED's ONCE clockwise as per ENCRYPTION |  Shall ON THE LED's ONCE clockwise | SUCCEESS |
| 04 | Check for THE APPROACH LIGHT | PRESS USER BUTTON FOUR TIMES | Shall ON LED's once anti-clockwise as per ENCRYPTION |  Shall ON LED's once anti-clockwise | SUCCEESS |
<br/>

# OUTPUT

### Output when switch is pressed for 1 time all LED are ON 
![All LED ON](https://user-images.githubusercontent.com/98867361/157999651-b1f84a65-6357-45f7-b9c2-74ce92898500.png)

### Output when switch is pressed for 2 times all LED are OFF
![All LED OFF](https://user-images.githubusercontent.com/98867361/157999664-c49cfa3b-9f1e-419e-9127-fb5f55f32754.png)
