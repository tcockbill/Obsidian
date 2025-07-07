---
tags:
  - Maths
date: 2025-03-04
---
---  
# Properties and arithmetic  
$$\begin{bmatrix} 3 & -1 \\ 0 & 2 \\ 5 & 2 \end{bmatrix} \qquad \text{order =} 3 \times 2$$  
$$\begin{bmatrix} 3 & 1 & 5\end{bmatrix} \qquad \text{order =} 1 \times 3$$  
$$A \times B = C$$  
You can multiply matrices if A has the number of rows across as B has down  
  
$$A+B=C$$  
You can add matrices if A and B both have the same order  
  
## Scalar multiplication  
$$3 \begin{bmatrix} 2&0&1\\5&7&2 \end{bmatrix} = \begin{bmatrix} 6&0&3\\15&21&6 \end{bmatrix}$$  
## Questions  
if $$A = \begin{bmatrix} 2&5\\0&4\\-1&-3 \end{bmatrix}, \space B=\begin{bmatrix} 2&-3\\0&5 \end{bmatrix}, \space C = \begin{bmatrix} 6&15\\0&12\\-3&-9 \end{bmatrix}$$  
a. $A+B = \text{not possible.}$  
b. $A+C = \begin{bmatrix} 8&20\\0&16\\-4&-12 \end{bmatrix}$  
c. $2B=\begin{bmatrix} 4&-6\\0&10 \end{bmatrix}$  
d. $C-3A = \begin{bmatrix} 0&0\\0&0\\0&0 \end{bmatrix}$  
## Key points  
The zero matrix, 0, is a matrix, of any order, with all elements equal to zero  
  
If two matrices can be multiplied, they are <b>conformable for multiplication</b>  
  
The product of an $n \times m$ matrix and an $m \times p$ matrix has order $n \times p$  
  
$$\begin{bmatrix} A&B\\ C &D \end{bmatrix} \times \begin{bmatrix} E&F\\ G&H \end{bmatrix} = \begin{bmatrix} A \times E + B \times F & A \times G + B \times H \\ C \times E + D \times F & C \times G + D \times H \end{bmatrix}$$  
  
## Questions  
1. Find the values of $a,b,c$ and $d$ such that $$\begin{bmatrix} 1&a\\3&7 \end{bmatrix} + \begin{bmatrix} -2&4\\ b&-5 \end{bmatrix} = \begin{bmatrix} c&1\\-2&d \end{bmatrix}$$  
$\begin{bmatrix} -2+ab  & 4-5a \\ -6+3b & 12-35 \end{bmatrix} = \begin{bmatrix} c & 1 \\ -2 & d \end{bmatrix}$  
$d=-13$  
$a=\frac{3}{5}$  
$b=\frac{4}{3}$  
$c=-\frac{6}{5}$  
  
## Simultaneous equations to matrices  
a.   
$x+7y=-5$  
$3x-y=29$  
$\begin{bmatrix} 1 & 7 \\ 3&-1 \end{bmatrix} \begin{bmatrix} x\\ y \end{bmatrix} = \begin{bmatrix} -5 \\ 29 \end{bmatrix}$  
  
To solve:  
$A^{-1} \times A = A^{-1} \times \begin{bmatrix} -5\\29 \end{bmatrix}$  
$\begin{bmatrix} \frac{1}{22} & \frac{7}{22} \\ \frac{3}{22} & -\frac{1}{22} \end{bmatrix} \begin{bmatrix} 1 & 7 \\ 3 & -1 \end{bmatrix} \begin{bmatrix} x \\ y \end{bmatrix} = \begin{bmatrix} -5\\29 \end{bmatrix} \begin{bmatrix} \frac{1}{22} & \frac{7}{22} \\ \frac{3}{22} & -\frac{1}{22} \end{bmatrix}$  
  
## Practice questions  
1. $\begin{pmatrix} 4&-1 \\ 2&3 \end{pmatrix} \begin{pmatrix} x \\ y \end{pmatrix} = \begin{pmatrix} 11 \\ -5 \end{pmatrix}$  
$\begin{pmatrix} \frac{3}{14}&\frac{1}{14}  \\ \frac{-2}{14}&\frac{4}{14} \end{pmatrix} \times \begin{pmatrix} 11 \\ -5 \end{pmatrix} = \begin{pmatrix} x \\ y \end{pmatrix}$  
$x=2 \qquad y=-3$  
  
