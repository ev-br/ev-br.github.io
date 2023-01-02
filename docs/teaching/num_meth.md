---
hide:
  - footer
  - navigation
---

# Numerical methods

This is a 3/4 of a year long Numerical analysis course I was teaching at HSE University 
to 3rd year Applied maths students in 2017-2022. A short version of this course 
was formerly offered as the _Introduction to numerical analysis_ MOOC on Coursera.

## Lecture notes

Note that these slides are basically drafts and are missing sketches, drawings and
other handwritten notes which I was adding in real time in class. 


## Introduction

- [The subject of numerical analysis. Review of elementary theory of uncertainties.](../assets/num_meth/intro/uncertainties.pdf)

- [Numerical stability. Condition number. Stable and unstable algorithms. ](../assets/num_meth/intro/stability.pdf)

- [Machine arithmerics.](../assets/num_meth/intro/machine_arithmetics.pdf)


## Numerical linear algebra
    
### Matrix decompositions. Eigenvalue problem.

- [Matrix decompositions. Eigenvalue problem. Characteristic polynomial of a matrix. Localization of eigenvalues, Gershgorin theorems.](../assets/num_meth/eigenvalues/eigv_intro.pdf)

- [Iterative eigenvalue algorithms. Power iteration, Krylov subspaces. Inverse iteration.](../assets/num_meth/eigenvalues/power_iteration.pdf)

- [Computing the full spectrum of a matrix. Schur factorization. QR iteration.](../assets/num_meth/eigenvalues/QR_iteration.pdf)


### Systems of linear equations

