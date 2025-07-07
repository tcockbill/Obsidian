---
tags:
  - chemistry
date: 2025-05-21
---
---  
# Rate-concentration graphs  
Plotted from measurements of initial rate at a different concentration  
Allows order of each reactant to be determined  
  
```tikz  
\begin{document}  
\begin{tikzpicture} [scale=2.0]  
  
\draw [-latex, line width=1] (0,0) -- (4,0)  node[midway, below] {concentration};  
\draw [-latex, line width=1] (0,0) -- (0,4)  node[midway, above, rotate=90] {rate};  
\draw [red, line width=1] (0,3) -- (4,3) node[midway, below] {zero order};  
\draw [blue, line width=1] (0,0) -- (4,3.5) node[midway, below, left] {first order};  
\draw [green, line width=1] (0,0) to[in=-90,out=10] (4,3.75) node[right] {second order};  
  
  
\end{tikzpicture}  
\end{document}  
```  
initial rates (t=0)  
There are two main methods of determining initial rate  
- gradient at t=0 on a concentration-time graph  
- clock reaction - time for a visual change to be observed is measured, repeated at different concentrations  
