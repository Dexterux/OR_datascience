# Optimization modelling with Python

This tutorial shows how to model optimization problems in Python using Pyomo. 

[Pyomo](http://www.pyomo.org/)  is a Python library released under BSD license that interfaces with several solvers, both commercial (e.g. CPLEX) and open source (e.g. GLPK). 

Pyomo provides a Python interface to create abstract models and populate such models with data from any source.

## Getting started

This tutorial requires [Jupyter Notebook](http://jupyter.org/) to run. Besides Pyomo, the tutorial requires the installation of [Matplotlib](https://matplotlib.org/) to plot the results and [Pandas](https://pandas.pydata.org/) to import data from `CSV` files.

On a Linux based system simply clone the content of the repository and run it:
```
$ git clone git@github.com:Dexterux/OR_datascience.git
$ cd OR_datascience
$ jupyter notebook
```
 
## Contents of this tutorial

This tutorial consists of:
- a binary knapsack problem with parametric analysis 
- an area surveillance problem where drones are scattered around to maximize the supervised area
- an assignment problem of pilots and copilots to flights with recovery from unexpected and disruptive events.




