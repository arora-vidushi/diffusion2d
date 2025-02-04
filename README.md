# Diffusion2D-Python-Package

## Instructions for students

Please follow the instructions in [pypi_exercise.md](https://github.com/Simulation-Software-Engineering/Lecture-Material/blob/main/03_building_and_packaging/pypi_exercise.md).

The code used in this exercise is based on [Chapter 7 of the book "Learning Scientific Programming with Python"](https://scipython.com/book/chapter-7-matplotlib/examples/the-two-dimensional-diffusion-equation/).

## Project description

In this project we solve 2D diffusion equation on the domains of the unit square application to a metal plate. Plate is exposed to given temperature apart from a disc of a specific size which is at a temperature different from before. 

## Installing the package


### Using pip3 to install from PyPI

This package can be installed running the following command:

```bash
pip install --user --index-url https://test.pypi.org/simple/ aroravi_diffusion2D
```


### Required dependencies
This package requires [NumPy](https://numpy.org/) and [Matplotlib](https://matplotlib.org/).

## Running this package

This package can be used by importing and running it like this:

```python
from aroravi_diffusion2D import diffusion2d
diffusion2d.solve()
```

## Citing
Simulation Software Engineering (Winter term 2022/23)
Exercise: Packaging Python Code. Universität Stuttgart.