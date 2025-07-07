---
tags: []
date: 2025-06-13
---
---  
  
### Integration by Parts  
  
Integration by parts is a technique used to integrate the product of two functions. It is based on the product rule for differentiation.  
  
**Formula:**  
  
∫ u dv = uv - ∫ v du  
  
Where:  
  
*   u is a function we choose to differentiate.  
*   dv is a function (including dx) we choose to integrate.  
*   du is the derivative of u.  
*   v is the integral of dv.  
  
**Choosing u and dv (The ILATE/LIATE Rule):**  
  
A helpful guideline for choosing u and dv is the acronym **ILATE** or **LIATE**:  
  
*   **I** - Inverse trigonometric functions (e.g., arcsin(x), arctan(x))  
*   **L** - Logarithmic functions (e.g., ln(x), log(x))  
*   **A** - Algebraic functions (e.g., x, x², x³, polynomials)  
*   **T** - Trigonometric functions (e.g., sin(x), cos(x), tan(x))  
*   **E** - Exponential functions (e.g., eˣ, 2ˣ)  
  
Choose *u* to be the function that comes *earlier* in the list.  This generally leads to a simpler integral for ∫ v du.  
  
**Steps:**  
  
1.  **Identify u and dv:** Carefully choose u and dv based on the integrand and the ILATE/LIATE rule.  
2.  **Calculate du and v:** Differentiate u to find du, and integrate dv to find v. Remember to *not* add a constant of integration (+C) when finding v.  
3.  **Apply the formula:** Substitute u, v, du, and dv into the integration by parts formula.  
4.  **Evaluate the new integral:** Evaluate the integral ∫ v du.  Sometimes, you may need to apply integration by parts again.  
5.  **Add the constant of integration:** Add "+C" to your final result.  
  
**Examples:**  
  
*   **∫ x cos(x) dx:**  
  
    *   u = x (Algebraic)  
    *   dv = cos(x) dx (Trigonometric)  
    *   du = dx  
    *   v = sin(x)  
  
    ∫ x cos(x) dx = x sin(x) - ∫ sin(x) dx = x sin(x) + cos(x) + C  
  
*   **∫ ln(x) dx:**  
  
    *   u = ln(x) (Logarithmic)  
    *   dv = dx  
    *   du = (1/x) dx  
    *   v = x  
  
    ∫ ln(x) dx = x ln(x) - ∫ x (1/x) dx = x ln(x) - ∫ 1 dx = x ln(x) - x + C  
  
*   **∫ eˣ sin(x) dx:** (Requires repeated integration by parts)  
  
    This example demonstrates a case where you apply integration by parts *twice* and then solve for the original integral algebraically.  (Often results in a situation where you can add the integral on both sides of the equation).  
  
**Tips and Considerations:**  
  
*   Sometimes, the choice of u and dv is not immediately obvious. Experiment with different choices to see which one leads to a simpler integral.  
*   In some cases, you may need to apply integration by parts multiple times to evaluate the integral.  
*   Remember to simplify the integral ∫ v du as much as possible before evaluating it.  
*   Be mindful of signs when applying the formula.  
*   Consider using tabular integration (also known as the "tic-tac-toe" method) for integrals that require repeated integration by parts, especially when one of the functions repeatedly differentiates to zero (e.g., x³, x⁴).  
  
$\int \sin kx \thinspace dx = -\frac{1}{k} \cos kx + c$  
$\int \cos kx \thinspace dx = \frac{1}{k} \sin kx + c$  
$\int \sec ^2 kx \thinspace dx = \frac{1}{k} \tan kx + c$  
$\int e^{kx} \thinspace dx = \frac{1}{k} e^{kx} + c$  
  
  
>[!formula] Integration by parts  
>To integrate by parts. consider the integral as being mad up of two parts, $u$ and $\frac{dv}{dx}$, and use $$\int u \frac{dv}{dx} dx = uv-\int v \frac{du}{dx}dx$$  
