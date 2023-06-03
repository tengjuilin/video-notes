---
marp: true
theme: simple
paginate: true
footer:
---
<!-- Marp for VS Code v1.5.2 -->

<!-- headingDivider: 2 -->
<!-- _class: cover -->
# Laplace Transform of Derivatives

Teng-Jui Lin
Department of Chemical Engineering, University of Washington
**Process Dynamics and Control**

## Laplace transform of derivatives

**Ex.** Evaluate $\mathcal{L}[f'(t)]$

<br/><br/><br/><br/><br/>

**Ex.** Evaluate $\mathcal{L}[f''(t)]$

<br/><br/><br/><br/><br/>

**Ex.** Evaluate by induction $\mathcal{L}[f'''(t)]$

## Laplace transform of a derivative

$$
\boxed{\mathcal{L}[f^{(n)}(t)] = s^n F(s) - s^{n-1} f(0) - s^{n-2} f'(0) - \cdots - sf^{(n-2)}(0) - f^{(n-1)}(0)}
$$

## Final value theorem

**Ex.** Proof the final value theorem.

$$
\boxed{\lim_{t \to\infty} y(t) = \lim_{s \to 0} [sY(s)]}
$$

## Initial value theorem

**Ex.** Proof the initial value theorem.

$$
\boxed{\lim_{t \to 0} y(t) = \lim_{s \to \infty} [sY(s)]}
$$
