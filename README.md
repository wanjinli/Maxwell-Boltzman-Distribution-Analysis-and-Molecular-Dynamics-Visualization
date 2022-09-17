# Maxwell Boltzman Distribution Analysis and Molecular Dynamics Visualization

In this repository, I used knowledge from my Computational Physics class (PHYS 260) at the University of Pennsylvania to write a program in Python that demonstrates the infamous Maxwell-Boltzmann distribution for molecular kinematics. 

Specifically, I stimulated gas molecules' movement and interactions with one another in an ideal environment using the VPython package. Along with NumPy, Matplotlib, and Pylab, I was able to plot a real-time velocity distribution histogram for all the gas molecules. Comparing the histogram to Maxwell-Boltzmann distribution, we can see how accurate the equation predicts real-time velocity distribution. To regularize the temperature in the environment (as it typically rises with molecules' kinetic energy transfers into heat), I also implemented two different types of thermostats that would scale the velocities according to the current temperature of the environment.

Some of the key measurements and calculations I made include:
  - Leonard-Jones potential (calculated with Verlet algorithm)
  - Van-der-Waals interaction potential energy and net forces (with radial distribution function)
