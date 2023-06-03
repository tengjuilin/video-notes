---
marp: true
theme: simple
paginate: true
footer:
---
<!-- Marp for VS Code v1.5.2 -->

<!-- headingDivider: 2 -->
<!-- _class: cover -->
# Inverse Laplace Transform

Teng-Jui Lin
Department of Chemical Engineering, University of Washington
**Process Dynamics and Control**

## Definition of inverse Laplace transform

If $F(s)$ represents the Laplace transform of $f(t)$, then $f(t)$ is the **inverse Laplace transform** of $F(s)$.

- If $\mathcal{L}[f(t)] = F(s)$, then $f(t) = \mathcal{L}^{-1}[F(s)]$

<br/>

- $\mathcal{L}^{-1}[\mathcal{L}[f(t)]] = f(t)$

<br/>

Inverse Laplace transform is also linear.

$$
\mathcal{L}^{-1}[\alpha F(s) + \beta G(s)] = \alpha\mathcal{L}^{-1}[F(s)] + \beta\mathcal{L}^{-1}[G(s)]
$$

## Common inverse Laplace transforms are tabulated

Use Seaborg Table 3.1... in reverse

|Inverse L.T. <br/> $f(t)$|Laplace Transform <br/> $F(s)$|Inverse L.T. <br/> $f(t)$|Laplace Transform <br/> $F(s)$|
|-:|:---|-:|:-|
|$1$|$\dfrac{1}{s}$|$e^{at}$|$\dfrac{1}{s-a}$|
|$t^{n}$|$\dfrac{n!}{s^{n+1}}$|$\sqrt{t}$|$\dfrac{\sqrt{\pi}}{2s^{3/2}}$|
|$\sin(at)$|$\dfrac{a}{s^{2}+a^{2}}$|$t\sin(at)$|$\dfrac{2as}{(s^{2}+a^{2})^{2}}$|
|$\cos(at)$|$\dfrac{s}{s^{2}+a^{2}}$|$t\cos(at)$|$\dfrac{s^{2}-a^{2}}{(s^{2}+a^{2})^{2}}$|

## Applying inverse Laplace transform

**Zill Ex. 4.2.1a** Evaluate $\mathcal{L}^{-1} \left[\dfrac{1}{s^5}\right]$

Recall $t^n = \mathcal{L}^{-1}\left[\dfrac{n!}{s^{n+1}} \right]$

<br/><br/>

**Zill Ex. 4.2.1b** Evaluate $\mathcal{L}^{-1} \left[\dfrac{1}{s^2 + 7}\right]$

Recall $\sin(at) = \mathcal{L}^{-1}\left[\dfrac{a}{s^{2}+a^{2}} \right]$

## Term-wise division and linearity

**Zill Ex. 4.2.2** Evaluate $\mathcal{L}^{-1} \left[\dfrac{-2s + 6}{s^2 + 4}\right]$

## Partial fractions and linearity

**Ex.** Evaluate $\mathcal{L}^{-1} \left[\dfrac{1}{(s-1)(s+4)}\right]$

## Partial fraction by Heaviside expansion (cover-up method)

**Ex.** Evaluate $\mathcal{L}^{-1} \left[\dfrac{1}{(s-1)(s+4)}\right]$ with Heaviside expansion.

1. Set up partial fraction expansion
2. Multiply both sides by one denominator term $(s + a)$
3. Evaluate at $s = -a$
4. Solve for coefficient

<br/><br/>

1. Cover up denominator term $(s+a)$
2. Evaluate at $s = -a$
3. The result is the coeff for the term

<br/>

Limitation: Rational function of $s$ with distinct linear factors in denominator

## Partial fraction by Heaviside expansion (cover-up method)

**Ex.** Evaluate $\mathcal{L}^{-1} \left[\dfrac{1}{(s-1)(s+4)}\right]$ with Heaviside expansion.

1. Set up partial fraction expansion
2. Multiply both sides by one denominator term $(s + a)$
3. Evaluate at $s = -a$
4. Solve for coefficient

<br/><br/>

1. Cover up denominator term $(s+a)$
2. Evaluate at $s = -a$
3. The result is the coeff for the term

<br/>

Limitation: Rational function of $s$ with distinct linear factors in denominator

## Partial fraction by Heaviside expansion (cover-up method)

**Ex.** Evaluate $\mathcal{L}^{-1} \left[\dfrac{1}{(s-1)(s+4)}\right]$ with Heaviside expansion.

## Cover-up method is great for more complicated expressions

**Zill Remarks 4.2.ii** Evaluate $\mathcal{L}^{-1} \left[\dfrac{s^2 + 6s + 9}{(s-1)(s-2)(s+4)}\right]$ with Heaviside expansion.
