---
marp: true
theme: simple
paginate: true
footer:
---
<!-- Marp for VS Code v1.5.2 -->

<!-- headingDivider: 2 -->
<!-- _class: cover -->
# Laplace Transforms of Integrals

Teng-Jui Lin
Department of Chemical Engineering, University of Washington
**Process Dynamics and Control**

## Laplace transforms of integrals

**Ex.** Proof that the Laplace transform of an integral is

$$
\mathcal{L}\left[\int_0^t f(t^*) dt^* \right] = \dfrac{1}{s} F(s)
$$

## Laplace transforms of derivatives and integrals

$$
\begin{aligned}
    \text{Derivative:}\quad && \mathcal{L}\left[ \dfrac{d}{dt} f(t) \right] &= sF(s) - f(0) \\
    \text{Integral:}\quad && \mathcal{L}\left[\int_0^t f(t^*) dt^* \right] &= \dfrac{1}{s} F(s)
\end{aligned}
$$
