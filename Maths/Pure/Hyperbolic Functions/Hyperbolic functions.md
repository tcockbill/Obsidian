---
tags:
  - Undone
  - Maths
  - Pure
date: 2025-01-24
---
---  
# Hyperbolic functions  
## Tuesday, February 25th 2025  
$$ \sinh (x) = \frac{e^x - e^{-x}}{2}$$  
$$ \cosh (x) = \frac{e^x - e^{-x}}{2}$$  
$$ \tanh(x) = \frac{\sinh (x)}{\cosh (x)} = \frac{e^x - e^{-x}}{e^x + e^{-x}}$$  
### $\text{The graph} \space y= \cosh x$  
The curve has a minimum point at (0,1)  
so $y \ge 1$  
The curve is symmetrical about the y-axis  
```desmos-graph  
top=10; bottom=-0.5;  
left=-3; right=3;  
---  
y=\cosh x  
```  
  
### $\text{The graph} \space y = \sinh x$  
The curve has rotational symmetry about the origin  
```desmos-graph  
top=10; bottom=-10;  
left=-3; right=3;  
---  
y = \sinh x  
```  
  
### $\text{The graph} \space y = \tanh x$  
As $x \rightarrow + \infty \Rightarrow e^{-x} \rightarrow 0 \Rightarrow \tanh x \rightarrow \pm 1$  
The curve has asymptotes at $y=1$ and $y=-1$  
so $-1 \lt y \lt 1$  
The curve has rotational symmetry about the origin   
```desmos-graph  
top=1.5; bottom=-1.5;  
left=-3; right=3;  
---  
y = \tanh x  
```  
  
## Questions  
Solve the equation $\tanh x = \frac{1}{2}$  
$\frac{e^x - e^{-x}}{e^x + e^{-x}} = \frac{1}{2}$  
$2(e^x - e^{-x}) = e^x + e^{-x}$  
$2e^x - 2e^{-x} = e^x + e^{-x}$  
$e^x=3e^{-x}$  
$e^{2x}=3$  
$2x = \ln 3$  
$x=\frac{1}{2} \ln 3$  
$x = \ln \sqrt{3}$  
  
$\sinh ^{-1} x = \ln(x+\sqrt{x^2+1})$  
$\cosh ^{-1} x = \ln(x + \sqrt{x^2-1}) : x\ge2$  
$\tanh ^{-1} = \frac{1}{2}(\frac{1+x}{1-x}) : -1 \lt x \lt 1$  
  
---  
# Graph  
```desmos-graph  
left=-10; right=10;  
top=10; bottom=-5;  
---  
y=(x+1)/(x-4)  
y=1|dashed|#42ddf5  
x=4|dashed|#42ddf5  
```  
  
## Hyperbolic Functions  
  
Hyperbolic functions are counterparts to trigonometric functions, but instead of being based on the unit circle, they are based on the hyperbola x² - y² = 1.  
  
**Definitions:**  
  
*   **Hyperbolic Sine (sinh x):**  (e<sup>x</sup> - e<sup>-x</sup>) / 2  
*   **Hyperbolic Cosine (cosh x):** (e<sup>x</sup> + e<sup>-x</sup>) / 2  
*   **Hyperbolic Tangent (tanh x):** sinh x / cosh x = (e<sup>x</sup> - e<sup>-x</sup>) / (e<sup>x</sup> + e<sup>-x</sup>)  
*   **Hyperbolic Cotangent (coth x):** cosh x / sinh x = (e<sup>x</sup> + e<sup>-x</sup>) / (e<sup>x</sup> - e<sup>-x</sup>)  (x ≠ 0)  
*   **Hyperbolic Secant (sech x):** 1 / cosh x = 2 / (e<sup>x</sup> + e<sup>-x</sup>)  
*   **Hyperbolic Cosecant (csch x):** 1 / sinh x = 2 / (e<sup>x</sup> - e<sup>-x</sup>)  (x ≠ 0)  
  
**Key Properties & Identities:**  
  
*   **cosh² x - sinh² x = 1**  (Analogous to cos² x + sin² x = 1)  
*   **sinh(-x) = -sinh(x)** (sinh is an odd function)  
*   **cosh(-x) = cosh(x)** (cosh is an even function)  
*   **tanh(-x) = -tanh(x)** (tanh is an odd function)  
*   **Derivatives:**  
    *   d/dx (sinh x) = cosh x  
    *   d/dx (cosh x) = sinh x  
    *   d/dx (tanh x) = sech² x  
*   **Integrals:**  
    *   ∫ sinh x dx = cosh x + C  
    *   ∫ cosh x dx = sinh x + C  
    *   ∫ sech² x dx = tanh x + C  
*   **Addition Formulas:**  
    *   sinh(x + y) = sinh x cosh y + cosh x sinh y  
    *   cosh(x + y) = cosh x cosh y + sinh x sinh y  
  
**Graphical Representation:**  
  
*   **cosh x:**  A U-shaped curve, symmetric about the y-axis.  cosh(0) = 1.  
*   **sinh x:**  An S-shaped curve, symmetric about the origin. sinh(0) = 0.  
*   **tanh x:** Approaches 1 as x approaches infinity and -1 as x approaches negative infinity.  
  
**Applications:**  
  
*   **Catenary Curve:** The shape of a hanging chain or cable is described by a hyperbolic cosine function (cosh x).  
*   **Physics:** Used in special relativity and other areas.  
*   **Engineering:**  Appear in calculations related to cable tensions, fluid dynamics, and heat transfer.  
*   **Mathematics:**  Appear in solutions to differential equations and other mathematical problems.  
  
**Inverse Hyperbolic Functions:**  
  
These are the inverse functions of the hyperbolic functions.  
  
*   **arcsinh x (sinh<sup>-1</sup> x):** ln(x + √(x² + 1))  
*   **arccosh x (cosh<sup>-1</sup> x):** ln(x + √(x² - 1))  (x ≥ 1)  
*   **arctanh x (tanh<sup>-1</sup> x):** (1/2) ln((1 + x) / (1 - x))  (|x| < 1)  
