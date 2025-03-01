# Diffusion2D-Python-Package

## Instructions for students

Please follow the instructions in [pypi_exercise.md](https://github.com/Simulation-Software-Engineering/Lecture-Material/blob/main/03_building_and_packaging/pypi_exercise.md).

The code used in this exercise is based on [Chapter 7 of the book "Learning Scientific Programming with Python"](https://scipython.com/book/chapter-7-matplotlib/examples/the-two-dimensional-diffusion-equation/).

## Project description

This code solves the two-dimensional diffusion equation on the domain of the unit square applied to a metal plate. This plate is of a given temperature apart from a disc of a prespecified size which is at a different temperature. The method used is the Finite Difference Method. 
The thermal diffusivity of the steel as well as the intervals in x- and y-directions are given by user input, though there are initial standard values given. The code produces four plots at different timepoints of the simulation showing the diffusion process.

## Installing the package

### Using pip3 to install from PyPI

This package can be installed running the following command:

```bash
pip install --user --index-url https://test.pypi.org/simple/ tuyetltg_diffusion2D
```

### Required dependencies

This package requires [NumPy](https://numpy.org/) and [Matplotlib](https://matplotlib.org/).

## Running this package

This package can be used by importing and running it like this:

```python
from tuyetltg_diffusion2D import diffusion2d

diffusion2d.solve()
```

## Citing

```
Simulation Software Engineering (Winter term 2022/23)
Exercise: Packaging Python Code. Universität Stuttgart.
```
