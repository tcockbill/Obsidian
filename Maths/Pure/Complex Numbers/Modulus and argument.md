---
tags:
  - Maths
  - Mechanics
date: 2025-01-10
---
---  
# Notes [[./index|]]  
$\sqrt{-1}=i$   $\therefore i^2={-1}$  
$\sqrt{-x}=\sqrt{-1}\times\sqrt{x}$  
  
  
## Modulus and Argument of a Complex Number  
  
The modulus and argument are two important properties that describe a complex number in polar form. They provide an alternative way to represent complex numbers, which can be useful for certain operations and visualizations.  
  
**1. Modulus:**  
  
*   **Definition:** The modulus of a complex number *z = a + bi* (where *a* and *b* are real numbers and *i* is the imaginary unit) is the distance from the origin (0, 0) to the point (a, b) in the complex plane.  It's often denoted as |*z*| or *r*.  
  
*   **Formula:**  |*z*| = √(*a*² + *b*²)  
  
*   **Interpretation:**  The modulus represents the magnitude or absolute value of the complex number. It is always a non-negative real number.  
  
*   **Example:** For *z* = 3 + 4*i*,  |*z*| = √(3² + 4²) = √(9 + 16) = √25 = 5  
  
**2. Argument:**  
  
*   **Definition:** The argument of a complex number *z = a + bi* is the angle *θ* (theta) measured counterclockwise from the positive real axis to the line segment connecting the origin (0, 0) to the point (a, b) in the complex plane.  
  
*   **Calculation:**  *θ* = arctan(*b*/ *a*)  
  
*   **Important Considerations:**  
    *   The arctangent function (arctan or tan⁻¹) has a range of (-π/2, π/2). Therefore, adjustments might be needed to obtain the correct argument, depending on the quadrant in which the complex number lies.  
    *   The argument is not unique. Adding or subtracting multiples of 2π results in the same complex number. The *principal argument*, denoted Arg(*z*), is the argument that lies within the interval (-π, π] or [0, 2π), depending on the convention.  
  
*   **Quadrant Analysis:**  
    *   **Quadrant I (a > 0, b > 0):**  *θ* = arctan(*b*/ *a*)  
    *   **Quadrant II (a < 0, b > 0):**  *θ* = arctan(*b*/ *a*) + π  (or arctan(*b*/ *a*) + 180° if using degrees)  
    *   **Quadrant III (a < 0, b < 0):** *θ* = arctan(*b*/ *a*) - π  (or arctan(*b*/ *a*) - 180° if using degrees)  
    *   **Quadrant IV (a > 0, b < 0):**  *θ* = arctan(*b*/ *a*)  
  
*   **Special Cases:**  
    *   If *a* = 0 and *b* > 0, then *θ* = π/2.  
    *   If *a* = 0 and *b* < 0, then *θ* = -π/2.  
    *   If *a* > 0 and *b* = 0, then *θ* = 0.  
    *   If *a* < 0 and *b* = 0, then *θ* = π.  
  
*   **Example:** For *z* = -1 + *i*,  *a* = -1, *b* = 1.  
    *   arctan(*b*/ *a*) = arctan(1/-1) = arctan(-1) = -π/4.  
    *   Since *z* is in Quadrant II, *θ* = -π/4 + π = 3π/4.  Therefore, Arg(*z*) = 3π/4.  
  
**3. Polar Form:**  
  
Using the modulus (*r*) and argument (*θ*), a complex number *z = a + bi* can be expressed in polar form as:  
  
*   *z* = *r*(cos(*θ*) + *i*sin(*θ*))  
  
This can also be written using Euler's formula:  
  
*   *z* = *r*e^(i*θ*)  
  
**4. Applications:**  
  
*   **Multiplication and Division:** Polar form simplifies multiplication and division of complex numbers.  To multiply, multiply the moduli and add the arguments.  To divide, divide the moduli and subtract the arguments.  
*   **Roots of Complex Numbers:**  Finding roots of complex numbers is much easier in polar form.  
*   **Geometric Interpretations:**  The modulus and argument provide a visual representation of complex numbers on the complex plane, making it easier to understand their geometric properties.  
*   **Phasors in Electrical Engineering:** Polar form is used extensively to represent AC voltages and currents using phasors.  
  
**5. Summary:**  
  
The modulus and argument provide a powerful alternative representation of complex numbers that simplifies certain calculations and offers a valuable geometric perspective.  Understanding them is crucial for working effectively with complex numbers in various mathematical and engineering applications.  
