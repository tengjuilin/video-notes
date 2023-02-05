---
marp: true
theme: simple
paginate: true
footer:
---

<!-- headingDivider: 2 -->
<!-- _class: cover -->
# Definition of Laplace Transform

Teng-Jui Lin
Department of Chemical Engineering, University of Washington
**Process Dynamics and Control**

## Review: improper integral

The **improper integral** is defined as a limit:

$$
\int_a^\infty f(t) dt = \lim_{b \to \infty} \int_a^b f(t) dt
$$

- Convergent - limit exists
- Divergent - limit does not exist

## Definition of Laplace transform

**Laplace transform** of a piece-wise continuous $f(t)$ defined for $t \ge 0$ is

$$
\mathcal{L}[f(t)] = \int_0^\infty e^{-st} f(t) dt
$$

if the integral converges.

- Notation
  - Lower case for original function $f(t)$
  - Upper case for Laplace-transformed function $\mathcal{L}[f(t)] \equiv F(s)$

## Laplace transform simplifies solving ODE to solving algebraic equations

Time domain
$f, f(t)$

<br/><br/><br/><br/><br/>

Laplace domain
$s, F(s)$

## Laplace transform of a constant

**Zill Ex. 4.1.1** Evaluate $\mathcal{L}[c]$, where $c$ is a constant.

## Laplace transform of a linear function

**Zill Ex. 4.1.2** Evaluate $\mathcal{L}[t]$.

## Laplace transform of a exponential function

**Zill Ex. 4.1.3a** Evaluate $\mathcal{L}[e^{-3t}]$.

<br/><br/><br/><br/><br/>

**Zill Ex. 4.1.3b** Evaluate $\mathcal{L}[e^{6t}]$.

## Laplace transform of a sine function

**Zill Ex. 4.1.4** Evaluate $\mathcal{L}[\sin(2t)]$.

## Laplace transform of a piecewise-continuous function

**Zill Ex. 4.1.6** Evaluate $\mathcal{L}[f(t)]$ for $
f(t) \begin{cases}
  0 & t \in [0, 3) \\
  2 & t \in [3, \infty)
\end{cases}
$

## Common Laplace transforms are tabulated

Use Seaborg Table 3.1

|Inverse L.T. <br/> $f(t)$|Laplace Transform <br/> $F(s)$|Inverse L.T. <br/> $f(t)$|Laplace Transform <br/> $F(s)$|
|-:|:---|-:|:-|
|$1$|$\dfrac{1}{s}$|$e^{at}$|$\dfrac{1}{s-a}$|
|$t^{n}$|$\dfrac{n!}{s^{n+1}}$|$\sqrt{t}$|$\dfrac{\sqrt{\pi}}{2s^{3/2}}$|
|$\sin(at)$|$\dfrac{a}{s^{2}+a^{2}}$|$t\sin(at)$|$\dfrac{2as}{(s^{2}+a^{2})^{2}}$|
|$\cos(at)$|$\dfrac{s}{s^{2}+a^{2}}$|$t\cos(at)$|$\dfrac{s^{2}-a^{2}}{(s^{2}+a^{2})^{2}}$|

## Linearity simplifies problem

- **Linear combination** - multiplication of terms by constant and/or addition of terms

<br/><br/><br/>

- **Linearity** - transform of a linear combination = linear combination of the transforms
  - $T[\alpha f(x) + \beta g(x)] = \alpha T[f(x)] + \beta T[g(x)]$

## Laplace transform is linear

**Ex.** Demonstrate Laplace transform is linear.

- Laplace transform is an integral transform
  - Definition: $\mathcal{L}[f(t)] = \int_0^\infty e^{-st} f(t) dt$

## Laplace transform is linear

$$
\begin{aligned}
  &\mathcal{L}[\alpha f(t) + \beta g(t)] \\
  =& \alpha \mathcal{L}[f(t)] + \beta \mathcal{L}[g(t)] \\
  =& \alpha F(s) + \beta G(s)
\end{aligned}
$$

**Zill Ex. 4.1.5a** Use linearity of Laplace transform to evaluate $\mathcal{L}[1 + 5t]$
