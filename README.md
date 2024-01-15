# Festo-Modular-Production-System

The Festo Modular Production System II was a project that Ashleen Bains and Joshua Selikem worked on. The project consists of 3 wheel sorting stations connected by ethernet to an Allen-Bradley PLC. A Star Topology network was implemented to allow independent communication to each point I/O Module. Using a project based structure, the PLC uses 3 separate state machines coded in ladder logic. 

An HMI was also implemented to provide better functionality and information to an operator. The content of the HMI includes: 
- Virtual start buttons for each/all stations
- A visual display of all the wheels placed for each station
- A display of all the faults for each station
- A developer mode for each station which allows manual control of all motors and pneumatic actuators 

The main job of the Festo MPS II is to:
1. Determine a wheel’s material/colour using 3 different sensors.
2. Determine if the wheel is the correct size by using an analog distance sensor.
3. Sort acceptable wheels into their corresponding silo or reject unacceptable wheels. 