2. $\begin{pmatrix} 4&6 \\ -8&3 \end{pmatrix} \begin{pmatrix} x \\ y \end{pmatrix} = \begin{pmatrix} 1 \\ 3 \end{pmatrix}$  
$\begin{pmatrix} \frac{1}{20}&\frac{-1}{10}  \\  \frac{2}{15} & \frac{1}{15} \end{pmatrix} \times \begin{pmatrix} 1 \\ 3 \end{pmatrix} = \begin{pmatrix} x \\ y \end{pmatrix} = \begin{pmatrix} \frac{-1}{4}  \\  \frac{1}{3} \end{pmatrix}$  
$x=\frac{-1}{4} \qquad \frac{1}{3}$  
  
## Calculations with matrices  
  
|           | March | April | May  |  
| --------- | ----- | ----- | ---- |  
| London    | 0.32  | 0.3   | 0.29 |  
| Edinburgh | 0.38  | 0.33  | 0.37 |  
| Cardiff   | 0.42  | 0.37  | 0.36 |  
| Belfast   | 0.45  | 0.38  | 0.38 |  
$A=\begin{bmatrix} 0.32&0.3&0.29\\0.38&0.33&0.37\\0.42&0.37&0.36\\0.45&0.38&0.38 \end{bmatrix}$  
$x=\begin{bmatrix} 31\\30\\31 \end{bmatrix}$  
$Ax=\begin{bmatrix} 0.32&0.3&0.29\\0.38&0.33&0.37\\0.42&0.37&0.36\\0.45&0.38&0.38 \end{bmatrix}x=\begin{bmatrix} 31\\30\\31 \end{bmatrix} = \begin{bmatrix} 27.91 \\ 33.15 \\ 35.28 \\ 37.13 \end{bmatrix}$  
So we can expect a total of 28 days in London, 33 days in Edinburgh, 35 days in Cardiff and 37 days in Belfast  
  
## Questions  
4. Solve these equations to find the possible values of x  
a.   
$\begin{bmatrix} 3 & x & -2 \\ 4&0&0 \end{bmatrix} \begin{bmatrix} 1&1\\5x&0\\ x&5 \end{bmatrix} = \begin{bmatrix} 6&-7\\4&4 \end{bmatrix}$  
$\begin{bmatrix} 3+5x^2-2x & -7 \\ 4 & 4 \end{bmatrix} = \begin{bmatrix} 6&-7\\4&4 \end{bmatrix}$  
$5x^2-2x-3=0$  
$x=1,-0.6$  
  
b.   
$\begin{bmatrix} 7&x&4 \end{bmatrix} \begin{bmatrix} x&3&0 \\ x&0&2 \\ 5&-1&x \end{bmatrix} = \begin{bmatrix} 10&17&6x \end{bmatrix}$  
$\begin{bmatrix} 7x+x^2+20 & 21-4 & 2x+4x \end{bmatrix}$  
$x^2+7x+20=10$  
$x^2+7x+10=0$  
$x=-2,-5$  
  
c.   
$\begin{bmatrix} 5&x \\ -x&-5 \end{bmatrix}^2 = 16 \begin{bmatrix} 1&0\\0&1 \end{bmatrix}$  
$\begin{bmatrix} 25-x^2 & 5x+-5x \\ -5x+5x&-x^2+25 \end{bmatrix} = \begin{bmatrix} 16 & 0 \\ 0&16 \end{bmatrix}$  
  
