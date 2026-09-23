# Delivery Robot Requirements

| Req. ID | Requirement Description | Priority |
|---|---|---|
| R1 | The robot shall remain in the IDLE state when it is switched on and no delivery request is available. | High |
| R2 | The robot shall start navigating toward the destination when a valid delivery request is received. | High |
| R3 | The robot shall continuously monitor its surroundings while navigating. | High |
| R4 | The robot shall enter the AVOIDING_OBSTACLE state when an obstacle is detected during navigation. | High |
| R5 | The robot shall resume navigation toward the destination after the obstacle has been successfully avoided. | High |
| R6 | The robot shall enter the DELIVERING state when it reaches the destination. | High |
| R7 | The robot shall return to the warehouse after the package has been successfully delivered. | High |
| R8 | The robot shall stop its current delivery journey and return to the warehouse when the battery becomes critically low. | High |
| R9 | The robot shall become IDLE after reaching the warehouse and wait for another delivery request. | High |
| R10 | The robot shall not enter the DELIVERING state directly from IDLE or while it is in AVOIDING_OBSTACLE. | High |
