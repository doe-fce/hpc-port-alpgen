# hpc-port-alpgen
This code is an edit of the ALPGEN (v2.14, http://mlm.home.cern.ch/mlm/alpgen/ ) event generator which was originally written by Michelangelo L. Mangano, Mauro Moretti, Fulvio Piccinini, Roberto Pittau and Antonello Polosa. This edited version makes no changes to the physics calculations, but has been optimized for running with parallel threads. Parallel execution was achieved using MPI.

Details of the optimizations applied can be found here: arXiv:1511.07312 (http://arxiv.org/abs/1511.07312).

# Warning
To ensure random number seeds are correctly set, please provide iseed1, iseed2, iseed3, and iseed4 in your configuration input file.



