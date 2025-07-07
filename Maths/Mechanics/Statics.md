---
tags:
  - Maths
  - Mechanics
date: 2025-02-12
---
---  
# Friction  
Friction is proportional to [[../../To do/Weight|weight]]   
The coefficient of friction is $\mu$  
  
```tikz  
\usetikzlibrary{arrows.meta, positioning}  
  
\begin{document}  
\begin{tikzpicture}[scale=1.2]  
    % Draw the box  
    \draw[thick] (0,0) rectangle (2,1) node[pos=.5] {Box (W)};  
      
    % Draw the surface  
    \draw[thick] (-1,0) -- (3,0);  
      
    % Draw the tension force  
    \draw[->, thick, blue] (2,0.5) -- (3,1.5) node[midway, above right] {Tension (600N)};  
      
    % Draw the normal force  
    \draw[->, thick, red] (1,1) -- (1,2) node[midway, left] {Normal Reaction (R)};  
      
    % Draw the weight force  
    \draw[->, thick, green] (1,0) -- (1,-1) node[midway, left] {Weight (W)};  
      
    % Draw the friction force  
    \draw[->, thick, orange] (0,0) -- (-1,0) node[midway, above] {Friction};  
      
    % Draw angle  
    \draw[thick] (2,0) -- (2.5,0.5);  
    \draw[dashed] (2,0) -- (2,1);  
    \node at (2.3,0.25) {45$^\circ$};  
      
    % Add labels  
    \node at (1,-1.5) {Weight (W) = ?};  
    \node at (1,2.5) {Normal Reaction (R) = ?};  
  
\end{tikzpicture}  
\end{document}  
```  
  
  
```tikz  
\usetikzlibrary{arrows.meta, positioning}  
  
\begin{document}  
  
\begin{tikzpicture}  
    % Draw the slope  
    \draw[thick] (0,0) -- (4,0) -- (3,2) -- (0,2) -- cycle; % slope  
    \draw[thick] (0,0) -- (3,2); % incline line  
  
    % Draw the block  
    \fill[blue!20] (1.5,0.5) rectangle (2.5,1.5);  
    \node at (2,1) {7 kg};  
  
    % Draw the force vector  
    \draw[->, thick, red] (2,1.5) -- (2,2.5) node[midway,right] {50 N};  
  
    % Draw the friction force vector  
    \draw[->, thick, green] (2,0.5) -- (1.5,0.5) node[midway,above] {Friction};  
  
    % Draw the weight vector  
    \draw[->, thick, blue] (2,1) -- (2,0) node[midway,left] {Weight};  
  
    % Draw the normal force vector  
    \draw[->, thick, orange] (2,1.5) -- (2.5,1.5) node[midway,above] {Normal Force};  
  
    % Add angle labels  
    \node at (0.5,0.5) {35°};  
    \node at (3.5,1) {Slope};  
  
    % Add labels for [[To do/Forces|forces]]  
    \node at (3.5,2.5) {Force (F)};  
    \node at (0.5,0) {Weight (W)};  
    \node at (0.5,1) {Normal Force (N)};  
    \node at (0.5,0.5) {Friction (f)};  
  
\end{tikzpicture}  
  
\end{document}  
```  
$$\text{Given: } m = 50 \text{ kg}, \, g = 9.8 \, \text{m/s}^2, $$$$ F_{\text{air}} = 175v, \, F_{\text{net}} = mg - F_{\text{air}} \Rightarrow F_{\text{net}} = 50 \cdot 9.8 - 175v = 490 - 175v$$$$ \, \text{Using } F = ma \Rightarrow m\frac{dv}{dt} = 490 - 175v \Rightarrow 50\frac{dv}{dt} = 490 - 175v \Rightarrow \frac{dv}{dt} = \frac{490 - 175v}{50} = 9.8 - 3.5v$$$$ \, \text{Thus, } \frac{dv}{dt} = -3.5(v - 2.8) \text{ and solving gives } v(t) = 2.8 + (v_0 - 2.8)e^{-3.5t} \text{ where } v_0 = 12.8 \text{ m/s.}$$  
