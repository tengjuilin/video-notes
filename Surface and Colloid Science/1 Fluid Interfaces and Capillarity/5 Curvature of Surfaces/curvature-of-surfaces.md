---
marp: true
theme: simple
paginate: true
footer:
---

<!-- headingDivider: 2 -->
<!-- _class: cover -->
# Curvature of Surfaces

Teng-Jui Lin
Department of Chemical Engineering, University of Washington
**Surface and Colloid Science**

## Curvature in 2D: every point on a plane curve
<!-- _class: twocol -->
![height:450px center](plane-curve-derive.png)

- $\kappa = \pm\dfrac{d\phi}{dS}$
- $\boxed{\kappa = \pm y'' [1 + (y'')^2]^{-3/2}}$

## Curvature in 2D: every point on a circle
<!-- _class: twocol -->
![height:550px center](circle-derive.png)

- $\boxed{\kappa = \dfrac{1}{R}}$

## Curvature in 3D: a point on a surface
<!-- _class: twocol -->
![height:550px center](surface-point-derive.png)

- $\kappa = \pm\left(\dfrac{1}{R_1} + \dfrac{1}{R_2}\right) = \pm\dfrac{2}{R_m}$

## Curvature in 3D: every point on a surface

![height:350px center](surface-general-derive.png)

$$\boxed{\kappa = \pm \dfrac{z_{xx}[1 + (z_y)^2] - 2 z_x z_y z_{xy} + z_{yy}[1 + (z_x)^2]}{[1 + (x_z)^2 + (z_y)^2]^{3/2}}}$$

## Special cases of 3D curvature: spheres and circular cylinders
<!-- _class: twocol -->
<!-- ![height:250px](sphere.png)![height:250px](circular-cylinder.png) -->

![height:250px](circular-cylinder.png)

![height:250px](sphere.png)

- Sphere
  - $\boxed{\kappa = \dfrac{2}{R}}$
- Circular cylinder
  - $\boxed{\kappa = \dfrac{1}{R}}$

## Special cases of 3D curvature: general cylindrical surface

![height:220px center](general-cylindrical.png)

$$\boxed{\kappa = \pm y'' [1 + (y')^2]^{3/2}}$$

![height:220px center](general-cylindrical-example.png)

## Special cases of 3D curvature: axially symmetric surfaces

![height:220px center](axially-symmetric.png)

$$\boxed{\kappa = \pm \left[\dfrac{y''}{[1 + (y')^2]^{3/2}} + \dfrac{y'}{x[1 + (y')^2]^{1/2}}\right]}$$

![height:220px center](axially-symmetric-examples.png)

## Special cases of 3D curvature: saddle-shaped surfaces

![height:250px center](saddle-shaped.png)

$$\boxed{\kappa = \pm \left[\dfrac{y''}{[1 + (y')^2]^{3/2}} - \dfrac{y'}{x[1 + (y')^2]^{1/2}}\right]}$$

![height:150px center](saddle-shaped-examples.png)

## Hermitian and Gaussian curvature together uniquely define a surface
<!-- _class: twocol -->
![height:450px center](gaussian-curvature.png)

- Hermitian curvature
  - $H = \dfrac{\kappa}{2} = \pm \dfrac{1}{2}\left(\dfrac{1}{R_1} + \dfrac{1}{R_2}\right)$
- Gaussian curvature
  - $\lambda = \pm \dfrac{1}{R_1 R_2}$

## Plateau's problem: minimal surface area with a given boundary

![height:400px](plateau-problem.png) &nbsp; ![height:400px](plateau-problem-real-example.jpg)