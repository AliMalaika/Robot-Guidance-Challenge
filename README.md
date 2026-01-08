# Robot-Guidance-Challenge
### Description:
Developed a fully autonomous line-following robot using Assembly on the HCS12 microcontroller. The robot navigates a maze using five analog sensors, handles intersections and dead ends, and provides real-time status updates on an LCD. A finite state machine was used to organize behaviors such as line following, alignment correction, turns, and obstacle recovery, ensuring predictable and modular control.

### Key Features:
- Implemented sensor polling, thresholding, and calibration to reliably detect lines and intersections despite variations in lighting and floor reflectivity.
- Designed a modular state machine to prioritize sensor inputs, handle navigation logic, and manage complex maze behaviors including dead-end recovery and backtracking.
- Integrated motor control routines with real-time decision-making to execute precise turns, alignment corrections, and path retracing.
- Implemented debugging strategies including variance tuning, state prioritization, and incremental testing to ensure reliable autonomous operation.

### Technologies Used:
Assembly (HCS12), Embedded Systems, Robotics, Real-Time Control, Sensor Integration, Finite State Machines

### Learning Outcomes:
- Gained hands-on experience designing and debugging complex embedded systems and low-level code.
- Applied structured software design, modular programming, and systematic testing in a hardware-in-the-loop environment.
- Developed practical problem-solving skills for real-time sensor processing, control logic, and autonomous navigation.
