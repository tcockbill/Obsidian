Let's explore the Product Rule, a fundamental concept in differential calculus.  
  
***  
  
**Statement:**  
  
The Product Rule states that the derivative of the product of two differentiable functions, *u(x)* and *v(x)*, is given by:  
  
d/dx [u(x)v(x)] = u'(x)v(x) + u(x)v'(x)  
  
Alternatively written as:  
  
(uv)' = u'v + uv'  
  
**In simpler terms:**  The derivative of a product is the derivative of the first function times the second function, plus the first function times the derivative of the second function.  
  
**Example 1:**  
  
Find the derivative of  *f(x) = x²sin(x)*  
  
*   Let  *u(x) = x²*   and   *v(x) = sin(x)*  
*   Then  *u'(x) = 2x*   and   *v'(x) = cos(x)*  
  
Applying the Product Rule:  
  
f'(x) = (2x)(sin(x)) + (x²)(cos(x))  
f'(x) = 2xsin(x) + x²cos(x)  
  
**Example 2:**  
  
Find the derivative of  *y = (3x + 2)(x² - 5x)*  
  
*   Let  *u = 3x + 2*  and  *v = x² - 5x*  
*   Then  *u' = 3* and  *v' = 2x - 5*  
  
Applying the Product Rule:  
  
y' = (3)(x² - 5x) + (3x + 2)(2x - 5)  
y' = 3x² - 15x + 6x² - 15x + 4x - 10  
y' = 9x² - 26x - 10  
  
**Why does it work? (Intuitive Explanation)**  
  
Imagine the area of a rectangle with sides *u(x)* and *v(x)*.  The product *u(x)v(x)* represents that area.  When *x* changes by a small amount, both *u* and *v* change.  The change in the area (the derivative) comes from two sources:  
  
1.  The change in *u* multiplied by the old *v* (*u'v*).  
2.  The change in *v* multiplied by the old *u* (*uv'*)  
  
The Product Rule accurately captures the rate of change of the product.  A rigorous proof involves using the limit definition of the derivative.  
  
**Applications:**  
  
*   This rule is indispensable when differentiating functions that are constructed as a product of simpler functions.  
*   It's used in various fields, including physics (e.g., finding the derivative of work done, which is force times displacement), engineering, and economics.  
  
**Important Notes:**  
  
*   Be careful to identify the two functions correctly.  
*   Remember to apply the chain rule if *u(x)* or *v(x)* are themselves composite functions.  
*   This rule only applies to products; there's a different rule for quotients (the [[./Quotient Rule|Quotient Rule]]).  
