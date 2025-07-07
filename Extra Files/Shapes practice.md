---
tags:
  - Undone
date: 2024-12-06
---
---  
# Shapes  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
\fill[blue!50] (0,0) ellipse (6 and 3);  
  
\end{tikzpicture}  
\end{document}  
```  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
\draw (0,0) parabola (4,4);  
\draw (3,0) arc (0:75:3cm);  
  
\end{tikzpicture}  
\end{document}  
```  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
\shade[left color=blue,right color=red] (0,0) rectangle (4,4);  
  
\end{tikzpicture}  
\end{document}  
```  
```smiles  
C(=O)(O)CCCCC(CCCCCC)(CC)CCCCC(c1ccccc1)(c1ccccc1)CC(CC(CCC)(C))(CCC(CC)CC(CC))C(N)CCCCC(Cl)(Br)CCCCCCC  
CCC(C)(C)CCC(CC)CCC(O)  
CC(=O)C  
Cl[Sn](Cl)(Cl)C1=CC=CC=C1  
C1=CC=CC=C1C(F)(N)(N)  
C1=CC=CC=C1C(N)(N)  
C1=CC=CC=C1C#C  
C=CCC#N  
CCS(=O)CCSP(=S)(OCC)OCC  
C1CC1CO  
C1=C(O)C=C(O)C=C1  
OC(=O)CC(=O)C(=O)O  
```  
	  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
\draw[line width=0.6mm] (0.1,0.1) grid (5.9,5.9);  
\fill[fill=blue!60] (3,3) rectangle (2,2);  
  
\end{tikzpicture}  
\end{document}  
```  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
\draw[line width=0.6mm] (0,0) grid (6,6);  
  
\end{tikzpicture}  
\end{document}  
```  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
\draw[line width=0.6mm] (0,0) circle (1.5);  
\draw[->] [line width=0.6mm] (0,-1.5) -- (0,-3);  
  
\end{tikzpicture}  
\end{document}  
```  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
\draw (0,0) -- (3,3);  
  
  
\end{tikzpicture}  
\end{document}  
```  
  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
\draw[step=1.0, thin] (0,0) grid (9,9);  
\draw[step=3.0, thick] (0,0) grid (9,9);  
\foreach \x in {0.5,...,8.5}{  
	\foreach \y in {0.5,...,8.5}{  
		\node at (0+\x,0+\y) {-} {};  
	}  
}  
  
\end{tikzpicture}  
\end{document}  
```  
