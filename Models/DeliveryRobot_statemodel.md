# Delivery Robot State Model

| State-ID | State Name | Description | Entry Condition | Exit Condition |
|---|---|---|---|---|
| S-01 | IDLE | The robot is waiting for a delivery request. | Robot is switched on or reaches the warehouse. | Delivery request is received. |
| S-02 | NAVIGATING | The robot is moving toward the delivery destination. | Delivery request is received or an obstacle has been avoided. | Destination is reached, an obstacle is detected, or battery becomes critically low. |
| S-03 | AVOIDING_OBSTACLE | The robot is temporarily dealing with an obstacle. | An obstacle is detected while navigating. | The obstacle is successfully avoided. |
| S-04 | DELIVERING | The robot is performing the package delivery at the destination. | The destination is reached. | Package is successfully delivered. |
| S-05 | RETURNING | The robot is travelling back to the warehouse. | Package is successfully delivered or battery becomes critically low. | Warehouse is reached. |
