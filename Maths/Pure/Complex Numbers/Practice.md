---
tags:
  - Undone
  - Maths
  - ComplexNumbers
date: 2025-01-16
---
---  
# Practice for [[./Modulus|modulus arguments]]  
$z_1=1+i$  
$z_2=-1-i$  
$|z_1|=\sqrt{2}$  
$|z_2|=\sqrt{2}$  
$arg(z_1)=\frac{\pi}{4}$  
$arg(z_2)=\frac{3\pi}{4}$  
  
  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
\draw[line width=0.5mm] (-5,0) -- (5,0) node [label=right:{$\Re$}] {};  
\draw[line width=0.5mm] (0,-5) -- (0,5) node [label=above:{$\Im$}] {};  
\node at (1,1) {\large $x_1$};  
\draw (1,1) circle (2);  
\node at (-1,-1) {\large $x_2$};  
\draw (-1,-1) circle (2);  
\draw (-5,5) -- (5,-5);  
  
\end{tikzpicture}  
\end{document}  
```  
  
midpoint of line is $$ M = \left( \frac{1 + (-1)}{2}, \frac{1 + (-1)}{2} \right) = (0, 0) $$  
bisector is $$ (Z - Z_1) = (Z - Z_2) $$  
$$∣x+yi−(1+i)∣=∣x+yi−(−1−i)∣$$  
$$∣(x−1)+(y−1)i∣=∣(x+1)+(y+1)i∣$$  
which leads to $$x+y=0$$  
  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
\draw[line width=0.5mm] (-8,0)--(8,0) node [label=right:{$\Re$}]{};  
\draw[line width=0.5mm] (0,-8)--(0,8) node [label=above:{$\Im$}]{};  
\draw[color=blue] (0,0) circle (3) node [label=center:{$p_i$}] {};  
\draw[color=red] (2,0) circle (5) node [label=center:{$p_ii$}] {};  
\draw[color=green] (1,2) circle (3) node [label=center:{$p_iii$}] {};  
\draw[color=red!50!blue] (1,8) -- (1,-8) node at (1.5,1) {$p_iv$} {};  
  
\end{tikzpicture}  
\end{document}  
```  
$|z+1|=|z-3|$  
$|x+iy+1|=|x+iy-3|$  
$|(x+1)+(y)i|=|(x-3)+(y)i|$  
[[../../../To do/Perpendicular bisector|perpendicular bisector]] of (1,0) and (-3,0) is x=1  
$(x+1)^2+y^2=(x-3)^2+y^2$  
$x^2+2x+1+y^2=x^2-6x+9+y^2$  
$2x+1=-6x+9$  
$8x=8$  
$x=1$  
