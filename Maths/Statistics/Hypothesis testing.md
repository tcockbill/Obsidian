---
tags:
  - Maths
  - Statistics
date: 2024-12-11
---
---  
# [[./Binomial Distribution|Binomial Distribution]] Hypothesis testing[[./Formula for probability of union|Formula for probability of union]]  
Is a coin biased?  
Flip it 10 times  
X is number of heads  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
\draw[latex-latex] (-0.5,0) -- (10.5,0) ;  
\foreach \x in  {0,1,2,3,4,5,6,7,8,9,10}  
\draw[shift={(\x,0)},color=black] (0pt,3pt) -- (0pt,-3pt);  
\foreach \x in {0,1,2,3,4,5,6,7,8,9,10}  
\draw[shift={(\x,0)},color=black] (0pt,0pt) -- (0pt,-3pt) node[below]   
{$\x$};  
\draw[red] (7.75,-0.125) rectangle (10.25,-0.625);  
  
\end{tikzpicture}  
\end{document}  
```  
$X$~$B(10,0.5)$  
$P(X\ge8)=0.055$  
  
The [[./Null Hypothesis|null hypothesis]] is a statistical statemment representing your basic assumption.  
The [[./Alternative Hypothesis|alternative hypothesis]] is a statement that contradicts the [[./Null Hypothesis|null hypothesis]]  
  
H$_0$:p=0.75  
overestimate - H$_1$:p<0.75  
underestimate - H$_1$:p>0.75  
not true - H$_1$:P$\neq0.75$  
  
H$_0$:p=0.7  
H$_1$:p>0.7  
$\frac{21}{25}=0.84$   
21/25=  
The likelyhood of that happening with the probablity is 0.09=9% that is more than significance level of 2.5%, so we can accept H$_0$ as there is insufficient evidence to suggest the proportion of new local buisnesses that have made profit has increased  
  
# Section 2  
1| 30 times to get a six 5% significance   
i| H$_0$: P=$\frac{1}{6}$  
H$_1$: P<$\frac{1}{6}$  
ii| P(X$\le1$)=0.029  
P(X$\le2$)=0.103  
iii| critical region is $\le1$. this is the region in which the [[./Null Hypothesis|null hypothesis]] is rejected  
  
2| get a 1 more  50 times  10% significance  
i|H$_0$: P=$\frac{1}{6}$  
H$_1$: P$\gt{\frac{1}{6}}$   
ii| P(X$\ge12$)=0.117  
P(X$\ge13$)=0.0627  
iii| The critical region is >12  
  
# Exam Questions  
1| H$_0$: P=0.25  
H$_1$: P>0.25  
The conclusion is that free samples increased the proportion of people buying loaves of bread.  
  
3| a| i| P(X=6)=0.2  
ii|  
$7 \times 0.7 = 4.90$  
b| $H_0: P=0.7$  
$H_1: P>0.7$  
$P(x\ge28)=0.13$  
  
5+15+12+20+3+5= 60  
5+15= 20  
20/60= 0.33  
$(20/60) \times (20/60) \times (3/60)$  = 0.01  
  
# Finding critical values  
A critical region is a region of the probability distribution which, if the test statistic falls within it, would cause you to reject the null hypothesis. The critical value is the first value to fall inside of the critical region.  
  
The actual significance level of a hypothesis test is the probability of incorrectly rejecting the null hypothesis.  
  
![[../../Extra Files/Scanned_20250604-0926.jpg|500]]  
*Figure 1.1, example of finding the critical values*  