## [[./Calculus/Proof by induction|Proof by induction]]  
Prove by induction that $\begin{bmatrix} 1&0\\2&1 \end{bmatrix}^n = \begin{bmatrix} 1&0\\2n&1 \end{bmatrix}$ for all positive integers $n$  
Let $n=1$  
$$ \begin{bmatrix} 1&0\\2&1 \end{bmatrix}^1=\begin{bmatrix} 1&0\\2 \times 1&1 \end{bmatrix} = \begin{bmatrix} 1&0\\2&1 \end{bmatrix} $$  
Assume true for $n=k$  
$$ \begin{bmatrix} 1&0\\2&1 \end{bmatrix} ^k = \begin{bmatrix} 1&0\\2k&1 \end{bmatrix} $$  
Prove true for $n=k+1$  
$$ \begin{bmatrix} 1&0\\2&1 \end{bmatrix} ^k \begin{bmatrix} 1&0\\2&1 \end{bmatrix} = \begin{bmatrix} 1&0\\2k&1 \end{bmatrix} \begin{bmatrix} 1&0\\2&1 \end{bmatrix} $$  
$$ = \begin{bmatrix} 1&0\\2k+2&1 \end{bmatrix} $$  
$$= \begin{bmatrix} 1&0\\2(k+1)&1 \end{bmatrix} $$  
1. Prove by induction that $$ \begin{bmatrix} 5&4\\0&1 \end{bmatrix} ^n = \begin{bmatrix} 5^n&5^n-1 \\ 0&1 \end{bmatrix} $$ for all positive integers $n$  
Let $n=1$ $$\begin{bmatrix} 5&4\\0&1 \end{bmatrix}^1 = \begin{bmatrix} 5^1&5^1-1\\0&1 \end{bmatrix} = \begin{bmatrix} 5&4\\0&1 \end{bmatrix} $$  
Assume true for $n=k$ $$\begin{bmatrix} 5&4\\0&1 \end{bmatrix} ^k = \begin{bmatrix} 5^k&5^k-1\\0&1 \end{bmatrix} $$  
Prove true for $n=k+1$ $$\begin{bmatrix} 5&4\\0&1 \end{bmatrix} ^{k+1} = \begin{bmatrix} 5^k&5^k-1\\0&1 \end{bmatrix} \begin{bmatrix} 5&4\\0&1 \end{bmatrix} = \begin{bmatrix} 5 \times 5^k&4 \times 5^k + 5^k-1\\0&1 \end{bmatrix}  = \begin{bmatrix} 5^{k+1}&5 \times5^k-1 \\ 0&1 \end{bmatrix}  = \begin{bmatrix} 5^{k+1}&5^{k+1} \\ 0&1 \end{bmatrix} $$  
  
## Transformations  
  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
\draw (0,-4) -- (0,4);  
\draw (-4,0) -- (4,0);  
\draw[color=red] (0,0) rectangle (1,1);  
\node[color=green!50!red] at (0,1) {\large X};  
\node[color=green!50!red] at (1,0) {\large X};  
  
\end{tikzpicture}  
\end{document}  
```  
  
The yellow crosses represent the coordinates of the unit square that are transformed.  
E.g. a reflection in the line $y=x$ would transform $\begin{bmatrix} 1&0 \\ 0&1 \end{bmatrix}$ to $\begin{bmatrix} 0&1 \\ 1&0 \end{bmatrix}$  
  
1. $\begin{bmatrix} 0&1\\1&0 \end{bmatrix}$  
2. $\begin{bmatrix} \cos30&-\sin30 \\ \sin30&\cos30 \end{bmatrix}$  
3. $\begin{bmatrix} 5&0\\0&5 \end{bmatrix}$  
4. $\begin{bmatrix} 1&0\\0&4 \end{bmatrix}$  
c. $\begin{bmatrix} 0&1\\1&0 \end{bmatrix} \times \begin{bmatrix} 1&0\\0&k \end{bmatrix}$  
$= \begin{bmatrix} 0&k\\1&0 \end{bmatrix}$  
$\begin{bmatrix} 1&0\\0&k \end{bmatrix} \times \begin{bmatrix} 0&1\\1&0 \end{bmatrix}$  
$= \begin{bmatrix} 0&1\\ k&0 \end{bmatrix}$  
$\therefore$ order does matter  
  
# Area of a transformed shape  
$$\begin{bmatrix} a&b \\ c&d \end{bmatrix} \times \begin{bmatrix} 0&1&0&1 \\ 0&0&1&1 \end{bmatrix} = \begin{bmatrix} 0&a&b&a+b  \\ 0&c&d&c+d \end{bmatrix}$$  
  
  
  
```tikz  
\begin{document}  
\begin{tikzpicture}[scale=3]  
  
\draw[line width = 0.5mm] (0,0) -- (3,0);  
\draw[line width = 0.5mm] (0,0) -- (0,3);  
\draw[color=red]  
	(0,0) -- (0,1) node {X}  
	(0,1) -- (1,1) node {X}  
	(1,1) -- (1,0) node {X}  
	(1,0) -- (0,0) node {X};  
