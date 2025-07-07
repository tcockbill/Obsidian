---
tags:
  - Undone
  - Physics
  - Optics
date: 2025-02-03
---
---  
# [[./Single slit diffraction|Diffraction]]gratings  
1. 39.95 m  
2. No, [[../To do/Charge|charge]] is not conserved  
3. $\sin ^{-1}\frac{1.47}{1.57}=69.44 \textdegree$  
4.   
```desmos-graph  
left=0; right=2;  
top=5; bottom=0;  
---  
y=x^6|x>0|y>0|  
```  
  
  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
\draw[-latex] (0,0) -- (2,0) node[midway,above] {Laser light};  
\draw[thick] (2,-1) -- (2,1) node[above] {Diffraction grating};  
\draw[dashed] (2,0) -- (7,0) node[right] {n=0};  
\draw[dashed] (2,0) -- (7,1) node[right] {n=1};  
\draw[dashed] (2,0) -- (7,2.5) node[right] {n=2};  
\draw[dashed] (2,0) -- (7,-2.5) node[right] {n=2};  
\draw[dashed] (2,0) -- (7,-1) node[right] {n=1};  
\draw[thick] (7,-3) -- (7,3) node[above] {screen};  
\draw (4,0) arc (0:11:2) node[midway,left] {\small $\theta$};  
\node at (7,0) {\large $\bullet$};  
\node at (7,1) {\large $\bullet$};  
\node at (7,2.5) {\large $\bullet$};  
\node at (7,-1) {\large $\bullet$};  
\node at (7,-2.5) {\large $\bullet$};  
  
\end{tikzpicture}  
\end{document}  
```  
  
$n \lambda = d\sin \theta$  
$n = \text{Order of constructive fringes}$  
$\lambda = \text{Wavelength of light}$  
$d= \text{Distance between slits}$  
$\theta = \text{Angle between normal to grating and the maxima}$  
  
$\sin ^{-1} (\frac{2 \times 0.0000007}{0.0000025}) - \sin ^{-1} (\frac{2 \times 0.0000004}{0.0000025}) = 15.39 \textdegree$  
