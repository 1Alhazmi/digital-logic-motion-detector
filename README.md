# Arduino PIR Motion Detection System

A Digital Logic Design (CEN2011T) final project dated 14 December 2025. Although the source filename contains “lab”, its cover explicitly labels it **Final project**. It is the course-end hardware project.

## Repository status

This repository currently publishes the project overview. The supporting files described below are prepared locally but have not yet been uploaded to GitHub. File paths describe that prepared package; they are not download links.

## Prepared project material

Project report and component illustrations — `docs/project-report.md`

The report describes an Arduino board, PIR motion sensor, LED, resistor and breadboard. A HIGH sensor signal turns the LED on; a LOW signal turns it off. It discusses component functions, operating environment, applications and future improvements.

## Components and signal flow

| Component | Function |
| --- | --- |
| PIR sensor | Detects changes in infrared radiation associated with movement |
| Arduino board | Reads the sensor's digital output and controls the indicator |
| LED | Provides a visible motion indication |
| Resistor | Limits current through the LED |
| Breadboard | Holds prototype connections |

Signal flow: movement → PIR sensor → digital HIGH/LOW input → Arduino decision → LED output. A PIR sensor senses infrared changes; it does not identify a person or record images.

## Digital logic demonstrated

| Sensor output | Meaning in the report | LED output |
| --- | --- | --- |
| LOW | No motion detected | Off |
| HIGH | Motion detected | On |

This project applies binary input/output, conditional control and hardware integration. The report discusses operating conditions, possible applications and future improvements. Exact wiring pins and an executable sketch are not available in the located submission.

## Team

Group 1: تركي السفياني، بسام الدوسري، عبدالرحمن الحازمي، عبدالله حسين، فيصل الصبحي. Individual implementation roles are not specified in the report.

## Available material and limits

This is a documentation portfolio entry. No original Arduino sketch, circuit schematic or final demonstration video was located with the report. The included images are component illustrations extracted from the submission, not photographs proving the circuit build. No code, pin assignments or hardware results have been invented. Hardware operation has not been independently tested.

## Publication

Academic portfolio documentation. Team credits are retained. No license has been selected.
