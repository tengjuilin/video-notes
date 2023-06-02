---
marp: true
theme: simple
paginate: true
footer:
math: mathjax
---

<!-- headingDivider: 2 -->
<!-- _class: cover -->
# Michaelis-Menten Kinetics

Teng-Jui Lin
Department of Chemical Engineering, University of Washington
**Chemical Reaction Engineering**

## Enzyme are proteins that speeds up biological reactions without being used up

- **Catalyzer** - substances that speeds up reactions without being used up
- **Enzyme** - proteins that catalyzes reactions
  - E.g. Sucrase - digestive enzyme that breaks down sucrose into glucose

## Michaelis-Menten kinetics describes simple enzymatic reactions

- Overall reaction
  - $\ce{S ->[E] P}$
- Reaction mechanism
  - $\ce{S + E <=>[\mathit{k}_1][\mathit{k}_{-1}] ES}$
  - $\ce{ES ->[\mathit{k}_{2}] P + E}$

## Michaelis-Menten kinetics can be derived with pseudo-steady-state approximation

**Ex**. Derive the rate of production $r_{\ce{P}}
$ described by Michaelis-Menten and determine $V_{\max}$ and $K_M$:

$$\boxed{r_{\ce{P}} = \dfrac{V_{\max} \ce{[S]}}{K_M + \ce{[S]}}}$$

- Rate expression of rate of production

<br/>

- Rate expression of rate of production of intermediate
  - **Pseudo-steady-state approximation** - intermediates are immediately consumed after production, so the net rate of intermediate is zero

## Michaelis-Menten kinetics relates rate of production with substrate concentration

<br/><br/>

- Enzyme balance - total amount of enzyme is constant

<br/>

- Solve for $[\ce{ES}]$

<br/><br/><br/>

- Solve for $r_{\ce{P}}$

## Michaelis-Menten parameters describes reaction properties

- Simplify $r_{\ce{P}}$ with
  - **Maximum rate** of reaction
    - $V_{\max} = k_2 [\ce{E_T}]$
  - **Michaelis-Menten constant** - attraction of enzyme of its substrate
    - $K_M = \dfrac{k_2 + k_{-1}}{k_1}$
  - **Turnover number** - # substrates converted to product per unit time on one enzyme at saturation
    - $k_{\text{cat}} = k_2$

<br/><br/>

- Given Michaelis-Menten parameters, we can know $r_{\ce{P}}([\ce{S}])$ by Michaelis-Menten eqn:

$$\boxed{r_{\ce{P}} = \dfrac{V_{\max} \ce{[S]}}{K_M + \ce{[S]}}}$$

## Michaelis-Menten parameters can be found by linearizing the Michaelis-Menten eqn

$$\boxed{r_{\ce{P}} = \dfrac{V_{\max} \ce{[S]}}{K_M + \ce{[S]}}}$$

- **Lineweaver-Burk equation**
  - $\dfrac{1}{r_{\ce{P}}} = \dfrac{K_M}{V_{\max}}\dfrac{1}{\ce{[S]}} + \dfrac{1}{V_{\max}}$
- Eadie-Hofstee equation
  - $r_{\ce{P}} = V_{\max} - K_M\dfrac{r_{\ce{P}}}{\ce{[S]}}$
- Hanes-Woolf equation
  - $\dfrac{\ce{[S]}}{r_{\ce{P}}} = \dfrac{K_M}{V_{\max}} + \dfrac{1}{V_{\max}}\ce{[S]}$
