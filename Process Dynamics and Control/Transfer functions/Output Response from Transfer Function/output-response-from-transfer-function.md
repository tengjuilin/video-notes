---
marp: true
theme: simple
paginate: true
footer:
---
<!-- Marp for VS Code v1.5.2 -->

<!-- headingDivider: 2 -->
<!-- _class: cover -->
# Output Response from Transfer Functions

Teng-Jui Lin
Department of Chemical Engineering, University of Washington
**Process Dynamics and Control**

## Evaluating nominal steady-state condition

**Seborg Ex. 4.5a** Given constant liquid density $\rho$, volume $V$, mass flow rates $w_1$, $w_2$, and $w$, the governing equation for a continuous blending process is

$$
\rho V \dfrac{dx}{dt} = w_1 x_1 + w_2 x_2 - wx
$$

where $x$ are compositions. When output $x$ varies upon change in input $x_1$ while $x_2$ is held constant, the transfer function is

$$
G(s) = \dfrac{K_1}{\tau s + 1}, \quad K_1 \equiv \dfrac{w_1}{w}, \quad \tau \equiv \dfrac{\rho V}{w}
$$

Determine the nominal exit concentration $\overline{x}$, given $w_1 = 600$ kg/min, $w_2 = 2$ kg/min, $x_1 = 0.05$, $x_2 = 1$.

## Output response upon step input change can be determined from transfer functions

**Seborg Ex. 4.5b** Derive an expression of the output response $x(t)$ given the transfer function

$$
G(s) = \dfrac{K_1}{\tau s + 1}, \quad K_1 \equiv \dfrac{w_1}{w}, \quad \tau \equiv \dfrac{\rho V}{w}
$$

and sudden input change in $x_1$ from 0.050 to 0.075 at $t = 0$. Assume the process is initially at steady-state. Given $w_1 = 600$ kg/min, $w_2 = 2$ kg/min, $x_1 = 0.05$, $x_2 = 1$, $V = 2 \ \mathrm{m^3}$, $\rho = 900 \ \mathrm{kg/m^3}$.
