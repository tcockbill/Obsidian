---
tags:
  - maths
date: 2025-05-21
---
---  
## Partial Fractions  
  
Partial fraction decomposition is a technique used in calculus and algebra to break down a rational function (a fraction where both the numerator and denominator are polynomials) into simpler fractions. This is particularly useful for integrating rational functions.  
  
**General Idea:**  
  
The basic principle is that any rational function P(x)/Q(x), where the degree of P(x) is less than the degree of Q(x), can be expressed as a sum of simpler fractions whose denominators are the factors of Q(x).  
  
**Steps for Partial Fraction Decomposition:**  
  
1.  **Check if the degree of the numerator is less than the degree of the denominator.** If not, perform polynomial long division first.  
  
2.  **Factor the denominator Q(x) completely.** The factors can be linear (ax + b) or quadratic (ax² + bx + c), and may be repeated.  
  
3.  **Set up the partial fraction decomposition based on the factors:**  
  
    *   **For each linear factor (ax + b) appearing once:**  Include a term of the form  A / (ax + b).  
    *   **For each linear factor (ax + b) appearing `n` times:** Include terms of the form:  
  
        A₁ / (ax + b)  +  A₂ / (ax + b)²  + ... + Aₙ / (ax + b)ⁿ  
  
    *   **For each irreducible quadratic factor (ax² + bx + c) appearing once:** Include a term of the form (Bx + C) / (ax² + bx + c).  
  
    *   **For each irreducible quadratic factor (ax² + bx + c) appearing `n` times:** Include terms of the form:  
  
        (B₁x + C₁) / (ax² + bx + c) + (B₂x + C₂) / (ax² + bx + c)² + ... + (Bₙx + Cₙ) / (ax² + bx + c)ⁿ  
  
4.  **Multiply both sides of the equation by the original denominator Q(x).** This clears all the fractions.  
  
5.  **Solve for the unknown constants (A, B, C, etc.).**  There are two common methods:  
  
    *   **Substitution:** Choose values of x that will make some of the factors zero, which simplifies the equation and allows you to solve for the constants directly.  
    *   **Equating Coefficients:**  Expand the right side of the equation and collect like terms.  Then, equate the coefficients of the corresponding terms on both sides of the equation. This gives you a system of linear equations that you can solve for the constants.  
  
6.  **Substitute the values of the constants back into the partial fraction decomposition.**  
  
**Example:**  
  
Decompose:  (5x - 3) / (x² - 2x - 3)  
  
1.  The degree of the numerator (1) is less than the degree of the denominator (2).  
2.  Factor the denominator: x² - 2x - 3 = (x - 3)(x + 1)  
3.  Set up the decomposition: (5x - 3) / (x² - 2x - 3) = A / (x - 3) + B / (x + 1)  
4.  Multiply by (x - 3)(x + 1):  5x - 3 = A(x + 1) + B(x - 3)  
5.  Solve for A and B:  
  
    *   **Substitution:**  
        *   Let x = 3:  15 - 3 = A(3 + 1) + B(0)  =>  12 = 4A  => A = 3  
        *   Let x = -1: -5 - 3 = A(0) + B(-1 - 3) => -8 = -4B => B = 2  
  
6.  Final decomposition: (5x - 3) / (x² - 2x - 3) = 3 / (x - 3) + 2 / (x + 1)  
  
**Applications:**  
  
*   **Integration:** Partial fraction decomposition makes integrating rational functions much easier.  
*   **Laplace Transforms:** Used in solving differential equations.  
*   **Circuit Analysis:** Used in analyzing electrical circuits.  
*   **Control Systems:** Used in designing control systems.  
  
**Important Notes:**  
  
*   Always check that the degree of the numerator is less than the degree of the denominator *before* attempting partial fraction decomposition.  
*   Irreducible quadratic factors are quadratic factors that cannot be factored further using real numbers.  
*   The system of linear equations you get when equating coefficients can be solved using techniques from linear algebra, such as Gaussian elimination or matrix inversion.  
*   The accuracy of the decomposition can be checked by adding the partial fractions back together and verifying that you obtain the original rational function.  
  
# Thursday, 22nd May 2025  
Express $\frac{5x+2}{(x+4)(x-5)}$ in the form $\frac{A}{(x+4)} + \frac{B}{(x-5)}$ where $A$ and $B$ are integers  
  
Matching cofficients  
$\frac{5x+2}{(x+4)(x-5)} \equiv \frac{A}{(x+4)} + \frac{B}{(x-5)}$  
$5x+2 \equiv A(x-5) + B(x+4)$  
$5x+2 \equiv Ax-5A+Bx+4B$  
$A+B=5$  
$4B-5A = 2$  
$A=2, B=5$  
$\frac{5x+2}{(x+4)(x-5)} \equiv \frac{2}{(x+4)} + \frac{5}{(x-5)}$  
  
  
# Fluency and skills  
$$\frac{18x+26}{(3x+2)(x-4)} \equiv \frac{A}{3x+2} + \frac{B}{x-4}$$  
$$Ax-4A+3Bx+2B \equiv 18x+26$$  
$$A+3B=18$$  
$$-4A+2B=26$$  
$$A=-3, B=7$$  
$$\frac{18x+26}{(3x+2)(x-4)} \equiv \frac{-3}{3x+2} + \frac{7}{x-4}$$  
  
$$\frac{3}{t-3} + \frac{2}{t-7} = \frac{2t-6 + (3t-21)}{(t-3)(t-7)} = \frac{5t-27}{(t-3)(t-7)}$$  
  
$$\frac{3}{(2x+1)(x+2)}$$  
$$2Ax+A + Bx+2B \equiv 3$$  
$$2A=-B$$  
$$A+2B=3$$  
$$A=3+4A$$  
$$-3A=3$$  
$$A=-1, B=2$$  
$$\frac{-1}{x+2}+\frac{2}{2x+1}$$  
  
---  
$$\frac{5x+3}{(2x-3)(x+2)} = \frac{A}{2x-3} + \frac{B}{x+2}$$  
$$A(x+2)+B(2x-3)=5x+3$$  
$$Ax+2A+2Bx-3B=5x+3$$  
$$Ax+2Bx=5x$$  
$$A+2B=5x$$  
$$2A-3B=3$$  
Solve the simultaneous equations  
$$7B=7$$  
$$B=1$$  
$$A+2=5$$  
$$A=3$$  
$$\frac{5x+3}{(2x-3)(x+2)} = \frac{3}{2x-3} + \frac{1}{x+2}$$  
Check by expanding  
$$3(x+2)+1(2x-3) = 3x+6+2x-3 = 5x+3$$  
  
  
