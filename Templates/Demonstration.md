```tikz  
  
  
\begin{document}  
\begin{tikzpicture}  
\usetikzlibrary{arrows}  
\newcommand{\midarrow}{\tikz \draw[Red, -triangle 90] (0,0) -- +(.1,0);}  
  
\draw[line width=0.5mm] (2,-5) -- node{\midarrow}(-2,-5);  
\draw[line width=0.5mm]  
	(0,-2) node[red] {$\bullet$}   
	-- node[rotate=90]{\midarrow} (0,-4) node[red] {$\bullet$}   
	-- node{\midarrow} (2,-5) node[red] {$\bullet$}  
	-- node{\midarrow}(0,-2)  
	-- node{\midarrow}(-2,-5) node[red] {$\bullet$}  
	-- node{\midarrow}(0,-4);  
  
\node at (0,-5.5) {$K_4$};  
  
\end{tikzpicture}  
\end{document}  
```  
