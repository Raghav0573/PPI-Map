# PPI-Map
Creates a protein-protein interaction network based on the number of nearest neighbours or a distance threshold. 

In this python notebook you simply enter the PDB id of your protein and how you want to calculate the nearest neighbours in the generate_PPI function. The generate_PPI function calls the helper functions to fetch, calculate the nearest neighbours and draw the network.  

Ways to calculate the nearest neighbours:
1. **N nearest neighbours**: Specify the value of the argument **N** in the generate_PPI function call. This will calulate the N number of nearest neighbours to each residue and make the corresponding edges.
2. **Distance threshold**: Specify the values of the argument **threshold** in the generate_PPI function call. This will calulate all the neighbours that are within the specified distance (in angstrom) to each residue and make the corresponding edges.
