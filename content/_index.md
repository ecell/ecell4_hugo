---
title: Home
---

![](https://github.com/ecell/ecell4_docs/raw/master/ecell-logo-with-title.png)

# E-Cell System version 4

A multi-algorithm, multi-timescale, multi-spatial-representation biochemical simulation environment

[Installation](https://github.com/ecell/ecell4#installation)
[Run without installing](https://github.com/ecell/ecell4_docs)
[Documentation](http://ecell4.readthedocs.io/en/latest/)

## Hello E-Cell4

E-Cell System is a software platform for modeling, simulation and analysis of complex, heterogeneous and multi-scale systems like the cell.

~~~python
from ecell4 import *

with reaction_rules():
    A + B == C | (0.01, 0.3)

run_simulation(10, {'A': 60, 'B': 60}, solver='gillespie')
~~~

![](http://www.e-cell.org/ecell4/images/gillespie.png)

## Features

### Single particle simulations
[The enhanced Green's Function Reaction Dynamics (eGFRD) method](http://gfrd.org/), [Spatiocyte](http://spatiocyte.org/), and the Reaction Brownian Dynamics (RBD) method.

### Multi-algorithm support
FILLME

### Rule-based modeling
FILLME

### Python programmable
FILLME

### Interactive visualizations on Jupyter Notebook
FILLME

### Bioinformatics integration
Garuda gadget, data source, etc.

## Examples

[![](http://www.e-cell.org/ecell4/images/drosophila.png)](https://github.com/ecell/ecell4-notebooks/blob/master/Examples/Drosophila%20Circadian%20Clock.ipynb)
[![](http://www.e-cell.org/ecell4/images/minde.gif)](https://github.com/ecell/ecell4-notebooks/blob/master/Examples/MinDE%20System%20with%20Spatiocyte%20Simulator.ipynb)
[![](http://www.e-cell.org/ecell4/images/attractors.png)](https://github.com/ecell/ecell4-notebooks/blob/master/Examples/Attractors.ipynb)

For more tutorials and examples, see http://ecell4.readthedocs.io/.

## License

This project is licensed under the terms of the GNU General Public License v3. See [LICENSE](https://github.com/ecell/ecell4_base/blob/master/LICENSE).

---
