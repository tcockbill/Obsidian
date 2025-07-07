---
tags:
  - maths
date: 2025-05-13
---
---  
# Parametric equations  
---  
aliases: [Parametric Equation, Parameterized Curve]  
tags: [mathematics, calculus, curves]  
---  
  
A **parametric equation** defines a set of quantities as explicit functions of one or more independent variables, known as **parameters**. These equations are especially useful for describing curves and surfaces in two or three dimensions, where expressing one variable directly as a function of the other might be difficult or impossible.  
  
**General Form:**  
  
For a curve in 2D space, a parametric equation is typically written as:  
  
*   `x = f(t)`  
*   `y = g(t)`  
  
Where `t` is the parameter, and `f` and `g` are functions of `t`. As `t` varies, the points (x, y) trace out a curve in the Cartesian plane.  
  
**Key Advantages:**  
  
*   **Handles Complex Curves:** Parametric equations can represent curves that are not functions in the standard Cartesian form (e.g., curves that loop back on themselves).  
*   **Provides Direction:** The parameter `t` can be interpreted as time, and the parametric equations describe the position of a particle moving along the curve as a function of time, giving the curve a natural direction.  
*   **Easier Calculations:** Certain calculations, such as arc length and surface area, are often easier to perform using parametric equations.  
*   **Representing Surfaces:** Can be extended to three dimensions to represent surfaces:  
	* `x = f(u, v)`  
	* `y = g(u, v)`  
	* `z = h(u, v)`  
  
**Examples:**  
  
*   **Circle:** `x = r*cos(t)`, `y = r*sin(t)`, where `r` is the radius and `t` ranges from 0 to 2π.  
*   **Line:** `x = x₀ + at`, `y = y₀ + bt`, where (x₀, y₀) is a point on the line and (a, b) is the direction vector.  
*   **Cycloid:** A curve traced by a point on the rim of a rolling circle: `x = r*(t - sin(t))`, `y = r*(1 - cos(t))`.  
  
**Converting to Cartesian Form (if possible):**  
  
Sometimes, it's possible to eliminate the parameter `t` to obtain a Cartesian equation (an equation relating `x` and `y` directly).  This is not always possible or practical.  
  
**Calculus with Parametric Equations:**  
  
*   **Slope (dy/dx):** `dy/dx = (dy/dt) / (dx/dt)`, provided `dx/dt ≠ 0`.  
*   **Second Derivative (d²y/dx²):** `d²y/dx² = d/dx(dy/dx) = [d/dt(dy/dx)] / (dx/dt)`.  
*   **Arc Length:** `L = ∫ √[(dx/dt)² + (dy/dt)²] dt` (integrated over the appropriate range of `t`).  
*   **Surface Area (Revolution about x-axis):** `S = ∫ 2πy √[(dx/dt)² + (dy/dt)²] dt`  
  
**Applications:**  
  
*   **Computer Graphics:** Used extensively for drawing curves and surfaces.  
*   **Physics:** Describing the motion of projectiles and other objects.  
*   **Engineering:** Designing curves for roads, bridges, and other structures.  
  
  
