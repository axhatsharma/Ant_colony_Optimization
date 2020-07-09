# Ant_colony_Optimization

A C language program to optimize the gas pipeline route to solve travelling salesman problem utilizing the Ant Colony Optimization Algorithm so as to minimize the operational cost of the process

This program makes and upgrades a solitary way for gas pipeline laying including all the stations of the pipeline. 

This program incorporates a coordinate matrix having all the coordinates of the stations that the pipeline need to visit(compulsorily). 

At that point from the coordinate matrix a distance matrix is determined by applying Euclidian distance formula for each pair of stations. 

From the Distance Matrix the Eta matrix is calculated which is the visibility of each edge. Also, Pheromone Matrix is determined for every Ant. 

In the beginning 5 ants are initialized(based on number of stations to be visited), and their separate routes were determined, with respective distances they travelled. 
Several iterations can be performed while updating the Pheromone matrix after each iteration.

Finally, the route with the least distance is picked and as indicated by the parameters the quantity of booster pumps are determined.
