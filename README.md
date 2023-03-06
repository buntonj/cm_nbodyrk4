# cm_nbodyrk4
An undergraduate project that solves the n-body problem using 4th-order Runge-Kutta integration, rather than Verlet integration as [before](https://github.com/buntonj/cm_nbody).
The simulation is written in pure Fortran, compiled (in the included `Makefile`) with `gfortran`.  The simulation computes the motion of an $n\times n\times n$ 3D lattice of Xenon atoms in both the Lennard-Jones and Morse potential energy models.
If you would like to read more about the simulation results, feel free to browse [my report](https://github.com/buntonj/cm_nbodyrk4/blob/main/nbodyrk4report.pdf)!
