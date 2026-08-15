# ⚡ Electronics Phase 02 - Capacitors

## 📖 Introduction

This repository documents my journey of learning about capacitors from first principles. Rather than memorizing formulas, I focused on understanding how capacitors store electrical energy, charge and discharge, and interact with resistance through logical reasoning and practical circuit simulations.

Every concept was reinforced with circuit experiments, predictions, and verification using a circuit simulator. This approach helped me develop engineering intuition instead of relying solely on equations.

---

## 🎯 Learning Objectives

At the end of this phase, I was able to:

- Explain what a capacitor is and how it stores electrical energy.
- Describe capacitance as the ability of a capacitor to store electric charge.
- Explain the relationship between charge, capacitance, and voltage.
- Explain how a capacitor charges when connected to a DC voltage source.
- Explain why charging current decreases as a capacitor charges.
- Describe how a capacitor discharges through a load.
- Explain how stored electrical energy can be released to power a circuit.
- Calculate the energy stored in a capacitor.
- Understand how resistance affects capacitor charging and discharging.
- Understand how capacitance affects charge storage and charging time.
- Explain the RC time constant and its significance in capacitor circuits.

---

## 📚 Topics Covered

- Capacitors
- Electric Charge Storage
- Capacitance
- Capacitor Charging
- Capacitor Discharging
- Stored Electrical Energy
- Charging Current
- Discharge Current
- Resistance and Capacitance
- RC Circuits
- RC Time Constant
- Capacitor Applications

  ---

# 🔬 Practical Experiments

## Experiment 1 - Capacitor Charging

### Description

To investigate how a capacitor behaves when connected to a DC voltage source and observe how its voltage and charging current change over time.

### Hypothesis

Before building the circuit, I predicted that:

- The capacitor voltage would initially be close to 0 V.
- The charging current would initially be high.
- The charging current would decrease as the capacitor voltage increased.
- The capacitor voltage would eventually approach the battery voltage.
- The current would eventually approach 0 A when the capacitor became fully charged.

### Circuit
![Experiment 1 - Capacitor Charging](images/experiment-1.jpg)
### Observation

When the circuit was connected, the capacitor voltage gradually increased while the charging current continuously decreased.

The charge movement was initially fast, but became progressively slower as the capacitor voltage approached the battery voltage. Eventually, the capacitor reached approximately 9 V and the charging current approached 0 A.

### Values

| Quantity | Observed Value |
|----------|---------------:|
| Supply Voltage | 9 V |
| Initial Capacitor Voltage | ~0 V |
| Final Capacitor Voltage | 9 V |
| Final Charging Current | 0 A |

### Inference

The experiment demonstrated that as the capacitor charges, its voltage increases while the charging current decreases. Once the capacitor voltage becomes equal to the battery voltage, there is no longer a potential difference driving current through the circuit, so the charging current approaches 0 A.

## Experiment 2 - Capacitor Discharging Through an LED

### Description

To investigate how a charged capacitor releases its stored electrical energy through a load and observe how the capacitor voltage, current, and LED brightness change during discharge.

### Hypothesis

Before performing the experiment, I predicted that:

- The charged capacitor would supply current to the LED.
- The LED would illuminate when connected to the capacitor.
- The LED would gradually become dimmer as the capacitor discharged.
- The capacitor voltage would decrease over time.
- The current would decrease as the capacitor voltage decreased.
- The LED would eventually stop glowing when the capacitor could no longer provide enough energy.

### Circuit
![Experiment 2 - Capacitor Discharging Through an LED](images/experiment-2.jpg)
### Observation

After the charged capacitor was connected to the LED through the 330 Ω resistor, the LED illuminated.

As the capacitor discharged, its voltage and current gradually decreased. The LED brightness also reduced as the capacitor voltage decreased until the LED eventually stopped glowing.

### Values

| Quantity | Observed Value |
|----------|---------------:|
| Initial Capacitor Voltage | 9 V |
| Resistor | 330 Ω |
| Capacitor Voltage | Decreased |
| Current | Decreased |
| LED Brightness | Decreased |

### Inference

The experiment demonstrated that a charged capacitor can temporarily supply electrical energy to a load. As the capacitor releases its stored energy, its voltage decreases, causing the current and LED brightness to decrease as well.
