---
tags:
  - maths
date: 2025-06-11
---
---  
# Starter  
A sequence is defined by $u_n=5n+1$, list the first 6 terms  
6,11,16,21,26,31  
  
A sequence is defined by $u_n=30-4n$. How many terms are positive?  
6  
  
  
## Iterative Sequences  
  
An iterative sequence is a sequence where each term is defined based on one or more preceding terms.  Essentially, you apply a function (or rule) to the previous term(s) to generate the next term.  
  
**Key Concepts:**  
  
*   **Seed Value(s):**  The initial term(s) required to start the sequence. Often denoted as  `x_0`, `x_1`, etc.  
*   **Iteration Function:**  The function `f(x)` that is applied repeatedly.  The recursive definition is often expressed as:  `x_{n+1} = f(x_n)`  (for sequences dependent on the immediately preceding term).  
*   **Convergence:**  Whether the sequence approaches a limit as *n* approaches infinity.  A convergent sequence settles towards a specific value.  
*   **Divergence:**  The sequence does not approach a limit. It may oscillate, grow infinitely large, or behave chaotically.  
*   **Fixed Point:** A value `x` such that `f(x) = x`. If an iterative sequence converges to a value, that value is often a fixed point of the iteration function.  
  
**Examples:**  
  
*   **Arithmetic Sequence (Simple):**  
    *   Seed: `x_0 = 2`  
    *   Iteration: `x_{n+1} = x_n + 3`  
    *   Sequence: 2, 5, 8, 11, 14... (Diverges)  
*   **Geometric Sequence (Simple):**  
    *   Seed: `x_0 = 1`  
    *   Iteration: `x_{n+1} = 2 * x_n`  
    *   Sequence: 1, 2, 4, 8, 16... (Diverges)  
*   **Fibonacci Sequence (Dependent on Two Previous Terms):**  
    *   Seeds: `x_0 = 0`, `x_1 = 1`  
    *   Iteration: `x_{n+1} = x_n + x_{n-1}`  
    *   Sequence: 0, 1, 1, 2, 3, 5, 8... (Diverges, grows infinitely large)  
*   **Newton-Raphson Method (Root Finding):**  
    *   Seed: `x_0` (Initial guess for the root)  
    *   Iteration: `x_{n+1} = x_n - f(x_n) / f'(x_n)`  (where `f'(x)` is the derivative of `f(x)`)  
    *   This sequence *can* converge to a root of the function `f(x)`. Convergence is not guaranteed and depends on the initial guess.  
*   **Logistic Map (Example of Chaos):**  
    *   Seed: `x_0` (between 0 and 1)  
    *   Iteration: `x_{n+1} = r * x_n * (1 - x_n)` (where `r` is a parameter, often between 0 and 4)  
    *   The behavior of this sequence is highly dependent on the value of `r`.  For some values, it converges to a fixed point.  For others, it exhibits periodic oscillations or chaotic behavior.  
  
**Applications:**  
  
*   **Numerical Analysis:**  Approximating solutions to equations, integrals, and differential equations.  
*   **Computer Science:**  Algorithms, such as iterative sorting algorithms (e.g., bubble sort).  
*   **Mathematics:**  Exploring complex systems and dynamical systems.  
*   **Physics & Engineering:**  Modeling systems that evolve over time.  
*   **Finance:** Calculating compound interest.  
  
**Important Considerations:**  
  
*   **Initial Conditions:** The seed value(s) can significantly impact the behavior of the sequence, especially for complex systems.  
*   **Error Accumulation:** In numerical implementations, rounding errors can accumulate over many iterations, potentially leading to inaccurate results.  
*   **Convergence Criteria:**  When implementing iterative algorithms, it's important to define clear convergence criteria (e.g., a tolerance level for the difference between consecutive terms).  
*   **Stability:**  Whether small changes in the seed value lead to large changes in the sequence's behavior.  
  
**Related Concepts:**  
  
*   **Recursion:** A programming technique where a function calls itself.  Iterative sequences can often be implemented using recursion, but recursion can be less efficient than iterative loops.  
*   **Dynamical Systems:** Mathematical systems that evolve over time, often modeled using iterative equations.  
*   **Chaos Theory:** The study of complex and unpredictable systems, often characterized by sensitive dependence on initial conditions.  
  
This note provides a foundational understanding of iterative sequences.  Further exploration into specific applications and mathematical properties is encouraged.  
