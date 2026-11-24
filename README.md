UART Transmitter and Receiver Using Verilog HDL

Project Overview

This project focuses on designing and implementing a UART (Universal Asynchronous Receiver/Transmitter) communication system using Verilog Hardware Description Language (HDL).

UART is a widely used asynchronous serial communication protocol that allows two digital devices to exchange data without requiring a separate clock signal.

The transmitter converts 8-bit parallel data into serial data, while the receiver converts the received serial data back into parallel data. The design is verified through simulation using a Verilog testbench.

Objectives

- To design a UART transmitter and receiver using Verilog HDL.
- To understand the working principle of UART communication.
- To convert parallel data into serial data.
- To convert received serial data into parallel data.
- To understand start bits, data bits, and stop bits.
- To verify the design using simulation and testbench.

Tools and Technologies Used

- Hardware Description Language: Verilog HDL
- Simulation Platform: EDA Playground
- Verification: Verilog Testbench
- Waveform Analysis: EPWave

Working Principle

The UART communication system works in two main stages:

1. UART Transmitter

- Accepts 8-bit parallel input data.
- Generates a start bit (logic 0).
- Transmits data bits one by one through the TX line.
- Sends a stop bit (logic 1) after data transmission.

2. UART Receiver

- Receives serial data through the RX line.
- Detects the start bit.
- Reads the incoming data bits.
- Converts serial data into 8-bit parallel data.
- Identifies the stop bit and indicates completion of reception.

UART Data Frame

A typical UART frame consists of:

Field| Description
Start Bit| Logic 0
Data Bits| 8-bit data
Parity Bit| Optional error detection bit
Stop Bit| Logic 1

Project Files

The repository contains the following files:

- "uart_tx.v" – UART transmitter module.
- "uart_rx.v" – UART receiver module.
- "uart_tb.v" – Testbench for verifying UART communication.
- "README.md" – Project documentation.

Note: File names may be changed according to the actual files uploaded.

Simulation and Verification

The UART transmitter and receiver are tested using a Verilog testbench.

The simulation verifies:

- Correct generation of the start bit.
- Proper serial transmission of 8-bit data.
- Correct reception of serial data.
- Conversion of serial data into parallel data.
- Proper generation of the stop bit.

Simulation waveforms are observed using EPWave to verify the functionality of the design.

Applications

- Microcontroller communication.
- Embedded systems.
- GPS communication modules.
- Bluetooth modules.
- Serial communication between computers and electronic devices.

Learning Outcomes

- Understanding UART serial communication.
- Learning parallel-to-serial and serial-to-parallel conversion.
- Understanding asynchronous data transmission.
- Gaining practical experience with Verilog HDL.
- Learning testbench development and waveform verification.

Conclusion

The UART Transmitter and Receiver project demonstrates the implementation of asynchronous serial communication using Verilog HDL. The transmitter and receiver modules are designed and verified through simulation. This project provides practical knowledge of digital communication, serial data transfer, and hardware design using Verilog.

---

Project Domain: Digital Electronics and Communication

Project Type: Verilog HDL Design and Simulation

Simulation Platform: EDA Playground

Author: Hemanth B
