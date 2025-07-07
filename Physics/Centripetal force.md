---
tags:
  - physics
date: 2025-05-09
---
---  
# Centripetal acceleration  
Acceleration is defined as the rate of change of velocity. Consider the change of direction of velocity below  
  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
\draw[-latex] (-1,0) -- (3,-2) node[midway, above] {$v_2$};  
\draw[-latex] (3,-2) -- (-2,-2) node[midway, below] {$v_1$};  
\draw[-latex] (-1,0) -- (-2,-2) node[midway, above] {$v_2 - v_1$};  
  
\end{tikzpicture}  
\end{document}  
```  
  
>[!note] Acceleration expressions  
>Centripetal acceleration  
>$$ a = \frac{v^2}{r}$$  
>Measured in $ms^-2$  
>---  
>Angular acceleration  
>$$a = \omega ^2r$$  
>measured in $rads^-2$  
  
```tikz  
\usepackage{tikz}  
\usetikzlibrary{arrows.meta, positioning}  
  
\begin{document}  
  
\begin{tikzpicture}[scale=1.5]  
    % Draw the circular path  
    \draw[thick] (0,0) circle(2);  
  
    % Draw the object moving in a circle  
    \fill[blue] (2,0) circle(0.1) node[right] {Object};  
  
    % Draw the radius  
    \draw[->, thick] (0,0) -- (2,0) node[midway, below] {Radius};  
  
    % Draw the centripetal force arrow  
    \draw[->, thick, red] (2,0) -- (1.5,1) node[midway, left] {Centripetal Force};  
  
    % Draw the velocity vector  
    \draw[->, thick, green] (2,0) -- (2,1) node[midway, right] {Velocity};  
  
    % Add labels  
    \node at (0,-2.5) {Centripetal Force Diagram};  
\end{tikzpicture}  
  
\end{document}  
```  
  
>[!note] Centripetal force  
>$$F = \frac{mv^2}{r}$$  
>$$F= m \omega^2 r$$  
  
