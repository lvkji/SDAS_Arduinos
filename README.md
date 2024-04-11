# SDAS_Arduinos
Self Adaptive Distributed Systems (SADS) is an innovative project designed to demonstrate the principles of distributed computing using physical hardware networks. The project utilizes a series of interconnected Arduino devices to create a robust network capable of communicating data and security-related information autonomously. This system exemplifies how distributed devices can share information, make collective decisions, and adapt to changes within the network dynamically.

Features
Data Communication: Seamless transmission of data between Arduino devices over a network.
Security Information Sharing: Enhanced protocols for exchanging security credentials and encryption keys securely.
Autonomous Decision Making: Devices assess shared data to make decisions without human intervention.
Adaptive Behavior: The system adjusts its operations in response to the network's communication state and the collective data from all devices.
Scalability: Easily scalable to include more devices without significant changes to the core logic.
Fault Tolerance: Designed to handle failures within the network gracefully, ensuring continuous operation.

Project Components
Hardware
Arduino Boards: Multiple Arduino microcontrollers interconnected through a wireless module (e.g., NRF24L01+).
Sensors: Various sensors (temperature, motion, etc.) connected to Arduinos to simulate data collection in a distributed environment.
Power Supplies: Adequate power sources for each Arduino unit, ensuring stable operations across the network.

Software
Arduino Firmware: Custom firmware written for all Arduino devices to handle data transmission, security management, and decision-making processes.
Communication Protocol: A robust protocol designed specifically for this network to handle the nuances of data and security information transmission.
Adaptive Algorithms: Algorithms capable of adjusting operational parameters based on the data received from other devices in the network.
