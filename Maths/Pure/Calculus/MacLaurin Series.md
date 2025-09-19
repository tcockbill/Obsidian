---
tags:
  - Maths
  - Calculus
---
---  
  
#  What is a McLaurin Series?  
  
A McLaurin series is an infinite series, as a simplified version of a [[./Taylor Series|Taylor series]] that relies on a function being continuous at $0$. Its principles state that any function can be reconstructed into an infinite series, provided that enough local information exists for this to occur.  
  
  
**MOST DISCRETE MATH FUNCTIONS ARE AN EXCEPTION TO THE RULE; CONTINUITY IS AN EXCEPTION NOT A STANDARD**  
  
  
#  Definition  
A McLaurin Series is defined as being being *the infinite sum of the nth [[./Differentiable Calculus|derivative]] of f(x) evaluated at 0, multiplied by $x^n$*.  Or in mathematical notation as,   
  
$$  
M(x) = \sum\limits^{\infty}_{n=0} \frac{{f^{(n)}(0)}}{n!}\cdot x^n  
$$  
  
where $f(x)$ is continuously differentiable at 0.   
  
# Series  
>[!formula] Examples  
Some popular series include:   
$$\sin(x) = x - \frac{x^3}{3!} + \frac{x^5}{5!} - \frac{x^7}{7!} + \cdots = \sum_{n=0}^{\infty} (-1)^n \frac{x^{(2n+1)}}{(2n+1)!}$$  
$$\cos(x) = 1 - \frac{x^2}{2!} + \frac{x^4}{4!} - \frac{x^6}{6!} + \cdots = \sum_{n=0}^{\infty} (-1)^n \frac{x^{2n}}{(2n)!}$$  
$$e^x = 1 + x + \frac{x^2}{2!} + \frac{x^3}{3!} + \frac{x^4}{4!} + \cdots = \sum_{n=0}^{\infty} \frac{x^n}{n!}$$  
  
  
# Some Important Uses  
  
When substituting $ix$ into the McLaurin expansion of  $e^x$ ; we are left with both the expansion for $\cos x$ and $i\sin x$; which is a useful proof for [[../Complex Numbers/Euler's Formula|Euler's Formula]] and the concepts of [[../Complex Numbers/Polar Form|Polar Form]].  
  
## Own notes  
$f(x) = a + bx + cx^2 + dx^3 + ex^4 + fx^5 ...$    $f(0) = a$  
$f ^ \prime (x) = b +2cx + 3dx^2 + 4ex^3 + 5fx^4 ...$    $f ^ \prime (0) = b$  
$f ^{\prime \prime} (x) = 2c + 6dx +1 2ex^2 + 20fx^3...$    $f^{\prime \prime}(0) = 2c$   $\frac{f^{\prime\prime}}{2!} = c$  
$f^{\prime\prime\prime}(x)=6d+24ex+60fx^2 ...$    $f^{\prime\prime\prime}(0) = 6d$   $\frac{f^{\prime\prime\prime}}{3!} = d$  
  
  
### Definition  
$$f(x) \equiv f(0) + xf^\prime + \frac{x^2}{2!}f^{\prime\prime} (0) + ... + \frac{x^r}{r!}f^{(r)}(0) + ...$$  
### Practice  
$f(x) = e^x = a+bx+cx^2+dx^2+ex^4$  
$f(0)=e^0=1=a$  
$f^\prime(x) = e^x = b+2cx + 3dx^2 + 4ex^3 ...$  
$f^\prime(0) = e^0 = 1=b$  
$f^{\prime\prime}(x) = e^x = 3c + 6dx + 12ex^2 ...$  
$f^{\prime\prime}(0) = e^0 = 1 = 2c \Rightarrow c=\frac{1}{2}$  
$f^3(x)=e^x=6d+24ex ...$  
$f^3(0) = e^0 = 1 = 6d \Rightarrow d=\frac{1}{6}$  
  
### Conditions  
- $f(x)$ can be expanded as a **convergent** infinite series of terms  
- each of the terms in $f(x)$ can be differentiated  
- each of the differentiated terms has a finite value when $x=0$  
  
### More pracitice  
$f(x) = \sin x = a+bx+cx^2+dx^3+ex^4+fx^5 ...$  
$f(0) = \sin 0 = 0 = a$  
$f^\prime (x) = \cos x = b+ 2cx +3dx^2 + 4ex^3 + 5fx^4 ...$  
$f^\prime (0) = \cos 0 =1 = b$  
$f^{\prime\prime}(x) = -\sin x = 2c+6dx+12ex^2+20fx^3 ...$  
$f^{\prime\prime} (0) = - \sin 0 = 0 = 2c$  
$f^3(x) = -\cos x = 6d+24ex+60fx^2$  
$f^3(0) = -\cos 0 = -1 = 6d \Rightarrow d=-\frac{1}{6}$  
  
