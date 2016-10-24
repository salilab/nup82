These scripts demonstrate the use of [IMP](http://integrativemodeling.org), [MODELLER](http://salilab.org/modeller), and [PMI](https://github.com/salilab/pmi) in the modeling of the Nup82 complex using DSS/EDC chemical cross-links and electron microscopy (EM) 2D class averages.

First, [MODELLER](http://salilab.org/modeller) is used to generate
initial structures for the individual components in the Nup82 complex. Then, IMP
is used to model these components using DSS/EDC crosslinks and the electron microscopy 2D class averages for the entire Nup82 complex.

The modeling protocol will work with a default build of IMP, but for most effective sampling, IMP should be built with [MPI](http://integrativemodeling.org/2.5.0/doc/ref/namespaceIMP_1_1mpi.html) so that replica exchange can be used.

## List of files and directories:

- `data`		                         contains all relevant data, input structures that were generated by MODELLER or deposited in PDB, etc.

- `template`
  
- `outputs` For reference, the models described in the Nup82 publication are
  deposited in this directory. For each of the two clusters discovered in
  the study, the cluster representative (the best scoring individual model in
  the cluster) is available in RMF format, together with the top five best
  scoring models in PDB format. An accompanying stat file contains useful
  statistics on the simulation, such as whether each of the crosslinks was
  satisfied. The localization densities, as shown in Figure 6 on the publication
  are also available, as Chimera session files.

## Running the MODELLER scripts:

## Running the IMP/PMI scripts for the Nup82 complex:

Finally, analyze the resulting clusters:

## Information

_Author(s)_: Seung Joong Kim, Ilan E. Chemmama, Riccardo Pellarin 

_Date_: October 6th, 2016

_License_: [LGPL](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html).
This library is free software; you can redistribute it and/or
modify it under the terms of the GNU Lesser General Public
License as published by the Free Software Foundation; either
version 2 of the License, or (at your option) any later version.

_Last known good IMP version_: [![build info](https://integrativemodeling.org/systems/?sysstat=6&branch=master)](http://integrativemodeling.org/systems/) [![build info](https://integrativemodeling.org/systems/?sysstat=6&branch=develop)](http://integrativemodeling.org/systems/)

_Testable_: Yes.

_Parallelizeable_: Yes

_Publications_:
 
 \*These authors contributed equally to this work as co-first authors.
