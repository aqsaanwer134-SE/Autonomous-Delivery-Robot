# State Transition Verification Table

| Transition ID | From State | Event / Condition | To State | Requirement |
|---|---|---|---|---|
| 01 | IDLE | Delivery Request Received | NAVIGATING | R2 |
| 02 | NAVIGATING | Obstacle Detected | AVOIDING_OBSTACLE | R4 |
| 03 | AVOIDING_OBSTACLE | Obstacle Avoided | NAVIGATING | R5 |
| 04 | NAVIGATING | Destination Reached | DELIVERING | R6 |
| 05 | DELIVERING | Delivery Successful | RETURNING | R7 |
| 06 | NAVIGATING | Critical Battery | RETURNING | R8 |
| 07 | RETURNING | Warehouse Reached | IDLE | R9 |
