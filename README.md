# Hybrid ADC Integration Project

## Table of Contents
- [Introduction](#introduction)
- [Specifications](#specifications)
- [Concept](#concept)
- [Verification](#verification)
- [Results](#results)
- [Conclusion](#conclusion)
- [License](#license)

## Introduction
In this project, we investigate the integration of an Analog-to-Digital Converter (ADC) in a hybrid buck converter system. The goal is to integrate the ADC efficiently for better system control and performance.

## Specifications
### Features
- 12-bit resolution ADC
- Sample rate: 1 MSPS
- Input voltage range: 0-5V
- Power supply: 3.3V

### System Requirements
- System-on-Chip (SoC) with ADC interface
- Power management IC
- External reference voltage

## Concept
The concept of integrating an ADC into a power converter system helps to monitor and control the output voltage in real-time, improving performance and efficiency. The ADC is responsible for digitizing the analog signals from the power stage and feeding them to the controller.

### Block Diagram
![Block Diagram](./images/Junu_3.jpg)

## Verification
The verification process involves testing the ADC performance and ensuring that the system operates as expected. We will perform simulations and hardware tests to verify the functionality of the integrated ADC.

### Simulation Results
![Simulation Results](./images/simulation_results.png)

## Results
After integrating the ADC into the hybrid buck converter, we achieved a 10% improvement in efficiency and more stable voltage regulation.

## Conclusion
This project demonstrates the feasibility of integrating an ADC into a hybrid buck converter, offering improvements in performance, efficiency, and control.

## License
This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

