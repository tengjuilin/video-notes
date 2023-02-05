---
marp: true
theme: simple
paginate: true
footer:
---

<!-- headingDivider: 2 -->
<!-- _class: cover -->
# Intro to Process Dynamics and Control

Teng-Jui Lin
Department of Chemical Engineering, University of Washington
**Process Dynamics and Control**

## Defining process dynamics and control

- **Process** - conversion of feed materials to products using chemical and physical operations
  - Continuous, batch, semi-batch
- **Process dynamics** - unsteady-state/transient process behavior
  - Start-ups, shutdowns, process disturbances, planned transitions
- **Process control** - maintain a process at desired operating conditions
  - Utilize information flow
  - Impacts safety, environment, quality, economics
  - **Manual control** - control strategy implemented by a person
  - **Automatic control** - control strategy automated by computers

## Types of variables

- **Set point** - desired nominal value of controlled variable
- **Controlled variable** - variable being regulated and maintained (to be controlled) at set point
- **Manipulated variable** - variable that can be adjusted
- **Disturbance variable** - variable that perturbs the system, changes controlled variable, but cannot be directly tuned

## Classification of control strategies

- **Feedback control** - controlled variable is measured to adjust manipulated variable (disturbance variable not measured)

<br/><br/><br/>

- **Feedforward control** - disturbance variable measured to adjust manipulated variable (controlled variable not measured)

## Feedback control measures controlled variable

- **Feedback control** - controlled variable is measured to adjust manipulated variable (disturbance variable not measured)
  - **Negative feedback** - controller forces controlled variable toward set point
  - **Positive feedback** - controller forces controlled variable farther away from set point
  - :heavy_plus_sign: Correction occurs regardless of source of disturbance
  - :heavy_plus_sign: Reduces sensitivity of controlled variable to unmeasured disturbance and process changes
  - :heavy_minus_sign: Correction only happens after controlled variable deviates set point (disturbance has occurred)

## Feedforward control measures disturbance variable

- **Feedforward control** - disturbance variable is measured to adjust manipulated variable (controlled variable not measured)
  - :heavy_plus_sign: Correction happens before controlled variable deviates set point
  - :heavy_minus_sign: Disturbance variable must be measured or accurately estimated
  - :heavy_minus_sign: Do not account for unmeasured disturbances
  - :heavy_minus_sign: Process model is required

## Challenges in process control

- Systems are often nonlinear

<br/><br/><br/>

- Time delays are common at scale

<br/><br/><br/>

- Real systems are complex and interconnected

## Types of control processes

- **Single-input/single-output (SISO)** - one manipulated variables (input) and one controlled variables (output)
  - :heavy_plus_sign: Easy to model and implement
  - :heavy_minus_sign: Less control
- **Multiple-input/multiple-output (MIMO)** - multiple manipulated variables (input) and multiple controlled variables (output)
  - :heavy_plus_sign: Better control
  - :heavy_minus_sign: Hard to model and implement
- Balance robustness to disturbance  and complexity of model

## Hierarchy of control activities

1. Measurement and actuation (< 1 s)
2. Safety and environmental/equipment protection (< 1 s)
3. Regulatory control (sec - min)
4. Multivariable and constraint control (sec - min)
5. Real-time optimization (hr - day)
6. Planning and scheduling (day - month)

## Theoretical models of chemical processes

- **Theoretical models** - developed using principles of physics, chemistry, and biology

<br/><br/><br/>

- **Empirical models** - obtained by fitting experimental data

<br/><br/><br/>

- **Semi-empirical models** - numerical values of 1(+) parameters in a theoretical model are calculated from experimental data

## Theoretical models of chemical processes

- **Theoretical models** - developed using principles of physics, chemistry, and biology
  - :heavy_plus_sign: Physical insight into process behavior
  - :heavy_plus_sign: Applicable over wide ranges of conditions
  - :heavy_minus_sign: Expensive and time-consuming to develop
  - :heavy_minus_sign: Model parameter not readily available
- **Empirical models** - obtained by fitting experimental data
  - :heavy_plus_sign: Easy to develop and use
  - :heavy_minus_sign: Do not extrapolate to conditions beyond range
- **Semi-empirical models** - numerical values of 1(+) parameters in a theoretical model are calculated from experimental data
  - :heavy_plus_sign: Incorporate theoretical knowledge
  - :heavy_plus_sign: Extrapolate over wider range of operating conditions
  - :heavy_plus_sign: Requires less developmental effort