\draw[color=blue]  
	(0,0) -- (2,0.5) node {X}  
	(2,0.5) -- (2.5,2.5) node {X}  
	(2.5,2.5) -- (0.5,2) node {X}  
	(0.5,2) -- (0,0) node {X};  
\node[color=green] at (0.5,0.5) {\huge 1};  
\node[color=green] at (2.25,0.25) {\large bc};  
\node[color=green] at (0.25,2.25) {\large bc};  
\node[color=green] at (0.75,2.25) {\large $\frac{1}{2}$ ac};  
\node[color=green] at (1.75,0.25) {\large $\frac{1}{2}$ ac};  
\node[color=green] at (0.25,1.75) {\large $\frac{1}{2}$ bd};  
\node[color=green] at (2.25,0.75) {\large $\frac{1}{2}$ bd};  
\draw[color=green]  
	(0,0) -- (0,2.5)  
	(0,2.5) -- (2.5,2.5)  
	(2.5,2.5) -- (2.5,0)  
	(2.5,0) -- (0,0)  
	(2,0) -- (2,0.5)  
	(2,0.5) -- (2.5,0.5)  
	(0.5,2.5) -- (0.5,2)  
	(0,2) -- (0.5,2);  
\draw[dashed, color=red!50!blue]  
	(2,0.5) -- (2,0) node[below] {a}  
	(2.5,0.5) -- (0,0.5) node[left] {c}  
	(2.5,2.5) -- (2.5,0) node[below] {a+b}  
	(0.5,2.5) -- (0.5,0) node[below] {b}  
	(0.5,2) -- (0,2) node[left] {d}  
	(2.5,2.5) -- (0,2.5) node[left] {c+d};  
  
