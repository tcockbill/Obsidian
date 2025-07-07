---
tags:
  - Maths
  - Mechanics
  - Physics
date: 2025-02-28
---
---  
# <u>Definition</u>  
A moment is the work needed to cause a turning effect  
$\text{Moment } = \text{ Force} \times \text{perpendicular distance}$  
Moments are measured in Newton Meters, (Nm)  
  
  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
\draw[line width=0.5mm] (2,-1) circle (0.02);  
\draw[-latex] (2,-1) -- ++(4,0);  
\draw[-latex] (2,-1) -- ++(0,-3);  
  
\end{tikzpicture}  
\end{document}  
```  
```tikz  
\usepackage{tikz}  
\usetikzlibrary{arrows.meta, positioning}  
  
\begin{document}  
\begin{tikzpicture}[scale=1, every node/.style={scale=0.8}]  
    % Define points  
    \coordinate (A) at (3, 2);  
    \coordinate (B) at (2, 1);  
    \coordinate (C) at (1, -1);  
      
    % Draw points  
    \fill[blue] (A) circle (2pt) node[above right] {A (3i + 2j)};  
    \fill[red] (B) circle (2pt) node[above right] {B (2i + j)};  
    \fill[green] (C) circle (2pt) node[below left] {C (i - j)};  
      
    % Draw forces  
    \draw[->, thick, blue] (A) -- ++(5, 2) node[midway, right] {5i + 2j N};  
    \draw[->, thick, red] (B) -- ++(1, 3) node[midway, right] {i + 3j N};  
      
    % Draw lines to point C  
    \draw[dashed] (A) -- (C);  
    \draw[dashed] (B) -- (C);  
      
    % Add labels for moments  
    \node at (1.5, 0.5) {Moment about C from A};  
    \node at (1.5, -0.5) {Moment about C from B};  
\end{tikzpicture}  
\end{document}  
```  
