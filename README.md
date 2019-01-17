# NJL Model Parameter Fitting

Mathematica files which fit the parameters of the three momentum and proper time
regularised NJL models using low energy hadron phenomenology as constraints.
These parameter sets were used in my PhD research which were published in Refs.


## Proper Time Regularised Model Parameter Fitting

This Mathematica notebook computes the PS1 and PS2 parameter sets (and their variations with the infra-red cutoff included) which were used in my thesis for quark matter calculations with the Schwinger proper time regularised NJL model. It fits the models parameters to properties of low energy hadron phenomenology. Please note this notebook does not perform any quark matter calculations. That was done in a separate C++ code. The parameter set for the three momentum regularised version of the model is computed in a different notebook. This is just a simple notebook to compute these parameter sets.

### PS1:
Hadron phenomenology input: Subscript[M, l]=400 MeV, Subscript[M, s]=563 MeV, Subscript[m, \[Pi]]=140 MeV, Subscript[f, \[Pi]]= 93MeV. $m_{\pi}$
* PS1-IR### include an infra-red cutoff Subscript[\[CapitalLambda], IR]= ### MeV.

### PS2:
Hadron phenomenology input: Subscript[m, l]=5.5 MeV, Subscript[m, s]=135.7 MeV, Subscript[m, \[Pi]]= 140 MeV, Subscript[f, \[Pi]]=93 MeV
* PS2-IR### include an infra-red cutoff Subscript[\[CapitalLambda], IR]= ### MeV.

Notebook Author: D. L. Whittenbury
Version: v1.0
Last Updated: 28/9/2018

References:
All equations can be found in my thesis and also in a number of other references. The relevant parts of my thesis are section 6.5 and the appendices B.8, B.9, B.10 and B11.