\end{tikzpicture}  
\end{document}  
```  
Area of the blue quadrilateral = $(a+b)(c+d)-\frac{1}{2}ac - \frac{1}{2} ac - 2bc - \frac{1}{2}bd - \frac{1}{2}bd$  
$= ac+ad+bc+bd-ac-2bc-bd$  
$= ad-bc$  
  
>[!tip] Matrices rules  
>$$\text{det} \begin{bmatrix} a&b \\ c&d \end{bmatrix} = \left| \begin{matrix} a&b \\ c&d \end{matrix} \right| = ad-bc$$  
>$$\text{det} AB = \text{det} A \times \text{det} B$$  
>$$\text{det} (A^{-1}) = \frac{1}{\text{det}A}$$  
>---  
>If $$A=\begin{bmatrix} a&b \\ c&d \end{bmatrix} \qquad A^{-1} = \frac{1}{\text{det}A}\begin{bmatrix} d&-b \\ -c&a \end{bmatrix}$$  
  
  
  
  
  
# Invariant lines  
## Questions  
1. $\begin{bmatrix} 4&-1 \\ 3&0 \end{bmatrix} \begin{bmatrix} x \\ y \end{bmatrix} = \begin{bmatrix} x \\ y \end{bmatrix}$  
$\begin{bmatrix} 4-1 & -1  \\ 3&0-1 \end{bmatrix} \begin{bmatrix} x \\ y \end{bmatrix}= 0$  
$\begin{bmatrix} 3x-y \\ 3x-y \end{bmatrix} = 0$  
Invariant line is $y=3x$  
  
2. a. $\begin{bmatrix} -2&3 \\ -3&4 \end{bmatrix}\begin{bmatrix} x \\ y \end{bmatrix}=\begin{bmatrix} x \\ y \end{bmatrix}$  
$-2x+3y=x \qquad x=y$  
$-3x+4y=y \qquad x=y$  
b. points on the line must map onto points on the line, $\therefore \begin{bmatrix} x \\ x+c \end{bmatrix}$  
Transform using $T$ - $\begin{bmatrix} -2&3 \\ -3&4 \end{bmatrix}\begin{bmatrix} x \\ x+c \end{bmatrix} = \begin{bmatrix} -2x+3(x+c) \\ -3x+4(x+c) \end{bmatrix}$  
$=\begin{bmatrix} x+3c \\ x+4c \end{bmatrix}$  
  
  
  
  
# Vectors  
A vector has direction and magnitude  
position vectors in 2d are classified by a $2 \times 1$ order matrix  
  
>[!tip] The equation for a line is  
>$$\underline{r} =\overset{\longrightarrow}{OA} + \lambda \overset{\longrightarrow}{AB}$$  
>OR  
>$$ \underline{r} = \underline{a} + \lambda(\underline{b} - \underline{a})$$  
  
>[!example] Example 1  
>Work out the vector equation of the line passing through the points with position vectors $$ \begin{pmatrix} 1 \\ -3 \\ 2 \end{pmatrix} \text{ and } \begin{pmatrix} 3 \\ 0 \\ -1 \end{pmatrix}$$  
>>[!formula] Working out  
>>First, find a vector in the direction of the line.   
>>$\begin{pmatrix} 3 \\ 0 \\ -1 \end{pmatrix} - \begin{pmatrix} 1 \\ -3 \\ 2 \end{pmatrix} = \begin{pmatrix} 2 \\ 3 \\ -3 \end{pmatrix}$ is parallel to the line  
>>Therefore, the equation of the line is:  
>> $$\underline{r} = \begin{pmatrix} 1 \\ -3 \\ 2 \end{pmatrix} + \lambda \begin{pmatrix} 2 \\ 3 \\ -3 \end{pmatrix}$$  
>>$$\huge{OR}$$  
>>$$\underline{r} = \begin{pmatrix} 3 \\ 0 \\ -1 \end{pmatrix} + \lambda \begin{pmatrix} 2 \\ 3 \\ -3 \end{pmatrix}$$  
  
>[!tip] Formula for a modulus  
>$$|\underline{b}| = \sqrt{x_2^2 + y_2^2}$$  
>$$|\underline{a}| = \sqrt{x_1^2+y_1^2}$$  
>$$|\underline{b} - \underline{a}| = \sqrt{(x_2-x_1)^2+(y_2-y_1)^2}$$  
# AI notes  
## What are Matrices?  
  
Matrices are rectangular arrays of numbers, symbols, or expressions arranged in rows and columns. They are fundamental in linear algebra and have applications across many scientific and engineering disciplines.  
  
**Formally:** A matrix *A* of size *m x n* (read as "m by n") has *m* rows and *n* columns.  Each element in the matrix is identified by its row and column index (e.g.,  *a<sub>ij</sub>* is the element in the *i*th row and *j*th column).  
  
**Example:**  
  
```  
A = | 1  2  3 |  
    | 4  5  6 |  
  
