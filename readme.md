# Smart Vehicle Parking Garage 
This project implements a smart parking garage system using STM32F103 microcontroller. The system manages entry and exit of vehicles using RFID cards, monitors available parking slots, and controls entry and exit gates accordingly. The system also includes features such as keypad entry for administrative tasks and LED indicators for status display.

## Table of Contents

- [Introduction](#introduction)
- [Hardware Requirements](#hardware-requirements)
- [Features](#features)
- [Video Demonstration](#video-demonstration)
- [Requirements](#requirements)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction
The Smart Parking Garage project aims to provide an efficient solution for managing parking spaces in a garage. It utilizes RFID technology for vehicle identification and provides an automated system for controlling entry and exit gates. Additionally, the system includes a keypad interface for administrative tasks such as registering RFID cards.

## Hardware Requirements
- STM32F103C6 Microcontroller
- RFID Card Reader Module
- Servo Motors for Entry and Exit Gates
- Keypad Interface
- LCD Display
- LEDs for Status Indication
- Passive Infrared (PIR) Sensors for Occupancy Detection

## Features
The Smart Vehicle Parking Garage offers the following key features:
1. **RFID Card Entry and Exit**:The system allows vehicles to enter and exit the parking garage using RFID card identification, providing a convenient and secure access method.

2. **Automated Gate Control**: Servo motors are used to control the entry and exit gates, allowing for automated operation based on RFID card authentication.


3. **Car Presence Detection:**:The system has Passive Infrared (PIR) sensors to detect the presence of a car under the entry and exit gates. This feature ensures safety by preventing the gates from closing if a car is still present underneath. Once the PIR sensors detect that the car has moved away, the gates automatically close, optimizing traffic flow and enhancing security within the parking garage.


4. **Real-time Slot Availability Monitoring**:The system continuously monitors the availability of parking slots and updates the display in real-time, providing users with information about vacant parking spaces.


5. **Administrative Interface**:A keypad interface is provided for administrative tasks, such as registering new RFID cards into the system, enhancing flexibility and customization.

6. **LED Status Indicators**: LED indicators are utilized to provide visual feedback on the status of the parking garage, indicating features such as parking availability and gate operations.

7. **User-friendly Interface**: The project includes an LCD display to present clear instructions and information to users, enhancing the overall user experience and usability of the system.

8. **Configurable and Scalable**: The system architecture allows for easy configuration and scalability to accommodate varying parking garage sizes and requirements, making it adaptable to different environments.


## Video Demonstration
[App Demo](https://drive.google.com/file/d/1DsEtabv-fge3M-7_DCIquuAIWNMyOcAe/view?usp=sharing)


## Requirements
### Hardware Requirements
- STM32F103C6 Microcontroller
- RFID Card Reader Module
- Servo Motors for Entry and Exit Gates
- Keypad Interface
- LCD Display
- LEDs for Status Indication
- Passive Infrared (PIR) Sensors for Occupancy Detection

### Software Requirements
- STM32CubeIDE or Any other IDE
- LCD library
- Keypad library
- Servo library
- UART library
- GPIO library
- Timer library

## Usage
1. **Power On**: Ensure that the system is powered on.

2. **RFID Card Entry and Exit**: Follow the instructions displayed on the LCD for RFID card entry or exit. Present the RFID card to the card reader for authentication.

3. **Administrative Tasks**: Use the keypad interface to perform administrative tasks such as registering new RFID cards into the system.
Follow the on-screen instructions for keypad interactions.

4. **LED Status Indicators**: Observe the LED indicators for visual feedback on the status of the parking garage. LEDs may indicate features such as parking availability and gate operations.

5. **Monitor Parking Availability**: Check the LCD display for real-time information on available parking slots.The display updates dynamically based on occupancy status.

6. **Gate Control**: The system controls the entry and exit gates using servo motors.
Gate operations are automated based on RFID card authentication.

7. **Occupancy Detection**: PIR sensors are used for occupancy detection, ensuring efficient management of parking spaces.

8. **Shutdown**:Ensure proper shutdown procedures if required, as per the system specifications.

9. **Maintenance**: Regularly check and maintain hardware components for optimal performance.
Update software as needed for improvements or bug fixes.

10. **Troubleshooting**:
Refer to the project documentation for troubleshooting guidelines in case of any issues.



## Contributing
Contributions to Smart Vehicle Parking Garage  are welcome! If you encounter any issues or have suggestions for improvements, please create a new issue or submit a pull request.

When contributing, please ensure that you follow the existing coding style and include clear commit messages to maintain a well-documented project history.

