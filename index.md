---
layout: default
---

# The CELMA model

The CELMA-model is a global drift-fluid model for modeling plasma turbulence in
a linear device with constant magnetic field.
The model describes the spatio-temporal evolution of the density, modified
vorticity, momentum-density and current.
It assumes isothermal electrons and cold ions, and does not use the
Boussinesq-approximation.
The derivation of the model can be found in the *Derivation*-part, and set of
equations can be found under *5.6 The set of equations*
[here]({{ page.diss_url }}).

# The CELMA code

The [CELMA-code]({{ page.repo_code_url }}) is written using the
[BOUT++](http://boutproject.github.io/)-framework, and contains:

* The code for simulation of the full model.
* The code for simulation of the model using the Boussinesq approximation.
* Pre- and post-processing scripts using `python3`.
* Verification of the code using the Method of Exact Solutions.
* `Jupyter-notebooks` for derivation of operators not already in the BOUT++ framework.

Add-ons to the BOUT++ framework is documented using [doxygen](http://www.doxygen.org/).
