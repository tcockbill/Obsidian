---
tags: []
date: 2025-09-08T18:10:38
---
---  
  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
\draw[line width=1] (0,0) circle [radius=2];  
\draw[line width=1, ->, red] (0,2) -- (2,2) node [above, midway] {v};  
\draw[line width=1, <->, red] (0,0) -- (0,2) node [right, midway] {r};  
  
\end{tikzpicture}  
\end{document}  
```  
$$v=\frac{2 \pi r}{T}$$  
  
  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
\draw[line width=1] (0,0) circle [radius=2];  
\draw[line width=1, red] (0,0) -- (0,2);  
\draw[line width=1, red] (0,0) -- (1,1.732);  
\draw[line width=1, red] (0,0.5) arc (90:60:0.5) node[above, midway] {$\theta$};  
  
\end{tikzpicture}  
\end{document}  
```  
$$\omega = \frac{2\pi}{T}$$  
$f=\frac{1}{t}$  
$V=2 \pi rf$  
$\omega = 2 \pi f$  
$v = \omega r$  
  
  
Simple harmonic motion is where acceleration is directly proportional to the displacement but acts in the opposite direction  
$a \propto -x$  
$x=A \cos (\omega t)$  
$v=-\omega A \sin (\omega t)$  
$a=-\omega ^2 \cos (\omega t)=-\omega^{2}x$  
