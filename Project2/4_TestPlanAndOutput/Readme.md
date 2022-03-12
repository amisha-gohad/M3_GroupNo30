
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

# OUTPUT

* Output when switch is pressed for 1 time all LED are ON 
![All LED ON](https://user-images.githubusercontent.com/98867361/157999651-b1f84a65-6357-45f7-b9c2-74ce92898500.png)

* Output when switch is pressed for 2 times all LED are OFF
![All LED OFF](https://user-images.githubusercontent.com/98867361/157999664-c49cfa3b-9f1e-419e-9127-fb5f55f32754.png)
