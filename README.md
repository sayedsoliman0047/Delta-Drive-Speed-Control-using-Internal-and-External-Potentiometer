#  Delta Drive Speed Control using Internal & External Potentiometer

##  Overview

This project demonstrates controlling the speed of an induction motor using a **Delta Variable Frequency Drive (VFD)** through two different methods:

* Internal Potentiometer (Built-in Keypad)
* External Potentiometer (Wired to Drive Terminals)

The project was implemented on a **real hardware setup**, including wiring, parameter configuration, and practical testing.

---

##  Objectives

* Control motor speed using the **internal potentiometer**
* Control motor speed using an **external potentiometer**
* Configure drive parameters for both modes
* Demonstrate switching between **Local** and **Remote** control modes

---

##  System Components

* Delta VFD (Motor Drive)
* 3-Phase Induction Motor
* External Potentiometer 
* Control Wiring Setup
* Power Supply

---

##  Control Methods

### 1️-Internal Potentiometer (Local Control)

* Speed is controlled using the **built-in potentiometer** on the drive keypad
* Drive operates in **Local Mode**
* No external wiring required

 Key Idea:
The frequency reference is taken directly from the drive interface

---

### 2️-External Potentiometer (Remote Control)

* Speed is controlled using an **external potentiometer**
* Connected to analog input terminals of the drive

 Typical Wiring:

* +10V → One side of potentiometer
* GND → Other side
* AI (Analog Input) → Middle (wiper)

 Key Idea:
The drive reads a **0–10V analog signal** and converts it to frequency

---

##  Drive Configuration 

###  Basic Parameters:

* Run Command Source → Keypad / External (depending on mode)
* Frequency Source:

  * Internal Pot → Keypad
  * External Pot → Analog Input (AVI)

###  Analog Settings:

* Input Type → Voltage (0–10V)
* Max Frequency → Based on motor rating

---

##  Practical Demonstration

###  External Potentiometer Demo

[Watch External Potentiometer Video](External_Potentiometer_Video.mp4)


###  Internal Potentiometer Demo

[Watch Internal Potentiometer Video](Internal_Potentiometer_Video.mp4)

---

##  Setup

* Real wiring implementation (no simulation)
* Tested on actual industrial components
* Stable and smooth speed variation observed

---

##  References

* Delta VFD Manual (Official Documentation)

---

##  Key Learning Outcomes

* Understanding VFD analog inputs
* Difference between Local and Remote control
* Practical wiring of potentiometer with drive
* Parameter configuration for real industrial systems

---
