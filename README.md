# Supersonic Flow Over a Wedge

CFD analysis of Supersonic Flow Over a Wedge using ANSYS Fluent. 

The flow is at an absolute pressure of 101325Pa and a Mach number of 3. Fluid is flowing over a 15 deg wedge. An inviscid compressible solver with second-order spatial discretisation was used. 

Results show a weak oblique shock forming close to the wedge. The Mach number of the flow reduces across the shock, however, it is still supersonic behind the shock. The plot shows the Mach number variation at y=0.4m and the flow dropping to around Mach 2.25 from Mach 3 can be observed. At the same time, the pressure increases across the shock. The direction of flow is not affected due to the shock as seen from velocity vectors. Further, the mesh was refined in regions with high-pressure gradients and the thickness of the shock was observed to have reduced. A more refined mesh can be used to check grid independence. 

https://confluence.cornell.edu/display/SIMULATION/FLUENT+-+Supersonic+Flow+Over+a+Wedge
