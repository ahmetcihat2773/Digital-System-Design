# Verilog Modules Repository

## Overview

This repository contains various Verilog modules for digital design and simulation. These modules can be used as building blocks for more complex digital systems. Each module is briefly described below.

## Modules

### 1. Basic D-Latch
A simple D-latch that stores data based on the level of the enable signal.

### 2. D Flip-Flop with Asynchronous Reset
A D flip-flop that can be reset asynchronously, useful for initializing the flip-flop to a known state.

### 3. D Flip-Flop with Synchronous Reset
A D flip-flop that resets synchronously with the clock signal, ensuring a controlled reset behavior.

### 4. Basic D Flip-Flop
A standard D flip-flop that stores data on the rising edge of the clock signal.

### 5. D-Latch with Asynchronous Reset
A D-latch that includes an asynchronous reset signal to clear the stored data.

### 6. 2-to-1 Multiplexer
A basic 2-to-1 multiplexer that selects between two input signals based on a control signal.

### 7. Four Bit Pattern Detection
Detects a specific four-bit pattern in a serial input stream and counts occurrences.

### 8. Signal Activation Duration
Measures how long a signal remains active, up to a specified count.

### 9. Data Repeater
Repeats an input signal based on a control signal, useful for data buffering and serialization.

### 10. Creating a 5us Long Pulse
Generates a pulse that lasts for 5 microseconds, often used for timing and control signals.

## Usage

1. Clone the repository:
   ```sh
   git clone <repository_url>
