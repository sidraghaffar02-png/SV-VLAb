| Transaction ID | Current State | Trigger/Event                              | Next State | Req-ID |
| -------------- | ------------- | ------------------------------------------ | ---------- | ------ |
| T-01           | S-01          | A new delivery order is received           | S-02       | R-02   |
| T-02           | S-02          | An obstacle is found on the route          | S-03       | R-04   |
| T-03           | S-03          | The robot successfully clears the obstacle | S-02       | R-05   |
| T-04           | S-02          | The required delivery location is reached  | S-04       | R-06   |
| T-05           | S-04          | Package handover is completed              | S-05       | R-07   |
| T-06           | S-02          | Battery level reaches a critical point     | S-05       | R-08   |
| T-07           | S-05          | Robot arrives back at the warehouse        | S-01       | R-09   |
