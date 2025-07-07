---
tags:
  - chemistry
  - quantative_chemistry
date: 2025-05-12
---
---  
# Concentration-time graphs  
**Continuous measurements** are taken throughout a reaction and plotted, allowing the rate and orders of reaction to be determined  
  
Methods of continuous measurement:  
- Gas produced  
	- Gas collection  
	- Mass lost  
- Change in pH  
- Colorimeter  
	- Change in colour  
	- Formation of a precipitate  
  
# Calculating rate  
Draw a tangent to determine the rate from the gradient using:$$\text{Rate }=\frac{\text{change in concentration}}{\text{change in time}}$$  
# Half life  
**Half life**$(t_{1/2})$ - time taken for the concentration of a reactant to decrease by half  
The half life of a reactant changes based on the overall order of the reaction, giving distict graphs  
  
## Zero order  
  
```tikz  
\begin{document}  
\begin{tikzpicture}[scale=0.5]  
  
\draw[step=1.0, thin] (0,0) grid (10,10);  
\draw[thick] (0,0) -- (0,10) node[midway, above, rotate=90] {Concentration};  
\draw[thick] (0,0) -- (10,0) node[midway, below] {Time};  
\draw[line width = 0.5mm, red] (0,10) -- (10,3);  
  
\end{tikzpicture}  
\end{document}  
```  
- Straight line with a negative gradient  
- Gradient = rate constant (k)  
- Constant rate  
- Half life decreases over time  
  
## First order  
```tikz  
\usepackage{pgfplots}  
\begin{document}  
\begin{tikzpicture}[scale=0.5]  
  
\draw[step=1.0, thin] (0,0) grid (10,10);  
\draw[thick] (0,0) -- (0,10) node[midway, above, rotate=90] {Concentration};  
\draw[thick] (0,0) -- (10,0) node[midway, below] {Time};  
\draw[red, domain=0.1:2.6, samples=100, line width=0.5mm] plot ({4*(\x)-0.35}, {(1/\x)});  
  
\end{tikzpicture}  
\end{document}  
```  
- Downward curve  
- Rate decreases over time  
- **Constant half life** - the concentration halves at regular intervals  
  
# Determining 'k' for a first order reaction  
>[!formula] Formula for K  
>$$k=\frac{\ln 2}{t_{1/2}}$$  
  
