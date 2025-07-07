---
tags:
  - Maths
  - ComplexNumbers
date: 2024-12-09
---
---  
# Graphing  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
\draw[line width=2mm, latex-latex] (0,-4) -- (0,4) node [label=above:{$\Im$}] {};  
\draw[line width=2mm] [latex-latex] (-4,0) -- (4,0) node [label=right:{$\Re$}] {};  
\draw (2,-1) node {\huge x};  
\draw (0,0) node {\huge x};  
\draw (3,1) node {\huge x};  
\draw[red, line width=1mm, ->] [->] (0,0) -- (2,-1) -- (0,0) -- (1,-0.5);  
\draw[red, line width=1mm, ->] [->] (0,0) -- (3,1) -- (0,0) -- (1.5,0.5);  
\draw[red, line width=1mm, ->] (2,-1) -- (3,1) -- (2,-1) -- (2.5,0);  
  
\end{tikzpicture}  
\end{document}  
```  
   
  
|3+1**i**| = $\sqrt{10}$  
  
The argument of the complex number is the angle from the $\Re$ axis (direction)   
  
$Z_1 = x + iy$  
|$Z_1$|=$\sqrt{10}$  
  
The circumference of a circle = $2r\pi$   
360$\textdegree$ = $2\pi$ [[../../../To do/Radians|radians]]  
  
$-\pi < \theta \le \pi$   
principle argument is in this range  
[[./index|Complex Numbers]][[./Complex Plane|Complex Plane]]  
