# Model-based analysis of multi-UAV path planning for post-disaster building damage surveying

Here we present a multi-UAV coverage path planning method for 3D reconstruction of postdisaster damaged buildings. 
The methodology has been implemented in NetLogo3D and tested in a virtual scenario built in Unity3D. 
The proposed method generate waypoints surrounding targeted damage buildings with a user define horizontal and vertical interval. 
These waypoints are filtered to avoid collision and then sorted using clustering methods (i.e K-means or Fuzzy C-means). 
After clustering waypoints and allocate these to each UAV unit, a route optimization is conducted as a multiple traveling salesman problem (MTSP).
The MTSP is solved using Nearest Neighbor (NN) or Genetic Algorithm (GA).
Final corrections in paths to avoid obstacles give a resulting path for each UAV balancing flight distance and time among them. 

## Reference
Nagasawa, R., Mas, E., Moya, L. & Koshimura, S. (2021). Model-based analysis of multi-UAV path planning for surveying postdisaster building damage. Scientific Reports, 11(1), 18588. https://doi.org/10.1038/s41598-021-97804-4
