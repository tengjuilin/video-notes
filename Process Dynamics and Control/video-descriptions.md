# Process Dynamics and Control Video Descriptions

- [Process Dynamics and Control Video Descriptions](#process-dynamics-and-control-video-descriptions)
  - [Intro to Process Dynamics and Control](#intro-to-process-dynamics-and-control)
    - [Introduction to Process Dynamics and Control [Process Dynamics and Control]](#introduction-to-process-dynamics-and-control-process-dynamics-and-control)
  - [Laplace transform](#laplace-transform)
    - [Definition and Linearity of Laplace Transform [Process Dynamics and Control]](#definition-and-linearity-of-laplace-transform-process-dynamics-and-control)
    - [Inverse Laplace Transform and Partial Fraction Decomposition [Process Dynamics and Control]](#inverse-laplace-transform-and-partial-fraction-decomposition-process-dynamics-and-control)
    - [Laplace Transform of Derivatives and Initial and Final Value Theorem [Process Dynamics and Control]](#laplace-transform-of-derivatives-and-initial-and-final-value-theorem-process-dynamics-and-control)
    - [Laplace Transform of Integrals [Process Dynamics and Control]](#laplace-transform-of-integrals-process-dynamics-and-control)
    - [Translation Theorems of Laplace Transform [Process Dynamics and Control]](#translation-theorems-of-laplace-transform-process-dynamics-and-control)
    - [Laplace Transforms of Special Input Functions [Process Dynamics and Control]](#laplace-transforms-of-special-input-functions-process-dynamics-and-control)
    - [Solving ODEs with Laplace Transforms [Process Dynamics and Control]](#solving-odes-with-laplace-transforms-process-dynamics-and-control)
  - [Transfer functions](#transfer-functions)
    - [Motivating Transfer Functions [Process Dynamics and Control]](#motivating-transfer-functions-process-dynamics-and-control)
    - [Transfer Functions of Multivariable ODEs and Linearity [Process Dynamics and Control]](#transfer-functions-of-multivariable-odes-and-linearity-process-dynamics-and-control)
    - [Transfer Functions Predicts Output Changes [Process Dynamics and Control]](#transfer-functions-predicts-output-changes-process-dynamics-and-control)
    - [Steady-State Gain [Process Dynamics and Control]](#steady-state-gain-process-dynamics-and-control)
    - [Addition Property of Transfer Functions [Process Dynamics and Control]](#addition-property-of-transfer-functions-process-dynamics-and-control)
    - [Multiplicative Property of Transfer Functions [Process Dynamics and Control]](#multiplicative-property-of-transfer-functions-process-dynamics-and-control)
    - [Linearization of Nonlinear Models [Process Dynamics and Control]](#linearization-of-nonlinear-models-process-dynamics-and-control)
  - [First-Order Processes](#first-order-processes)
    - [Standard Process Inputs [Process Dynamics and Control]](#standard-process-inputs-process-dynamics-and-control)
    - [Step Responses of First-Order Processes [Process Dynamics and Control]](#step-responses-of-first-order-processes-process-dynamics-and-control)
    - [Ramp Responses of First-Order Processes [Process Dynamics and Control]](#ramp-responses-of-first-order-processes-process-dynamics-and-control)
    - [Sinusoidal Responses of First-Order Processes [Process Dynamics and Control]](#sinusoidal-responses-of-first-order-processes-process-dynamics-and-control)
  - [Second-Order Processes](#second-order-processes)
    - [Transfer Function Models of Second-Order Processes [Process Dynamics and Control]](#transfer-function-models-of-second-order-processes-process-dynamics-and-control)
    - [Step Responses of Second-Order Processes [Process Dynamics and Control]](#step-responses-of-second-order-processes-process-dynamics-and-control)
    - [Modeling Step Responses of Second-Order Processes [Process Dynamics and Control]](#modeling-step-responses-of-second-order-processes-process-dynamics-and-control)
    - [Sinusoidal Responses of Second-Order Processes [Process Dynamics and Control]](#sinusoidal-responses-of-second-order-processes-process-dynamics-and-control)
  - [Feedback Controllers](#feedback-controllers)
    - [Proportional Control [Process Dynamics and Control]](#proportional-control-process-dynamics-and-control)

## Intro to Process Dynamics and Control

### Introduction to Process Dynamics and Control [Process Dynamics and Control]

## Laplace transform

### Definition and Linearity of Laplace Transform [Process Dynamics and Control]

```
We define and motivate Laplace transforms, evaluate Laplace transforms of simple functions, and introduce linearity of Laplace transforms.
---------
Video notes and slides available on GitHub: https://github.com/tengjuilin/video-notes
Equation sheets available on GitHub: https://github.com/tengjuilin/equation-sheets
Course notes available on GitHub: https://github.com/tengjuilin/course-notes
---------
References:
Zill, D. G. (2016). Advanced Engineering Mathematics (6th edition). Jones & Bartlett Learning.
---------
%%% CHAPTERS %%%
00:00 Review of improper integrals
00:30 Definition of Laplace transform
01:08 Motivation of Laplace transform
02:59 Example: L of constant
05:40 Example: L of linear function
08:26 Example: L of exp function
14:24 Example: L of sine function
21:10 Example: L of piecewise-continuous function
25:04 Intro to Linearity
30:01 Laplace transform is linear
32:20 Example: use linearity
```

### Inverse Laplace Transform and Partial Fraction Decomposition [Process Dynamics and Control]

```
We loosely define inverse Laplace transforms, resorting to tabulated values with examples, and introduced partial fraction expansion by Heaviside expansion or the cover-up method.
---------
Video notes and slides available on GitHub: https://github.com/tengjuilin/video-notes
Equation sheets available on GitHub: https://github.com/tengjuilin/equation-sheets
Course notes available on GitHub: https://github.com/tengjuilin/course-notes
---------
References:
Seborg, D. E., Edgar, T. F., Mellichamp, D. A., & Doyle, F. J. (2016). Process Dynamics and Control (4th ed.). Wiley.
Zill, D. G. (2016). Advanced Engineering Mathematics (6th edition). Jones & Bartlett Learning.
---------
%%% CHAPTERS %%%
00:00 Intro
00:23 Definition of inverse Laplace transform
02:00 Tabulated values
02:52 Example: inverse Laplace transform
05:28 Term-wise division and linearity
08:15 Partial fractions and linearity
13:41 Heaviside expansion (cover-up method)
20:22 Example: cover-up method
```

### Laplace Transform of Derivatives and Initial and Final Value Theorem [Process Dynamics and Control]

```
We derived the Laplace transform of n-th order derivatives and loosely proved the final and initial value theorems.
---------
Video notes and slides available on GitHub: https://github.com/tengjuilin/video-notes
Equation sheets available on GitHub: https://github.com/tengjuilin/equation-sheets
Course notes available on GitHub: https://github.com/tengjuilin/course-notes
---------
References:
Seborg, D. E., Edgar, T. F., Mellichamp, D. A., & Doyle, F. J. (2016). Process Dynamics and Control (4th ed.). Wiley.
Zill, D. G. (2016). Advanced Engineering Mathematics (6th edition). Jones & Bartlett Learning.
---------
%%% CHAPTERS %%%
00:00 Intro
00:21 L of derivatives
07:32 L of n-th order derivatives
09:38 Final value theorem
13:02 Initial value theorem
```

### Laplace Transform of Integrals [Process Dynamics and Control]

```
We derived the Laplace transform of an integral and draw parallel between Laplace transform of derivatives and integrals.
---------
Video notes and slides available on GitHub: https://github.com/tengjuilin/video-notes
Equation sheets available on GitHub: https://github.com/tengjuilin/equation-sheets
Course notes available on GitHub: https://github.com/tengjuilin/course-notes
---------
References:
Seborg, D. E., Edgar, T. F., Mellichamp, D. A., & Doyle, F. J. (2016). Process Dynamics and Control (4th ed.). Wiley.
---------
%%% CHAPTERS %%%
00:00 Intro
00:10 Derive L of integral
03:48 L of derivative and integral
```

### Translation Theorems of Laplace Transform [Process Dynamics and Control]

### Laplace Transforms of Special Input Functions [Process Dynamics and Control]

### Solving ODEs with Laplace Transforms [Process Dynamics and Control]

```
We brought everything together by reviewing the framework for solving ODEs with Laplace transforms and demonstrated with examples.
---------
Video notes and slides available on GitHub: https://github.com/tengjuilin/video-notes
Equation sheets available on GitHub: https://github.com/tengjuilin/equation-sheets
Course notes available on GitHub: https://github.com/tengjuilin/course-notes
---------
References:
Seborg, D. E., Edgar, T. F., Mellichamp, D. A., & Doyle, F. J. (2016). Process Dynamics and Control (4th ed.). Wiley.
Zill, D. G. (2016). Advanced Engineering Mathematics (6th edition). Jones & Bartlett Learning.
---------
%%% CHAPTERS %%%
00:00 Intro
00:21 Method overview
02:56 Example: first-order ODE
15:25 Example: second-order ODE
```

## Transfer functions

### Motivating Transfer Functions [Process Dynamics and Control]

```
We motivated and defined transfer functions and deviation variables. We derived transfer functions from governing ODEs and used them to predict output changes upon step changes in inputs.

Erratum: Slide 8, liquid height h is the output, which is the "effect", not the "cause".
---------
Video notes and slides available on GitHub: https://github.com/tengjuilin/video-notes
Equation sheets available on GitHub: https://github.com/tengjuilin/equation-sheets
Course notes available on GitHub: https://github.com/tengjuilin/course-notes
---------
References:
Seborg, D. E., Edgar, T. F., Mellichamp, D. A., & Doyle, F. J. (2016). Process Dynamics and Control (4th ed.). Wiley.
---------
%%% CHAPTERS %%%
00:00 Intro
00:22 Original variable
02:46 Deviation variable
10:43 Definition of transfer function
14:05 Multivariable ODE
19:13 Transfer func predicts step change
24:24 Example: get transfer function from ODE
30:26 Example: get output change using transfer function
```

### Transfer Functions of Multivariable ODEs and Linearity [Process Dynamics and Control]

```
We worked an example of finding transfer functions of a multivariable ODE. We show that the transfer functions of different inputs are linearly additive.
---------
Video notes and slides available on GitHub: https://github.com/tengjuilin/video-notes
Equation sheets available on GitHub: https://github.com/tengjuilin/equation-sheets
Course notes available on GitHub: https://github.com/tengjuilin/course-notes
---------
References:
Seborg, D. E., Edgar, T. F., Mellichamp, D. A., & Doyle, F. J. (2016). Process Dynamics and Control (4th ed.). Wiley.
---------
%%% CHAPTERS %%%
00:00 Intro
00:12 Example 1: multivariable ODE
06:00 Example 2: multivariable ODE
12:01 Linearity of transfer functions
14:14 Linearity and input-output relationship
```

### Transfer Functions Predicts Output Changes [Process Dynamics and Control]

```
We worked an example of finding the output response given a step change of input using transfer functions.
---------
Video notes and slides available on GitHub: https://github.com/tengjuilin/video-notes
Equation sheets available on GitHub: https://github.com/tengjuilin/equation-sheets
Course notes available on GitHub: https://github.com/tengjuilin/course-notes
---------
References:
Seborg, D. E., Edgar, T. F., Mellichamp, D. A., & Doyle, F. J. (2016). Process Dynamics and Control (4th ed.). Wiley.
---------
%%% CHAPTERS %%%
00:00 Intro
00:14 Example: steady-state value
02:17 Example: output response from transfer function
```

### Steady-State Gain [Process Dynamics and Control]

```
We defined steady-state gain and proved a way to find steady-state gain by setting s = 0 for its transfer function
---------
Video notes and slides available on GitHub: https://github.com/tengjuilin/video-notes
Equation sheets available on GitHub: https://github.com/tengjuilin/equation-sheets
Course notes available on GitHub: https://github.com/tengjuilin/course-notes
---------
References:
Seborg, D. E., Edgar, T. F., Mellichamp, D. A., & Doyle, F. J. (2016). Process Dynamics and Control (4th ed.). Wiley.
---------
%%% CHAPTERS %%%
00:00 Intro
00:12 Definition of steady-state gain
02:29 Evaluation of steady-state gain
06:08 Example: Evaluation of gain
```

### Addition Property of Transfer Functions [Process Dynamics and Control]

Example 4.6

### Multiplicative Property of Transfer Functions [Process Dynamics and Control]

Example 4.7

### Linearization of Nonlinear Models [Process Dynamics and Control]

Example 4.8

## First-Order Processes

### Standard Process Inputs [Process Dynamics and Control]

### Step Responses of First-Order Processes [Process Dynamics and Control]

### Ramp Responses of First-Order Processes [Process Dynamics and Control]

### Sinusoidal Responses of First-Order Processes [Process Dynamics and Control]

## Second-Order Processes

### Transfer Function Models of Second-Order Processes [Process Dynamics and Control]

### Step Responses of Second-Order Processes [Process Dynamics and Control]

### Modeling Step Responses of Second-Order Processes [Process Dynamics and Control]

### Sinusoidal Responses of Second-Order Processes [Process Dynamics and Control]

## Feedback Controllers

### Proportional Control [Process Dynamics and Control]

```
We identified basic components in a control loop and defined proportional controllers and their transfer functions. We discussed the advantages and disadvantages of proportional controllers.
---------
Video notes and slides available on GitHub: https://github.com/tengjuilin/video-notes
Equation sheets available on GitHub: https://github.com/tengjuilin/equation-sheets
Course notes available on GitHub: https://github.com/tengjuilin/course-notes
---------
References:
Seborg, D. E., Edgar, T. F., Mellichamp, D. A., & Doyle, F. J. (2016). Process Dynamics and Control (4th ed.). Wiley.
---------
%%% CHAPTERS %%%
00:00 Intro
00:
```
