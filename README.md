# Polarization in Epidemics
### Study of the effect of opinion polarization about vaccines in the spreading of epidemics
Final project for the course "Life Data Epidemiology", MSc in Physics of Data.

In this work, we consider a two-layer multiplex network. The physical layer is a static network on which we model the propagation of epidemics through a SIRV model. This one interacts with the information layer, which aims at reproducing the opinion spreading typical of social networks. The simulation starts with a proportion of people that are averse to vaccines ("no-vax") and the remaining part of the nodes are prone to adopting vaccines ("pro-vax"). A Voter model dynamics joined with the dynamic rewiring of the information layer are intended to simulate the opinion polarization, namely the aggregation and isolation of nodes with similar beliefs against nodes with a different opinion.

In particular, we study the effect of `polarization tendency` (the probability of breaking a link with a node of a different opinion) and the `vaccination rate` involving pro-vax nodes on the dynamics of the epidemics (final attack rate and total number of vaccinated) and on the final structure of the information layer (by inspecting the clustering coefficient).