### Example  
Use the Maclaurin series of $(1+x)^n$ to find the first five terms of the series for $f(x)=\frac{1}{(1-x)^2}$  
$(1+x)=1+nx+\frac{n(n-1)}{2}x^2+\frac{n(n-1)(n-2)}{6}x^3+\frac{n(n-1)(n-2)(n-3)}{24}x^4 ...$  
$f(x)=(1+(-x))^{-2}$  
$f(x)=1+(-2)(-x)+\frac{(-2)(-3)}{2}(-x)^2+\frac{(-2)(-3)(-4)}{6}(-x)^3+\frac{(-2)(-3)(-4)(-5)}{24}(-x)^4$  
$f(x)=1+2x+3x^2+4x^3+5x^4$  
  
![[../../../Extra Files/Pasted image 20250226105638.png|Pasted image 20250226105638.png]]  
a. $-1 \lt -3x \le 1$  
$1 \gt 3x \ge 3$  
$-\frac{1}{3}\le x \lt \frac{1}{3}$  
  
b. $-1 \lt x^2 \le 1$  
$0 \le x^2 \le 1$  
$-1 \le x \le 1$  
  
c. $-1 \lt (3+x)^{-1} \le 1$  
$(3+x)^{-1} = 3^{-1}(1+\frac{x}{3})^{-1}$  
$-1 \lt \frac{x}{3} \lt 1$  
$-3 \lt x \lt 3$  
  
  
# Using the formulae  
## Thursday, February 27th 2025  
  
Formula for $^nC_r$:  
$$ ^nC_r = \frac{n!}{r!(n-r!)}$$  
$$^5C_2=\frac{5!}{2! \times 3!} = \frac{5 \times 4 \times 3 \times 2 \times 1}{2 \times 1 \times 3 \times 2 \times 1} = \frac{5 \times 4}{2 \times 1} = 10$$  
  
## $\text{For } (1+x)^n$  
$$ ^n C _0 = \frac{n!}{0!n!} = 1$$  
$$ ^n C_1 = \frac{n!}{1!(n-1)!} = \frac{n \times (n-1)!}{(n-1)!}=n$$  
$$ ^n C _2 = \frac{n!}{2!(n-2)!} = \frac{n (n-1)}{2!}$$  
$$ ^n C_3 = \frac{n(n-1)(n-2)(n-3)}{3!(n-3!)} = \frac{n(n-1)(n-2)}{3!}$$  
$$(1+x)^n = 1 + nx + \frac{n(n-1)x^2}{2!} + \frac{n(n-1)(n-2)x^3}{3!} \space ... $$  
## $\text{Put into practice}$  
$\frac{1}{1+x} = (1+x)^{-1}$ First five terms  
$$1-1x+\frac{-1 \times -2}{2}x^2 + \frac{-1 \times -2 \times -3}{6}x^3 + \frac{-1 \times -2 \times -3 \times -4}{24}x^4 = 1-x+x^2-x^3+x^4$$  
  
## $\text{Questions}$  
1. $e^{2x}$ = $$ 1 + 2x + \frac{(2x)^2}{2!} + \frac{(2x)^3}{3!} + \frac{(2x)^4}{4!} = 1+2x+2x^2 + \frac{4x^3}{3} + \frac{2x^4}{3}$$  
2. $e^{-x}=$ $$1-x + \frac{(-x)^2}{2!} + \frac{(-x)^3}{3!} + \frac{(-x)^4}{4!} = 1-x+\frac{x^2}{2}-\frac{x^3}{6} + \frac{x^4}{24}$$  
3. $e^{-3x} =$ $$1-3x+\frac{(3x)^2}{2}-\frac{(3x)^3}{6}+\frac{(3x)^4}{24} = 1-3x+\frac{9x^2}{2}-\frac{9x^3}{2}+\frac{27x^4}{8}$$  
4. $e^{\frac{x}{2}} =$ $$1+\frac{x}{2}+\frac{(\frac{x}{2})^2}{2!}+\frac{(\frac{x}{2})^3}{3!}+\frac{(\frac{x}{2})^4}{4!} = 1+\frac{x}{2} + \frac{x^2}{8} + \frac{x^3}{48} + \frac{x^4}{384}$$  
5. $e^{\frac{-x}{3}} =$ $$1-\frac{x}{3}+\frac{x^2}{2! \times 3^2} - \frac{x^3}{3! \times3^3} + \frac{x^4}{4! \times3^4} = 1 - \frac{x}{3} + \frac{x^2}{18} - \frac{x^3}{162} + \frac{x^4}{1944}$$  
6. $\ln (1-x) = \ln (1+(-x)) =$ $$-x-\frac{x^2}{2}-\frac{x^3}{3}-\frac{x^4}{4} \text{ for } -1 \le x \lt 1$$  
  
