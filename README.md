# Model‑based analysis of multi‑UAV path planning for surveying postdisaster building damage

This paper presents a multi‑UAV coverage path planning method for the 3D reconstruction of postdisaster damaged buildings. The methodology has been implemented in NetLogo3D, a multi‑agent model environment, and tested in a virtual built environment in Unity3D. The proposed method generates camera location points surrounding targeted damaged buildings. These camera location points are filtered to avoid collision and then sorted using the K‑means or the Fuzzy C‑means methods. After clustering camera location points and allocating these to each UAV unit, a route optimization process is conducted as a multiple traveling salesman problem. Final corrections are made to paths to avoid obstacles and give a resulting path for each UAV that balances the flight distance and time. The paper presents the details of the model and methodologies, and an examination of the texture resolution obtained from the proposed method and the conventional overhead flight with the nadir‑looking method used in 3D mappings. The algorithm outperforms the conventional method in terms of the quality of the generated 3D model.

## Demo
This [demo](http://www.regid.irides.tohoku.ac.jp/shared/publications/videos/uav-cpp.mp4) can be found also [here](https://www.nature.com/articles/s41598-021-97804-4#Sec21)

## Reference
Nagasawa, R., Mas, E*., Moya, L. & Koshimura, S. (2021). Model-based analysis of multi-UAV path planning for surveying postdisaster building damage. Scientific Reports, 11(1), 18588. https://doi.org/10.1038/s41598-021-97804-4
