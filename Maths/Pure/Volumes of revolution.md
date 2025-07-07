---
tags:
  - Undone
  - Maths
  - Calculus
date: 2025-03-17
---
---  
# Mean value of a function  
From deriving $x^2+y^2=r^2$  
$$V=2\pi\int^r_0 r^2-x^2 dx = 2\pi\left[r^2x-\frac{x^3}{3}\right]^r_0 = \frac{4 \pi r^3}{3} = \frac{4}{3}\pi r^3$$  
  
>[!formula] Mean value of a function  
>The mean value of a function $f(x)$ in the range $a\le x \le b$ is given by: $$\frac{1}{b-a} \int_a^b \thinspace f(x)dx$$  
# Example  
>[!example] Example 1  
>Find the  volume formed when the area enclosed by the curve with equation $y=x^3+1$, the coordiante axis and the line x=2 is rotated  
>a. 360$\degree$ around the x axis     $\qquad$      b. 180$\degree$ around the x-axis  
>  
>a.  
>$V=\pi \int ^2 _0 (x^3+1)^2 dx$  
>$=\pi \int ^2 _0 x^6+2x^3+1 \thinspace dx$  
>$=\pi \left[\frac{x^7}{7} + \frac{x^4}{4}+x\right]^2_0$  
>$=\pi \left(\frac{128}{7}+8+2-0\right)$  
>$=\frac{198}{7}\pi \space \text{cubic units}$  
>  
>b.  
>Rotating through 180$\degree$ produces exactly $\frac{1}{2}$ of the shape in part **a**, so the volume in this case would be $\frac{1}{2}\left(\frac{198}{7}\pi = \frac{99}{7}\pi\right) \space \text{cubic units}$  
  
>[!formula] Integration  
>$$ \int_a^b f(x) \, dx = F(b) - F(a) $$  
>So, $$ \int_0^2 \thinspace x^2+2x-1 = \left[\frac{x^3}{3}+x^2-x\right]_0^2 = \left(\frac{8}{3} + 4 - 2\right) - 0 = \frac{14}{3}$$  
  
  
## Volumes of Revolution  
  
This note covers the basic concepts and methods for calculating the volume of a solid formed by revolving a 2D region around an axis.  
  
### The Disk Method  
  
*   **Concept:** Imagine slicing the solid into thin disks perpendicular to the axis of revolution.  Each disk has a volume of approximately πr²h, where r is the radius of the disk and h is its thickness.  
  
*   **Revolution around the x-axis:**  If the region is bounded by y = f(x), x = a, x = b, and the x-axis, then the volume is:  
  
    ```  
    V = π ∫[a, b] (f(x))² dx  
    ```  
  
*   **Revolution around the y-axis:** If the region is bounded by x = g(y), y = c, y = d, and the y-axis, then the volume is:  
  
    ```  
    V = π ∫[c, d] (g(y))² dy  
    ```  
  
*   **Key Idea:**  *r* is a function of the variable of integration (x or y).  The thickness *h* is *dx* or *dy*, respectively.  
  
### The Washer Method  
  
*   **Concept:**  Similar to the disk method, but used when there's a "hole" in the solid.  Imagine slicing the solid into thin washers (disks with a hole in the center).  The volume of each washer is the difference between the volumes of the outer and inner disks.  
  
*   **Revolution around the x-axis:**  If the region is bounded by y = f(x) (outer radius) and y = g(x) (inner radius), x = a, and x = b, then the volume is:  
  
    ```  
    V = π ∫[a, b] ((f(x))² - (g(x))²) dx  
    ```  
  
*   **Revolution around the y-axis:**  If the region is bounded by x = F(y) (outer radius) and x = G(y) (inner radius), y = c, and y = d, then the volume is:  
  
    ```  
    V = π ∫[c, d] ((F(y))² - (G(y))²) dy  
    ```  
  
*   **Key Idea:** Identify the outer and inner radii correctly. Ensure *f(x) > g(x)* or *F(y) > G(y)* on the interval of integration.  
  
### The Shell Method  
  
*   **Concept:** Imagine slicing the solid into thin cylindrical shells parallel to the axis of revolution. The volume of each shell is approximately 2πrhΔx or 2πrhΔy, where r is the radius of the shell, h is its height, and Δx/Δy is its thickness.  
  
*   **Revolution around the y-axis:**  If the region is bounded by y = f(x), x = a, x = b, and the x-axis, then the volume is:  
  
    ```  
    V = 2π ∫[a, b] x * f(x) dx  
    ```  
  
*   **Revolution around the x-axis:** If the region is bounded by x = g(y), y = c, y = d, and the y-axis, then the volume is:  
  
    ```  
    V = 2π ∫[c, d] y * g(y) dy  
    ```  
  
*   **Key Idea:** Notice that the variable of integration is *perpendicular* to the axis of revolution.  *r* is the distance from the shell to the axis of revolution, and *h* is the height of the shell.  
  
### Choosing the Right Method  
  
*   **Disk/Washer:** Best when slicing perpendicular to the axis of revolution is straightforward. The functions bounding the region are easily expressed in terms of the variable that is perpendicular to the axis of revolution.  
  
*   **Shell:** Best when slicing parallel to the axis of revolution is easier.  Especially useful if it's difficult to express the bounding functions in terms of the variable perpendicular to the axis of revolution, or if the integral becomes significantly simpler.  
  
### General Tips  
  
*   **Draw a diagram!** Visualizing the region and the solid is crucial.  
*   **Identify the axis of revolution.**  This determines whether you integrate with respect to *x* or *y*.  
*   **Determine the limits of integration.**  
*   **Write the volume integral carefully.**  Double-check your formulas and be mindful of squaring terms.  
*   **Evaluate the integral.** Don't be afraid to use u-substitution or other integration techniques.  
  
### Examples  
  
(Examples will be added here later as separate, linked notes. This keeps this note concise and focused on the core concepts.)  
  
### See Also  
  
*   Integration Techniques  
*   Applications of Integration  
