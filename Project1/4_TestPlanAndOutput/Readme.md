# Test plan and output

### Test plan is created and verified

## HIGH LEVEL TEST PLAN / Integrated test plan

| Test ID | Description | Input | Expected output | Actual Output | 
| --- | --- | --- | --- | --- | 
| 01 | LOCK | PRESS USER BUTTON ONCE  | Shall LOCK THE CAR | SHALL LOCK THE CAR  | 
| 02 | UNLOCK | PRESS USER BUTTON TWICE | Shall UNLOCK THE CAR |  SHALL UNLOCK THE CAR | 
| 03 | ALARM ACTIVATE / DEACTIVATE | PRESS USER BUTTON THRICE | SHALL ACTIVATE / DEACTIVATE ALARM  | Shall ACTIVATE / DEACTIVATE ALARM |
| 04 | APPROACH LIGHT | PRESS USER BUTTON FOUR TIMES | SHALL TURN ON THE approach light | SHALL TURN ON APPROACH LIGHT |
| 05 |  ENCRYPTION | 1 OR 2 0R 3 0R 4 | Encrypted Data for 1/2/3/4 | Encrypted Data for 1/2/3/4 |


## LOW LEVEL TEST PLAN

| Test ID (for LOCK)| Description | Input | Expected output | Actual Output | PASSED/NOT |
| --- | --- | --- | --- | --- | --- |
| 01 | Check for LOCK | UPRESS USER BUTTON ONCE  | Shall ON all THE LED's as per ENCRYPTION | Shall ON all THE LED's as per ENCRYPTION | ✅ |
| 02 | Check for UNLOCK | PRESS USER BUTTON TWICE  | Shall OFF all THE LED's as per ENCRYPTION | Shall OFF all THE LED's as per ENCRYPTION | ✅ |
| 03 | Check IF THE ALARM ACTIVATE/DEACTIVATE | PRESS USER BUTTON THRICE | Shall ON THE LED's ONCE clockwise as per ENCRYPTION |  Shall ON THE LED's ONCE clockwise as per ENCRYPTION | ✅ |
| 04 | Check for THE APPROACH LIGHT | PRESS USER BUTTON FOUR TIMES | Shall ON LED's once anti-clockwise as per ENCRYPTION |  Shall ON LED's once anti-clockwise as per ENCRYPTION | ✅ |
| 05 | Check for ENCRYPTION | 1/2/3/4  | 1244/1843/6789/5478 | 1244/1843/6789/5478 | ✅ |
| 06 | Check for btn_press() | counts no of button press  | 1/2/3/4 | 1/2/3/4 | ✅ |

