# Heart Rate Monitoring System with PIC16F877A

![Image](https://ibb.co/k1KSYhM)

## Overview
This project utilizes the PIC16F877A microcontroller along with a 2x16 LCD, a 4x4 keypad, and a heart rate sensor to create a Heart Rate Monitoring System. The system displays user inputs and requested operations on the LCD, calculates and displays BPM (Beats Per Minute) and IBI (Inter-Beat Interval) based on heart rate sensor data, and stores patient data for future reference.

## Components Used
- **Microcontroller:** PIC16F877A operating at 20MHz.
- **Display:** 2x16 LCD for displaying user input, operations, and health metrics.
- **User Interface:** 4x4 keypad for user interaction, allowing operations such as addition (+), subtraction (-), multiplication (*), division (/), clear (C), and more.
- **Health Monitoring:** Heart rate sensor for detecting and measuring heart rate.
- **Data Handling:** Implements age validation (age > 0) and ID constraints (0-9). Displays "This Patient is Not Found" for invalid data entries (age = 0 or BPM = 0).

## Key Features
- Displays user inputs and operations on the LCD for clear user interaction.
- Calculates and displays BPM and IBI based on real-time heart rate sensor data.
- Stores and retrieves patient data including ID, age, BPM, and IBI for future reference.
- Implements error handling to ensure data integrity and user feedback.

## Operation
1. **User Input:** Use the keypad to enter patient ID and age.
2. **Operations:** Select desired operations (+, -, *, /) for calculations.
3. **Health Monitoring:** Monitor and display real-time BPM and IBI on the LCD.
4. **Data Storage:** Store patient data and retrieve stored data as needed.
5. **Error Handling:** Displays "This Patient is Not Found" for invalid age (age = 0) or no heart rate data (BPM = 0).

## Usage
1. Clone the repository and upload the code to your PIC16F877A microcontroller using MPLAB X IDE.
2. Ensure all necessary libraries and components are correctly connected as per the circuit diagram.
3. Power on the system and follow the LCD prompts to input patient data and initiate monitoring.
4. Use the keypad to navigate through operations and view real-time health metrics.

## Credits
Include any credits or acknowledgments for libraries, resources, or inspirations used in your project.

## License
This project is licensed under the [Your License Name] License - see the LICENSE file for details.

## Support
For any issues or questions, please open an issue on GitHub.

