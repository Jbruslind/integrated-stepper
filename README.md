# Integrated Stepper

Full stepper motor control w/ local feedback and power conversion in a small package. The main idea was to have an all-in-one solution PCB which would run some open source FOC firmware (Simple-FOC for now) and have some higher level control through ethernet, CAN, or UART (CAN for now). 

Power and comms should be provided on the same wire harness either using RJ45 (original idea) or the XT30 + 2wire connector (current design) which allows for high voltage + current and 2wire comms. These can then be daisy chained to as many nodes as possible (limited by wire lengths for the most part)

## Key Features

- **High Precision:** Sub-degree positioning accuracy
- **Smooth Motion:** Advanced motion planning and acceleration control
- **Multiple Modes:** Position, velocity, and torque control modes
- **Microstepping:** Configurable microstepping for smooth operation
- **Communication:** UART, SPI, I2C, and CAN bus support

## Hardware Specifications

- **Current Rating:** Configurable current output up to 2A per phase continous
- **Voltage Range:** 8V to 35V operation
- **Microstepping:** Up to 256 microsteps per full step
- **Protection:** Overcurrent, overvoltage, and thermal protection

## Applications

- Industrial automation and conveyor systems
- Robotics and robot arms
- CNC machines and 3D printers
- Laser positioning systems
- Research and prototyping

## License

This project is open source and available under the MIT License.
