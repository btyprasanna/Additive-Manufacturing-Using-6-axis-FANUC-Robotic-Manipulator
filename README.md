# Additive Manufacturing using 6-axis FANUC Robotic Manipulator

This repository contains the code and documentation for an Additive Manufacturing system implemented using a Fanuc LR Mate 200iD 6-axis robotic manipulator. The system is designed to perform 3D printing using a MK8 extruder, which is connected to the end effector of the robot using a custom-designed L bracket. The extruder includes a stepper motor for filament feeding, a heater coil, and a 0.4mm nozzle. The system is controlled by a Ramps 1.4 board connected to an Arduino Mega, which runs the Marlin firmware.

![Additive Manufacturing](https://github.com/your-username/additive-manufacturing/images/additive_manufacturing.jpg)
> All project images and videos were taken by me unless stated otherwise.

## Index

- [Features](#features)
- [Hardware Components 🔌](#hardware-components)
- [Software Reqs](#software-reqs)
- [System Configuration](#system-configuration)
  - [L Bracket Design](#l-bracket-design)
  - [Robot Configuration](#robot-configuration)
  - [Programming the Arduino Mega with Marlin Firmware](#programming-the-arduino-mega-with-marlin-firmware)
  - [Toolpath Generation](#toolpath-generation)
  - [System Calibration and Testing](#system-calibration-and-testing)
- [Usage](#usage)


## Features

- Utilizes the Fanuc LR Mate 200iD 6-axis robotic manipulator for precise and flexible 3D printing.
- Integration of the MK8 extruder with a stepper motor for accurate filament feeding.
- Control of the extruder's heater coil and temperature using the Ramps 1.4 board and Arduino Mega with Marlin firmware.
- Custom-designed L bracket to securely attach the extruder to the end effector of the robot.
- System configuration with user frame and tool frame to ensure proper positioning and movement during 3D printing.
- Toolpath generation using RoboDK software to generate precise and optimized paths for printing CAD designs.
- Seamless execution of the generated robot program uploaded to the Fanuc robot's teach pendant.
- Real-time monitoring of the printing process to ensure successful and reliable additive manufacturing.


## Hardware Components

- [FANUC LR Mate 200iD](https://www.fanucamerica.com/products/robots/series/lr-mate/lr-mate-200id)
- [MK8 Extruder](https://www.example.com/mk8-extruder)
- [Stepper Motor](https://www.example.com/stepper-motor)
- [Heater Coil](https://www.example.com/heater-coil)
- [0.4mm Nozzle](https://www.example.com/0.4mm-nozzle)
- [Ramps 1.4](https://www.example.com/ramps-1.4)
- [Arduino Mega](https://www.example.com/arduino-mega)
- Filament


## Software Reqs

- [Marlin Firmware](https://marlinfw.org/)
- [RoboDK](https://robodk.com/)


## System Configuration

### L Bracket Design:

Create a custom-designed L bracket using CAD software to attach the MK8 extruder to the end effector of the Fanuc robot. Ensure proper alignment and stability of the extruder.

### Robot Configuration:

Configure the user frame and tool frame of the Fanuc robot according to the position of the printing bed base surface. This ensures accurate positioning and movement of the robot during the 3D printing process.

### Programming the Arduino Mega with Marlin Firmware:

Program the Arduino Mega with Marlin firmware using Arduino IDE software. Connect the Arduino Mega to the Ramps 1.4 board and upload the firmware. Configure the firmware with the appropriate settings for filament feeding, heater control, and temperature. This firmware will control the operation of the MK8 extruder during the 3D printing process.

### Toolpath Generation:

Use RoboDK software to generate the toolpath for printing specific CAD designs. Import the CAD models and define the printing parameters such as layer height, print speed, and extrusion temperature. Generate the robot program that includes the necessary movements and commands for the additive manufacturing process.

### System Calibration and Testing:

Calibrate the robot and the additive manufacturing system to ensure precise movements and accurate 3D printing. Verify the alignment and functionality of the extruder, including filament feeding, heater control, and temperature regulation. Perform testing to ensure proper extrusion, layer adhesion, and overall print quality. Fine-tune system parameters as needed to achieve optimal performance and reliability.

## Usage

- Ensure all hardware components are properly connected and powered on.
- Upload the Marlin firmware to the Arduino Mega connected to the Ramps 1.4 board. Configure the firmware with the appropriate settings for filament feeding, heater control, and temperature.
- Load the generated robot program onto the teach pendant of the Fanuc robot.
- Position the printing bed and ensure it is properly leveled.
- Start the 3D printing process by executing the robot program.
- Monitor the printing progress and make any necessary adjustments to ensure successful printing.

***Note:*** This repository is intended for educational and research purposes. Follow safety guidelines and precautions while working with the additive manufacturing system.
