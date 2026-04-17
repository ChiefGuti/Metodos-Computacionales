# Computational Methods (Métodos Computacionales)

Coursework from Universidad de los Andes, 2017.

---

## Problem: 2D Steady-State Heat Equation

Solves the Laplace equation on a rectangular plate with fixed boundary conditions using the finite-difference method (Jacobi iteration) implemented in C, with results visualized in Python/matplotlib.

## Repository structure

```
t1/
  Entrega/          Final submission
    Entrega.c       Main solver (finite differences + Jacobi iteration)
    makefile        Build configuration
    plotter.py      Python visualization of the temperature field
    V.png           Sample output plot
  sinparalelisar/   Serial baseline version (no parallelization)
```

## Build & run

```bash
cd t1/Entrega
make
./a.out
python plotter.py
```
