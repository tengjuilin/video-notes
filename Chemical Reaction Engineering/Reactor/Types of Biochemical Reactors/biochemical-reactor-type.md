---
marp: true
theme: simple
paginate: true
footer:
math: katex
---

<!-- headingDivider: 2 -->
<!-- _class: cover -->
# Types of Biochemical Reactors

Teng-Jui Lin
Department of Chemical Engineering, University of Washington
**Chemical Reaction Engineering**

## Chemical processes can be classified as batch, continuous, or semibatch

- **Batch process** - no mass crosses the system boundary

<br/><br/><br/>

- **Continuous process** - inputs and outputs flow continuously through the system boundary

<br/><br/><br/>

- **Semibatch process** - neither batch nor continuous

## Biochemical reactors can also be classified as batch, continuous, or semibatch

- **Batch reactor** - feed is put into the reactor before $t = 0$, no inlet or outlet during operation
  - Batch process

<br/><br/>

- **Continuous stirred tank reactor (CSTR, chemostat)** - inlet and outlet flow continuously in and out
  - Continuous process

<br/><br/>

- **Semibatch reactor** - feed is added to the reactor OR the reactor content is drained
  - Semibatch process

## Conservation of mass is the foundation of mass balance

- **Conservation of mass** - no mass is created nor destroyed in physical and chemical processes
- **Mass balance** of a chemical species
$$\begin{aligned}
\text{In} - \text{Out} + \text{Generation} &= \text{Accumulation} \\
\dot{m}_{i, 0} - \dot{m}_{i} + \tilde{G}_i &= \dfrac{dm_i}{dt} \\
\dot{n}_{i, 0} - \dot{n}_{i} + G_i &= \dfrac{dn_i}{dt}
\end{aligned}$$

- In $\dot{n}_{i, 0}$
- Out $\dot{n}_{i}$
- Generation/Destruction $G_i$
- Accumulation $\dfrac{dn_i}{dt}$

## Batch reactor mass balance gives its design equation

$$
\dot{n}_{i, 0} - \dot{n}_{i} + G_i = \dfrac{dn_i}{dt}
$$

- Assumptions
  - No inlet - $\dot{n}_{i, 0} = 0$
  - No outlet - $\dot{n}_{i} = 0$

## Continuous stirred tank reactor (CSTR) mass balance gives its design equation

$$
\dot{n}_{i, 0} - \dot{n}_{i} + G_i = \dfrac{dn_i}{dt}
$$

- Assumptions
  - Steady state - $\dfrac{dn_i}{dt} = 0$

## Semibatch reactor mass balance gives its design equation

$$
\dot{n}_{i, 0} - \dot{n}_{i} + G_i = \dfrac{dn_i}{dt}
$$

- Assumptions
  - Feed batch, no outlet - $\dot{n}_{i} = 0$
  - Well-mixed, spatially uniform - $G_i = r_i V(t)$
