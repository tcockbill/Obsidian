---
tags:
  - Maths
  - Calculus
---
---  
  
# What is it?  
Implicit differentiation is an application of the [[./Chain Rule|Chain rule]], wherein it is possible   
to differentiate $y$ with respect to $x$.  
  
# Origins  
Implicit differentiation stems from the [[./Chain Rule|Chain Rule]], where $\frac{dy}{dx} = \frac{dy}{du}\frac{du}{dx}$. In this case, $u = y$ providing the fundamental systems for which this functions on.  
  
# Example   
  
Let $x^{2} + y^{2} = 8$.  
$$2x + 2y \cdot \frac{dy}{dx} = 0$$  
$$  
2y + \frac{dy}{dx} = -2x  
$$  
$$  
\frac{dy}{dx} = -\frac{2x}{y} = -\frac{x}{y}  
$$  
  
# Differentiation of exponentials  
$$\frac{d (e ^x)}{dx} = e ^x$$  
$$\frac{d(e ^{kx})}{dx} = ke ^{kx}$$  
# Differentiating product (the [[./Product Rule|product rule]])  
$$y=u(x)v(x)$$  
$$y=uv$$  
$$y+\delta y=(u+\delta u)(v+\delta v)$$  
$$y+\delta y = uv+(\delta u)v+(\delta v)u +(\delta u)(\delta v)$$  
$$y + \delta y = uv + \delta uv + u \delta v + \delta u \delta v$$  
$$y=uv$$	$$\delta y = \delta uv + u \delta v + \delta u \delta v$$  
$$\frac{dy}{dx} = u \frac{\delta v}{\delta x}+v \frac{\delta u }{\delta x}+ \frac{\delta u \delta v}{\delta x}$$  
  
$$\frac{dy}{dx}=u \frac{dv}{dx} + v \frac{du}{dx}$$  
$$\frac{d(uv)}{dx} = u\frac{dv}{dx} + v \frac{du}{dx}$$  
$$e^x \times \cos x + \sin x \times e^x$$  
$$e^x \cos x + e^x \sin x$$  
$$e^x(\sin x + \cos x)$$  
# [[./Quotient Rule|Quotient rule]]  
$$y = \frac{e^x}{\sin x}$$  
$$y=\frac{u}{v}=ev^{-1}$$  
$$e^x \times -\frac{1}{\sin^2x} \times \cos x + \arcsin x e^x$$  
$$e^x\left(\arcsin x-\frac{\cos x}{\sin ^2 x}\right)$$  
  
## Questions  
$$\sqrt{x} (5-3x)^4$$  
$$\frac{dv}{dx} = -12(5-3x)^3$$  
$$\frac{du}{dx} = \frac{1}{2}x^{\frac{1}{3}}$$  
$$\frac{dy}{dx} = -12x^{\frac{1}{2}}(5-3x)^3 + \frac{1}{2}x^{\frac{1}{3}}(5-3x)^4$$  
# differentiating tan x  
$$\tan x = \frac{\sin x}{\cos x}$$  
$$\frac{dy}{dx} = \frac{\cos x \cos x + \sin x \sin x}{\cos ^2 x} = \frac{\cos ^2 x + \sin ^2x}{\cos ^2x} = \frac{1}{\cos ^2x}= \sec ^2x$$  
  
## More questions  
Find the coordinates of the turning points of the curve $y=\frac{x^2}{x-1}$  
$$x^2 \times -\frac{1}{(x-1)^2} \times 1 + \frac{1}{x-1} \times 2x$$  
$$=\frac{2x}{x-1}-\frac{x^2}{(x-1)^2}$$  
$$=\frac{2x(x-1)-x^2}{(x-1)^2}$$  
  
  
![[../../../Extra Files/image.png|image]]  
  
1. $e^{x^2} =$  
$u=x^2$  
$y=e^u$  
$\frac{du}{dx} = 2x$  
$\frac{dy}{du} = e^u$  
$\frac{dy}{dx} = \frac{du}{dx} \times \frac{dy}{du} = 2x \times e^{x^2} = 2xe^{x^2}$  
  
## Implicit Differentiation  
  
**Concept:**  
  
Implicit differentiation is a technique used to find the derivative of a function defined implicitly. This means the function is not explicitly solved for one variable in terms of the other (e.g., y = f(x)). Instead, the equation relating the variables is given implicitly (e.g., x² + y² = 25).  
  
**Why use it?**  
  
*   Some equations are difficult or impossible to solve explicitly for *y*.  
*   Sometimes, we only need the derivative at a specific point, making solving for *y* unnecessary.  
  
**Procedure:**  
  
1.  **Differentiate both sides of the equation with respect to *x***.  Remember that *y* is a function of *x*, so apply the chain rule when differentiating terms involving *y*.  
    *   `d/dx [f(y)] = f'(y) * dy/dx` (where `dy/dx` is often written as *y'*)  
  
2.  **Collect all terms containing *dy/dx* on one side of the equation.**  
  
3.  **Factor out *dy/dx* from those terms.**  
  
4.  **Solve for *dy/dx* (which is *y'*) by dividing both sides by the factored expression.**  
  
**Example 1: x² + y² = 25 (Circle)**  
  
1.  `d/dx (x² + y²) = d/dx (25)`  
2.  `2x + 2y * dy/dx = 0`  (Applying the chain rule to `y²`)  
3.  `2y * dy/dx = -2x`  
4.  `dy/dx = -2x / 2y`  
5.  `dy/dx = -x/y`  
  
**Example 2:  xy + sin(y) = x²**  
  
1.  `d/dx (xy + sin(y)) = d/dx (x²)`  
2.  `(1*y + x*dy/dx) + cos(y) * dy/dx = 2x` (Using the product rule on `xy` and chain rule on `sin(y)`)  
3.  `x * dy/dx + cos(y) * dy/dx = 2x - y`  
4.  `dy/dx * (x + cos(y)) = 2x - y`  
5.  `dy/dx = (2x - y) / (x + cos(y))`  
  
**Tips & Common Mistakes:**  
  
*   **Chain Rule is Crucial:** Don't forget to apply the chain rule whenever you differentiate a term involving *y*.  
*   **Product Rule:**  Use the product rule when differentiating expressions like *xy*, *x²y*, etc.  
*   **[[./Quotient Rule|Quotient Rule]]:** While you *could* use the [[./Quotient Rule|quotient rule]], it's often easier to multiply through and use the product rule (or rewrite the expression with negative exponents).  
*   **Simplification:** After finding *dy/dx*, simplify the expression if possible.  
*   **Evaluating at a Point:** If you need the slope at a specific point (x, y), substitute those values into your derivative expression *after* you've found *dy/dx*. Don't substitute before differentiating.  
*   **Notation:**  Remember that *dy/dx* is the same as *y'*.  
  
**Higher Order Derivatives:**  
  
To find the second derivative (d²y/dx² or y''), differentiate *dy/dx* with respect to *x*, again using implicit differentiation and the chain rule. Be mindful that the first derivative *dy/dx* often involves *y*, so you'll need to use the chain rule and substitute the expression you found for *dy/dx* in the first step.  This can get messy quickly.  
  
**Related Concepts:**  
  
*   **Derivatives:** This topic builds upon the fundamental concepts of derivatives.  
*   **Chain Rule:** A prerequisite for understanding implicit differentiation.  
*   **Product Rule:**  Often necessary for applying implicit differentiation.  
*   **Related Rates:** The application of implicit differentiation is key to solving related rates problems.  
  
**Further Exploration:**  
  
*   Practice numerous examples with varying complexity.  
*   Consult your textbook or online resources for more detailed explanations and examples.  
