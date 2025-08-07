# Microprocessor_Exercises
Contains solutions for Microprocessor exercises, including programs for counting byte occurrences, serial communication, string case conversion, negative number counting, timer-based pulse generation, array data transfer, LED display, and ADC voltage reading. 

**Overview**

This repository contains solutions for the Microprocessor Technology course exercises. The tasks involve programming for the MCS-51 microcontroller, covering various functionalities such as byte counting, serial communication, string manipulation, timer-based pulse generation, data array transfer, LED display, and ADC voltage reading. Each solution includes algorithm flowcharts as required.

**Exercises**

Byte Counting: Count occurrences of a given byte in a 12-byte RAM region starting at 70H, storing the result in R1.

Serial Communication: Subroutine to receive 5 bytes via serial port, store 3 bytes (#SOT, Data1, Data2, Data3, #EOT) starting at 20H, with serial port initialization and RI flag handling.

String Case Conversion: Convert a string of length R2 starting at R1 to lowercase if uppercase.

Negative Number Counting: Count negative numbers in a 50-byte RAM region starting at 30H.

Timer-Based Pulse Generation: Generate 100 pulses at 0.5 Hz on P1.1 using a 12 MHz crystal (50% duty cycle).

Array Data Transfer: Subroutine to transfer two arrays (50H–5FH in internal RAM to 1000H–100FH in external RAM).

LED Display (Units and Tens): Subroutine to display the units and tens digits in R5 on an AC 7-segment LED.

Button Press Counter: Display the number of PB1 button presses (0–9) on a 7-segment LED.

ADC Voltage Reading: Read voltage U1 (0–1.5V) and display on a 7-segment LED (0–F mapping).

Byte to BCD Conversion: Subroutine to convert a byte in R2 to 3 BCD bytes, stored starting at 40H.

**Hardware Notes**

Microcontroller: MCS-51.

Components: 7-segment LEDs, ADC (4-bit), push button (PB1), 12 MHz crystal.

Pin Configurations: Refer to the provided circuit diagrams for LED, ADC, and button connections.

<img width="938" height="626" alt="image" src="https://github.com/user-attachments/assets/0b10d752-8ade-4363-90d7-eebbefcaeea9" />


**Usage**
Each exercise solution is implemented in assembly language for the MCS-51 microcontroller. 
