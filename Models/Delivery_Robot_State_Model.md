# Delivery Robot State Model

| State ID | State | Description | Entry Condition | Exit Condition |
|---|---|---|---|---|
| 01 | IDLE | Robot is switched on, waiting for a delivery request. | Robot is switched on or reaches the warehouse. | Delivery Request Received |
| 02 | NAVIGATING | Robot is moving toward the delivery destination and monitoring its surroundings and battery. | A valid delivery request is received. | Destination Reached, Obstacle Detected, or Critical Battery |
| 03 | AVOIDING_OBSTACLE | Robot temporarily stops normal navigation and handles an detected obstacle. | Obstacle is detected while navigating. | Obstacle Avoided |
| 04 | DELIVERING | Robot performs the package delivery at the destination. | Robot reaches the destination. | Delivery Successful |
| 05 | RETURNING | Robot travels back toward the warehouse after delivery or because of critically low battery. | Delivery is successful or battery becomes critically low. | Warehouse Reached |
