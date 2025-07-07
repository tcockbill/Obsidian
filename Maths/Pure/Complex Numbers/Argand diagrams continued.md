---
tags:
  - Maths
  - ComplexNumbers
date: 2025-01-13
---
---  
# Argand diagram [[./Complex Conjugate|]][[./index|]][[./Geometrical Approach to Complex Numbers|]]  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
\draw[line width=0.5mm] (0,8.9) -- (0,-8.9);  
\draw[line width=0.5mm] (8.9,0) -- (-8.9,0);  
\foreach \y in {-8,-7,...,8} {  
	\node at (-0.5,0+\y) {\y};  
	\draw[shift={(0,\y)}, color=black, line width=0.25mm] (4pt,0pt) -- (-4pt,0pt);  
}  
\foreach \x in {-8,-7,...,8} {  
	\node at (0+\x,-0.5) {\x};  
	\draw[shift={(\x,0)}, color=black, line width=0.25mm] (0pt,4pt) -- (0pt,-4pt);  
}  
\node at (1,1) {\large X};  
\node at (0,2) {\large X};  
\node at (-2,2) {\large X};  
\node at (4,-4) {\large X};  
\node at (0,-8) {\large X};  
\node at (8,-8) {\large X};  
\node at (-4,0) {\large X};  
  
\end{tikzpicture}  
\end{document}  
```  
  
  
Prove that $|z_1z_2|=|z_1||z_2|$ and $|\frac{z_1}{z_2}|=\frac{|z_1|}{|z_2|}$ for all $z_1,z_2\in{C}$   
$z_1=x_1+iy_1$  
$z_2=x_2+iy_2$  
$|(x_1+iy_2)(x_2+iy_2)|=|x_1+iy_1|\times|x_2+iy_2|$  
$|x_1x_2-y_1y_2+i(x_1y_2+x_2y_1)|=\sqrt{x_1^2+y_1^2}\times\sqrt{x_2^2+y_2^2}$  
$(x_1x_2-y_1y_2)^2+(x_1y_2+x_2y_1)^2=(x_1^2+y_1^2)(x_2^2+y_2^2)$  
expand  
$(x_1x_2)^2+(y_1y_2)^2+(x_1y_2)^2+(x_2y_1)^2=(x_1x_2)^2+(y_1y_2)^2+(x_1y_2)^2+(x_2y_1)^2$  
  
