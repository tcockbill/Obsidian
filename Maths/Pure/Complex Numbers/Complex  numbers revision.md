---
tags:
  - Maths
  - ComplexNumbers
date: 2025-01-17
---
---  
# Argument [[./Modulus and argument|Modulus and argument]]  
The formula for the argument of $z=a+bi$  is $$\theta=arg(z)=\tan^{-1}(\frac{a}{b})$$  
# Greater than or less than equations  
$|z-1|>|z-i|$  
The boundary of this set of points is the [[../../../To do/Perpendicular bisector|perpedicular bisector]] of the points 1 and i. The locus is the region closer to point i than the point 1, and does not include the [[../../../To do/Perpendicular bisector|perpendicular bisector]]  
  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
\draw[line width=0.5mm] (0,-2)--(0,2) node [label=above:{$\Im$}] {};  
\draw[line width=0.5mm] (-2,0)--(2,0) node [label=right:{$\Re$}] {};  
\node (dot1) at (1,0) {$\bullet$};  
\node (i) [above of=dot1, yshift=-20pt, xshift=5pt] {$i$};  
\node (dot2) at (0,1) {$\bullet$};  
\node (1) [right of=dot2, yshift=5pt, xshift=-20pt] {$1$};  
\draw (2,2)--(-2,-2);  
\draw [-latex] (0,0)--(-1,1);  
  
\end{tikzpicture}  
\end{document}  
```  