This is a 2x3 matrix.  
```  
  
## Key Concepts  
  
*   **Elements:**  The individual numbers or symbols within the matrix.  
*   **Rows:** Horizontal lines of elements.  
*   **Columns:** Vertical lines of elements.  
*   **Dimensions:**  The size of the matrix, given as rows x columns (e.g., 2x3).  
*   **Square Matrix:** A matrix where the number of rows equals the number of columns (m = n).  
*   **Identity Matrix:**  A square matrix with 1s on the main diagonal (from top-left to bottom-right) and 0s elsewhere.  Often denoted as *I*.  
  
    ```  
    I = | 1  0  0 |  
        | 0  1  0 |  
        | 0  0  1 |  
  
    This is a 3x3 Identity Matrix.  
    ```  
*   **Zero Matrix:** A matrix where all elements are 0.  
  
## Basic Matrix Operations  
  
*   **Addition:** Matrices can be added if they have the same dimensions.  Addition is performed element-wise.  
*   **Subtraction:** Similar to addition, requires matching dimensions.  Performed element-wise.  
*   **Scalar Multiplication:** Multiplying a matrix by a scalar (a single number).  Each element in the matrix is multiplied by the scalar.  
*   **Matrix Multiplication:** A more complex operation. For matrix multiplication *A* x *B* to be possible, the number of columns in *A* must equal the number of rows in *B*.  The resulting matrix will have the dimensions (rows of *A*) x (columns of *B*).  
*   **Transpose:**  The transpose of a matrix, denoted as *A<sup>T</sup>*, is obtained by swapping its rows and columns.  
*   **Determinant:** A scalar value calculated from a square matrix.  It provides information about the matrix's properties and invertibility.  
*   **Inverse:**  The inverse of a square matrix *A*, denoted as *A<sup>-1</sup>*, is a matrix such that *A* x *A<sup>-1</sup>* = *I* (the identity matrix). Only square matrices with non-zero determinants have inverses.  
  
## Applications  
  
Matrices are used extensively in:  
  
*   **Linear Algebra:** Solving systems of linear equations, finding eigenvalues and eigenvectors, and performing linear transformations.  
*   **Computer Graphics:** Representing transformations (rotation, scaling, translation) of objects in 3D space.  
*   **Physics:** Describing physical systems, such as quantum mechanics and classical mechanics.  
*   **Engineering:**  Analyzing structures, controlling systems, and processing signals.  
*   **Data Science:** Representing data, performing data analysis, and building machine learning models.  
*   **Cryptography:**  Encoding and decoding messages.  
  
## Further Exploration  
  
*   Linear Algebra textbooks  
*   Khan Academy Linear Algebra course  
*   Online matrix calculators (e.g., on Wolfram Alpha)  
*   Specific applications in your field of interest.  
  
# Questions  
  
$3A-2B = 3\begin{pmatrix} 2 & 0 \\ -3 & a \end{pmatrix} - 2\begin{pmatrix} 0 & 2 \\ a & -4 \end{pmatrix} = \begin{pmatrix} 6 & 0 \\ -9 & 3a \end{pmatrix} - \begin{pmatrix} 0 & 4 \\ 2a & -8 \end{pmatrix}$  
$= \begin{pmatrix} 6 & -4 \\ -9-2a & 3a-8 \end{pmatrix}$  
  
$AB^2 = \begin{pmatrix} 2 & 0 \\ -3 & a \end{pmatrix}\begin{pmatrix} 0 & 2 \\ a & -4 \end{pmatrix}\begin{pmatrix} 0 & 2 \\ a & -4 \end{pmatrix}$  
$= \begin{pmatrix} 0 & 4 \\ a^2 & -6-4a \end{pmatrix}\begin{pmatrix} 0 & 2 \\ a & -4 \end{pmatrix}$  
$= \begin{pmatrix} 0+4a & -16 \\ a(-6-4a) & 2a^2 -4(-6-4a) \end{pmatrix}$  
  
## Questions further  
$l_1=\begin{pmatrix} 2 \\ -1 \\ -8 \end{pmatrix} + s \begin{pmatrix} 4 \\ 2 \\ -k \end{pmatrix}$  
$l_2 = \begin{pmatrix} 3 \\ -k \\ t \end{pmatrix} + t \begin{pmatrix} -12 \\ -6 \\ 3k \end{pmatrix}$  
  
# The distance between two lines  
>[!formula]  
>$$ \huge{\left|\frac{d_1 \times d_2}{|d_1 \times d_2|} \space \dot \space \space (a_1-a_2)\right|}$$  
>Where we use the cross product instead of multiplication  
  
>[!example]  
>  
>  
>### **Step 1: Understand the problem**  
We're given two skew lines $L_1$ and $L_2$, which means these lines don't intersect and aren't parallel. The task is to calculate the shortest distance between them.  
>  
>#### Line $L_1$:  
> - The equation is given in symmetric form:  
>$$frac{x - 2}{3} = \frac{y + 4}{8} = \frac{4z - 5}{5}$$  
  From this form, we know:  
 > - A **point** on $L_1$ is $\mathbf{r_1} = \begin{pmatrix} 2 \\ -4 \\ \frac{5}{4} \end{pmatrix}$ (obtained by considering values of $x, y, z$ that satisfy the equation).  
 > - The **direction vector** of $L_1$ is $\mathbf{d_1} = \begin{pmatrix} 3 \\ 8 \\ 5 \end{pmatrix}$ (derived from the denominators in the symmetric form).  
>  
>#### Line $L_2$:  
> - The equation is:  
  $$\left( \mathbf{r} - \begin{pmatrix} -2 \\ 0 \\ 3 \end{pmatrix} \right) \times \begin{pmatrix} 2 \\ 1 \\ 3 \end{pmatrix} = 0$$  
>  
  >This means:  
 > - A **point** on $L_2$ is  $\mathbf{r_2} = \begin{pmatrix} -2 \\ 0 \\ 3 \end{pmatrix}$ (explicitly given).  
 > - The **direction vector** of $L_2$ is $\mathbf{d_2} = \begin{pmatrix} 2 \\ 1 \\ 3 \end{pmatrix}$ (as indicated by the vector used in the cross-product condition).  
>  
> ---  
>  
>### **Step 2: Use the formula for the shortest distance**  
The shortest distance $d$ between two skew lines is:  
>  
>$$d = \frac{| (\mathbf{r_2} - \mathbf{r_1}) \cdot (\mathbf{d_1} \times \mathbf{d_2}) |}{\| \mathbf{d_1} \times \mathbf{d_2} \|}$$  
>  
This formula works because the shortest distance between skew lines is along the common perpendicular to both lines.  
>  
> ---  
>  
###**Step 3: Compute $\mathbf{r_2} - \mathbf{r_1}$**  
Subtract the position vectors of the points on $L_1$ and $L_2$:  
>  
>$$\mathbf{r_2} - \mathbf{r_1} = \begin{pmatrix} -2 \\ 0 \\ 3 \end{pmatrix} - \begin{pmatrix} 2 \\ -4 \\ \frac{5}{4} \end{pmatrix} = \begin{pmatrix} -4 \\ 4 \\ \frac{7}{4} \end{pmatrix}$$  
> ---  
>  
> ### **Step 4: Find $\mathbf{d_1} \times \mathbf{d_2}$ (cross product)**  
>The cross product of the direction vectors $\mathbf{d_1} = \begin{pmatrix} 3 \\ 8 \\ 5 \end{pmatrix}$ and $\mathbf{d_2} = \begin{pmatrix} 2 \\ 1 \\ 3 \end{pmatrix}$ is calculated as:  
>  
>$$\mathbf{d_1} \times \mathbf{d_2} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ 3 & 8 & 5 \\ 2 & 1 & 3 \end{vmatrix}$$  
Expanding the determinant:  
>  
>$$\mathbf{d_1} \times \mathbf{d_2} = \begin{pmatrix} 8 \times 3 - 5 \times 1 \\ 5 \times 2 - 3 \times 3 \\ 3 \times 1 - 8 \times 2 \end{pmatrix} = \begin{pmatrix} 24 - 5 \\ 10 - 9 \\ 3 - 16 \end{pmatrix} = \begin{pmatrix} 19 \\ 1 \\ -13 \end{pmatrix}$$  
>---  
>  
>### **Step 5: Find  $\| \mathbf{d_1} \times \mathbf{d_2} \|$**  
The magnitude of the cross product vector $\mathbf{d_1} \times \mathbf{d_2} = \begin{pmatrix} 19 \\ 1 \\ -13 \end{pmatrix}$ is:  
>$$\| \mathbf{d_1} \times \mathbf{d_2} \| = \sqrt{19^2 + 1^2 + (-13)^2} = \sqrt{361 + 1 + 169} = \sqrt{531}$$  
>  
> ---  
>  
>### **Step 6: Compute $(\mathbf{r_2} - \mathbf{r_1}) \cdot (\mathbf{d_1} \times \mathbf{d_2})$**  
>Take the dot product between $\mathbf{r_2} - \mathbf{r_1} = \begin{pmatrix} -4 \\ 4 \\ \frac{7}{4} \end{pmatrix}$ $and$ $\mathbf{d_1} \times \mathbf{d_2} = \begin{pmatrix} 19 \\ 1 \\ -13 \end{pmatrix}$:  
>  
>$$(\mathbf{r_2} - \mathbf{r_1}) \cdot (\mathbf{d_1} \times \mathbf{d_2}) = (-4)(19) + (4)(1) + \left(\frac{7}{4}\right)(-13)$$  
>  
>Simplify:  
>  
>$$= -76 + 4 - \frac{91}{4} = \frac{-304}{4} + \frac{16}{4} - \frac{91}{4} = \frac{-379}{4}$$>  
>  
>Take the absolute value:  
>$$\left| \frac{-379}{4} \right| = \frac{379}{4}$$  
>  
>  
> ---  
>  
> ### **Step 7: Compute the shortest distance**  
>Substitute everything into the formula:  
>  
>$$d = \frac{\frac{379}{4}}{\sqrt{531}} = \frac{379}{4\sqrt{531}}$$  
>  
>Simplify as needed or approximate numerically.  
  
