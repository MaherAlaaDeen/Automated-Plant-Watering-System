# Automatic-Plant-Watering-System
## Abstract
This project presents the development of an Automated Plant Monitoring System designed to optimize energy usage and ensure effective irrigation. The system harnesses renewable solar energy, employing a 12V solar panel as the primary power source. A current sensor monitors the charging current for a lead-acid battery, ensuring safe and efficient operation. An MPPT (Maximum Power Point Tracking) controller regulates the solar panel's output, dynamically adjusting a connected buck converter's PWM input to implement the three-stage charging process critical for lead-acid batteries.
A secondary buck converter steps down the battery voltage to 5V to power the Arduino-based MPPT controller. This controller integrates three soil moisture sensors and three relay-controlled water pumps to automate irrigation based on soil conditions. The system efficiently manages energy distribution and enhances plant care, combining renewable energy utilization with precise moisture monitoring and irrigation control. This solution is suitable for sustainable agricultural applications, reducing manual intervention while optimizing energy and water resources

## Introduction
The need for sustainable and efficient agricultural systems has never been more critical as the global demand for food continues to grow. Automated plant monitoring and irrigation systems offer a solution by optimizing resource utilization and reducing manual labor. This project introduces an Automated Plant Monitoring System that combines renewable energy, smart sensors, and automated control to monitor and maintain soil moisture levels effectively
The system harnesses solar energy as its primary power source, utilizing a 12V solar panel and a lead-acid battery for energy storage. An integrated Maximum Power Point Tracking (MPPT) controller ensures maximum energy extraction from the solar panel under varying environmental conditions. The MPPT controller also manages the three-stage charging process of the battery, ensuring its longevity and safe operation
Connected to the controller are three soil moisture sensors and three relay-controlled water pumps. The sensors continuously monitor soil moisture levels, providing real-time feedback to the system. When the soil moisture falls below a specified threshold, the corresponding pump is activated via a relay module to irrigate the plants.
This project demonstrates the integration of renewable energy, smart monitoring, and automated irrigation in a cost-effective and scalable system. It is designed for small-scale farming, gardens, and other agricultural applications, emphasizing sustainability and energy efficiency.

## Block Diagram

![Block Diagram](8.png)

## Components Used
### BOM

![BOM](5.png)

## Circuit Design
### Schematic

![Schematic](1.png)

### Step-By-Step Circuit Analysis
#### 
