# ⚡ Electronics Phase 01 - Electrical Fundamentals

## 📖 Introduction

This repository documents my journey of learning the fundamentals of electrical engineering from first principles. Rather than memorizing formulas, I focused on understanding the physical concepts behind electricity, voltage, current, resistance, circuit analysis, electrical power, and resistors through logical reasoning and practical circuit simulations.

Every concept was reinforced with circuit experiments, predictions, and verification using a circuit simulator. This approach helped me develop engineering intuition instead of relying solely on equations.

---

## 🎯 Learning Objectives

At the end of this phase, I was able to:

- Explain what electricity is and how electric charge moves through a circuit.
- Describe voltage as electrical potential difference (energy per unit charge).
- Explain current as the rate of flow of electric charge.
- Understand resistance from the perspective of electron movement and collisions within materials.
- Apply Ohm's Law to analyze simple electrical circuits.
- Analyze series, parallel, and mixed resistor circuits.
- Understand Kirchhoff's Current Law (Conservation of Charge).
- Understand Kirchhoff's Voltage Law (Conservation of Energy).
- Calculate electrical power using multiple equivalent equations.
- Explain how resistors work physically and how they are used in practical circuits.

---

## 📚 Topics Covered

- Electricity
- Electric Charge
- Voltage
- Current
- Conductors and Insulators
- Electric Field
- Resistance
- Ohm's Law
- Series Circuits
- Parallel Circuits
- Mixed Circuits
- Kirchhoff's Current Law (KCL)
- Kirchhoff's Voltage Law (KVL)
- Electrical Power
- Resistors

  ---

# 🔬 Practical Experiments

## Experiment 1 - Series Circuit

### Objective

To understand how voltage and current behave in a series circuit.

### Prediction

Before building the circuit, I predicted that:

- Current would remain the same throughout the circuit because there is only one path for charge to flow.
- The source voltage would be shared between the resistors.
- The sum of all voltage drops would equal the battery voltage.

### Circuit

![Series Circuit](images/01-series-circuit.png)

### Measurements

| Quantity | Measured Value |
|----------|---------------:|
| Supply Voltage | 9 V |
| Current | 30 mA |
| Voltage across 100 Ω | 3 V |
| Voltage across 200 Ω | 6 V |

### What I Learned

- Current remains constant throughout a series circuit.
- Components in series divide the source voltage.
- The sum of all voltage drops equals the source voltage, demonstrating Kirchhoff's Voltage Law.

---

## Experiment 2 - Parallel Circuit

### Objective

To understand how voltage and current behave in a parallel circuit.

### Prediction

Before building the circuit, I predicted that:

- Every branch would experience the full supply voltage.
- Current would divide between the branches.
- The total current supplied by the battery would equal the sum of the branch currents.

### Circuit

![Parallel Circuit](images/02-parallel-circuit.png)

### Measurements

| Quantity | Measured Value |
|----------|---------------:|
| Supply Voltage | 9 V |
| Battery Current | 180 mA |
| Left Branch Current | 90 mA |
| Right Branch Current | 90 mA |
| Voltage across Left Resistor | 9 V |
| Voltage across Right Resistor | 9 V |

### What I Learned

- Components connected in parallel share the same voltage.
- Current divides among the available paths.
- The total current entering a junction equals the total current leaving the junction, demonstrating Kirchhoff's Current Law.
