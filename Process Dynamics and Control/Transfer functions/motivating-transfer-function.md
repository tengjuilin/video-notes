---
marp: true
theme: simple
paginate: true
footer:
---

<!-- headingDivider: 2 -->
<!-- _class: cover -->
# Motivating Transfer Functions

Teng-Jui Lin
Department of Chemical Engineering, University of Washington
**Process Dynamics and Control**

## Laplace-transformed output in original variables are hard to find

**Ex.** Find the Laplace-transformed output $Y(s)$ of the ODE

$$
\dfrac{dy}{dt} = x - y
$$

where $x$ is the input and $y$ is the output.

## Deviation variables have vanishing initial condition at steady-state in $\mathcal{L}$ space

**Ex.** Find the Laplace-transformed output deviation $Y'(s)$ of the ODE

$$
\dfrac{dy}{dt} = x - y
$$

where $x$ is the input and $y$ is the output, by defining deviation variable of $y' = y - \overline{y}$.

- Derive governing ODE
- Identify variables
  - Input variable (cause)
  - Output variable (effect)
- Derive steady-state expression
- Derive ODE in deviation variables
- Get transfer function in $\mathcal{L}$ space

## Deviation variables have vanishing initial condition at steady-state in $\mathcal{L}$ space

**Ex.** Find the Laplace-transformed output deviation $Y'(s)$ of the ODE

$$
\dfrac{dy}{dt} = x - y
$$

where $x$ is the input and $y$ is the output, by defining deviation variable of $y' = y - \overline{y}$.

## Transfer function maps input-output relationship in the $\mathcal{L}$ space

- **Transfer function** - characterizes dynamic relationship of input and output variables in the Laplace space
$$\boxed{G(s) = \dfrac{\mathcal{L}[\text{output}]}{\mathcal{L}[\text{input}]}}$$
- **Deviation variable** - deviation from a nominal steady-state
  - Have vanishing initial condition at steady-state in $\mathcal{L}$ space

<br/>

## Laplace transform of multivariable ODE show linearity of transfer function

**Ex.** Find the Laplace-transformed output deviation $Z'(s)$ of the ODE

$$
\dfrac{dz}{dt} = x - y - z
$$

where $x$ and $y$ are the inputs and $z$ is the output.

## Transfer function can predict step change

**Ex.** Determine the response $y(t)$ to a step change in $x$ of magnitude $M$ at $t = 0$ using the transfer function

$$
G(s) = \dfrac{1}{s+1}
$$

- Rearrange for $Y'(s)$

- Determine $X'(s)$ from $x'(t)$

- Get deviation in time space

- Get response in time space

## Obtaining transfer function from ODE

**Seborg Ex. 4.1a** Find the transfer function model between liquid level $h$ and inlet flow rate $q_i$ in deviation variables with governing ODE of
$$
A\dfrac{dh}{dt} = q_i - \dfrac{1}{R_v}h
$$

- Derive steady-state expression

<br/>

- Derive ODE in deviation variables

## Obtaining transfer function from ODE

**Seborg Ex. 4.1a** Find the transfer function model between liquid level $h$ and inlet flow rate $q_i$ in deviation variables with governing ODE of
$$
A\dfrac{dh}{dt} = q_i - \dfrac{1}{R_v}h
$$

- Know ODE in deviation variables

$$
A\dfrac{dh'}{dt} = q'_i - \dfrac{1}{R_v}h'
$$

- Get transfer function in $\mathcal{L}$ space
  - Initial condition

## Use transfer function to predict step change

**Seborg Ex. 4.1b** Determine the response $h(t)$ to a step change in $q_i$ of magnitude $M$ at $t = 0$ using the transfer function

$$
G(s) = \dfrac{H'(s)}{Q_i'(s)} = \dfrac{R_v}{AR_v s + 1}
$$

- Rearrange for $H'(s)$

- Determine $Q'_i(s)$ from $q'_i(t)$

- Get deviation response in time space

- Get response in time space