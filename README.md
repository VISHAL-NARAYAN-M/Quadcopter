# Manual Quadcopter Drone using Pixhawk 4.8



This project documents the development of a manually controlled quadcopter using the Pixhawk 4.8 flight controller. The drone is assembled from standard parts and flown using a radio transmitter in stabilized/manual mode.



##  Features

- Manually operated via RC transmitter

- Pixhawk 4.8 for flight control and stabilization

- Configured using Mission Planner

- Custom-built quadcopter frame (e.g., F450)

- BLDC motors + ESCs + LiPo power system



##  Components Used

- **Flight Controller:** Pixhawk 4.8

- **Frame:** F450 Quadcopter Frame

- **Motors:** 1000KV BLDC

- **ESCs:** 30A ESCs

- **Battery:** 3S/4S LiPo (2200mAh)

- **Propellers:** 10x4.5

- **Transmitter/Receiver:** FS-i6 or equivalent

- **Misc:** Power Distribution Board, XT60 connectors, GPS (optional)



## Setup Process

1. Assemble frame and mount all components.

2. Connect ESCs and motors to Pixhawk via PDB.

3. Calibrate Pixhawk using Mission Planner.

4. Bind transmitter with receiver.

5. Power up and test motor directions.

6. Arm the drone and test flight in open area.







## Repository Contents

- `docs/` – Setup instructions or wiring diagram 

- `README.md` – This file



##  Notes

This drone is purely manually operated and does not include autonomous features or sensors. It can be upgraded in the future with GPS, telemetry, or computer vision modules.



##  Author

Vishal Narayan M
