# Assembly Guide

## Introduction
This guide provides step-by-step instructions for assembling your CNC Pen Plotter.

## Materials Needed
- Frame components (Aluminum/Wood/Plastic)
- Linear rails and bearings
- Stepper motors
- Microcontroller (Arduino)
- Stepper motor drivers
- Power supply
- Wiring
- Belts and pulleys
- Pen holder mechanism
- Screws and bolts

## Steps

### 1. Frame Assembly
1. Gather all frame components as per the design provided in `hardware/frame_design/frame_design.pdf`.
2. Assemble the frame using screws and bolts. Ensure all joints are tight and the frame is stable.

### 2. Motion System
1. Attach the linear rails and bearings to the frame.
2. Install the stepper motors at designated locations on the frame.
3. Connect the belts and pulleys to the stepper motors and linear rails.

### 3. Electronics Integration
1. Connect the stepper motors to the stepper motor drivers.
2. Wire the limit switches and connect them to the microcontroller.
3. Connect the power supply to the microcontroller and motor drivers.
4. Ensure all connections are secure and properly insulated.

### 4. Pen Holder Mechanism
1. Attach the pen holder to the movable part of the linear rail.
2. Ensure the pen can be easily installed and removed.

## Calibration
1. Connect the microcontroller to your computer.
2. Install the GRBL firmware on the Arduino as per the instructions in the firmware folder.
3. Use the Universal Gcode Sender (UGS) to send calibration commands.
4. Adjust the system to ensure precise and accurate drawing.

## Troubleshooting
- **Stepper Motor Not Moving:** Check wiring and connections.
- **Inaccurate Drawing:** Recalibrate the system and ensure the frame is stable.
- **Pen Not Drawing:** Check the pen installation and ensure it has ink.

For more details, refer to the diagrams in `docs/images/diagram.png`.
