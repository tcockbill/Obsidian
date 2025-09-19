---
tags:
  - Maths
  - Calculus
---
---  
  
# What is a derivative?  
  
A derivative is defined as the rate of change of mathematical function, it could be [[../../../To do/Displacement|Displacement]], Velocity, or just plain $y$  units. Fundamentally, it relies on the principal that gradient, $m$ equals $\frac{\Delta y}{\Delta x}$.  
  
Lets start by defining our function, $f(x)$. And let $f'(x)$ be the gradient function of $f(x)$. Following this we can state that $\lim_{\Delta \to 0} \frac{\Delta y}{\Delta x} = f'(x)$. This forms the basis of First Principle differentiation, and many of the proofs for differentiation rules.   
  
Fundamentally, differentiation is the opposite to *[[./Indefinite Integration|indefinite integration]]*, or the anti-derivative. Additionally, both fall under the umbrella of [[./index|calculus]].  
  
# Rules for differentiation  
  
## [[./Power Rule|Power rule]]  
  
## [[./Log Rule|Log Rule]]  
  
## [[./Product Rule|Product Rule]]  
  
## [[./Quotient Rule|Quotient Rule]]  
  
## [[./Chain Rule|Chain rule]]  
  
# Extra Info  
  
See, [[./Implicit Differentiation|Implicit differentiation]] on how to differentiate equations such as,   
$$(x-2)^{2} + (y+1)^{2}= 64$$  
  
# Differential equations  
e.g. $$\frac{dy}{dx} = f(x) \longrightarrow y = \int f(x)dx$$  
What about $$\frac{dy}{dx} = xy$$?  
  
Split it up into $$\frac{1}{y}dy=x\space dx$$  
Then integrate both sides $$\int \frac{1}{y}dy = \int x \space dx$$  
$$\ln |y| +C_1 = \frac{x^2}{2}+C_2$$  
$$\ln |y| = \frac{x^2}{2} + k$$  
where$$k=C_1-C_2$$  
  
---  
$$y= e^{\frac{x^2}{2}+k}$$  
$$y=Ae^{\frac{x^2}{2}}$$  
where $$A=e^k$$  
  
  
