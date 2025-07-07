---
tags:
  - Undone
  - Maths
  - Proof
date: 2025-02-11
---
---  
# Setting up  
The three key steps to a proof by induction are:  
1. Prove the statement is true for $n=1$  
2. Assume the statement is true for n=k and use this to prove the statement is true for $n=k+1$  
3. Write a conclusion  
  
# Example  
Prove by induction that $$ \sum ^n _{r=1} 4^{r-1}=\frac{1}{3}(4^n-1)$$ for all $n \in \mathbb{N}$  
  
$n=1$  
$$ \sum ^1 _{r=1} 4^{r-1} = 4^0 = 1$$  
$$ \frac{1}{3}(4^1-1) = \frac{4-1}{3} = 1$$  
So it is true for $n=1$  
  
Assume for $n=k$  
  
$$\sum ^k _1 4^{r-1} = \frac{1}{3}(4^k-1)$$  
Prove true for $n=k+1$  
$$\sum ^{k+1} _1 4^{r-1} = \sum ^k _1 4^{r-1} + 4 ^{k+1-1}$$  
$$ \frac{1}{3} (4^k-1) +4^k$$  
$$=\frac{4^k-1}{3}+\frac{3 \times 4^k}{3} = \frac{4^k+3 \times 4^k-1}{3}$$  
$$\sum ^{k+1} _1 4^{r-1} = \frac{4^1+4^k-1}{3} = \frac{1}{3} (4^{k+1}-1)$$  
So the statement is true when $n=k+1$  
  
The statement is true for $n=1$ and by assuming it is true for $n=k$ it is shown to be true for $n=k+1$  
Therefore, by mathematical induction, it is true for all $n \in \mathbb{N}$  
  
  
# Example 2  
Prove by induction that $$\sum ^n _{r=1}r^2=\frac{1}{6} n (n+1) (2n+1)$$ for all $n \in \mathbb{N}$  
  
$n=1$  
$$\sum ^1 _1 r^2 = 1^2 = 1$$  
$$ \frac{1}{6} (1) (2) (3) = 1$$  
True for n=1  
  
Assume it is true for $n=k$  
$$\sum ^k _1 r^2 = \frac{k}{6}(k+1)(2k+1)$$  
Prove true for $n=k+1$  
$$\sum ^{k+1} _1 r^2 = \sum ^k _1 r^2+(k+1)^2$$  
$$ \frac{k(k+1)(2k+1)}{6} + \frac{6 \times (k+1)^2}{6}$$  
$$=\frac{k+1}{6}(k(2k+1)+6(k+1))$$  
$$=\frac{(k+1)}{6}(2k^2+k+6k+6)$$  
$$=\frac{(k+1)}{6}(2k^2+7x+6)$$  
$$=\frac{(k+1)(k+2)(2k+3)}{6}$$  
$$=\frac{(k+1)(k+1+1)(2(k+1)+1)}{6}$$  
The statement is true for n=1 and by assuming it is true for $n=k$ it is shown to be true for $n=k+1$.   
Therefore, by mathematical induction, it is true for all $n \in \mathbb{N}$  
  
# Practice  
1. Prove by induction to prove that $$ \sum ^r _{r=1} r = \frac{1}{2} n(n+1)$$for all $n \in \mathbb{N}$  
  
Prove for 1  
$$ \sum ^1 _1 r = 1$$  
$$ \frac{1}{2} \times 1 \times (1+1) = 1$$  
True for n=1  
Assume true for $n=k$  
  
$$\sum ^k _1 r = \frac{1}{2}k(k+1)$$  
Prove true for $n=k+1$  
$$\sum ^{k+1} _1 r = \sum ^k _1 r + (k+1)$$  
$$ = \frac{1}{2} (k)(k+1) + (k+1)$$  
$$=\frac{k(k+1)}{2}+\frac{2(k+1)}{2}$$  
$$=\frac{(k+1)(k+2)}{2}$$  
$$= \frac{1}{2} (k+1)(k+1)$$  
Which is what you get when you sub in $n=k+1$ into $\frac{1}{2}n(n+1)$  
  
The statement is true for $n=1$ and by assuming it is true for $n=k$ it is shown to be true for $n=k+1$  
Therefore, by mathematical induction, it is true for all $n \in \mathbb{N}$  
  
# Proof by induction - Multiples  
Prove that $n^3+2n$ is divisible by 3 for all $n \in \mathbb{N}$  
$n=1$  
$1^3+2 \times 1 = 3 = 1 \times 3$  
$\therefore \text{true for} \space n=1$  
Assume true for $n=k$  
$k^3+2k=3A$  
Prove true for $n=k+1$  
$(k+1)^3+2(k+1)$  
$=k^3+3k^2+3k+1+2k+2$  
$=k^3+3k^2+5k+3$  
$=k^3+2k+3k^2+3k+3$  
$=3A+3(k^2+k+1)$  
$=3(A+k^2+k+1)$  
  
The statement is true for n=1, and by assuming theh statement is true for n=k, it is shown to be true for n=k+1. Therefore, by mathematical induction, the statement is true for all $n \in \mathbb{N}$  
  
