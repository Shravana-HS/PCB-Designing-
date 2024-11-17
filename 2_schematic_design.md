# Schematic Design

## Overview

Schematic design is the first step in designing a PCB (Printed Circuit Board). In this phase, the circuit is represented using symbols for components and wires to show how they connect electrically. This helps you visualize the components and their interconnections, allowing for a clear and error-free board design. Once the schematic is complete, it's good practice to simulate it with basic tests like DC simulations, transient analysis, and more. This helps check key parameters like delays, current and voltage ranges, and power consumption.

## Key Concepts

### 1. **Components and Symbols**
   - Every component in a schematic is represented by a symbol that matches its physical form on the PCB.
   - Common components in schematics include resistors, capacitors, transistors, ICs (integrated circuits), and op-amps (operational amplifiers).
   - Using standard symbols ensures consistency and helps make the design easy to understand.

### 2. **Connections and Nets**
   - A **net** is an electrical connection between components.
   - You create connections by drawing lines, or "wires," between component pins that need to be connected.
   - Nets ensure that components are linked correctly, making the design easier to follow and less prone to mistakes.

### 3. **Power and Ground Connections**
   - Properly connecting power and ground is crucial for making sure the circuit works correctly.
   - Power lines (like Vcc) and ground (GND) should be clearly defined and correctly connected to avoid confusion and ensure stability.

### 4. **Design Rules and Constraints**
   - When designing a schematic, you must define certain constraints, like the tolerance of resistors or the voltage ratings of capacitors.
   - It's important to think about component availability, lifespan, and compatibility before finalizing the design. This helps prevent problems later on when you start building the PCB.

### 5. **Component Selection**
   - When selecting components, you need to check if they are available, affordable, and reliable.
   - Platforms like Octopart can help you find parts, compare prices, and check if they are in stock.

### 6. **Electrical Rule Check (ERC)**
   - After completing the schematic, it should be checked for errors using an Electrical Rule Check (ERC).
   - ERC helps you identify potential issues, like unconnected pins or incorrectly linked components, ensuring that the schematic is correct.
   - ERC uses rules and equations to analyze the schematic and check for errors before moving on to the next stage of design.

## Example: Simple LED Circuit

Let’s look at an example of a simple LED circuit. In this case, we’ll use a 220Ω resistor and an LED, powered by a 5V source.

### Components:
   - **Resistor**: 220Ω
   - **LED**: 1
   - **Power Source**: 5V

### Connections:
   - The positive side of the LED connects to the power source (5V).
   - The negative side of the LED connects to one end of the resistor.
   - The other end of the resistor connects to the ground (GND), completing the circuit.


