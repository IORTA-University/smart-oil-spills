# Smart Oil Spill Solutions

**Aim**- To use a swarm-based drone network to map the oil spill, detect the oil spill locations and use a distributed approach in order to restrict the spreading of the oil spill. 

**Proposed Solution**

1. Create a 'Swarm of drones' and setup basic communications with each other.
2. Each drone will be equipped with either a vision-sensor (Go-Pro camera) or a thermal sensor (FLIR camera) and will update map where the GPS locations of an oil spill affected region are updated in real-time. 
3. A clustering algorithm (K-means clustering or Disjoint sets based cluserting) will use a distance parameter in order to cluster these oil spilled areas into multiple regions. 
4. The drone network will use these clusters as input and will plan a path in order to clear these oil spills in unison. The drones may return to the base in order to be mounted with a funnel which will be used to spray Spill-sorb.
5. Involve the mesh-like boat structure in the process of oil-spill clearance. In short, that robot will also be part of the swarm network. 