1. Use proof by induction to prove these statements for all $n \in \mathbb{N}$  
a. $n^2+3n$ is divisible by 2  
$n=1$  
$1^2+3 \times 1 = 4 = 2(2)$  
$\therefore \text{it is divisible by 2}$  
Assume true for $n=k$  
$k^2+3k=2A$  
Prove true for $n=k+1$  
$(k+1)^2 +3(k+1)$  
$=k^2+2k+1+3k+3$  
$=k^2+3k+2k+4$  
$=2A+2k+4$  
$=2(A+k+2)$  
$\therefore \text{all values of n are divisible by 2}$  
  
$$ \begin{bmatrix} 1 & 1 & 1 \\ 1 & 1 & 1 \\ 1 & 1 & 1 \end{bmatrix} \times \begin{bmatrix} 1 & 1 & 1 \\ 1 & 1 & 1 \\ 1 & 1 & 1 \end{bmatrix} = \begin{bmatrix} 1+1+1 & 1+1+1 & 1+1+1 \\ 1+1+1 & 1+1+1 & 1+1+1 \\ 1+1+1 & 1+1+1 & 1+1+1 \end{bmatrix} = \begin{bmatrix} 3 & 3 & 3 \\ 3 & 3 & 3 \\ 3 & 3 & 3 \end{bmatrix}$$  
# Question Practice  
$$ \sum ^n _{r=1} r^2(r+1) = \frac{n(n+1)(n+2)(3n+1)}{12}$$  
Prove true for $n=1$  
$$ \sum ^1 _1 r^2(r+1) = 2$$  
$$ \frac{(1)(2)(3)(4)}{12} = \frac{24}{12} = 2$$  
Assume true for $n=k$  
$$ \sum ^k _1 r^2(r+1) = \frac{k(k+1)(k+2)(3k+1)}{12}$$  
Prove true for $n=k+1$  
$$ \sum ^{k+1} _1 r^2(r+1) = \sum ^k _1 r^2(r+1) + (k+1)^2 (k+2)$$  
$$ = \frac{k(k+1)(k+2)(3k+1)}{12} + (k+1)^2(k+2)$$  
$$ = \frac{k(k+1)(k+2)(3k+1)}{12} + \frac{12(k+1)^2(k+2)}{12}$$  
$$ = \frac{(k+1)(k+2)(k(3k+1)+12(k+1))}{12}$$  
$$= \frac{(k+1)(k+2)}{12}(k(3k+1)+12(k+1))$$  
$$= \frac{(k+1)(k+2)}{12}(3k^2+k+12k+12)$$  
$$= \frac{(k+1)(k+2)}{12}(k+3)(3k+4)$$  
$$ = \frac{(k+1)(k+2)(k+3)(3k+4)}{12}$$  
$$ = \frac{(k+1)((k+1)+1)((k+1)+2)(3(k+1)+1)}{12}$$  
So the statement is true when $n=k+1$  
  
The statement is true for $n=1$ and by assuming it is true for $n=k$ it is shown to be true for $n=k+1$  
Therefore, by mathematical induction, it is true for all $n \in \mathbb{N}$  
  
  
$$ \sum ^n _{n=1} \frac{r}{2^r} = 2-\frac{(n+2)}{2^n}$$  
Prove true for $n=1$  
$$ \sum ^1 _1 \frac{r}{2^r} = \frac{1}{2}$$  
$$ 2 - \frac{(1+2)}{2} = 2 - \frac{3}{2} = \frac{1}{2}$$  
Assume true for $n=k$  
$$\sum ^k _{r=1} \frac{r}{2^r} = 2 - \frac{(k+2)}{2^{k}}$$  
Prove true for $n=k+1$  
$$ \sum ^{k+1} _{r=1} \frac{r}{2^r} = \sum ^k _{r=1} \frac{r}{2r} + \frac{(k+1)}{2^{k+1}}$$  
$$ = 2 - \frac{k+2}{2^k} + \frac{k+1}{2^{k+1}}$$  
$$ = \frac{2^{k+1} \times 2}{2^{k+1}} - \frac{2(k+2)}{2 \times 2^k} + \frac{k+1}{2^{k+1}}$$  
$$ = \frac{2 \times 2^{k+1} - 2{k+2} + k+1}{2^{k+1}}$$  
$$ = \frac{2 \times 2^{k+1}}{2^{k+1}} + \frac{-2k-4+k+1}{2^{k+1}}$$  
$$ = 2 - \frac{(k+3)}{2^{k+1}} = 2 - \frac{(k+1)+2}{2^{(k+1)}}$$  
# Function proof  
The function $f$ is defined by   
$$f(n) = 3^{3n+1} + 2^{3n+4} \qquad (n \in \mathbb{Z} ^+)$$  
Prove by induction that $f(n)$ is divisible by 19 for $n \ge 1$  
  
Prove true for $n=1$  
$$3^{3+1}+2^{3+4} = 3^4+2^7 = 209 = 19(11) \space \therefore \space \text{it is divisible by 19}$$  
Assume true for $n=k$  
$$ 3^{3k+1}+2^{3k+4} = 19A$$  
Prove true for $n=k+1$  
$$ 3^{3(k+1)+1}+2^{3(k+1)+4}$$  
$$ = 3^{3k+4} + 2^{3k+7}$$  
$$ = 3^{3k} \times 3^4 + 2^{3k} \times 2^7$$  
$$ = 3^{3k+1} \times 3^3 + 2^{3k+4} \times 2^3$$  
$$ = 27 \times 3^{3k+1} + 8 \times 2^{3k+4}$$  
