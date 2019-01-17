# NJL Model Parameter Fitting

This repository contains Mathematica notebooks which fit the parameters of the three momentum and proper time
regularised NJL models using low energy hadron phenomenology as constraints.
These parameter sets were used in [my PhD research](https://inspirehep.net/record/1495499/files/02whole.pdf) which were published [here](https://journals.aps.org/prc/abstract/10.1103/PhysRevC.93.035807) and [here](https://www.sciencedirect.com/science/article/pii/S0370269316305627?via%3Dihub).


Please note these notebooks do not perform any quark matter calculations. Those were done in a separate C++ code. These are just simple notebooks to compute the parameter sets.

## Proper Time Regularised Model Parameter Fitting

This was done in the Mathematica notebook **NJL_PTR_Parameter_Fitting.nb**. It computes the PS1 and PS2 parameter sets (and their variations with the infra-red cutoff included) which were used in my thesis for quark matter calculations with the Schwinger proper time regularised NJL model.    

All equations can be found in [my thesis](https://inspirehep.net/record/1495499/files/02whole.pdf) and also in a number of other references. The relevant parts of my thesis are section 6.5 and the appendices B.8, B.9, B.10 and B11.

## Three Momentum Regularised Model Parameter Fitting

This was done in the Mathematica notebook **NJL_TMR_Parameter_Fitting.nb**. It computes the HK parameter set which was used in my thesis for quark matter calculations with the three momentum regularised NJL model. The HK parameter set is only used for the three momentum regularised version of the model.

## References:

1. [D. L. Whittenbury, PhD thesis](https://inspirehep.net/record/1495499/files/02whole.pdf) Hadrons and Quarks in Dense Matter: From Nuclear Matter to Neutron Stars, University of Adelaide.

2. [Phys. Rev. C 93, 035807 (2016)](https://journals.aps.org/prc/abstract/10.1103/PhysRevC.93.035807) D. L. Whittenbury, H. H. Matevosyan, and A. W. Thomas, Hybrid stars using the quark-meson coupling and proper-time Nambu–Jona-Lasinio models.

3. [Phys. Lett. B762 467-472 (2016)](https://www.sciencedirect.com/science/article/pii/S0370269316305627?via%3Dihub) D. L. Whittenbury, M. E. Carrillo-Serrano, and A. W. Thomas, Quark–meson coupling model based upon the Nambu–Jona Lasinio model.

4. [PRD, 83, 034005 (2011)](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.83.034005) T. Inagaki, D. Kimura, H. Kohyama, A. Kvinikhidze, Nonet meson properties in the Nambu-Jona-Lasinio model with dimensional versus cut-off regularisation.

5. [PTEP, 7, 073D01 (2013)](https://academic.oup.com/ptep/article/2013/7/073D01/1571314) K. Masuda, T. Hatsuda and T. Takatsuka, Hadron-quark crossover and massive hybrid stars.

6. [Phys. Rept. 247, 221-367 (1994)](https://www.sciencedirect.com/science/article/abs/pii/0370157394900221) T. Hatsuda and T. Kunihiro, QCD phenomenology based on a chiral effective Lagrangian.
