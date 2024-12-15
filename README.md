# Gravity-finder
This Arduino project calculates gravity using a pendulum by timing 20 oscillations, with results shown on an LCD. A keypad-controlled stepper motor adjusts the setup.

This project is a Gravity Measurement System Using a Simple Pendulum and Arduino Technology. It uses an Arduino Uno to automate the process of determining the acceleration due to gravity (g) through a pendulum experiment. Key features include:

Oscillation Timing: The system uses an IR sensor to detect pendulum midpoint crossings. It calculates the time for 20 complete oscillations, starting after the first three crossings and counting every subsequent pair of crossings. This time is used to determine the period of oscillation.

Precision Stepper Motor Control: A 4x4 keypad enables users to input a distance, which moves a stepper motor to precisely adjust components of the experimental setup. The motor can also operate in reverse mode and return to the zero position with a reset button.

Real-Time Display and Monitoring: A 16x2 LCD with an I2C module provides live updates on oscillation counts, time measurements, and motor operations. Simultaneously, the serial monitor logs detailed data for further analysis.

By combining simple pendulum physics with Arduino technology, this project enables accurate measurement of the gravitational constant in an automated, user-friendly setup, ideal for educational and research purposes.
