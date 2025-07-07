---
date: 2025-06-18
---
---  
## Gravitational Potential Energy  
  
**Definition:** Gravitational potential energy (GPE) is the energy an object possesses due to its position in a gravitational field. It represents the amount of work required to move the object from a reference point (often ground level) to its current position against the force of gravity.  
  
**Formula:**  
  
U = mgh  
  
Where:  
  
*   `U` is the gravitational potential energy (measured in Joules, J)  
*   `m` is the mass of the object (measured in kilograms, kg)  
*   `g` is the acceleration due to gravity (approximately 9.81 m/s² on Earth's surface)  
*   `h` is the height of the object above the reference point (measured in meters, m)  
  
**Key Concepts:**  
  
*   **Reference Point:**  The choice of the reference point (where U = 0) is arbitrary.  The *change* in gravitational potential energy is the physically meaningful quantity.  
*   **Path Independence:**  The change in GPE depends only on the initial and final heights, not the path taken. This is because gravity is a conservative force.  
*   **Work-Energy Theorem:**  The change in GPE is equal to the negative of the work done by gravity:  ΔU = -W_gravity.  
  
**Examples:**  
  
*   A book held above a table has GPE. The higher the book, the greater the GPE.  
*   Water held in a reservoir has GPE. This energy can be converted to kinetic energy to generate electricity in a hydroelectric dam.  
*   An airplane flying at a high altitude has GPE.  
  
**Units:**  
  
*   The SI unit for gravitational potential energy is the Joule (J), which is equivalent to kg⋅m²/s².  
  
**Important Considerations:**  
  
*   This formula assumes a uniform gravitational field (i.e., g is constant). This is a good approximation for objects near the Earth's surface.  
*   For very large distances from the Earth or other celestial bodies, a more general formula for gravitational potential energy that takes into account the variation of 'g' with distance is needed.  
*   GPE is a scalar quantity; it only has magnitude and no direction.  
  
**Related Concepts:**  
  
*   Kinetic Energy  
*   Potential Energy  
*   Work  
*   Conservative Forces  
*   Gravitational Force  
  
$$GPE = \frac{GMm}{r}\qquad \text{in a radial gravitational field}$$  
$V_p$ = potential  
Potential  
Gravitational potential  
$$V_p=\frac{GM}{r}$$  
  
<mark>Gravitational potential is the amount of energy (work done) per unit mass required to move an object from infinity to that point in space</mark>  
  
## Escape velocity  
$$V_{\text{esc}} = \sqrt{2GM}$$  
$$V_{\text{esc}} = \sqrt{2gr}$$  
  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
\draw[line width = 0.5mm, -latex] (-0.5,0) -- (7,0) node[midway, above] {distance};  
\draw[line width = 0.5mm, -latex] (0,-7) -- (0,0.5) node[rotate=90, midway, above] {potential};  
\draw[line width = 0.25mm] (0.5,-6.5) to[out=90, in=190] (6.5,-0.5);  
\draw[dashed] (0.5,-6.5) -- (0,-6.5) node[left] {$-V_p$};  
\draw[dashed] (0.5,-6.5) -- (0.5,0) node[above] {$R_p$};  
  
\end{tikzpicture}  
\end{document}  
```  
$$\frac{\Delta V_p}{\Delta r} = g \quad \text{as} \quad \frac{GM}{r} \div r = \frac{GM}{r^2} = g $$  
