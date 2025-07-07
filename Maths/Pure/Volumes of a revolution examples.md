---
tags:
  - maths
date: 2025-06-04
---
---  
## Volumes of a Revolution: Examples  
  
[[./Volumes of revolution|Volumes of revolution]] are calculated by integrating cross-sectional areas along an axis of rotation. Here are some common examples:  
  
**1. Disk Method:**  
  
*   **Concept:** Used when the region is directly adjacent to the axis of rotation, creating solid disks. The volume is the integral of the area of these disks (πr²).  
  
*   **Formula:**  
  
    *   Rotation around x-axis:  `V = ∫[a, b] π [f(x)]² dx`  
    *   Rotation around y-axis:  `V = ∫[c, d] π [g(y)]² dy`  
  
*   **Example:** Find the volume of the solid formed by rotating the region bounded by  `y = √x`,  `x = 4`, and `y = 0` about the x-axis.  
  
    *   `V = ∫[0, 4] π (√x)² dx = π ∫[0, 4] x dx = π [x²/2] |_[0, 4] = π(16/2 - 0) = 8π`  
  
**2. Washer Method:**  
  
*   **Concept:** Used when the region is *not* directly adjacent to the axis of rotation, creating washers (disks with holes).  The volume is the integral of the difference in the areas of the outer and inner radii (π(R² - r²)).  
  
*   **Formula:**  
  
    *   Rotation around x-axis: `V = ∫[a, b] π ([f(x)]² - [g(x)]²) dx`, where `f(x)` is the outer radius and `g(x)` is the inner radius.  
    *   Rotation around y-axis: `V = ∫[c, d] π ([h(y)]² - [k(y)]²) dy`, where `h(y)` is the outer radius and `k(y)` is the inner radius.  
  
*   **Example:** Find the volume of the solid formed by rotating the region bounded by `y = x²` and `y = x` about the x-axis.  
  
    *   Intersection points: `x² = x  => x² - x = 0 => x(x - 1) = 0 => x = 0, x = 1`  
    *   `V = ∫[0, 1] π (x² - (x²)²) dx = π ∫[0, 1] (x² - x⁴) dx = π [(x³/3 - x⁵/5)] |_[0, 1] = π(1/3 - 1/5) = (2π)/15`  
  
**3. Shell Method:**  
  
*   **Concept:**  Used when integrating *parallel* to the axis of rotation.  Imagine the solid as being composed of cylindrical shells. The volume is the integral of the surface area of these shells (2πrh).  
  
*   **Formula:**  
  
    *   Rotation around y-axis:  `V = ∫[a, b] 2πx f(x) dx`  
    *   Rotation around x-axis:  `V = ∫[c, d] 2πy g(y) dy`  
  
*   **Example:** Find the volume of the solid formed by rotating the region bounded by `y = x²`, `x = 0`, `x = 2`, and `y = 0` about the y-axis.  
  
    *   `V = ∫[0, 2] 2πx (x²) dx = 2π ∫[0, 2] x³ dx = 2π [x⁴/4] |_[0, 2] = 2π(16/4 - 0) = 8π`  
  
**Key Considerations:**  
  
*   **Choosing the right method:** Disk/Washer method integrates *perpendicular* to the axis of rotation. Shell method integrates *parallel* to the axis of rotation.  Sometimes, one method is significantly easier than the other.  
*   **Finding the limits of integration:** Determine where the curves intersect to find the bounds for the integrals.  
*   **Identifying the correct radius/height:**  Carefully determine the functions representing the radius and/or height based on the chosen method and axis of rotation.  Sketching the region is crucial.  
*   **Solving for x or y:** If rotating around the y-axis and using the Disk/Washer method, you may need to solve the functions for `x` in terms of `y`.  
