---
tags: []
date: 2025-05-06
---
---  
# Graphs and networks  
  
## Graphs  
Graphs are built up with a set of points (nodes) connected by lines (edges)  
The layout of the graph is irrelevant. What matters is which nodes are connected to which  
  
Isomorphic graphs - of the same form  
Connected graphs, can travel from any vertex to another  
  
```tikz  
\begin{document}  
\begin{tikzpicture}[radius=2cm]  
  
\draw[line width=0.5mm] (-0.35,-0.35) circle (0.5);  
\draw[line width=0.5mm] (4,0) arc[start angle=180, end angle=90];  
\draw[line width=0.5mm] (6,2) arc[start angle=-180, end angle=-270, radius=-2cm];  
\draw[line width=0.5mm]  
	(0,0) node[red] {$\huge\bullet$}  
	-- (2,3) node[red] {$\huge\bullet$}  
	-- (4,0) node[red] {$\huge\bullet$}  
	-- (0,0);  
\node[red] at (6,2) {$\bullet$};  
  
\end{tikzpicture}  
\end{document}  
```  
  
<center><i><b>Fig. 1</b></i></center>  
  
A simple graph is one with no multiple edges or loops  
  
Subgraph - formed using some of the edges and nodes of another graph  
Subdivision - add extra nodes along the edges of a graph  
  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
\draw[line width=0.5mm]  
	(0,0) node [below, left] {D} node[red] {$\bullet$}  
	-- (0,2) node [above,left] {A} node[red] {$\bullet$}  
	-- (1,2) node [above] {E} node[red] {$\bullet$}  
	-- (2,2) node [above,right] {B} node[red] {$\bullet$}  
	-- (2,0) node [below,right] {C} node[red] {$\bullet$}  
	-- (0,0);  
  
\end{tikzpicture}  
\end{document}  
```  
  
<center><i><b>Fig. 2</b></i></center>  
  
*In this figure, E is a point on the line AB, so square AEBCD is a subdivision of square ABCD*  
  
Complete graph - a simple graph connecting all pairs of nodes. A complete graph with $n$ nodes is called $K_n$  
  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
%k2  
\draw[line width=0.5mm]  
	(-2,0) node[red] {$\bullet$}  
	-- (2,0) node[red] {$\bullet$};  
\node at (0,-0.5) {$K_2$};  
  
%k3  
\draw[line width=0.5mm]  
	(4,0) node[red] {$\bullet$}  
	-- (6,3) node[red] {$\bullet$}  
	-- (8,0) node[red] {$\bullet$}  
	-- (4,0);  
\node at (6,-0.5) {$K_3$};  
  
%k4  
\draw[line width=0.5mm] (2,-5) -- (-2,-5);  
\draw[line width=0.5mm]  
	(0,-2) node[red] {$\bullet$}  
	-- (0,-4) node[red] {$\bullet$}  
	-- (2,-5) node[red] {$\bullet$}  
	-- (0,-2)  
	-- (-2,-5) node[red] {$\bullet$}  
	-- (0,-4);  
  
\node at (0,-5.5) {$K_4$};  
  
\end{tikzpicture}  
\end{document}  
```  
  
  
<center><i><b>Fig. 3</b></i></center>  
The complete graph $K_n$ will have number edges $\frac{1}{2}n^2 - \frac{1}{2}n$  
  
Order/degree - the number of edges going into/from a node  
Bipartite graph - The verticies belong to two distinct sets and each edge joins a node from one set to the other  
Complete bipartite graph - containing all possible edges  
  
The number of degrees in a graph will always be equal to 2 times the sumber of edges  
Planar graphs - can be draws so that no 2 edges cross  
The areas created by the edges in a planar graph are called faces. The area outside the graph is also a face (the infinite face)  
  
# Adjacency matrix  
```tikz  
\begin{document}  
\begin{tikzpicture}[radius=2cm]  
  
\draw[line width=0.5mm] (2,3) -- (6,2);  
\draw[line width=0.5mm] (-0.35,-0.35) circle (0.5);  
\draw[line width=0.5mm] (4,0) arc[start angle=180, end angle=90];  
\draw[line width=0.5mm] (6,2) arc[start angle=-180, end angle=-270, radius=-2cm];  
\draw[line width=0.5mm]  
	(0,0) node[red] {$\huge\bullet$} node[left,below] {B}  
	-- (2,3) node[red] {$\huge\bullet$} node[above] {A}  
	-- (4,0) node[red] {$\huge\bullet$} node[right,below] {C}  
	-- (0,0);  
\node[red] at (6,2) {$\bullet$};  
\node at (6,2.5) {D};  
  
\end{tikzpicture}  
\end{document}  
```  
  
|     | A   | B   | C   | D   |  
| --- | --- | --- | --- | --- |  
| A   | 0   | 1   | 1   | 1   |  
| B   | 1   | 2   | 1   | 0   |  
| C   | 1   | 1   | 0   | 2   |  
| D   | 1   | 0   | 2   | 0   |  
An adjacency matrix shows how many edges go into each node from other nodes. For example, in this matrix, 2 edges from node C will go into node D, but only one edge from node A will go into node D  
  
# Traversing a graph  
A trail - a walk with no repeated edges. If a trail returns to its starting node, it is called a closed trail.  
A path - a walk with no repeated edges or nodes  
A cycle - a closed path  
A tree - a connected graph with no cycles  
Hamiltonian cycle - visits every node once only  
Eulerian trail - traverses ever edge once. A graph is eulerian if all nodes are of even degree  
Semi-eulerian - a graph that has two odd degree nodes. These two nodes have to be the start and finish nodes  
A spanning tree with n nodes has (n-1) edges  
A minimum spanning tree - has the lowest total weight  
