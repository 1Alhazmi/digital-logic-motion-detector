# Arduino-Based Motion Detection

A Digital Logic Design (CEN2011T) final project demonstrating motion detection and automatic LED control using an Arduino Uno R3 and a passive infrared (PIR) sensor. The circuit is simulated in Tinkercad.

## Interactive circuit

**[Open the circuit and simulation in Tinkercad](https://www.tinkercad.com/things/3JmI1qsUgJa-arduino-based-motion-detection)**

Open the Tinkercad design to inspect the circuit connections, view the control logic, and run the simulation.

## Project overview

Developed as a university team project with five members, dated 14 December 2025. The system reads the PIR sensor signal and switches an LED on when movement is detected and off otherwise.

The project connects input/output control, conditional logic, and sensor integration with a practical circuit simulation.

## Components

| Component | Purpose |
| --- | --- |
| Arduino Uno R3 | Reads the sensor input and controls the LED |
| PIR motion sensor | Detects infrared changes associated with movement |
| LED | Indicates detected motion |
| Resistor | Limits current through the LED |
| Breadboard and jumper wires | Connect the circuit components |

## How it works

1. The PIR sensor detects movement.
2. The Arduino reads the sensor signal.
3. Conditional control logic switches the LED on or off.
4. The LED provides a visible indication of the motion state.

| Motion state | LED state |
| --- | --- |
| Motion detected | On |
| No motion detected | Off |

## Tools and concepts

- Tinkercad Circuits and block-based control logic
- Arduino Uno R3
- Sensor input and LED output
- Conditional statements and continuous monitoring
- Circuit prototyping and digital logic

## Project materials

- **Circuit and simulation:** [Tinkercad design](https://www.tinkercad.com/things/3JmI1qsUgJa-arduino-based-motion-detection)
- **Project overview:** this README

## Credits and license

This is a team academic project and a remix of an existing Tinkercad circuit. Refer to the Tinkercad design for its remix attribution and circuit license. No separate license has been assigned to this repository.