## Example 1  
Expand $\frac{\sin x}{\sqrt{(1+x)}}$ as far as the term in $x^5$ and give the range of $x$ for which the series is valid  
  
1. $e^x \sin x =$ $$e^x =  1 + x + \frac{x^2}{2!}$$  
$$ \sin x = x - \frac{x^3}{3!} + \frac{x^5}{5!}$$  
$$e^x \sin x =(1+x+\frac{x^2}{2!})(x-\frac{x^3}{3!}+\frac{x^5}{5!})$$  
$$x+x^2-\frac{x^3}{3!}-\frac{x^4}{3!} + \frac{x^3}{2!}$$  
Smallest terms  
$$x+x^2+\frac{x^3}{3}$$  
## Exam questions  
Show that the MacLaurin series for $\ln (e+2ex)$ is $$1+2x-2x^2+ax^3$$ Where $a$ is also to be determined  
$$\ln ((1+x+\frac{x^2}{2!}+\frac{x^3}{3!})+(1+2x+2x^2 + \frac{4x^3}{3}))$$  
  
$$ \ln (1-3x)$$  
$$-3x-\frac{9x^2}{2}-\frac{27x^3}{3}$$  
  
  
---  
<p align="right">17/09/2025</p align="right">  
# Maclaurin series 2  
A function f(x) can be expanded using the Maclaurin series given that:  
- f(x) can be expanded as a convergent infinite series of terms  
- each of the terms in f(x) can be differentiated  
- each of the differentiated terms has a finite value when x=0  
  
>[!Formula] Equation  
>The Maclaurin series, or expansion, for f(x) is  
>$$f(x) \equiv xf^`(0)+\frac{x^2}{2!}f^{``}(0)+\frac{x^3}{3!}f^{```}+\frac{x^4}{4!}f^{````} ... +\frac{x^r}{r!}f^r+ ...$$  
  
![[../../../Extra Files/Pasted image 20250917145829.png|Pasted image 20250917145829]]  
$f(x) = \ln (1+x)$  
$f(0) = \ln(1+0)=0$  
$f^`(x)=\frac{1}{1+x}=(1+x)^{-1}$  
$f^`(0)=\frac{1}{1+0}=1$  
$f^{``}(x)=-(1+x)^{-2}$  
$f^{``}(0)=-(1+0)^{-2}=-1$  
$f^3(x)=2(1+x)^{-3}$  
$f^3(0)=2(1+0)^{-3}=2$  
$f^4(x)=-3(1+x)^{-4}$  
$f^4(0)=-3(1+0)^{-4}=-6$  
  
$f(x)=0+1x-\frac{1}{2}x^2 + \frac{2}{6}x^3-\frac{3\times2}{4!}x^4 ...$  
$f(x)=x-\frac{x^2}{2}+\frac{x^3}{3}-\frac{x^4}{4}+\frac{x^5}{5}...$  
  
![[../../../Extra Files/Pasted image 20250917150901.png|Pasted image 20250917150901]]  
$\tan (2x) = (2x)+\frac{(2x^3)}{3} + \frac{2(2x)^5}{15}...$  
$\tan (2x)\ln(1+x) = (2x+\frac{8}{3}x^3+\frac{64}{15}x^5)(x-\frac{x^2}{2}+\frac{x^3}{3}-\frac{x^4}{4})$  
  
---  
<p align="right">19/09/2025</p align="right">  
# General terms and limits  
  
>[!example]  
>Find this limit:   
>$$\underset{n \rightarrow \infty}{\lim} \frac{2n+5}{n}$$  
>  
>$$\underset{n \rightarrow \infty}{\lim} \frac{2+\frac{5}{n}}{1}$$  
>$$\underset{n \rightarrow \infty}{\lim} 2+\frac{5}{n}=2$$  
  
![[../../../Extra Files/Pasted image 20250919140859.png|800]]  
