# NeuroNeck

## Overview

NeuroNeck is an innovative project designed to aid in the training for the mobilization of spinal injuries. Developed by Siobhan Lee, Spencer Osborn, Coleman Farvolden, and Ryan McGillivray, NeuroNeck employs sensors and algorithms to provide instant feedback on the precision of neck and head movements. This device is particularly useful for emergency first responders and healthcare professionals, offering a significant advancement in medical simulation.

## Features

- **Real-Time Feedback**: Utilizes sensors and algorithms to deliver immediate feedback on neck and head movement accuracy.
- **LED and Gyroscope Integration**: Signals movement with remarkable accuracy through LEDs and gyroscopes.
- **Force Measurement**: Collects data on head movement using force sensors and gyroscopes, with real-time graphing of force levels.
- **Machine Learning Analysis**: Processes the collected data to calculate the damage caused to the neck using advanced machine learning techniques.

## Key Components

### Hardware
- **Sensors**: Force sensors and gyroscopes to detect and measure head movements.
- **LEDs**: Indicate the level of force and movement precision.
- **Piezo**: Provides auditory feedback based on the force level.

### Software
- **data_collection.ino**: The final software for the Arduino, responsible for collecting data on head movement. It graphs the amount of force in real-time and uses LED indicators and a piezo on the neck to signal the force level.
- **damagemachinelearning.py**: Uses the data collected from `data_collection.ino` and employs machine learning to calculate the damage caused to the neck.

## Project Uniqueness

Siobhan Lee emphasizes the project's distinctiveness: "We were determined to create a device that filled an unmet need in the market. By focusing on a less explored aspect of medical simulation, we were able to distinguish our project from others, contributing a novel solution to the field."

## Installation and Usage

### Hardware Setup
1. Connect the force sensors and gyroscopes to the Arduino.
2. Attach the LEDs and piezo to the designated output pins on the Arduino.

### Software Setup
1. **Arduino Code**:
   - Upload `data_collection.ino` to your Arduino board.
2. **Machine Learning Script**:
   - Ensure you have Python installed on your system.
   - Install necessary Python libraries (e.g., numpy, pandas, scikit-learn).
   - Run `damagemachinelearning.py` to process the collected data and calculate neck damage.

## Files

- **data_collection.ino**: Arduino code for data collection on head movement.
- **damagemachinelearning.py**: Python script for machine learning analysis of neck damage data.

## Contributors

- Siobhan Lee
- Spencer Osborn
- Coleman Farvolden
- Ryan McGillivray

## Acknowledgements

We thank our mentors and the entire project team for their support and guidance in developing NeuroNeck. Their contributions were invaluable in making this project a success.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

For more details, feel free to contact any of the contributors. We h
