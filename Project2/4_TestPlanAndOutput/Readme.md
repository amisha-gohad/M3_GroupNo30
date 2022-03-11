
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
