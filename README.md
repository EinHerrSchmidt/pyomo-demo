# pyomo-demo
A simple demo using Jupyter Notebook to show basic Pyomo features.
Directories abstract and concrete contain an implementation for solving the same linear program, whose definition can be found in the pyomo_concrete.ipynb notebook.

The main difference between the two approaches lies in that an abstract model can be used to easily define new instances of a problem, provided the general structure (objective function, constraints and so on) remains the same.
A .dat file is used to feed the abstract model the data it needs to generate an instance. By simply extending the data.dat file it is possible to specify new instances of the abstract model.

Both the abstract model's instance and the concrete model in this repository yield the same result, which can be seen by executing the corresponding notebooks.