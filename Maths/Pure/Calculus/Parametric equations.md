---
tags:
  - maths
date: 2025-06-05T09:08:39
---
---  
# Parametric equations  
## Parametric Equations  
  
Parametric equations provide a way to define a curve or surface using independent parameters. Instead of expressing `y` directly as a function of `x` (like `y = f(x)`), both `x` and `y` are expressed as functions of a third variable, often denoted as `t`. This parameter `t` can represent time, angle, or any other convenient quantity.  
  
**General Form:**  
  
*   `x = f(t)`  
*   `y = g(t)`  
  
Where `t` belongs to some interval `[a, b]`.  Each value of `t` yields a point `(x, y) = (f(t), g(t))` on the curve.  
  
**Advantages of Using Parametric Equations:**  
  
*   **Representing complex curves:**  Parametric equations can easily describe curves that are difficult or impossible to represent with a single Cartesian equation (e.g., curves that loop back on themselves).  
*   **Defining motion:** When `t` represents time, parametric equations naturally describe the path of a moving object.  
*   **Orientation:** Parametric equations inherently define a direction (orientation) along the curve, determined by increasing values of the parameter `t`. This is crucial for understanding the path traced.  
*   **Easier modeling:** In certain situations, it's easier to model the behavior of `x` and `y` separately as functions of a third variable.  
  
**Examples:**  
  
*   **Circle:**  
    *   `x = r * cos(t)`  
    *   `y = r * sin(t)`  
    *   `0 <= t <= 2π`  
    This describes a circle with radius `r` centered at the origin.  As `t` increases from 0 to 2π, the point `(x, y)` traces the circle in a counter-clockwise direction.  
  
*   **Line:**  
    *   `x = x0 + at`  
    *   `y = y0 + bt`  
    This describes a line passing through the point `(x0, y0)` with direction vector `<a, b>`.  
  
*   **Ellipse:**  
    *   `x = a * cos(t)`  
    *   `y = b * sin(t)`  
    *   `0 <= t <= 2π`  
    This describes an ellipse centered at the origin with semi-major axis `a` along the x-axis and semi-minor axis `b` along the y-axis.  
  
**Conversion to Cartesian Form (Sometimes Possible):**  
  
If possible, you can eliminate the parameter `t` to obtain a Cartesian equation relating `x` and `y`. However, this is not always straightforward or even possible. Even when it is possible, the Cartesian equation may not fully capture the information (e.g., orientation) provided by the parametric equations.  
  
**Differentiation:**  
  
*   **dy/dx:**  To find the slope of the tangent line to the parametric curve, use the chain rule:  
  
    `dy/dx = (dy/dt) / (dx/dt)`   provided `dx/dt != 0`  
  
*   **Second Derivative:**  To find the concavity, we differentiate `dy/dx` with respect to `x` again:  
  
    `d²y/dx² = d/dx (dy/dx) =  (d/dt (dy/dx)) / (dx/dt)`  
  
**Applications:**  
  
*   Computer graphics  
*   Animation  
*   Robotics  
*   Physics (projectile motion)  
*   Game development  
  
**Key Considerations:**  
  
*   The range of the parameter `t` is crucial for defining the portion of the curve being represented.  
*   Understanding the orientation of the curve is essential.  
*   Eliminating the parameter `t` (if possible) can help visualize the curve, but it may lose information.  
