---
tags:
  - physics
date: 2025-05-20
---
---  
>[!formula] Simple harmonic motion is defined as oscillating motion in which:  
>$$a \propto -x$$  
>the acceleration is directly proportional to displacement, but in the opposite direction  
  
Free oscillations = ignore friction  
1. Their velocity increases downwards to the equilibrium point, then decreases from there, until they reach the turning point, where their velocity is zero, then their velocity increases upwards until the equilibrium point, where their velocity is a maximum  
  
This comes from [[./The principles of simple harmonic motion|The principles of simple harmonic motion]]  
  
## Simple Harmonic Motion (SHM)  
  
**Definition:**  Periodic motion where the restoring force is directly proportional to the displacement and acts in the opposite direction.  Think of a spring being stretched or compressed – the farther you pull it, the stronger it pulls back.  
  
**Key Characteristics:**  
  
*   **Periodic:**  Repeats itself after a specific time interval (period).  
*   **Restoring Force:** Force always directed towards the equilibrium position.  
*   **Proportionality:** Restoring force is *directly proportional* to the displacement from equilibrium.  This is mathematically crucial!  
  
**Mathematical Representation:**  
  
*   **Displacement:**  `x(t) = A cos(ωt + φ)`  (or `A sin(ωt + φ)`)  
    *   `x(t)`: Displacement at time *t*  
    *   `A`: Amplitude (maximum displacement)  
    *   `ω`: Angular frequency (rad/s)  
    *   `t`: Time  
    *   `φ`: Phase constant (initial phase – determines the starting position at t=0)  
*   **Velocity:** `v(t) = -Aω sin(ωt + φ)` (derivative of displacement)  
*   **Acceleration:** `a(t) = -Aω² cos(ωt + φ) = -ω²x(t)` (derivative of velocity)  
  
**Important Parameters:**  
  
*   **Amplitude (A):** The maximum displacement from the equilibrium position. Units: meters (m).  
*   **Period (T):** The time for one complete oscillation.  Units: seconds (s).  
*   **Frequency (f):** The number of oscillations per unit time.  Units: Hertz (Hz) = 1/s.  
*   **Angular Frequency (ω):**  `ω = 2πf = 2π/T`. Represents the rate of change of the angle in radians per second. Units: rad/s.  
*   **Phase Constant (φ):**  Determines the initial position of the oscillator at t=0. Units: radians (rad).  
  
**Energy in SHM:**  
  
*   **Kinetic Energy (KE):** `KE = 1/2 * m * v² = 1/2 * m * A²ω² sin²(ωt + φ)`  
*   **Potential Energy (PE):** `PE = 1/2 * k * x² = 1/2 * k * A² cos²(ωt + φ)`  (where k is the spring constant)  
*   **Total Mechanical Energy (E):** `E = KE + PE = 1/2 * k * A² = 1/2 * m * A²ω²`  (constant – energy is conserved)  
  
**Examples of SHM:**  
  
*   **Mass-Spring System:**  A mass attached to a spring oscillating horizontally.  `ω = √(k/m)`, `T = 2π√(m/k)`  
*   **Simple Pendulum:** A mass suspended from a string, oscillating with a small angle. `ω = √(g/L)`, `T = 2π√(L/g)` (where g is the acceleration due to gravity and L is the length of the pendulum)  
  
**Key Relationships & Implications:**  
  
*   Acceleration is always proportional to and opposite in direction to displacement: `a = -ω²x`  
*   The period and frequency depend on the physical properties of the system (e.g., mass and spring constant for a mass-spring system, length and gravity for a pendulum) and *not* on the amplitude (for small oscillations in a pendulum).  
*   Energy is continuously exchanged between kinetic and potential energy, but the total energy remains constant.  
  
**Damped Oscillations:**  
  
*   In reality, oscillations are rarely perfectly simple harmonic.  Damping forces (like friction or air resistance) cause the amplitude to decrease over time.  The oscillations eventually die out.  
  
**Driven Oscillations and Resonance:**  
  
*   Applying an external periodic force to an oscillator can cause it to oscillate at the driving frequency.  If the driving frequency is close to the natural frequency of the oscillator, *resonance* occurs, and the amplitude of oscillation becomes very large.  
