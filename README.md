# PulseCode: Smart Posture Monitoring Cushion (P.A.P.A.Y.A.)

## Overview

PulseCode (Posture Analysis and Proactive Alignment for Your Awareness) is a smart posture-monitoring cushion designed to encourage healthy sitting habits through real-time posture detection and vibrotactile feedback.

The system was developed as part of the BM1190 Engineering Design Project at the University of Moratuwa. It combines pressure sensing, distance sensing, embedded processing, and haptic feedback to identify poor sitting posture and provide unobtrusive corrective feedback to the user.

The project was awarded Second Runners-Up at Brainstorm 2025, a university-wide engineering innovation competition.

---

## Motivation

Poor sitting posture is a common contributor to musculoskeletal discomfort and long-term back pain among students and office workers. Many existing solutions rely on visual notifications, audio alerts, or wearable devices that may disrupt users during work.

PulseCode was developed as a non-intrusive posture awareness system that integrates directly into a seating environment and provides corrective feedback without significantly interrupting user activities.

---

## System Description

The system continuously monitors the user's sitting posture using an array of force-sensitive resistors and an ultrasonic distance sensor.

Pressure distribution across the seat and the distance between the user's back and the backrest are analyzed by an ATmega328P microcontroller. When posture deviations exceed predefined thresholds, a vibration motor provides haptic feedback, prompting the user to readjust their posture.

---

## Key Features

* Real-time posture monitoring
* Pressure-based seat occupancy and posture analysis
* Backrest distance measurement
* Vibrotactile posture correction feedback
* Battery-powered operation
* USB-C charging support
* Custom PCB implementation
* Custom-designed enclosure and cushion integration

---

## Hardware Components

| Component                 | Purpose                       |
| ------------------------- | ----------------------------- |
| ATmega328P                | Main processing unit          |
| FSR402 Sensors (8)        | Pressure sensing              |
| HC-SR04 Ultrasonic Sensor | Backrest distance measurement |
| Vibration Motor           | Haptic feedback               |
| Li-ion Battery Pack       | Portable power supply         |
| Custom PCB                | System integration            |

---

## System Architecture

![System Architecture](images/system_block_diagram.png.jpg)

The system consists of:

1. Pressure sensing subsystem
2. Distance sensing subsystem
3. Embedded processing unit
4. Haptic feedback subsystem
5. Battery management and power delivery circuitry

---

## Mechanical Design

The enclosure and structural components were designed in SOLIDWORKS to support integration of the electronics while maintaining user comfort and accessibility for maintenance.

![Enclosure Design](images/enclosure_design.jpg)

---

## Prototype

| Final Prototype                          | Internal Structure                        |
| ---------------------------------------- | ----------------------------------------- |
| ![Prototype](images/prototype_front.jpg) | ![Inside View](images/cushion_inside.jpg) |

---

## PCB Design

| PCB Layout                              |
| --------------------------------------- |
| ![PCB Layout 1](images/pcb_layout1.jpg) |
| ![PCB Layout 2](images/pcb_layout2.jpg) |

---

## Design Considerations

Several design decisions were made to improve user experience and encourage long-term adoption:

* Haptic feedback was selected instead of audio alerts to minimize disruption during work or study.
* Sensor placement was refined to improve posture detection reliability while maintaining comfort.
* Electronics were integrated within the cushion structure to reduce interference with normal seating behavior.
* The enclosure was designed to be compact, accessible, and comfortable for extended daily use.

---

## Project Outcomes

* Functional posture-monitoring prototype developed and tested
* Integrated sensing, embedded processing, and haptic feedback system
* Custom PCB and enclosure successfully implemented
* Recognition as Second Runners-Up at Brainstorm 2025

---

## Repository Structure

```text
Documentation/
├── Final_Report_PAPAYA.pdf
├── Final_Presentation.pdf
└── PAPAYA_Project_Pitch.pdf

images/
├── prototype_front.jpg
├── cushion_inside.jpg
├── enclosure_design.jpg
├── pcb_layout1.jpg
├── pcb_layout2.jpg
└── system_block_diagram.png.jpg
```

## Contributors

* Abdul Rahman
* Mokshan Colombage
* Buddhima Imbulpitiya
* Chaleesha Keerawella

## Acknowledgements

This project was developed as part of the BM1190 Engineering Design Project conducted at the University of Moratuwa.
