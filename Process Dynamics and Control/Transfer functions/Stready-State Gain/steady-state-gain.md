---
marp: true
theme: simple
paginate: true
footer:
---
<!-- Marp for VS Code v1.5.2 -->

<!-- headingDivider: 2 -->
<!-- _class: cover -->
# Steady-State Gain *K*

Teng-Jui Lin
Department of Chemical Engineering, University of Washington
**Process Dynamics and Control**

## Steady-state gain quantifies how much output changes upon *unit* input change

**Steady-state gain** $K$ - ratio of the output variable change to an sustained input variable change at new steady state

$$
K = \dfrac{\overline{y}_2 - \overline{y}_1}{\overline{u}_2 - \overline{u}_1}
$$

Steady state gain is a constant for linear processes.

## Steady-state gain can be evaluated from $G(0)$

**Ex.** Prove that steady-state gain can be evaluated from $G(s)$ by setting $s = 0$ (if the gain exists).

- Final value theorem: $\displaystyle\lim_{t\to \infty} [y(t)] = \lim_{s \to 0}[sY(s)]$

## Example: determining steady-state gain

**Ex.** Determine the steady state gain given transfer function of $G(s) = \dfrac{w_1}{\rho V s +  w}$
