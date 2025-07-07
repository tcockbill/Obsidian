---
date: 2025-06-01
tags: maths
---
  
The Quotient Rule allows you to find the derivative of a function that is expressed as a quotient of two other functions.  It states:  
  
If  `f(x) = u(x) / v(x)`,  where `u(x)` and `v(x)` are differentiable functions, then:  
  
`f'(x) = [v(x) * u'(x) - u(x) * v'(x)] / [v(x)]^2`  
  
**In simpler terms:**  
  
The derivative of the quotient is equal to (the denominator times the derivative of the numerator) minus (the numerator times the derivative of the denominator), all divided by (the denominator squared).  
  
**Mnemonic:**  
  
(Low dHigh minus High dLow) over Low Squared.  
  
*   `Low` refers to the denominator, `v(x)`.  
*   `High` refers to the numerator, `u(x)`.  
*   `dHigh` refers to the derivative of the numerator, `u'(x)`.  
*   `dLow` refers to the derivative of the denominator, `v'(x)`.  
  
**Important Considerations:**  
  
*   **Order Matters:** The subtraction in the numerator is crucial.  Switching the terms will result in the wrong answer.  
*   **Simplification:** Always try to simplify the derivative after applying the quotient rule.  This often involves factoring or combining like terms.  
*   **Domain:** Remember to consider the domain of the original function and the derivative.  The denominator, `v(x)`, cannot be zero.  
  
**Examples:**  
  
Let's say `f(x) = (x^2) / (sin(x))`.  
  
*   `u(x) = x^2`  
*   `u'(x) = 2x`  
*   `v(x) = sin(x)`  
*   `v'(x) = cos(x)`  
  
Applying the quotient rule:  
  
`f'(x) = [sin(x) * 2x - x^2 * cos(x)] / [sin(x)]^2`  
  
`f'(x) = (2x*sin(x) - x^2*cos(x)) / sin^2(x)`  
  
**When to use:**  
  
The Quotient Rule should be used when you have a function divided by another function, and those functions are both differentiable.  If you can rewrite the expression to avoid a quotient (e.g., by multiplying by a reciprocal with a negative exponent), that may be a simpler approach.  
  
The quotient rule for the differentiation of $\frac{f(x)}{g(x)}$:  
$$\huge \frac{dy}{dx} = \frac{f^{\prime}(x)g(x)-f(x)g^{\prime}(x)}{(g(x))^2}$$  
  
