| Req-ID | Requirement                                                                                                 | Priority |
| ------ | ----------------------------------------------------------------------------------------------------------- | -------- |
| R-01   | When powered on, the robot must wait in IDLE until a delivery order is assigned.                            | High     |
| R-02   | A valid delivery request must cause the robot to begin its journey to the given location.                   | High     |
| R-03   | While moving, the robot must keep checking the area around it for possible obstacles.                       | High     |
| R-04   | Finding an obstacle must cause the robot to switch to its avoidance state.                                  | High     |
| R-05   | Once the path is clear, the robot must leave avoidance mode and continue toward the delivery location.      | High     |
| R-06   | Upon arriving at the destination, the robot must initiate the package handover.                             | High     |
| R-07   | After the package has been delivered, the robot must make its way back to the warehouse.                    | High     |
| R-08   | A critically low battery must interrupt the current trip and cause the robot to head back to the warehouse. | High     |
| R-09   | After returning to the warehouse, the robot must change back to the IDLE state.                             | High     |
| R-10   | The robot must not begin package delivery while in IDLE or during obstacle avoidance.                       | High     |
