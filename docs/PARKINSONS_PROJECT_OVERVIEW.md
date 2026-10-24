# Parkinson's Wearable Glove — Project Documentation

## 1. Project Title
**AI-Powered Multimodal Wearable Glove for Preliminary Parkinson's Screening and Motor Function Monitoring**

## 2. Problem Statement
Parkinson's disease can affect hand movements, coordination, and motor control, making everyday activities increasingly difficult. Since clinical assessments usually take place at scheduled intervals, changes in motor function between visits may be difficult to track consistently. There is a need to explore an accessible wearable solution that records hand-movement indicators and helps users and healthcare professionals review changes over time.

## 3. Project Objectives
- Monitor hand tremor and movement patterns using motion sensors.
- Measure finger bending using flex sensors.
- Capture grip-related activity using force sensors.
- Explore AI-assisted analysis to identify relevant movement patterns.
- Develop a user-friendly dashboard for viewing assessment summaries and historical records.
- Investigate the feasibility of a lightweight, affordable wearable glove for preliminary screening and monitoring.

## 4. Proposed Solution
The project proposes a wearable glove equipped with multiple sensors to collect hand-movement data during guided activities such as finger tapping, hand opening and closing, and gripping.

An ESP32 microcontroller is proposed to collect readings from the sensors and transfer the data to connected software. The software will process the readings and explore AI/ML techniques to identify movement patterns. A dashboard is planned to display recorded measurements and compare results across assessment sessions.

The system is intended to support preliminary screening and motor-function monitoring. It will not independently diagnose Parkinson's disease or replace assessment by a qualified healthcare professional.

## 5. Proposed Technologies
- **Hardware:** ESP32 microcontroller, IMU sensor, flex sensors, and grip/force sensors.
- **Embedded programming:** C/C++ for sensor interfacing and data collection.
- **Data processing and AI:** Python and suitable machine-learning libraries.
- **User interface:** HTML, CSS, and JavaScript for a web-based dashboard.
- **Data storage:** A suitable database or structured file format for assessment records.
- **Design tools:** CAD software for glove and enclosure modelling, and circuit-design software for electronic schematics.

*The final selection of components, software frameworks, and data-storage methods will be confirmed during development.*

## 6. Development Roadmap

### Phase 1: Planning and Research
Finalize project requirements, review relevant research, identify suitable datasets, and select potential hardware components.

### Phase 2: Hardware and CAD Design
Prepare the glove layout, determine sensor placement, design the electronics enclosure, and create the circuit schematic.

### Phase 3: Prototype Development
Assemble the glove, interface the sensors with the ESP32, and verify that sensor readings can be collected reliably.

### Phase 4: Software and AI Development
Develop the sensor-data processing pipeline, extract relevant movement features, and investigate suitable machine-learning methods using appropriate datasets.

### Phase 5: Dashboard Development
Build an interface to display sensor readings, assessment summaries, and historical trends.

### Phase 6: Testing and Evaluation
Evaluate sensor consistency, usability, data quality, and model performance. Document limitations and seek appropriate expert guidance before any clinical use.

## 7. Current Project Status
The project is currently in the **planning and documentation stage**. Hardware assembly, CAD modelling, software implementation, AI model development, and experimental testing have not yet started. These activities are planned for the subsequent development phases.

## 8. Expected Outcome
The expected outcome is a functional prototype of a sensor-equipped wearable glove, supported by software for movement-data analysis and visualization. The prototype will be evaluated to determine whether it can provide useful, consistent measurements for preliminary motor-function screening and monitoring.

## 9. Safety and Limitations
The proposed glove is intended as a research and development prototype. Sensor readings and AI-generated results may be affected by sensor placement, individual movement differences, and data quality. The system must not be used as a standalone diagnostic tool. Any future clinical application will require appropriate validation, privacy safeguards, and professional oversight.
