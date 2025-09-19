---
tags:
  - Maths
  - Pure
date: 2025-01-30
---
---  
# Sum of n terms  
$s_n=1+2+3 . . . (n-2)+(n-1)+n$  
$s_n=n+(n-1)+(n-2)...3+2+1$  
$2s_n=(n+1)+(n+1)+(n+1)...(n+1)$  
$2s_n=n(n+1)$  
$s_n=\frac{n(n+1)}{2}$  
$$\sum ^{r=n} _{r=1}r=\sum^n_1r=\frac{n(n+1)}{2}$$  
  
# Summations  
$$ \sum ^n _{r=1}1 = n$$  
$$ \sum ^n _{r=1} r = \frac{1}{2} n(n+1)$$  
$$\sum^n_{r=1}r^2=\frac{1}{6}n(n+1)(2n+1)$$  
$$\sum^n_{r=1}r^3=\frac{1}{4}n^2(n+1)^2$$  
# Put into practice  
4 terms of $r^2$  
$1^2 +2^2 +3^2 +4^2=$  
$1+4+9+16=30$  
$$ \sum ^4 _{r=1} r^2 = \frac{1 \times 4(5)(9)}{6} = 30$$  
  
6 terms of $r^3$  
$1^3+2^3+3^3+4^3+5^3+6^3=441$  
$$ \sum ^6 _1 r^3 = \frac{6^2 \times 7^2}{4} = \frac{36 \times 49}{4} = 441$$  
$$ \sum ^5 _1 1 = 5$$  
$$ \sum ^n _1 1 = n$$  
$$\sum ^n _4 r = \sum ^n _1 r - \sum ^3 _1 r$$  
Evaluate $$ \sum ^n _5 r(r+4)$$  
$$ \sum ^n _5 (r^2+4r) $$$$= \sum ^n _5 r^2 +4 \sum ^n _5 r$$  
$$= \sum ^{n} _{1}r^2 + 4\sum ^{n} _{1}r-\sum ^{4} _{1}r^2-4\sum ^{4} _{1}r$$  
$$=\frac{n(n+1)(2n+1)}{6} + \frac{4n(n+1)}{2} - \frac{4 \times 5 \times 9}{6} - \frac{4 \times 4 \times 5}{2} $$  
  
How many terms are in the series $$ \sum  ^{3n}_{1} (r^2-r+3)$$  
3n terms  
  
b. write and simplify the $(2n+1)th$ term  
$(2n^2+1)^2-(2n+1)+3$  
$=4n^2+4n+1-2n-1+3$  
$=4n^2+2n+3$  
  
c. find the sum of the first 3n terms  
  
$$ \sum ^{3n}_{1}r^2- \sum ^{3n} _1 r +3\sum ^{3n} _1 1$$  
$$ = \frac{3n(3n+1)(6n+1)}{6} - \frac{3n(3n+1)}{2} +9n $$  
$$ = \frac{n(3n+1)(6n+1)}{2} - \frac{3n(3n+1)}{2} + \frac{18n}{2}$$  
$$ = \frac{n}{2}((3n+1)(6n+1)-3(3n+1)+18)$$  
$$ = \frac{n}{2} (18n^2+9n+1-9n-3+18)$$  
$$ = \frac{n}{2} (18n^2+16)$$  
$$ = 9n^2 + 8$$  
1. Find the sum of these series  
	1. $1+2+3+...+3n$  
	$$ \sum ^{3n} _1 r = \frac{n(n+1)}{2} = \frac{3n(3n+1)}{2} = \frac{9n^2+3n}{2}$$  
	2. $1^2+2^2+3^2+...+(2n-1)^2$  
	$$ \sum ^{2n-1} _1 r^2 = \frac{n(n+1)(2n+1)}{6} = \frac{(2n-1)(2n)(2(2n-1)+1)}{6} = \frac{(4n^2-2n)(4n-1)}{6} = \frac{4n^3-4n^2-8n^2+2n}{6} = \frac{4n^3+12n^2+2n}{6}$$  
	3.  $1^3 +2^3 +3^3 +...+(2n-1)^3$  
	$$ \sum ^{2n-1} _1 r^3 = \frac{(2n-1)^2((2n-1)+1)^2}{4} = \frac{(4n^2-4n+1)(4n^2)}{4} = \frac{16n^4-16n^2+4n^2}{4}$$  
	4.  $1+3+5+...+(2n-1)$  
	$$ \sum ^n _1 (2r-1) = 2\sum ^n _1 r - \sum ^n _1 1 = 2\frac{(n(n+1))}{2}-n = n^2+n-1 = n^2$$  
  
