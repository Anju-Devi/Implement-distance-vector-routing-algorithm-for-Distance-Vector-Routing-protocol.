# Implement-distance-vector-routing-algorithm-for-Distance-Vector-Routing-protocol.
A distance-vector routing (DVR) protocol requires that a router inform its neighbors of topology changes periodically. Historically known as the old ARPANET routing algorithm (or known as Bellman-Ford algorithm).  Bellman Ford Basics – Each router maintains a Distance Vector table containing the distance between itself and ALL possible destination nodes. Distances,based on a chosen metric, are computed using information from the neighbors’ distance vectors.  Information kept by DV router - Each router has an ID Associated with each link connected to a router,  there is a link cost (static or dynamic).

ALGORITHM
1. Start
2. By default, the distance of the node to itself is assigned to zero and when a node is unreachable the distance is accepted as 999.
3. Accept the input distance matrix from the user that represents the distance between each node in the network.
4. Store the distance between nodes in a suitable variable. 
5. Calculate the minimum distance between two nodes by iterating.
6. If the distance between two nodes is larger than the calculated alternate available path, replace the existing distance with the calculated distance.
7. Print the shortest path calculated. 
8. Stop.nce to itself = 0 Distance to ALL other routers = infinity number.
