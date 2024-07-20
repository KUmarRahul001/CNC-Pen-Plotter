# CNC Pen Plotter

Welcome to the CNC Pen Plotter project! This repository contains all the necessary files, instructions, and resources to build and operate your own CNC Pen Plotter.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Components](#components)
- [Assembly](#assembly)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The CNC Pen Plotter is a DIY project that combines mechanical design, electronics, and software to create a machine capable of drawing precise patterns and designs with a pen. This project is an excellent way to learn about CNC machines and explore the integration of various engineering disciplines.

## Features
- **Precision Drawing:** Achieves accurate and repeatable drawings.
- **DIY Build:** Constructed using easily available materials.
- **Open Source Software:** Utilizes GRBL firmware and Universal Gcode Sender (UGS) for control.

## Components
- **Mechanical Parts:**
  - Frame (Aluminum/Wood/Plastic)
  - Linear Rails and Bearings
  - Stepper Motors
  - Belts and Pulleys
  - Pen Holder Mechanism

- **Electronics:**
  - Microcontroller (Arduino)
  - Stepper Motor Drivers
  - Power Supply
  - Limit Switches
  - Wiring

- **Software:**
  - Inkscape 0.92.5 (for design and G-code generation)
  - Universal Gcode Sender (UGS) (for sending G-code to the plotter)

## Assembly
Detailed assembly instructions can be found in the [Assembly Guide](docs/assembly_guide.md).

### Steps:
1. **Frame Assembly:**
    - Assemble the frame using the provided design in `hardware/frame_design/frame_design.pdf`.
2. **Motion System:**
    - Attach the linear rails and bearings to the frame.
    - Install the stepper motors and connect them to the motion system.
3. **Electronics Integration:**
    - Connect the stepper motors to the motor drivers.
    - Wire the limit switches and connect them to the microcontroller.
    - Ensure all connections are secure and properly insulated.

## Usage
1. **Install the GRBL firmware on your Arduino:**
    - Follow the instructions in the GRBL repository to install the firmware on your Arduino.

2. **Design your artwork using Inkscape 0.92.5:**
    - Use Inkscape to create your design and convert it to G-code using the provided Inkscape extension (`software/inkscape_extension/gcode_tools.py`).

3. **Use Universal Gcode Sender (UGS):**
    - Open UGS (`software/UGS/UniversalGcodeSender.jar`) and connect it to your CNC Pen Plotter.
    - Load your G-code file and send it to the plotter.

4. **Calibrate the system:**
    - Follow the calibration steps in the [Assembly Guide](docs/assembly_guide.md) to ensure precise and accurate drawing.

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


