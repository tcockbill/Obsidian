```tikz  
\begin{document}  
  
\begin{tikzpicture}  
  \draw[thick] (0.5,0.5) rectangle (14.5,11.5);  
  
  % Draw vertical lines for the days  
  \foreach \x in {2.5, 4.5, 6.5, 8.5, 10.5, 12.5} {  
    \draw[thick] (\x,0.5) -- (\x,11.5);  
  }  
  
  % Draw horizontal lines for the hours  
  \foreach \y in {1.5, 2.5, 3.5, 4.5, 5.5, 6.5, 7.5, 8.5, 9.5, 10.5} {  
    \draw[thick] (0.5,\y) -- (14.5,\y);  
  }  
  
  % Column headers  
  \node at (1.5,11) {Time};  
  \node at (3.5,11) {Monday};  
  \node at (5.5,11) {Tuesday};  
  \node at (7.5,11) {Wednesday};  
  \node at (9.5,11) {Thursday};  
  \node at (11.5,11) {Friday};  
  \node at (13.5,11) {Saturday};  
  
  % Time labels  
  \foreach \y in {0, 1, 2, 3, 4, 5, 6, 7, 8, 9} {  
    \node at (1.5,10-\y) {\the\numexpr 8+\y\relax:00};  
  }  
\end{tikzpicture}  
  
\end{document}  
```  
