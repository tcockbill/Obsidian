---
tags:
  - maths
date: 2025-05-19
---
---  
# Dimentional analysis  
## Dimensional Analysis  
  
Dimensional analysis, also known as unit analysis, is a powerful technique used to check the relationships between physical quantities by identifying their dimensions.  It's a fundamental tool in physics, engineering, and other scientific disciplines.  
  
**Core Principles:**  
  
*   **Dimensions vs. Units:** Dimensions are fundamental concepts like length (L), mass (M), time (T), electric charge (Q), and temperature (Θ).  Units are specific standards for measuring these dimensions, such as meters (m) for length or kilograms (kg) for mass.  
*   **Dimensional Homogeneity:**  An equation is dimensionally homogeneous if each term in the equation has the same dimensions.  This is a *necessary* condition for the equation to be correct.  If an equation is not dimensionally homogeneous, it is guaranteed to be incorrect.  
*   **Addition and Subtraction:**  You can only add or subtract quantities that have the same dimensions. Adding length to mass, for example, is meaningless.  
*   **Multiplication and Division:** You *can* multiply and divide quantities with different dimensions.  The resulting quantity will have dimensions that are the product or quotient of the original dimensions.  
  
**Notation:**  
  
*   Dimensions are often represented by symbols enclosed in square brackets: `[L]`, `[M]`, `[T]`.  
*   For example:  
    *   Speed = Distance / Time  =>  `[Speed] = [L] / [T] = LT⁻¹`  
    *   Area = Length × Width => `[Area] = [L] × [L] = L²`  
    *   Force = Mass × Acceleration => `[Force] = [M] × (LT⁻²) = MLT⁻²`  
  
**Applications:**  
  
*   **Checking Equations:**  Verifying the dimensional correctness of equations to catch errors.  
*   **Deriving Equations:**  Guiding the derivation of equations by ensuring dimensional consistency.  
*   **Unit Conversions:** Converting between different units within the same dimension.  
*   **Scale Modeling:**  Designing and interpreting scale models of physical systems.  
*   **Problem Solving:**  Provides a sanity check during problem solving.  
  
**Steps for Dimensional Analysis:**  
  
1.  **Identify the relevant variables:** List all the physical quantities that you believe are important for the problem.  
2.  **Write the dimensions of each variable:** Express each variable in terms of its fundamental dimensions (M, L, T, etc.).  
3.  **Postulate a relationship:**  Assume a general form for the relationship between the variables, using exponents to represent unknown powers. For example: `A = k * Bˣ * Cʸ`, where A, B, and C are variables, x and y are unknown exponents, and k is a dimensionless constant.  
4.  **Equate the dimensions:** Substitute the dimensions of each variable into the postulated relationship.  
5.  **Solve for the exponents:** Solve the resulting system of equations for the unknown exponents.  
6.  **Write the final equation:**  Substitute the values of the exponents back into the postulated relationship.  
  
**Example:**  
  
Let's say we want to find the period (T) of a simple pendulum.  We suspect that it depends on the length (l) of the pendulum and the acceleration due to [[../../To do/Gravity|gravity]] (g).  
  
1.  **Variables:** Period (T), Length (l), [[../../To do/Gravity|Gravity]] (g)  
2.  **Dimensions:** `[T] = T`, `[l] = L`, `[g] = LT⁻²`  
3.  **Postulate:** `T = k * lˣ * gʸ` (where k is a dimensionless constant)  
4.  **Equate Dimensions:** `T = Lˣ (LT⁻²)ʸ`  => `T¹ = L^(x+y) * T^(-2y)`  
5.  **Solve for Exponents:**  
    *   `x + y = 0`  (equating exponents of L)  
    *   `-2y = 1` (equating exponents of T)  
    *   Solving, we get `y = -1/2` and `x = 1/2`  
6.  **Final Equation:** `T = k * l^(1/2) * g^(-1/2)  => T = k * √(l/g)`  
  
Dimensional analysis gives us the correct *form* of the equation, but it doesn't tell us the value of the dimensionless constant *k*. In this case, *k* is 2π, which requires a more detailed analysis using physics principles.  
  
**Limitations:**  
  
*   Cannot determine dimensionless constants.  
*   Cannot detect errors in trigonometric functions, exponents, or logarithms.  
*   Cannot determine if an equation is numerically correct, only dimensionally correct.  
*   Relies on knowing the relevant variables.  Omitting an important variable will lead to an incorrect result.  
  
**Benefits:**  
  
*   Simple and powerful technique for error detection.  
*   Useful for deriving relationships between physical quantities.  
*   Provides insights into the structure of physical laws.  
*   Helps in understanding the fundamental nature of physical quantities.  
  
## Questions  
$$[T]=[LT^{-2}]^{\frac{1}{2}}[L]^{-\frac{1}{2}}$$  
$$=L^{\frac{1}{2}}T^{-1}L^{-\frac{1}{2}}$$  
$$T^1 \neq T^{-1}$$  
