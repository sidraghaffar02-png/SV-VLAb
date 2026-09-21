# SV-VLAb
# Delivery Robot State Model

This project represents the working of a delivery robot using a **state model**.

### States

* **IDLE** – Waits for a delivery request.
* **NAVIGATING** – Moves toward the destination.
* **AVOIDING_OBSTACLE** – Handles detected obstacles.
* **DELIVERING** – Delivers the package.
* **RETURNING** – Returns to the warehouse.

The model includes **10 requirements** and **7 state transitions** that describe how the robot responds to delivery requests, obstacles, successful deliveries, and critical battery levels.