# Exam questions  
$$ \sum ^n _1 r(r+3) = \sum ^n _1 r^2+3r = \sum ^n _1 r^2 + 3 \sum ^n _1 r = \frac{n(n+1)(2n+1)}{6} + 3(\frac{n(n+1)}{2}) = \frac{(n^2+n)(2n+1)}{6} + \frac{3n^2+3n}{2} = \frac{2n^3+3n^2+n}{6} +\frac{9n^2+9n}{6} = \frac{2n^3+12n^2+10n}{6} = \frac{n^3+6n^2+5n}{3}$$  
$$ = \frac{1}{3} n(n^2+6n+5) = \frac{1}{3} n(n+1)(n+5)$$  
  
b. $$ \frac{1}{3} 5n(5n+1)(5n+5) - \frac{1}{3} (n)(n+1)(n+5) = \frac{1}{3} 5n(25n^2+30n+5) - \frac{1}{3} (n)(n^2+6n+5) = \frac{1}{3} 125n^3+150n^2+25n - \frac{1}{3} (n^3+6n^2+5n)$$  
$$= \frac{125n^3+150n^2+25n-n^3-6n^2-5n}{3} = \frac{124n^3+144n^2+20n}{3}$$  
  
a. simplify $(2r+1)^3-(2r-1)^3$  
$=8r^3+12r^2+6r+1-(8r^2-12r^2+6r-1) = 24r^2+2$  
b. Hence, use the method of differences to show that $$ \sum ^n _1 r^2 = \frac{n(n+1)(2n+1)}{6}$$  
$24r^2+2=(2r+1)^3-(2r-1)^3$  
$r^2 = \frac{1}{24} ((2r+1)^3-(2r-1)^3-2)$  
the sum of both sides is equal  
$$ \sum ^n _1 r^2 = \sum ^n _1 \frac{1}{24} ((2r+1)^3-(2r-1)^3-2)$$  
$r=1 \qquad \frac{1}{24} (3^3-1^3-2)$  
$r=2 \qquad \frac{1}{24} (5^3-3^3-2)$  
$r=3 \qquad \frac{1}{24} (7^3-5^3-2)$  
  
