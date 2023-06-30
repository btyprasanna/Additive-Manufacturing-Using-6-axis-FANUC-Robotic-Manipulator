# Additive Manufacturing using 6-axis FANUC Robotic Manipulator

<p align="justify">
This repository contains the code and documentation for an Additive Manufacturing system implemented using a Fanuc LR Mate 200iD 6-axis robotic manipulator. The system is designed to perform 3D printing using a MK8 extruder, which is connected to the end effector of the robot using a custom-designed L bracket. The extruder includes a stepper motor for filament feeding, a heater coil, and a 0.4mm nozzle. The system is controlled by a Ramps 1.4 board connected to an Arduino Mega, which runs the Marlin firmware.
</p>

![Additive Manufacturing](https://github.com/your-username/additive-manufacturing/images/additive_manufacturing.jpg)
> Image for illustration purposes only.

## Index

- [Hardware Components 🔌](#hardware-components)
- [Software Reqs](#software-reqs)
- [System Configuration](#system-configuration)
  - [L Bracket Design](#l-bracket-design)
  - [Robot Configuration](#robot-configuration)
  - [Toolpath Generation](#toolpath-generation)
- [Usage](#usage)

## Hardware Components

- [FANUC LR Mate 200iD](https://www.fanucamerica.com/products/robots/series/lr-mate/lr-mate-200id)
- [MK8 Extruder](https://www.example.com/mk8-extruder)
- [Stepper Motor](https://www.example.com/stepper-motor)
- [Heater Coil](https://www.example.com/heater-coil)
- [0.4mm Nozzle](https://www.example.com/0.4mm-nozzle)
- [Ramps 1.4](https://www.example.com/ramps-1.4)
- [Arduino Mega](https://www.example.com/arduino-mega)

## Software Reqs

- [Marlin Firmware](https://marlinfw.org/)
- [RoboDK](https://robodk.com/)

## System Configuration

### L Bracket Design:

<p align="justify">
Create a custom-designed L bracket using CAD software to attach the MK8 extruder to the end effector of the Fanuc robot. Ensure proper alignment and stability of the extruder.
</p>

### Robot Configuration:

<p align="justify">
Configure the user frame and tool frame of the Fanuc robot according to the position of the printing bed base surface. This ensures accurate positioning and movement of the robot during the 3D printing process.
</p>

### Toolpath Generation:

<p align="justify">
Use RoboDK software to generate the toolpath for printing specific CAD designs. Import the CAD models and define the printing parameters such as layer height, print speed, and extrusion temperature. Generate the robot program that includes the necessary movements and commands for the additive manufacturing process.
</p>

## Usage

- Ensure all hardware components are properly connected and powered on.
- Upload the Marlin firmware to the Arduino Mega connected to the Ramps 1.4 board. Configure the firmware with the appropriate settings for filament feeding, heater control, and temperature.
- Load the generated robot program onto the teach pendant of the Fanuc robot.
- Position the printing bed and ensure it is properly leveled.
- Start the 3D printing process by executing the robot program.
- Monitor the printing progress and make any necessary adjustments to ensure successful printing.

***Note:*** This repository is intended for educational and research purposes. Follow safety guidelines and precautions while working with the additive manufacturing system.
