A k-coloring of a map is an assignment of k colors, one to each country, in such a way that no two countries sharing a border have the same color. This problem can be translated to a constraint graph. A coloring of a graph G assigns a color to each vertex of G, with the restriction that two adjacent vertices never have the same color. The chromatic number of G, written χ(G), is the smallest number of colors needed to color G. In this project, we will experiment with map coloring techniques and compare the observed results in the context of USA and Australia map. 

Compute the chromatic number of USA and Australia map. 
Experiment the CSP with the following methods
Depth first search only 
Depth first search + forward checking
Depth first search + forward checking + propagation through singleton domains
Depth first search + forward checking + propagation through reduced domain [optional]
The order of variables needs to be defined in the following order MRV, Degree Constraint, and Least Constraining Value
Present the results in a tabular format recording number of backtracking happened and the time to compute the result.

Without Heuristics

Define the order of states randomly for map coloring
Run the following algorithms for the same random order of states
Depth first search only 
Depth first search + forward checking
Depth first search + forward checking + propagation through singleton domain
Repeat steps 1 and 2 at least three times. 
With Heuristics

Start with a state 
Run the following algorithms - this time, you will use heuristics to select next variable and value where appropriate at runtime
Depth first search only 
Depth first search + forward checking
Depth first search + forward checking + propagation through singleton domain
Repeat steps 1 and 2 at least three times. 
