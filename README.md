
# diffusion2D

## Project description

This code solves the diffusion equation in 2D over a square domain which is at a certain temperature and a circular disc at the center which is at a higher temperature. This code solves the diffusion equation using the Finite Difference Method. The thermal diffusivity and initial conditions of the system can be changed by the user. The code produces four plots at various timepoints of the simulation. The diffusion process can be clearly observed in these plots.
Take a few minutes to play around with parameters dx, dy and D in the solver file and observe how the value of dt and the output changes. Do you notice if the code takes more or less time to finish the computation? This tuning is only for you to understand the underlying physical phenomenon and not part of the evaluation.

## Installing the package

There are two ways to install this package:

### Installing from Github

1. `git clone https://github.com/MarcelWolkober/diffusion2D`

2. `cd diffusion2D`

3. `pip install .`

### Using pip3 to install from PyPI

`pip3 install --index-url https://test.pypi.org/simple/ wolkobml_diffusion2d --extra-index-url https://pypi.org/simple`

### Required dependencies

The required dependencies are [Numpy](https://numpy.org) and [Matplotlib](https://matplotlib.org) which are automatically installed.

## Running this package

Use the provided `solve()` function in python:

```python
from wolkobml_diffusion2d.diffusion2d import solve
solve(dx = 0.1, dy = 0.1, D = 4)
```

It contains three parameter, which can be adjusted:

- `dx` intervals in x-direction
- `dy` intervals in y-direction
- `D` thermal diffusivity

## Citing

This is a student project forked from <https://github.com/Simulation-Software-Engineering/diffusion2D>.
