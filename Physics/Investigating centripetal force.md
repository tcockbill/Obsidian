---
tags:
  - physics
date: 2025-05-13
---
---  
# Starter  
i. 31.6 N  
ii. to shift his center of mass closer to the center, but having his contact with the platform behind his center of mass stops his from sliding backwards due to direct velocity  
  
  
```tikz  
\begin{document}  
\begin{tikzpicture}  
\usetikzlibrary{decorations.markings}  
  
\begin{scope}[very thick,decoration={  
    markings,  
    mark=at position 0.5 with {\arrow[->]{stealth}}}  
    ]   
    \draw[postaction={decorate}] (0,3)--(0,0) node[midway, left] {F};  
\end{scope}  
  
\node at (0,0) {$\bullet$};  
\draw[dashed] (0,0) circle (3);  
\draw[-latex] (0,3) -- (-2,3) node[midway, above] {v};  
\draw[latex-latex] (0.25,0) -- (0.25,3) node[midway, right] {r};  
\node at (0,3) {$\bullet$};  
\draw[-latex, line width = 0.5mm] (0,3) arc[radius=-3, start angle=-90, end angle=0] node[midway, left] {direction of motion};  
  
\end{tikzpicture}  
\end{document}  
```  
