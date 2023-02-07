---
marp: true
theme: simple
paginate: true
footer:
---

<!-- headingDivider: 2 -->
<!-- _class: cover -->
# Proportional Control

Teng-Jui Lin
Department of Chemical Engineering, University of Washington
**Process Dynamics and Control**

## Basic components in a control loop

- Process being controlled
  - System of interest
- Sensor-transmitter combination
  - Composition analyzer-transmitter (AT) - measure composition and transmits electrical signal
- Feedback controller
  - Feedback controller (AC) - takes AT electrical signal and calculates appropriate output electrical signal
- Current-to-pressure transducer
  - Current-to-pressure transducer (I/P) - converts electrical signal to pneumatic (air) signal
- Final control element - adjusts manipulated variable
  - Control valve - takes in electrical or pneumatic signal and changes flow rate
- Transmission lines between instruments
  - Electrical cables
  - Pneumatic tubing

## Proportional controller has output proportional to the error signal

- Objective: deviation (error) from set point is 0
  - Error signal = Set point - Measured controlled variable

$$
e(t) = y_{sp}(t) - y_m(t)
$$

<br/>

- Proportional control

$$
p(t) = \overline{p} + K_c e(t)
$$

## Controller gain could be positive or negative

- Want to maintain constant flow rate $w$ to tank

<br/><br/><br/><br/><br/><br/>

- Want to maintain constant composition $x$ in tank

## Transfer function for proportional controller is the controller gain

**Ex.** Show that the proportional controller transfer function is

$$
\boxed{\dfrac{P'(s)}{E(s)} - K_s}
$$

- Proportional controller:

$$
p(t) = \overline{p} + K_c e(t)
$$

## Proportional band can be used instead of controller gain

- Proportional band

$$
\mathrm{PB} \equiv \dfrac{1}{K_c} \times 100\%
$$

## Advantages and disadvantages of proportional controllers

- Advantage
  - Simple
    - Great if exact value of controlled value is not important: prevent overflow/empty
- Disadvantage
  - **Offset** - steady-state error
    - Set point change
    - Sustained disturbance