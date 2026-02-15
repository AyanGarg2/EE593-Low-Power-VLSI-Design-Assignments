# EE593: Low Power VLSI Design (IIT Mandi)

This repository contains lab assignments for **EE593: Low Power VLSI Design (IIT Mandi)**.

---

## Assignment 1: Design and Analysis of a CMOS Inverter

1. Switching threshold estimation through DC VTC analysis  
2. Propagation delay characterization (tPLH, tPHL) using transient simulations  
3. Impact of transistor sizing on delay symmetry  
4. Effect of input rise time on propagation delay and power consumption  
5. Effect of load capacitance on delay and power  
6. Operation under near-threshold supply voltage  
   \[
   V_{DD} = V_{tn} + |V_{tp}|
   \]
   for ultra-low-power analysis  

---

## Assignment 2: Design and Analysis of 6-Input CMOS AND/OR Gate Using Multi-Stage NAND/NOR Implementations

This assignment focuses on the design, simulation, and comparison of a 6-input CMOS AND/OR gate using different NAND/NOR decompositions under low-power design constraints.

### Problem Overview

Design a 6-input AND/OR gate using:

- **Implementation-A:** 6-input NAND/NOR + Inverter  
- **Implementation-B:** 3-input NAND/NOR + 2-input NAND/NOR  
- **Implementation-C:** 2-input NAND/NOR + 3-input NAND/NOR  

---

### Work Done

#### 1. Area, Delay, and Power Analysis
- Designed all three implementations for both AND and OR logic  
- Measured average propagation delay  
- Calculated dynamic power   

#### 2. Switching Activity Variation
- One input set to high activity (α = 0.5)  
- One input set to low activity (α = 0.125)  
- Evaluated delay, power, and Power-Delay Product (PDP)  

#### 3. Rise/Fall Time Variation
- Increased rise/fall time of one input to 500 ps from 50ps
- Observed delay degradation and increased short-circuit power  

#### 4. Input Position Effect (Implementation-A)
- Moved highest-activity input from top to bottom of the transistor stack  
- Analyzed impact on dynamic power  

#### 5. Leakage Power Estimation
- Evaluated leakage for input vectors:  
  `000000`, `000001`, `000011`, `000111`, `001111`, `011111`, `111111`  

---