- [Systems of linear equations. Cramer's rule and why it is not usable. Gaussian elimination.](../assets/num_meth/linalg/gauss.pdf)

- [LU factorization. Pivoting.](../assets/num_meth/linalg/lu.pdf)

- [Sensitivity of a linear system. Vector and matrix norms. Condition number of a matrix.](../assets/num_meth/linalg/m_v_norms.pdf)


### (Some) matrices of special structure

- [Cholesky factorization for positive definite matrices.](../assets/num_meth/linalg/cholesky.pdf)

- [Banded and trigiagonal matrices. Thomas algorithm.](../assets/num_meth/linalg/tridiag.pdf)

- [Rank-one updates. Sherman-Morrison formula.](../assets/num_meth/linalg/SM.pdf)


### QR factorization

- [QR factorization of a matrix. Constructing the QR factorization: Householder reflections and Givens rotations.](../assets/num_meth/linalg/qr.pdf)


### SVD factorization. Solving linear systems in the least-squares sense.

- [SVD factorization. Singular values and singular vectors. Properties of SVD. Invariant subspaces. Wigner-Eckhart theorem. Low-rank approximations.](../assets/num_meth/linalg/svd.pdf)

- Detour: Interpolation and approximation of data. Basis functions. [Solving linear systems in the least-squares sense. Linear least squares. Normal equations, solutions via QR and SVD factorizations.](../assets/num_meth/approx_interp/approx_interp.pdf)

- [Under- and over-determined linear systems. Moore-Penrose pseudoinverse. Minimum norm solution. Pseudoinverse via SVD.](../assets/num_meth/linalg/pinv.pdf)


## Iterative methods for linear systems

- [Large-scale linear systems. Sparse matrices. Iterative methods for linear systems. Jacobi iteration.](../assets/num_meth/linalg_iterative/simple_iteration_Jacobi.pdf)

- [Seidel iteration. Successive over-relaxation.](../assets/num_meth/linalg_iterative/Seidel_SOR.pdf)

- [Canonical form of iterative methods. Convergence criteria. Variational approaches: minimum residual method.](../assets/num_meth/linalg_iterative/iterative_linalg_3.pdf)
non


## Nonlinear algebraic equations and systems of equations.

- [Nonlinear root-finding. Fixed-point iteration. Analysis of convergence. _A priori_ and _a posertiori_ error estimates. Newton iteration and its variants.](../assets/num_meth/nonlinear_eq/nonlinear_eq.pdf)

- [Roots of polynomials. Companion matrix of a polynomial. Reduction to the eigenvalue problem](../assets/num_meth/nonlinear_eq/polynomials_companion_matrix.pdf)

- [Systems of non-linear equations. Relation to numerical mininimzation problems. Linear and nonlinear iterations.](../assets/num_meth/nonlinear_eq/systems_of_nonlinear_equations.pdf)


## Interpolation and approximation of data

- Interpolation and approximation of data. Basis functions. [Solving linear systems in the least-squares sense. Linear least squares. Normal equations, solutions via QR and SVD factorizations.](../assets/num_meth/approx_interp/approx_interp.pdf)

- [Interpolation and approximation of data. Basis functions. Gram matrix. A global polynomial interpolant. Lagrange interpolating polynomial. Runge phenomenon. Chebyshev nodes.](../assets/num_meth/approx_interp/approx_interp_2.pdf)

- [Spline interpolation. Cubic splines. Monotone interpolants.](../assets/num_meth/approx_interp/interp_splines.pdf)


## Calculus

### Numerical derivatives

- [Finite-difference formulas. Numerical stability, sources of error. Optimal FD step](../assets/num_meth/derivatives/derivatives.pdf)

- [Richardson extrapolation. Neville algorithm. Complex-step finite differences.](../assets/num_meth/derivatives/derivatives_2.pdf)
- [Algorithmic differentiation. Dual numbers.](../assets/num_meth/derivatives/derivatives_algo.pdf)

### Numerical integraion: quadratures

- [Quadrature formulas. Elementary quadratures, rates of convergence. Integrable singularities.](../assets/num_meth/integrals/integrals.pdf)

- [Newton-Cotes formulas. Nodes and weights. Gaussian quadratures.](../assets/num_meth/integrals/integrals_2.pdf)


### Fredholm integral equations

- [Fredholm integral equations. Nystrom method.](../assets/num_meth/fredholm/fredholm_equations.slides.html)


## Ordinary differential equations

### Initial value problem for ODEs

- [Discretization of IVPs. Euler-like methods. Explicit and implicit methods. Approximation and convergence. Predictor-corrector approaches, Runge-Kutta methods. Asymptototic stability. Absolutely and conditionally stable methods. Stiff systems.](../assets/num_meth/ode_ivp/ode_ivp.pdf)

- [Linear multistep methods (a family of). Zero-stability.](../assets/num_meth/ode_ivp/ode_ivp_2.pdf)

- [Stability of numerical approaches to solving discretized IVP. Dahlquist test equation. A-stability.](../assets/num_meth/ode_ivp/ode_ivp_3.pdf)


### Boundary value problems for ODEs.

- [Two-point boundary-value problems for 2nd order ODEs. Discretization. Reduction to linear algebraic systems. Convergence, approximation, stability.](../assets/num_meth/ode_bvp/bvp.pdf)

- [Variational approaches: Ritz method. Galerkin projectional approach. The road towards FEM.](../assets/num_meth/ode_bvp/bvp_proj.pdf)


## Partial differential equations

### Non-stationary problems

- [Discretization of PDEs: 1D parabolic equation. Stencils. Explicit and implicit schemes. von Neumann stability analysis. Absolute/conditional stability.](../assets/num_meth/pde/1D_parabolic.pdf)

- [Non-constant coefficients and non-linear equations.](../assets/num_meth/pde/nonlin.pdf)

- [1D wave equation.](../assets/num_meth/pde/1D_wave_eq.pdf)

- [Flux-conservative equations, relation to the wave equation. The failure of the naive FCTS scheme, The Lax construction, numerical dissipation. Improvements to the Lax scheme: Lax-Wendroff variants, staggered leapfrog.](../assets/num_meth/pde/2D_Poisson.pdf)


### Statitionary problems

- [Boundary value problem for the 2D Poisson equation. The need for sparse linear algebra. Seidel-like iterations. 1D Fourier + Thomas algorithm.](../assets/num_meth/pde/flux_conservative_eq.pdf)


### Higher dimensions

- [(2+1)D diffusion equation. Operator splitting. Alternating-direction implicit (ADI) schemes.](../assets/num_meth/pde/multidim_adi.pdf)


## Monte Carlo methods

- Motivation: integration in higher dimensions. [Monte Carlo integration. Buffon's needle. Quasi-random sequences (Sobol, Halton). Non-uniform sampling.](../assets/num_meth/mc/highD_integrals_and_MC.slides.html)

- [Markov chain Monte Carlo. Metropolis algorithm.](../assets/num_meth/mc/MCMC.slides.html)




