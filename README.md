# RF Learning Journey - Smith Chart Practice

Documenting my hands-on RF impedance matching simulations as a first-year ECE student using mobile tools.

## Simulations

### 1. Adding a Series Capacitor
* **Action:** Added a series capacitor with $-50\ \Omega$ reactance at $1\ \text{GHz}$.
* **Result:** The point curved downward along the Smith Chart.

![Series Capacitor Simulation](Screenshot_20261010-105025_Smith%20Chart.png)

### 2. Adding a Series Inductor
* **Action:** Added a series inductor with $+50\ \Omega$ reactance at $1\ \text{GHz}$.
* **Result:** The point curved upward along the Smith Chart.

![Series Inductor Simulation](Screenshot_20261010-105042_Smith%20Chart.png)

## Day 2: Parallel (Shunt) Components

### 3. Parallel Capacitor
* **Action:** Added a parallel capacitor with $+0.05\ \text{S}$ susceptance at $1\ \text{GHz}$.
* **Result:** The point curved downward along the conductance circles.

![Parallel Capacitor Simulation](Screenshot_20261011-070202_Smith%20Chart.png)

### 4. Parallel Inductor
* **Action:** Added a parallel inductor with $-0.05\ \text{S}$ susceptance at $1\ \text{GHz}$.
* **Result:** The point curved upward along the conductance circles.

![Parallel Inductor Simulation](Screenshot_20261011-070437_Smith%20Chart.png)

## Day 3: L-Network Impedance Matching

* **Objective:** Match a $25\ \Omega$ unmatched load to the $50\ \Omega$ center ($1.0 + j0$) at $1\ \text{GHz}$.
* **Components Used:**
  1. **Series Inductor:** $25.0\ \Omega$ ($3.98\ \text{nH}$) to reach the $1.0$ conductance circle.
  2. **Parallel Capacitor:** $0.02\ \text{S}$ ($3.18\ \text{pF}$) to cancel susceptance and land in the center.
* **Result:** $\Gamma = 0.01$, normalized impedance $Z = 1.02 - j0.00\ \Omega$.

![L-Network Match Simulation](Screenshot_20261012-081811_Smith%20Chart.png)
