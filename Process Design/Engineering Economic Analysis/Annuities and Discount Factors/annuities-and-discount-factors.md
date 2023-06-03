---
marp: true
theme: simple
paginate: true
footer:
---
<!-- Marp for VS Code v1.5.2 -->

<!-- headingDivider: 2 -->
<!-- _class: cover -->
# Annuities and Discount Factors

Teng-Jui Lin
Department of Chemical Engineering, University of Washington
**Process Design**

## Annuities give same amount of cash flow for each consecutive year

**Ex.** Verify that the future value $F_n$ of annuities with each transaction value of $A$ for $n$ consecutive years is

$$
\boxed{F_n = A \left[\dfrac{(1+i)^n - 1}{i}\right]}
$$

where $i$ is the annual interest rate.

- **Annuities** - A series of uniform value cash transactions in consecutive years
- Hint: $n$th partial sum of geometric series: $S_n = a_1 \dfrac{1 - r^n}{1 - r}$

## Discount factor converts money value between the present, future, and annuities

- Discount factor for converting $A$ to $F$

$$
F_n = A \left[\dfrac{(1+i)^n - 1}{i}\right]
$$

- Notation

## Discount factors are derived from known discount factors

**Ex.** Derive the discount factor for converting $A$ to $P$.

## Common discount factors are tabulated

Turton Table 9.1

|Conversion|Symbol|Common Name|Formula|
|:-:|:-:|-|:-:|
|$P$ to $F$|$F/P$|Single payment compound amount factor|$(1+i)^n$|
|$F$ to $P$|$P/F$|Single payment present worth factor|$\dfrac{1}{(1+i)^n}$|
|$A$ to $F$|$F/A$|Uniform series compound amount factor; <br/> Future worth of annuity|$\dfrac{(1+i)^n - 1}{i}$|
|$F$ to $A$|$A/F$|Sinking fund factor|$\dfrac{1}{(1+i)^n - 1}$|
|$P$ to $A$|$A/P$|Capital recovery factor|$\dfrac{i(1+i)^n}{(1+i)^n - 1}$|
|$A$ to $P$|$P/A$|Uniform series present worth factor; <br/> Present worth of annuity|$\dfrac{(1+i)^n - 1}{i(1+i)^n}$|

## Example of using discount factor as a conversion factor

**Turton Ex. 9.14** A lottery winner will receive $200,000/year for the next 20 years.
(**a**) What is the equivalent present value of the winnings if there is a secure investment opportunity providing 7.5% p.a.?
(**b**) What rate of return in part (a) would be needed for a present value of $2.5 million?