$r=n-1 \qquad \frac{1}{24} (2n-1)^3-(2n-3)^3-2$  
$r=2 \qquad \frac{1}{24} (2n+1)^3-(2n-1)^3-2$  
$= \frac{1}{24}(-1+(2n+1)^3-2n$  
$= \frac{1}{24}(-1+8n^3+12n^2+6n+1-2n)$  
$=\frac{1}{24} (8n^3+12n^2+4n)$  
$= \frac{4n}{24} (2n^2 + 3n^2 +n)$  
$= \frac{n}{6}(2n^2+3n+1) = \frac{1}{6}n(n+1)(2n+1)$  
  
$$ \sum ^9 _1 r^3 = \frac{9^2(9+1)^2}{4} = 2025$$  
$$ \sum ^{3n} _1 r + \sum ^{2n} _1 r^2 + \sum ^n _1 r^3 = 382$$  
$\frac{3n(3n+1)}{2}+\frac{2n(2n+1)(2n+2)}{6}+\frac{n^2(n+1)^2}{4}=382$  
$\frac{9n^2+3n}{2}+\frac{8n^3+10n^2+4n}{6}+\frac{n^4+2n^3+n^2}{4}=382$  
$4584=54n^2+18n+16n^3+20n^2+8n+3n^4+6n^3+3n^2$  
$3n^4+22n^3+77n^3+26n-4584=0$  
$n=4$  
i.  
  
$$ \sum ^{50} _{30} (r^3-2) = \sum ^{50} _1 (r^3-2) - \sum ^{29} _1 (r^3-2) = \sum ^{50} _1 r^3 - 2 \sum ^{50} _1 1 - \sum ^{29} _1 r^3 + 2\sum ^{29} _1 1$$  
$$ \frac{50^2 \times 51^2}{4} - 100 - \frac{29^2 \times 30^2}{4} + 58$$  
$$ 1625625-100-189225+58 = 1436358$$  
ii.   
$$ \sum ^{20} _{10} r(r-2) = \sum ^{20} _{10} r^2 - 2\sum ^{20} _{10} r = \sum ^{20} _{0} r^2 - 2\sum ^{20} _{0} r - \sum ^{10} _{0} r^2 + 2\sum ^{10} _{0} r = 164280$$  
  
## Summing Series: Techniques and Considerations  
  
Summing series involves finding the sum of an infinite or finite sequence of numbers (terms).  Different techniques apply depending on the type of series.  
  
### Arithmetic Series  
  
An arithmetic series has a constant difference between consecutive terms (common difference 'd').  
  
*   **Formula for the sum of the first n terms (Sn):**  
  
    `Sn = n/2 * [2a + (n-1)d]`  
  
    Where:  
  
    *   `n` is the number of terms  
    *   `a` is the first term  
    *   `d` is the common difference  
  
*   **Alternative Formula:**  
  
    `Sn = n/2 * (a + l)`  
  
    Where:  
  
    *   `l` is the last term  
  
### Geometric Series  
  
A geometric series has a constant ratio between consecutive terms (common ratio 'r').  
  
*   **Formula for the sum of the first n terms (Sn):**  
  
    `Sn = a * (1 - r^n) / (1 - r)`  (where r ≠ 1)  
  
    Where:  
  
    *   `n` is the number of terms  
    *   `a` is the first term  
    *   `r` is the common ratio  
  
*   **Formula for the sum to infinity (S∞):**  
  
    `S∞ = a / (1 - r)` (when |r| < 1)  
  
    This sum only exists when the absolute value of the common ratio is less than 1 (the series converges).  If |r| >= 1, the series diverges.  
  
### Telescoping Series  
  
A telescoping series is one where most of the terms cancel out, leaving only a few terms in the final sum.  Often these can be recognized by a partial fraction decomposition.  
  
*   **General Approach:**  
  
    1.  Write out the first few terms of the series.  
    2.  Observe the cancellation pattern.  
    3.  Write out the last few terms.  
    4.  Identify the terms that *don't* cancel.  
    5.  Sum the remaining terms.  
  
### Power Series  
  
A power series is an infinite series of the form:  
  
`∑ c_n (x - a)^n`  (from n=0 to infinity)  
  
Where:  
  
*   `c_n` are the coefficients  
*   `x` is a variable  
*   `a` is the center of the series  
  
*   **Convergence:**  Power series converge within a certain radius of convergence around the center `a`.  The radius of convergence (R) can be found using the ratio test or the root test.  
  
### General Strategies for Summing Series  
  
*   **Recognizing Patterns:** Look for arithmetic, geometric, or telescoping patterns.  
*   **Partial Fractions:**  Decompose rational functions into partial fractions to simplify the series (often leads to telescoping).  
*   **Calculus Techniques:**  Use integration or differentiation (term-by-term) on known power series to derive new series representations and their sums.  
*   **Special Functions:** Recognize series representations of known functions (e.g., exponential, trigonometric, logarithmic).  
*   **Ratio Test / Root Test:** Used to determine convergence, particularly for power series. These tests don't directly give you the sum but tell you *if* a sum exists.  
*   **Computer Algebra Systems (CAS):**  Tools like Mathematica, Maple, and Wolfram Alpha can be helpful for finding sums of more complex series.  
  
### Important Considerations  
  
*   **Convergence:** Always check for convergence *before* attempting to find a sum. A divergent series does not have a finite sum.  
*   **Assumptions:** Be aware of any assumptions made when applying formulas (e.g., |r| < 1 for the sum to infinity of a geometric series).  
*   **Manipulations:**  Carefully justify any manipulations of the series to ensure that the sum remains unchanged.  Reordering terms in a divergent series can change its apparent sum, which is mathematically invalid.  
  
# Using Partial fractions  
  
In order to express a function as $f(r+1)-f(r)$, you may need to use partial fractions  
  
You can decompose some functions into their partial fractions  
