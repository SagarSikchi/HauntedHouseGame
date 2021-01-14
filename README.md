# HauntedHouseGame

The document contains important scripts used in the project and the exported asset of game. The game has main focus on A* path tracing algorithm mostly used in games in AI. To open the game in Unity, import the unity package inside HauntedHouse Document.

A* algorithm is the Informed Search Algorithm used to find the shortest path with cost function. Cost function is implemented using the heuristic value and actual cost value.

Consider, the cost function is F'(N) is given as-

    F'(N) = G(N) + H'(N)
         
    where, 
    F'(N) = Cost Function (Approximate value). It is the cost value to reach from initial state to final state.
    G(N)  = It is the actual value to reach from initial state to current state.
    H'(N) = It is the heuristic value to reach from current state to final state.
 

In this project, Euclidean Distance is used as an heuristic function. The two lists namely **OPEN** and **CLOSED** are implemented internally in this project. The OPEN list contains the states which are generated but not processed. While CLOSED list contains the states which are generated and proocessed(created further successors of this current state).

