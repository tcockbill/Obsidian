---
tags:
  - Maths
  - Mechanics
date: 2025-01-30
---
---  
# Questions  
3. a particle of [[../../To do/Mass|mass]] 3kg moves horizontally to the left under its own [[../../To do/Weight|weight]] and two [[../../To do/Forces|forces]], $P$ and $Q$, as shown in the diagram  
  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
\draw[fill=blue] (-0.25,-0.25) rectangle (0.25,0.25);  
\draw[-latex] (0.25,0) -- (3.25,0) node [label=below:{$Q$}] {};  
\draw[-latex] (0,-0.25) -- (0,-3.25) node [label=right:{$3gN$}] {};  
\draw[-latex] (0,0.25) -- (-1.399,3.25) node [label=above:{$P$}] {};  
\draw[dashed] (-2,0) -- (4,0);  
\draw (-1,0) arc (0:-71:-1);  
\node at (-0.5,0.4) {$65 ^\circ$};  
  
\end{tikzpicture}  
\end{document}  
```  
if the [[../../Physics/Acceleration|acceleration]] of the particle is $2ms^{-2}$, work out the values of P and Q  
$W=mg=3 \times 9.81 = 29.43N$  
$P \sin (65\textdegree)=W$  
$P \sin (65\textdegree)=29.43$  
$P=\frac{29.43}{\sin (65 \textdegree)} \approx 32.46N$  
  
$P_x-Q=ma$  
$32.46 \cos (65 \textdegree) - Q = 3 \times 2$  
$13.73-Q=6$  
$Q=13.73-6$  
$Q=7.73N$  
  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
\draw[fill=black] (-0.25,-0.25) rectangle (0.25,0.25);  
\draw[-latex] (0,0) -- (3,5.196) node [label=above:{60N}] {};  
\draw[-latex] (0,0) -- (3.464,-2) node [label=below:{40N}] {};  
\draw[-latex] (0,0) -- (-1.710,-4.698) node [label=below:{50N}] {};  
\draw[-latex] (0,0) -- (0,-3.924) node [label=below:{39N}] {};  
\draw[dashed] (-6,0) -- (6,0);  
\draw[dashed] (0,-6) -- (0,6);  
\draw (1,0) arc (0:60:1) node [label=right:{60$^\circ$}] {};  
\draw (1,0) arc (0:-30:1) node [label=right:{30$^\circ$}] {};  
\draw (0,-1) arc (-90:-110:1) node [label=below:{20$^\circ$}] {};  
  
\end{tikzpicture}  
\end{document}  
```  
What is the magnitude and direction of the [[../../Physics/Acceleration|acceleration]]?  
  
  
  
```tikz  
  
  
\begin{document}  
  
\begin{tikzpicture}  
    % Draw the flat surface  
    \draw[thick] (-3,0) -- (3,0);  
      
    % Draw the block  
    \fill[gray] (-0.25,0) rectangle (0.25,0.5);  
      
    % Draw the forces  
    % Weight  
    \draw[->, thick] (0,0) -- (0,-1.5) node[below] {2g};  
      
    % Upwards force R  
    \draw[->, thick] (0,0) -- (0,1.5) node[above] {R};  
      
    % Backwards force 0.2R  
    \draw[->, thick] (0,0) -- (-1,0) node[midway,above] {0.2R};  
      
    % Force at 30 [[To do/Degrees|degrees]]  
    \draw[->, thick] (0,0) -- (30:2) node[label=right:{20N}] {};  
\end{tikzpicture}  
  
\end{document}  
```  
  
  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
\draw[fill=black] (-0.25,-0.25) rectangle (0.25,0.25);  
\draw[dashed] (0,0) -- (4,0);  
\draw (1,0) arc (0:60:1) node[midway] {60$^\circ$};  
\draw (-1,0) arc (180:120:1) node[midway] {60$^\circ$};  
\draw[->] (0,0) -- (270:3) node[below] {600gN};  
\draw[->] (0,0) -- (180:2) node[left] {400N};  
\draw[->] (0,0) -- (60:3) node[midway,right] {$T_1$};  
\draw[->] (0,0) -- (120:3) node[midway,left] {$T_2$};  
  
\end{tikzpicture}  
\end{document}  
```  
$T_1V+T_2V=5886$  
  
  
A "kite buggy" is a wheeled cart pulled along by the force of the wind acting on a kite attatched to it. The buggy has a [[../../To do/Mass|mass]] of 100kg(including the driver). It is travelling down a 10$\textdegree$ slope towed by a kite whose tether makes an angle of 40$\textdegree$ with the horizontal. The [[../../Physics/Tension|tension]] in the tether is 250N and resistance [[../../To do/Forces|forces]] total 50N. Taking $g=10ms^{-1}$, work out the [[../../Physics/Acceleration|acceleration]] of the buggy  
  
$1000\sin(10)+250\cos(50)-50=284N$  
$F=ma$  
$a=\frac{F}{m}=\frac{284}{100}=2.84ms^{-2}$  
  
