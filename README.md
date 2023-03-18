# Ballistic-Molecular-Flow-Sim
Ballistic Molecular Flow Sim

This is a simple simulation to calculate ballistic molecular flow

It can readily take in lambertian cosine emission for adsorptive-desorptive processes
but is currently configured to
1) generate a maze
2) emit a particle into that maze 
3) when the particle collides with a wall, calculate the normal and reflect the velocity
4) output the simulation visually

Very simple model. Intent was to be used for modeling molecular flows in thin channels
to reduce to 'Atomic Flux Circuit' rules (i.e. lumped element models for loading 
magneto-optical traps or putting atomic beams on a chip). A Monete-Carlo model fed with a thermal
distribution of particles can be implemented using this with arbitrary geometries to 
simulate time constants of the system. This model was suitable for non-lambertian emission surfaces
as well such as purely-adsorptive surfaces like graphite which can act to baffle atomic
beams and prevent a rise in pressure as well as prevent atoms lost from the beam
from coming back and increasing the velocity distribution. 

![Ballistic Flow Example](https://user-images.githubusercontent.com/30641156/226085537-52756d80-0419-49e2-9c78-aa851cf35048.png)
