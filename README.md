# Lattice Boltzmann Method
Here some simple codes for the Lattice Boltzmann Method are presented. Along with the codes I as well present some simple Python scripts to analyze results produced by those codes.

1. Shan-Chen gas-liquid model with the droplet in the center of a domain.
![](https://github.com/shurikkuzmin/LatticeBoltzmannMethod/blob/master/ShanChen/droplet.png "Droplet simulated by the Shan-Chen method")

2. Binary-liquid free energy model with the droplet on the surface.
![](https://github.com/shurikkuzmin/LatticeBoltzmannMethod/blob/master/FreeEnergy/droplet_on_surface.png "Droplet simulated by the free energy method")

3. Shan-Chen gas-liquid model programmed on GPU with OpenCL technology.

4. Binary liquid model of the long gas bubbles in 3D microchannels (Bretherton flow). The implementation is parallelized in MPI. Two different implementations are covering full scale simulation and quarter channel simulations with symmetry conditions.

![](https://github.com/shurikkuzmin/LatticeBoltzmannMethod/blob/master/Microchannel3D/benchmark.jpg "Long gas bubbles in the 3D microchannels")

5. The binary liquid droplets on the curved surface. The boundary condition for a phase field is established in a such way as to control the wetting angle.
![](https://github.com/shurikkuzmin/LatticeBoltzmannMethod/blob/master/CurvedSolid/droplet_on_solid.png "Three droplets on the solid surface")

6. Deposition of the droplet to the curved solid.
<video width="400" height="222" controls>
    <source src="https://github.com/shurikkuzmin/LatticeBoltzmannMethod/blob/master/Deposition/deposition.avi" type="video/mp4">
</video>


