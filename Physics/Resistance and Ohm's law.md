---
tags:
  - Undone
  - Physics
date: 2025-02-04
---
---  
# Starter [[./Kirchhoff's second law (PD and EMF)|Kirchhoff's second law (PD and EMF)]]  
1. 4A  
2. 225  
3. $1.4 \times 10^{21}$  
4. 8280 C  
```tikz  
\usepackage{circuitikz}  
  
\begin{document}  
  
\begin{circuitikz} \draw  
  
    % Battery  
    (0,0) to[battery1, l_=$5V$] (4,0)  
	(4,0) -- (4,-4) to[vR, l_=$vR$] (0,-4)  
	(0,-4) -- (0,0)  
	(0,-4) to[ammeter] (0,-6)  
	(0,-6) -- (0,-8) to[voltmeter] (2,-8)  
	(0,-6) to[R, l_=$?$] (2,-6)  
	[-latex] (2,-8) -- (2,-4.25)  
;  
  
\end{circuitikz}  
  
\end{document}  
```  
  
  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
\draw (0,0) -- (4,0) node[right] {V};  
\draw (0,0) -- (0,4) node[above] {I};  
\draw (0,0) -- (4,4);  
\draw (1,1) -- (2,1) -- (2,2) node[midway,right] {$=\frac{1}{R}$};  
  
\end{tikzpicture}  
\end{document}  
```  
  
| Current | P.d. |  
| ------- | ---- |  
| 0.04    | 0.43 |  
| 0.05    | 0.56 |  
| 0.06    | 0.65 |  
| 0.07    | 0.78 |  
| 0.08    | 0.86 |  
| 0.09    | 0.96 |  
| 0.1     | 1.07 |  
| 0.12    | 1.28 |  
| 0.18    | 1.95 |  
