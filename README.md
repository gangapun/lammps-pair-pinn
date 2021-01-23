# lammps-pair-pinn
LAMMPS implementation of Physically-Informed Neural Network potential

This package implements the PINN potential as a LAMMPS pair style. 

The description of the PINN model can be found in G. P. Purja Pun et al.,
"Development of a general-purpose machine-learning interatomic potential 
for aluminum by the physically informed neural network method", 
PHYSICAL REVIEW MATERIALS 4, 113807 (2020).

It was written by 
	Ganga P Purja Pun, gangapurjapun@gmail.com

Use "make yes-user-pinn" to enable this package when building LAMMPS.

In your LAMMPS input script, specifiy
  pair_style pinn
to enable the use of this implementation. All parameters, input files and
outputs are exactly identical to these used with pair_style eam/alloy.
