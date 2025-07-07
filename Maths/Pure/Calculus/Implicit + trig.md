---
tags:
  - maths
date: 2025-05-23
---
---  
# Notes  
$y= \arcsin$  
$y= \sin ^{-1} x$  
$\sin y=x$  
$\cos y \frac{dy}{dx} = 1$  
$\frac{dy}{dx} = \frac{1}{\cos y}$  
$\sin^2 y + \cos^2 y =1$  
$x^2+\cos^2y=1$  
$\cos^2y = 1-x^2$  
$\therefore \frac{dy}{dx} = \frac{1}{\sqrt{1-x^2}}$  
  
  
$$y=(\sin x)^n \Rightarrow \frac{dy}{dx} = n(\sin x)^{n-1} \times \cos x$$  
## [[./Implicit Differentiation|Implicit Differentiation]] & Trigonometric Functions  
  
**Key Idea:** [[./Implicit Differentiation|Implicit differentiation]] is used when you can't easily (or at all) solve for *y* explicitly as a function of *x*.  We differentiate both sides of the equation with respect to *x*, treating *y* as a function of *x*, and applying the chain rule where necessary.  
  
**Chain Rule Reminder:** When differentiating a function of *y* with respect to *x*, we must multiply by dy/dx (or y').  
  
**Example 1: [[./Implicit Differentiation|Implicit Differentiation]] with Trigonometry**  
  
Let's consider the equation:  `sin(x) + cos(y) = 1`  
  
1. **Differentiate both sides with respect to x:**  
  
   `d/dx [sin(x) + cos(y)] = d/dx [1]`  
  
2. **Apply the derivative rules:**  
  
   `cos(x) - sin(y) * dy/dx = 0`  (Notice the application of the chain rule on cos(y))  
  
3. **Solve for dy/dx:**  
  
   `-sin(y) * dy/dx = -cos(x)`  
  
   `dy/dx = cos(x) / sin(y)`  
  
   `dy/dx = cot(y)`  (Technically not a complete simplification, but demonstrates relationship)  
  
**Example 2: More Complex [[./Implicit Differentiation|Implicit Differentiation]]**  
  
Let's try: `tan(x) + sec(y) = x*y`  
  
1. **Differentiate both sides with respect to x:**  
  
   `d/dx [tan(x) + sec(y)] = d/dx [x*y]`  
  
2. **Apply derivative and product rules:**  
  
   `sec^2(x) + sec(y)tan(y) * dy/dx = (1*y) + (x * dy/dx)`  
  
3. **Isolate terms with dy/dx:**  
  
   `sec(y)tan(y) * dy/dx - x * dy/dx = y - sec^2(x)`  
  
4. **Factor out dy/dx:**  
  
   `dy/dx [sec(y)tan(y) - x] = y - sec^2(x)`  
  
5. **Solve for dy/dx:**  
  
   `dy/dx = (y - sec^2(x)) / (sec(y)tan(y) - x)`  
  
**Important Considerations:**  
  
*   **Chain Rule is Crucial:** Remember to apply the chain rule whenever you are differentiating a term involving *y* with respect to *x*.  
*   **Product Rule & [[./Quotient Rule|Quotient Rule]]:** Don't forget these rules when differentiating terms that involve products or quotients containing *x* and *y*.  
*   **Simplification:**  While solving for dy/dx is the primary goal, simplifying the result as much as possible is often desirable.  Look for trigonometric identities that can help.  
*   **Notation:** `dy/dx` is often written as `y'` or `f'(x)`. Choose the notation that makes sense for the context.  
*   **Second Derivatives:** You can find the second derivative `d^2y/dx^2` by differentiating `dy/dx` *implicitly* again with respect to x.  This will involve differentiating `dy/dx` itself, requiring the product/[[./Quotient Rule|quotient rule]] depending on its form.  
  
**Common Trigonometric Derivatives to Remember:**  
  
*   d/dx [sin(x)] = cos(x)  
*   d/dx [cos(x)] = -sin(x)  
*   d/dx [tan(x)] = sec^2(x)  
*   d/dx [sec(x)] = sec(x)tan(x)  
*   d/dx [csc(x)] = -csc(x)cot(x)  
*   d/dx [cot(x)] = -csc^2(x)  
  
**Practice Problems:**  
  
Try finding dy/dx for the following:  
  
1.  `x*sin(y) + y*cos(x) = 1`  
2.  `sin(x*y) = x^2 - y`  
3.  `csc(x) + cot(y) = x/y`  
  
>[!formula] Differentiation of ln  
>$$y= \ln f(x)$$  
>$$\frac{dy}{dx} = \frac{f ^{\prime} (x)}{f(x)}$$  
  
Find the turning points of the line $\sin x + \cos x$ for range $0 \le x \le 2\pi$  
$\frac{dy}{dx} = \cos x - \sin x = 0$  
$\cos x = \sin x$  
$\tan x = 1$  
$x=\frac{\pi}{4} , \frac{5 \pi}{4}$  
when $x = \frac{\pi}{4}$, $\sin x + \cos x = \sqrt 2$  
when $x=\frac{5 \pi}{4}$, $\sin x + \cos x = -\sqrt 2$  
turning points = $(\frac{\pi}{4}, \sqrt{2})$ and $(\frac{5 \pi}{4}, -\sqrt{2})$  
  
# Exponentials  
$$y=e^x \text{ is THE exponential function}$$  
$$y=a^x \text{ is AN exponential function}$$  
## Differentiate an exponential  
$y=a^x \qquad a \neq e$  
$\ln y = \ln a^x$  
$\ln y = x \ln a$  
$\frac{1}{y} \frac{dy}{dx} = \ln a$  
$\frac{dy}{dx} = y \ln a$  
$= a^x \times \ln a$  
