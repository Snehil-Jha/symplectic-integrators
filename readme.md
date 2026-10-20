# Plan
0. Hamiltonian Mechanics Basics
    - Hamilton's Equations
    - Liouville's Theorem
    - Poisson Brackets

1. Basics of Integrators
    - Typical Integrators: Euler-Explicit
    - Failure of Typical Integrators for Classical Mechanics Systems
    - Utilize Symplectic Structure

2. Error Analysis of Symplectic Integrators
    - ??

3. Numerical Simulation Demo
    - ??

# Resources

## Videos

- [The Code That Revolutionized Orbital Simulation](https://youtu.be/nCg3aXn5F3M)

## Books

### Geometric Numerical Integration  
The comprehensive reference text for the field. Chapters VI and VII detail symplectic Runge–Kutta methods, composition/splitting schemes, and generating functions. Chapter IX provides the definitive treatment of Backward Error Analysis, proving that a symplectic integrator exactly solves a perturbed "shadow" Hamiltonian

### Numerical Hamiltonian Problems
One of the pioneering books dedicated strictly to symplectic integration. It offers a gentle, rigorous introduction to canonical transformations, Poisson brackets, and order conditions.

### Simulating Hamiltonian Dynamics
Excellent bridge between rigorous numerical analysis and physical applications, focusing on molecular dynamics, constrained systems, and statistical physics ensembles.

## Papers

### Symplectic Integrators Revisited
Stuchi (2002) presents a pedagogical review of Hamiltonian phase space geometry, generating functions, and Lie algebraic tools used to build explicit symplectic integrators such as Verlet and Strang splitting (Stuchi, 2002).

### Runge-Kutta Schemes for Hamiltonian Systems
Sans-Serna (1988) contains a derivation for the symplectic condition for a Runge-Kutta integrator using differential 2-forms.