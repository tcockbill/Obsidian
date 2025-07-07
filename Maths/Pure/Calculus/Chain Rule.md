---
tags:
  - Maths
  - Calculus
---
---  
  
# What is the Chain Rule?   
  
The Chain Rule is one of the fundamental rules of [[./Differentiable Calculus|differentiation]], it allows for mathematicians to calculate the derivative of composite functions, take for example $\sin{(x^{2})}$. The rule states as follows:   
$$  
\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx}  
$$  
  
One such popular usage of the rule includes [[./Implicit Differentiation|Implicit Differentiation]], where it is possible to differentiate $y$ with respect to $x$.  
  
# How does it work?   
First let us define our example function, $f(x) = \sin{x^{2}}$. As can  be seen, $x^{2}$ is a composite part of the function, being situated inside the sin function. We define this inner function as being $u$. Following this definition, we then integrate $u$ with respect to x; in this case leaving us with $2x$.   
We may then differentiate $\sin u$ with respect to $u$, this gives us $-\cos u$. We then multiply these two numbers, and resubstitute $u$ with $x^{2}$. Finally we get, $f'(x) = -2x \cos{(x^{2})}$ as our derivative for the function.   
  
  
  
  
## The Chain Rule  
  
The Chain Rule is a fundamental concept in calculus that allows us to find the derivative of composite functions. A composite function is a function that is nested inside another function, like `f(g(x))`.  
  
**Statement:**  
  
If we have a composite function `y = f(g(x))`, then the derivative of `y` with respect to `x` is given by:  
  
$dy/dx = dy/du * du/dx$  
  
Where:  
  
*   `y = f(u)`  (outer function)  
*   `u = g(x)`  (inner function)  
  
**In words:** The derivative of the outer function evaluated at the inner function, multiplied by the derivative of the inner function.  
  
**Example:**  
  
Let's find the derivative of `y = sin(x^2)`  
  
1.  **Identify the inner and outer functions:**  
    *   `u = g(x) = x^2` (inner function)  
    *   `y = f(u) = sin(u)` (outer function)  
  
2.  **Find the derivatives:**  
    *   `du/dx = d(x^2)/dx = 2x`  
    *   `dy/du = d(sin(u))/du = cos(u)`  
  
3.  **Apply the Chain Rule:**  
      
    dy/dx = dy/du * du/dx = cos(u) * 2x  
  
4.  **Substitute back for `u`:**  
     
    dy/dx = cos(x^2) * 2x = 2x * cos(x^2)  
  
  
Therefore, the derivative of `sin(x^2)` is `2x * cos(x^2)`.  
  
**Generalization:**  
  
The Chain Rule can be extended to more complex compositions of functions. For example, if `y = f(g(h(x)))`, then:  
  
  
$dy/dx = dy/dv * dv/du * du/dx$  
  
  
Where:  
  
* `v = g(h(x))`  
* `u = h(x)`  
  
**Importance:**  
  
The Chain Rule is crucial for:  
  
*   Differentiating complex functions.  
*   Related rates problems.  
*   [[./Implicit Differentiation|Implicit differentiation]].  
*   Many applications in physics, engineering, and economics.  
  
**Common Mistakes:**  
  
*   Forgetting to multiply by the derivative of the *inner* function.  
*   Not correctly identifying the inner and outer functions.  
*   Applying the chain rule when it's not needed (e.g., just `sin(x)`).  
  
**Mnemonics/Tips:**  
  
*   "Derivative of the *outside* (leaving the inside alone) times the derivative of the *inside*."  
*   Work from the outside in.  
  
**Related Concepts:**  
  
*   [[./Product Rule|Product Rule]]  
*   [[./Quotient Rule|Quotient Rule]]  
*   [[./Implicit Differentiation|Implicit Differentiation]]  
*   Derivatives of Trigonometric Functions  
*   Derivatives of Exponential and Logarithmic Functions  
  
# Using chain rule to differentiate trigonometric functions  
  
$$ \frac{dy}{dx} = \lim_{\delta x \rightarrow 0} \space \frac{\sin()}{}$$  
