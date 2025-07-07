---
tags:
  - Maths
  - Pure
date: 2025-02-10
---
---  
# Cartesian coordinates  
2d - (x,y)  
  
  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
\draw[line width=0.5mm, ->] (-5,0) -- (5,0) node[right,above] {x};  
\draw[line width=0.5mm, ->] (0,-5) -- (0,5) node[above,left] {y};  
\draw (0,0) -- (2,0) -- (2,2) -- (0,0);  
\draw (0.5,0) arc (0:45:0.5) node[midway,right] {$\theta$};  
\node at (1,-0.25) {x};  
\node at (2.25,1) {y};  
\node at (0.75,1) {r};  
\node at (2,2) {\tiny $\bullet$};  
  
\end{tikzpicture}  
\end{document}  
```  
To convert from cartesian to polar, use the pol() button on the calculator  
  
$r=5\sin(3\theta)$  
```desmos-graph  
r=5 \sin (3 \theta)  
```  
  
$x=r \cos \theta$  
$y = r \sin \theta$  
$(x,y) \rightarrow (r, \theta)$  
$(r, \theta) \rightarrow (x,y)$  
$x^2+y^2 = r^2$  
$\tan \theta = \frac{r \sin \theta}{r \cos \theta} = \frac{y}{x}$  
$\theta = \tan^{-1}(\frac{y}{x})$  
  
```desmos-graph  
top=1; bottom=-1;  
left=-1; right=1;  
---  
r= \cos 2 \theta   
```  
  
1. $(4,4)$ = $(4\sqrt{2},\frac{1}{4} \pi)$  
  
```desmos-graph  
top=3; bottom=-3;  
left=-3; right=3;  
---  
r=\sin2^{\theta} - 1.7|0 <= \theta <= 2 \pi  
```  
  
1. Given the curve$$r=f(\theta) = \sin (\theta) + \frac{1}{\sin \theta}$$ Show $f(-\theta)=-f(\theta)$ and $f( \pi - \theta) = f(\theta)$  
