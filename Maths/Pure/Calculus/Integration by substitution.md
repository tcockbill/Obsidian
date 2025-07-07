---
tags: []
date: 2025-06-19
---
---  
## Integration by Substitution  
  
**Concept:**  
  
Integration by substitution, also known as u-substitution, is a technique used to simplify integrals by replacing a function within the integrand with a new variable (often *u*) and its derivative. The goal is to transform the integral into a more manageable form that can be easily solved using standard integration rules.  
  
**The Process:**  
  
1.  **Identify a suitable *u*:** Look for a function and its derivative within the integrand.  Ideally, *u* should be an "inner" function, such as the argument of a composite function (e.g., inside a square root, raised to a power, or as part of a trigonometric function's argument).  
  
2.  **Calculate *du*:** Find the derivative of *u* with respect to *x* and express it in differential form (i.e., *du* = *u'*(x) *dx*).  
  
3.  **Rewrite the integral in terms of *u* and *du*:** Replace the identified function with *u* and replace the corresponding portion of *dx* with *du*.  The entire original integral should now be expressed solely in terms of *u* and *du*.  If this isn't possible, your initial choice of *u* may be incorrect.  
  
4.  **Evaluate the *u*-integral:** Solve the new integral with respect to *u*.  This should be a simpler integral than the original.  
  
5.  **Substitute back for *x*:** Replace *u* with its original expression in terms of *x*.  This gives you the integral in terms of the original variable.  
  
6.  **Add the constant of integration, *C*:** Remember that the antiderivative is defined up to an arbitrary constant.  
  
>[!formula]  
>$$\int f(g(x)) \times g^\prime (x) dx = \int f(u) du, \text{ where } u =g(x) \text{ and } du = g^\prime(x) dx$$  
  
**Examples:**  
  
*   **Example 1:**  ∫ *2x* cos(*x*<sup>2</sup>) *dx*  
  
    *   Let *u* = *x*<sup>2</sup>  
    *   Then *du* = 2*x* *dx*  
    *   The integral becomes: ∫ cos(*u*) *du*  
    *   Solve: sin(*u*) + *C*  
    *   Substitute back: sin(*x*<sup>2</sup>) + *C*  
  
*   **Example 2:** ∫ (3*x*<sup>2</sup> + 1) / (*x*<sup>3</sup> + *x* + 1) *dx*  
  
    *   Let *u* = *x*<sup>3</sup> + *x* + 1  
    *   Then *du* = (3*x*<sup>2</sup> + 1) *dx*  
    *   The integral becomes: ∫ 1/*u* *du*  
    *   Solve: ln|*u*| + *C*  
    *   Substitute back: ln|*x*<sup>3</sup> + *x* + 1| + *C*  
  
**Common Choices for *u*:**  
  
*   Expressions under radicals (square roots, cube roots, etc.)  
*   Denominators of fractions  
*   Arguments of trigonometric functions  
*   Exponents of exponential functions  
*   "Inner" functions in composite functions  
  
**Tips & Tricks:**  
  
*   If you can't find a direct *du* in the integral, sometimes you can manipulate the equation *du* = *u'*(x) *dx* to solve for *dx* and substitute that into the integral.  
*   Practice! The more examples you work through, the better you'll become at recognizing suitable choices for *u*.  
*   Don't be afraid to try different substitutions. If one doesn't work, try another.  
*   Always check your answer by differentiating the result. It should match the original integrand.  
  
**Definite Integrals:**  
  
When evaluating definite integrals using u-substitution, you have two options:  
  
1.  **Change the limits of integration:** Convert the original limits of integration (in terms of *x*) to the corresponding limits in terms of *u* using the equation *u* = *g(x)*. Then, evaluate the integral with respect to *u* using the new limits.  This avoids the need to substitute back for *x*.  
  
2.  **Evaluate the indefinite integral and substitute back:** Evaluate the indefinite integral as described above, then substitute back *x* into the result and evaluate using the original limits of integration.  
  
**Example with Definite Integrals:**  
  
∫<sub>0</sub><sup>2</sup> *x* *e*<sup>-*x*<sup>2</sup></sup> *dx*  
  
*   Let *u* = -*x*<sup>2</sup>  
*   Then *du* = -2*x* *dx*  => -1/2 *du* = *x* *dx*  
  
*   **Changing Limits:**  
    *   When *x* = 0, *u* = -0<sup>2</sup> = 0  
    *   When *x* = 2, *u* = -2<sup>2</sup> = -4  
    *   The integral becomes: ∫<sub>0</sub><sup>-4</sup> -1/2 *e*<sup>*u*</sup> *du* = -1/2 [*e*<sup>*u*</sup>]<sub>0</sub><sup>-4</sup> = -1/2(*e*<sup>-4</sup> - *e*<sup>0</sup>) = -1/2(*e*<sup>-4</sup> - 1) = (1 - *e*<sup>-4</sup>)/2  
  
*   **Substituting back (verifying):**  
    * Indefinite integral:  ∫ *x* *e*<sup>-*x*<sup>2</sup></sup> *dx* = -1/2 *e*<sup>-*x*<sup>2</sup></sup> + C  
    * Evaluating with original limits: [-1/2 *e*<sup>-*x*<sup>2</sup></sup>]<sub>0</sub><sup>2</sup> = -1/2 *e*<sup>-4</sup> - (-1/2 *e*<sup>0</sup>) = (1 - *e*<sup>-4</sup>)/2  
  
**Related Topics:**  
  
*   [[./Integration by parts|Integration by Parts]]  
*   Trigonometric Substitution  
*   Partial Fraction Decomposition  
  
$$\int \frac{dy}{dx} \times \frac{dx}{du} \space du$$  
$$\int ^2 _0 x^2 \sqrt{x^3+1} \space dx$$  
$$\int ^2 _0 x^2(x^3+1)^\frac{1}{2} dx$$  
![[../../../Extra Files/Pasted image 20250703091122.png|600]]  
  
$$\int^1_0 \frac{x^9}{(x^5+2)^3} = \frac{1}{180}$$  
$$u = x^5+2 \qquad \frac{du}{dx} = 5x^4 \qquad \frac{dx}{du} = \frac{1}{5x^4}$$  
$$\int^3_2 \frac{x^9}{5x^4u^3} = \frac{1}{5}\int^3_2 \frac{x^5}{u^3}$$  
$$x^5 = u-2$$  
$$\frac{1}{5}\int ^3_2 \frac{u-2}{u^3} = \frac{1}{5}\int^3_2 \frac{u}{u^3} - \frac{2}{u^3} = \frac{1}{5}\int^3_2 u^{-2} - 2u^{-3}$$  
$$\frac{1}{5}\left[-u^{-1} + \frac{1}{2} u^{-2}\right]^3_2$$  
$$\frac{1}{5}\left[-(x^5+2)^{-1} + \frac{1}{2}(x^5+2)^{-2}\right]^1_0$$  
  
  
