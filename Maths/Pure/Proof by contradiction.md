---
tags:
  - maths
date: 2025-05-22
---
---  
# Starter questions  
Divide $2x^4+x^3-5x^2-5x-3$ by $2x+3$  
  
Let's say you want to prove a statement *P*.  Instead of directly showing *P* is true, proof by contradiction (also known as *reductio ad absurdum*, Latin for "reduction to the absurd") works by:  
  
1.  **Assuming the negation of P is true:**  Assume *¬P* (not P) is true.  
  
2.  **Deduction:**  Use logical reasoning and established axioms, theorems, and definitions to derive a contradiction from the assumption that *¬P* is true.  This contradiction usually takes the form of showing that both *Q* and *¬Q* are true for some statement *Q*.  
  
3.  **Conclusion:**  Since the assumption *¬P* leads to a contradiction, the assumption must be false.  Therefore, *P* must be true.  
  
**General Structure:**  
  
*   Assume *¬P*.  
*   ... (logical steps) ...  
*   Therefore, *Q*.  
*   ... (logical steps) ...  
*   Therefore, *¬Q*.  
*   Thus, we have *Q ∧ ¬Q*, which is a contradiction.  
*   Therefore, *¬P* is false, and *P* is true.  
  
**Why does it work?**  
  
We rely on the law of excluded middle, which states that either a statement is true, or its negation is true. There's no middle ground.  If assuming the negation leads to a contradiction, then the negation *cannot* be true. Therefore, the original statement *must* be true.  
  
**Example: Proving √2 is irrational.**  
  
*   **Statement (P):** √2 is irrational.  
*   **Negation (¬P):** √2 is rational.  
  
*   **Proof:**  
    1. Assume √2 is rational. This means √2 can be expressed as a fraction a/b, where a and b are integers with no common factors (i.e., the fraction is in simplest form), and b ≠ 0.  
    2. So, √2 = a/b.  
    3. Squaring both sides, we get 2 = a²/b².  
    4. Multiplying both sides by b², we get 2b² = a².  
    5. This means a² is even (since it's equal to 2 times an integer).  
    6. If a² is even, then a must also be even.  (Proof: if a were odd, then a² would also be odd).  
    7. Since a is even, we can write a = 2k for some integer k.  
    8. Substituting a = 2k into 2b² = a², we get 2b² = (2k)² = 4k².  
    9. Dividing both sides by 2, we get b² = 2k².  
    10. This means b² is even.  
    11. If b² is even, then b must also be even.  
    12. Therefore, both a and b are even.  This contradicts our initial assumption that a and b have no common factors.  
    13. Since our assumption that √2 is rational leads to a contradiction, √2 must be irrational.  
  
**When to use it:**  
  
*   When direct proof seems difficult or impossible.  
*   When proving the *non-existence* of something.  
*   When the negation of the statement gives you something concrete to work with.  
  
**Important Considerations:**  
  
*   Ensure your reasoning is valid and each step follows logically.  
*   Clearly identify the contradiction you arrive at.  
*   The contradiction must stem from the initial assumption (¬P) and not from any other incorrect assumptions you might have made along the way. If the contradiction does not stem from the negation of P, your proof fails.  
  
## Practice  
Try and prove when $n^2$ is odd, $n$ is even