# Labview-Projects

## Overview

This project consists of a series of LabVIEW applications designed to demonstrate various capabilities ranging from simple binary manipulation and signal generation to complex data logging and analysis. Each application is designed to provide practical insights into different aspects of LabVIEW programming and data handling.

## Projects Description

### 1. Binary Configuration Value Display

- **Objective:** Given 8 switches that can be controlled by the user, display the decimal and hexadecimal values of the binary configuration represented by the switch settings.
- **Key Features:**
  - Interactive switch interface for binary input.
  - Real-time calculation and display of decimal and hexadecimal values.

### 2. Signal Generator

- **Objective:** Generate rectangular, sinusoidal, and sawtooth wave signals with variable parameters and display their graphical representations.
- **Key Features:**
  - User input for signal parameters (frequency, amplitude, etc.).
  - Graphical representation of generated signals.

### 3. Dice Roll Simulator

- **Objective:** Simulate "n" rolls of a die, where "n" is provided by the user. Count the occurrences of each number and display the results on a graph.
- **Key Features:**
  - User-defined number of die rolls.
  - Graphical display of roll outcomes and frequency.
  - Highlight the most and least frequent numbers with two different colors.

### 4. Burn-in Test Data Logger and Analyzer

- **Objective:** Monitor and log the temperature inside ovens during "Burn-in" tests of manufactured boards. Provide graphical analysis of temperature over time, including duration within and outside specified limits.
- **Key Features:**
  - Real-time temperature monitoring and logging for each board.
  - User selection of board serial numbers from a dropdown menu.
  - Graphical display of temperature history.
  - Indication of durations within and outside temperature limits.
- **Inputs:**
  - Maximal temperature.
  - Minimal temperature.
- **Data Format Example:** `serial_number {Tab} datetime {Tab} temperature` (e.g., `123FA4 10-11-2004 08:13 54`).

## Implementation Notes

- These projects are implemented in LabVIEW, a visual programming language suited for data acquisition, instrument control, and industrial automation.
- Each project is designed to be standalone, focusing on specific aspects of LabVIEW programming and data visualization.

## Getting Started

To run these projects, you will need:
- LabVIEW installed on your computer. The version of LabVIEW required depends on the complexity of the projects. Generally, any recent version should suffice for most projects.
- Basic knowledge of LabVIEW's interface and programming paradigm.

## Usage

- Open each project using LabVIEW.
- Follow any user prompts or instructions within each VI (Virtual Instrument) to interact with the applications.
- For the Burn-in Test Data Logger and Analyzer, ensure that the log files are correctly formatted and located in the specified directory for data analysis.

## Contribution

- These projects are open for improvement and contributions. Whether it's adding new features, improving the existing code, or fixing bugs, your contributions are welcome.

## License

- This project is licensed under the MIT License - see the LICENSE file for details.

