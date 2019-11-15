# Scheduling of Electric Buses
[Vehicle scheduling problem](https://onlinelibrary.wiley.com/doi/abs/10.1002/net.3230110204) (VSP) or blocking problem involves assigning vehicles to serve a set of predetermined trips associated with a timetable subjected to operational constraints. The electric bus (e-Bus) scheduling problem is classified as a special case of classic VSP taking into consideration the additional objectives and constraints specific to electric buses in addition to the traditional VSP constraints.

Vehicle scheduling problem is a well-studied optimization problem implementing both heuristic and non-heuristic optimization techniques. The classical VSP based on in-depot charging is categorized into two: Single-depot VSP (SDVSP) and Multi-depot VSP (MDVSP). SDVSP assigns vehicle trips from single-depot to multiple routes and MDVSP assigns vehicle trips from multiple-depots to multiple routes. The Single-depot VSP and Multi-depot VSP are generally mixed integer linear optimization problem. The commonly defined objective of a VSP is to minimize the vehicle operating costs restricted to several constraints in operation. Although in past years a large number of studies on e-Bus schedule optimization have considered in-depot slow-charging and fast-charging options, a significant number of studies in recent years are largely focussed on on-route charging options.

A core objective of this project is to define a schedule of recharging activity adopted by each electric bus in the system for a given timetable and charging constraints.

## Type 1: Single-depot slow-charging e-Bus VSP (unconstrained charging capacity)

The Type 1 system assumes that the depot location has enough capacity to accommodate all electric buses arriving for charging operation [[1]](http://dx.doi.org/10.1287/trsc.2013.0468). The mixed-interger linear programming optimization problem is solved using PuLP, an LP modeler written in Python. The documentation for PuLP is available at: https://coin-or.github.io/pulp/

### References
[1] Bodin, L. and Golden, B., 1981. Classification in vehicle routing and scheduling. Networks, 11(2), pp.97-108.
